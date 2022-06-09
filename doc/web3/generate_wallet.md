# 使用ether.js生成钱包

ether.js

```html
<script src="https://cdn.ethers.io/scripts/ethers-v4.min.js"></script>
```

### 五种方式

#### 1.加载私钥

```javascript
let privateKey = "0x0123456789012345678901234567890123456789012345678901234567890123";
let wallet = new ethers.Wallet(privateKey);

// Connect a wallet to mainnet
let provider = ethers.getDefaultProvider();
let walletWithProvider = new ethers.Wallet(privateKey, provider);
```

#### 2.创建随机钱包

```javascript
let randomWallet = ethers.Wallet.createRandom();
```

#### 3.加载JSON文件

```javascript
let data = {
    id: "fb1280c0-d646-4e40-9550-7026b1be504a",
    address: "88a5c2d9919e46f883eb62f7b8dd9d0cc45bc290",
    Crypto: {
        kdfparams: {
            dklen: 32,
            p: 1,
            salt: "bbfa53547e3e3bfcc9786a2cbef8504a5031d82734ecef02153e29daeed658fd",
            r: 8,
            n: 262144
        },
        kdf: "scrypt",
        ciphertext: "10adcc8bcaf49474c6710460e0dc974331f71ee4c7baa7314b4a23d25fd6c406",
        mac: "1cf53b5ae8d75f8c037b453e7c3c61b010225d916768a6b145adf5cf9cb3a703",
        cipher: "aes-128-ctr",
        cipherparams: {
            iv: "1dcdf13e49cea706994ed38804f6d171"
        }
    },
    "version": 3
};

let json = JSON.stringify(data);
let password = "foo";

ethers.Wallet.fromEncryptedJson(json, password).then(function (wallet) {
    console.log("Address: " + wallet.address);
    // "Address: 0x88a5C2d9919e46F883EB62F7b8Dd9d0CC45bc290"
});
```

#### 4.加载助记词

```javascript
let mnemonic = "radar blur cabbage chef fix engine embark joy scheme fiction master release";
let mnemonicWallet = ethers.Wallet.fromMnemonic(mnemonic);

// Load the second account from a mnemonic
let path = "m/44'/60'/1'/0/0";
let secondMnemonicWallet = ethers.Wallet.fromMnemonic(mnemonic, path);

// Load using a non-english locale wordlist (the path "null" will use the default)
let secondMnemonicWallet = ethers.Wallet.fromMnemonic(mnemonic, null, ethers.wordlists.ko);
```

#### 5.先生成私钥,再生成钱包

```javascript
let privateKey = ethers.utils.bigNumberify(ethers.utils.randomBytes(32));
let wallet = new ethers.Wallet(privateKey);
```

### 钱包对象wallet的5个属性

1. wallet.address - 获取钱包地址
2. wallet.privateKey - 获取钱包私钥
3. wallet.provider - 返回连接的Provider它允许钱包连接到以太坊网络以查询其状态并发送交易，如果没有连接提供者，则返回null。要更改提供者，请使用connect方法
4. wallet.mnemonic - 返回钱包的助记词，如果没有助记词，则为null
5. wallet.path - 返回此钱包的助记词上的路径，如果没有助记词，则为null
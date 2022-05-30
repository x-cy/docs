# ERC-20

ERC-20引入了可替代令牌的标准，换句话说，它们具有一个属性，使得每个令牌与另一个令牌完全相同。

ERC20包括:

#### 9个方法
```solidity
// Token名称：Ethereum
function name() public view returns (string)
// Token符号：ETH
function symbol() public view returns (string)
// Token精度
function decimals() public view returns (uint8)
// 获取Token总发行量
function totalSupply() public view returns (uint256)
// 获取用户Token数量
function balanceOf(address _owner) public view returns (uint256 balance)
// 转账
function transfer(address _to, uint256 _value) public returns (bool success)
// 按地址转账
function transferFrom(address _from, address _to, uint256 _value) public returns (bool success)
// 允许_spender多次从你的账户提取Token，最高为_value
function approve(address _spender, uint256 _value) public returns (bool success)
// 允许_spender从_owner撤回的Token数量
function allowance(address _owner, address _spender) public view returns (uint256 remaining)
```

#### 2个事件
```solidity
event Transfer(address indexed _from, address indexed _to, uint256 _value)
event Approval(address indexed _owner, address indexed _spender, uint256 _value)
```

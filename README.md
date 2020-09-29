# ERC20
ERC20 practice for Blockchain coursework at Seoul National University. Fall, 2020.

# Downloads
- ERC20.sol
- SafeMath.sol

# TODO
- Set *_totalSupply* with *_decimals*
>hint: _totalSupply = x times 10^_decimals
- Mint *_totalSupply* to the creator (*msg.sender*)
```
constructor (string memory name, string memory symbol) public {
    _name = name;
    _symbol = symbol;
    _decimals = 18;
    // TODO 1: set _totalSupply with _decimals
    // TODO 2: mint _totalSupply to the msg.sender
}
```
- Deploy the contract
- Register the token to the Metamask

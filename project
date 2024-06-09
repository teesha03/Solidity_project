pragma solidity 0.8.18;

contract MyToken {
    string public token;
    string public Abbreviation;
    uint public totalSupply;

    mapping(address => uint) public balances;

    constructor() {
        token = "My Token";
        Abbreviation = "MT";
        totalSupply = 0;
    }
    
    function mint(address _address, uint _amount) public {
        totalSupply += _amount;
        balances[_address] += _amount;
    }

    function burn(address _address, uint _amount) public {
        require(balances[_address] >= _amount, "Insufficient balance");
        totalSupply -= _amount;
        balances[_address] -= _amount;
    }
}

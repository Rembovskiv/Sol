# Sol// Specify Solidity compiler version
pragma solidity ^0.8.0;

// Declare the contract
contract SimpleStorage {
    // Declare a variable to store the value
    uint256 public value;

    // Function to set the value
    function setValue(uint256 _value) public {
        value = _value;
    }

    // Function to get the value
    function getValue() public view returns (uint256) {
        return value;
    }
}

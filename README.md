# AddressBook.sol
AddressBook.sol4
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AddressBook {
    address public user;

    function setAddress(address _addr) public {
        user = _addr;
    }
}
Initialize smart contract examples

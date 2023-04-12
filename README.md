// SPDX-License-Identifier: MIT

pragma solidity ^0.8.9;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MCZM3RO is ERC20 {
    constructor() ERC20("MCZM3RO", "M3RO") {
        _mint(msg.sender, 666000000000000000000);
    }
    
}

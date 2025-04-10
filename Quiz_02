// SPDX-License-Identifier: MIT
// Compatible with OpenZeppelin Contracts ^5.0.0
pragma solidity ^0.8.22;

import {ERC20} from "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract Quiz_02 is ERC20 {
    constructor(address recipient) ERC20("Quiz_02", "MTK") {
        _mint(recipient, 10000 * 10 ** decimals());
    }
    struct Listing{
        address seller;
        IERC20 token;
        uint pricepertoken;
        uint remainingamount;
    }

    Listing[] public listings;

    function ListTokens(IERC20 token, uint totalamount, uint pricepertoken){

    }

    function BuyTokens(uint listingid, uint tokenamount) payable {

    }

    getlistcount() view returns (uint){

    }
}

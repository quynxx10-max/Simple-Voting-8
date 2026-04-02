# Simple-Voting-8
Simple Voting.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Voting {
    uint public yesVotes;
    uint public noVotes;

    function voteYes() public {
        yesVotes++;
    }

    function voteNo() public {
        noVotes++;
    }
}

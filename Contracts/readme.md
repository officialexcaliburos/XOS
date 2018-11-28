Excalibur OS XOS Coin
This repository contains the solidity code for the XOS token.
Excalibur Operating System, which will solve the issue of mining as it has built-in mining management feature so user can mine cryptocurrency by their own, It also solves the problem of Viruses and Data Theft by its unique method of data security system, and additionally it solves second major issue of System users in which the users can now experience different platforms application on Excalibur, which means application files from major OS will be supported by Excalibur Operating System. It also has the feature of Blockchain based Mining Management System, in which user can mine, trade & user can add their own script of tokens.

Coin Info

XOS is an ERC20 compliant token with a few additional features seen below.
Type	Info
name	XOSCoin
symbol	XOS
decimals	18
cap	20000000

Solidity Inheritence
The following is a list of contracts that XOS inherits along with a brief description of the functionality.
•	PausableToken
o	This is an ERC20 token that inherits the StandardToken from zeppelin-solidity. PausableToken token allows the owner of the contract to freeze and unfreeze all token transfers.
•	CappedToken
o	CappedToken is a MintableToken that is capped. The mintable token feature creates tokens through a mint method that creates new tokens and transfers them to a given address. This can be used for ICOs, airdrops, promotions, etc as long as the max supply cap has not been reached.
•	HasNoTokens
o	Blocks ERC223 tokens from being transferred to this contract. Allows the contract owner to transfer ownership of ERC20 tokens that are sent to the contract address (which would otherwise be locked up and immovable at this contract).
•	Claimable
o	Gives contract owner the ability to transfer ownership of the contract to a new owner pending the new owner accepts this transfer of ownership.


# Mintable ERC20 Extension Module

The Mintable ERC20 extension module extends the functionality of the ERC20 Token module by allowing users to mint new tokens. To use this module, the ERC20 Token module must already be installed.

`Ensure that the ERC20 Token module is already installed.`

# Usage
Once the Mintable ERC20 extension module is installed, users can mint new tokens by calling the mint function of the ERC20 token contract. The mint function takes the following parameters:

`to (address)`: The address to which the newly minted tokens will be sent.
`amount (uint256)`: The amount of tokens to mint.

Here's an example of how to mint 100 new tokens and send them to the address `0x1234567890123456789012345678901234567890`:

`ERC20(tokenContract).mint(0x1234567890123456789012345678901234567890, 100);`
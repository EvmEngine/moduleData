# ERC20 Token Module

The ERC20 Token module allows users to generate new ERC20 tokens on the EVM Engine blockchain. Once the module is installed, users can create new tokens by providing the following installation details:

1. Name (`_name`) (string): The name of the token.
2. Symbol (`_symbol`) (string): The symbol of the token.
3. Decimal (`_decimals`) (uint8): The number of decimals for the token.
4. Total Supply (`_supply`) (uint256): The total supply of the token which will be `_supply * 10**_decimals`.

# Example
To create a new ERC20 token "My Token (MYT)" with 18 decimals and 1 billion supply use following installation details:

`_name: My Token`
`_symbol: MYT`
`_decimals: 18`
`_supply: 1000000000`

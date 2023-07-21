# eth-avax_module-3
ERC20: This is the standard ERC20 token contract implementation, providing basic functionality for a fungible token. ERC20Burnable: This contract extends ERC20 and adds the ability to burn (destroy) tokens. Ownable: This contract provides a basic access control mechanism, allowing only the contract owner to execute certain functions. The CustomToken contract is defined and inherits from ERC20, ERC20Burnable, and Ownable.

The constructor function is defined without any parameters. It is executed once when the contract is deployed. Within the constructor, the ERC20 constructor is called with the name "MyToken" and symbol "MyTk" to initialize the token.

The mint function is a public function that can only be called by the contract owner (as defined by the Ownable contract). It takes two parameters: to (the address to which the tokens will be minted) and amount (the number of tokens to mint). Inside the function, the _mint function from the ERC20 contract is called to create and assign the specified amount of tokens to the given address.

https://www.loom.com/share/53be3313179949cc9efbc797e42908fc

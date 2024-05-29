# Metacrafters_2
mint and burn functions

In this project, we will be creating a token that has primarily two functions, namely mint and burn, and some conditions for the functions.

For this, we will be declaring a contract named myToken In this, we will declare the public variables tokenName, tokenAbbrv, and totalSupply. We will be setting the value to zero. We will be setting the values of the code in the code itself rather than declaring them at runtime. We will set the access modifier of all three variables to the public so that everyone can access them. We will be creating a mapping function, which is also similar to dict and hash functions in other programming languages). Every address is associated with a uint value, and whenever we pass an address to the mapping function, it returns the token amount that the address has. So the address is mapped to the balances variable. We declare the first function, mint, which has two parameters: address and value. The function then increases the total supply by that number and increases the balance of the sender address by that amount. Similarly, we declare the second function burn, which works the opposite of the mint function as it will destroy the tokens. It will take an address and value, just like the mint function. It will deduct the value from the total supply and from the balance of the sender. At last, we will be imposing a condition on the burn function, that the balance of the sender is greater than or equal to the amount that is supposed to be burned. 

# Description

MyToken" written in Solidity for the Ethereum blockchain. The contract includes public variables to store essential details of the token, such as its name, abbreviation, and total supply. It utilizes a mapping called "tokenHolders" to associate Ethereum addresses with their respective token balances, enabling efficient tracking and management of ownership. The program offers two core functions: "mint" and "burn". The "mint" function allows for the creation of new tokens, increasing the total supply and updating the balance of the recipient address. The "burn" function facilitates the destruction of tokens, reducing the total supply and deducting the specified amount from the token holder's balance. Importantly, the "burn" function includes a check to ensure that the token holder's balance is sufficient for the requested burn amount. With these functionalities, the contract provides a comprehensive solution for token creation, destruction, and balance management within a secure and decentralized blockchain environment.


# Getting started

Installing

Copy the code and paste it into Remix- Etherium IDE

Executing program

After completing the code, we will compile it by clicking on the myToken.sol icon in the Solidity compiler. After clicking on the icon, go to Deploy and run transactions. Under the deployed contracts, we can see the variables and the functions declared. After that, we can use the default address provided. Paste the address in the mint, add the value, and check the balance. Also, we can burn the token via the burn function. Add the address, and burn the token. Check the balance  We can work with the functions by applying different values. In this way, we can create a new token.

# Authors
BYLAPUDI DEEPAK VENKATA SWAMY NAIDU
@bdvsnaidu(https://github.com/bdvsnaidu)

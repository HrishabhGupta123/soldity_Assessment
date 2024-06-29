## Solidity Final Project

The project name "Create a Token" signifies the ability to utilise state variables in the Solidity language to build tokens, which can then be employed for operations such as minting and burning tokens.

## Summary

This Solidity Project's smart contract does the following tasks: The contract encompasses the token's appellation, acronym, and overall quantity. The account balance of each sender is aligned with their respective sender address. Minting tokens refers to the process of increasing their overall value and the balance of the sender's account by a specific amount.The burning token feature deducts a defined amount from the sender's balance and total value only if the sender's account has enough funds. In order to establish a project that is comparable, it is necessary to execute the following tasks: The contract includes public variables such as Token Name, Token Abbrv, and Total Supply, which will store the relevant information about the token. A mapping from addresses to balances (address => uint) will be included in your contract. Additionally, a mint function will be introduced that requires two inputs: an address and a value. The function then raises the address's balance by that amount and the total supply by that number. The burn function in your contract will destroy tokens, functioning in opposition to the mint function. In the same way as the mint operates, it will require an address and value. The amount will then be removed from both the address's balance and the total supply. Finally, conditionals should be included in your burn function to guarantee that the account balance is more than or equal to the amount that is supposed to be burned.

## Getting Started
### Installing

Just click the <> code button to start the program, and you'll be able to download it as a zip file.You can click on the "fork repository" option to utilize it for your project, and it will be saved to your Github account for future editing.

## Executing Program

Paste the file you downloaded into RemixIDE to launch the program.Next After building the code, run it.Click on the address part after deployment, add your account, and input the value you wish to increase in the mint function. Click on Mint, and you will notice that your overall supply has grown. In a similar approach, you can carry out the burn function for your token and update its name, abbreviation, and total supply in ways such as

* string public tokenName="YOUR TOKENNAME";  // like in above code as BETA
* string public tokenAbbrv="YOUR TOKENABV.";//  like in above code as BTA
* string public totalSupply=Your total supply; // like in above code initally set as zero
## Help

Be aware and alert for some errors: 

* You will notice if your code have an error check on the upper right side of your screen you will your mini-minimize entire code there that have a red lines, blue lines mean you are in that lines and red lines means error.

* You will see a Red Exclamation Mark in that line so you will notice that there some errors

* Check your File name if its red

* Don't forget to count and check some valuable symbols
* **_{  }_** , **_[ ]_** , **_( )_** , **_;_**


## Authors

Creator: Hrishabh Gupta

Email: hrishabhguptapip@gmail.com

Contact Number: 7696527292


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

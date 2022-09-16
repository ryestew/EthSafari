# Remix Workshop

## Non-essential Prerequisites
- Github account would be nice (not necessary)
- Metamask link for installation (advised not essential)
- Test Ether https://goerli-faucet.mudit.blog/ (not necessary)

## Basic tasks for people who have never used Remix

1. Make a new workspace with the default template
2. Change the name of the workspace
3. Change the theme - by going to the Settings tab
    - And check what else is in settings
    - You will probably be adding a github key later
4. Go to the Plugin Manager
5. Activate Learneth (although you could do this on the hometab)
6. Check the tutorials **Solidity Beginner Course**, **Soldity ERC20 Token Course**, **Soldity NFT Course**,  and the **NFT Auction Contract** course.
7. Go back to the File Explorer and choose 2_owner.sol 
8. Compile it in the Solidity Compiler
9. Then compile it again with the clue mentioned here: https://twitter.com/EthereumRemix/status/1511901727389147136
10. Click the follow button in Twitter (only if you like)
11. In the top of the Solidity Compiler, click the `>` symbol and then click the link to get to the documentation of this plugin.
12. Open a new tab and go to:
    - https://medium.com/remix-ide to see our articles
    - Our docs are located at: https://remix-ide.readthedocs.io
13. Go to the Deploy & Run Module
14. Deploy 2_Owner.sol to remix vm
15. Interact with the **changeOwner** function - in 2_Owner.sol 
    - Hint: you need to input an account address that is not the address of the 1st account in the **ACCOUNT** select box. If you switch to a different account to copy, remember to switch back to the original account.
14. Start a debugging session from the terminal
    - Find out what the solidity state & local variables are at different points by dragging the slider or stepping through the transaction.
14. Switch back to the Deploy & Run Module.  Then deploy to another testnet (ganache, hardhat, or a public test chain with Metamask)


## More Advanced (but often used) Tasks

### Console.log & Switching Accounts
1. Check the use of console.log in 2_Owner.sol 
2. Edit the message on line 33.  
3. Compile and deploy the contract. 
4. Find your message in the terminal.
5. Try putting a console.log in the **changeOwner** function.
6. Compile and Deploy the contract.
7. Open up the **deployed instance** and find the **changeOwner** function.
8. Change the account and copy the new account.
9. Switch back to the original account.
10. Paste the account address that you copied into **changeOwner**'s  parameter **newOwner**. 
11. Click the changeOwner button.
12. Why did you need to change back to the original account to run this function?
13. Find the console.log message you put in this function.

### Sending value with a transaction
1. Make a function `changeOwner` payable:
2. Add the word **payable** after the word **public** on line 42.  - - - Compile the contract and deploy it to the Remix VM.  
3. Send 4 ETH to the contract (using our not so intuitive UI)
4. Check gas usage of the function - see gas line in the editor
5. In the deployed instance, see how much value has been sent to the contract.

### Cloning and Editing
1. In the File Explorer, click the clone icon on the row of Workspace icons.
2. and use this repo - or any other you like: `https://github.com/Aniket-Engg/solidity-school.git`
 




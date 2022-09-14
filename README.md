# Remix Workshop

## Prereq:
- Github account and access token (might be needed)
- Test ether (might need to be distributed)
- Eth address
- Metamask installed

## Basic tasks for people who have never used Remix

1. Make a new workspace with the default template
2. Change the name of the workspace
3. Change the theme - by going to the Settings tab
    - And check what else is in settings
    - You will probably be adding a github key later
4. Go to the Plugin Manager
5. Activate Learneth (although you could do this on the hometab)
6. Check the tutorials about Solidity & ERC 20, ERC 721 and the auction contract
7. Go back to the File Explorer and choose 2_owner.sol 
8. Compile it in the Solidity Compiler
9. Then compile it again with the clue mentioned here: https://twitter.com/EthereumRemix/status/1511901727389147136
10. Click the follow button in Twitter (only if you like)
11. In the top of the Solidity Compiler, click the `>` symbol and then click the link to get to the documentation of this plugin.
12. Open a new tab and go to:
    - https://medium.com/remix-ide to see our articles
    - Our docs are located at: https://remix-ide.readthedocs.io
13. Go to the Deploy & Run Module
13. Deploy 2_Owner.sol to remix vm
13. Interact with the **changeOwner** function - in 2_Owner.sol 
    - Hint: you need to get another account and you need to switch back to the original account.
14. Start a debugging session from the terminal
    - Find out what the solidity state & local variables are at different points by dragging the slider or stepping through the transaction.
14. Switch back to the Deploy & Run Module.  Then deploy to another testnet (ganache, hardhat, or a public test chain with Metamask)






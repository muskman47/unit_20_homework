# unit_20_homework
Assosiate Profit Splitter user manual - 2/23/2021

The Associate Profit Splitter contract is a contract designed to accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

In order to run the contract, the user will need to import the AssociateProfitSplitter.sol file into Remix.

Next, you will need to open up Ganache and ensure that your MetaMask account is connected to Localhost 8545.

Once you have imported the file into remix you will need to compile the code. In order to compile, you will need to open up the compiler on the left hand side of the remix portal. Ensure the compiler is set to 0.5.0. Once the compiler is set, select the compile button and ensure the compiler is reflecting a green check mark. 

Once compiled you will need to navigate to the Deploy screen and ensure the following:
- Ensure the Environment is set to Injected Web3
- Select the arrow to the right of the "Deploy" field and expose the Three deploy address lines listed as "_one", "_two" and "_three"
- Select three different addresses from Ganache and paste them into the respective fields. Once added select "transact" This will deploy the contract

Once the contract is deployed, you need to scroll to the bottom of the screen and open up the contract by selecting the drop down arrow.
You will see two buttons. One will say "deposit" and the other will say "balance". Scroll up on the left where you see an input window that says value. Input any amount. Scroll back down to the bottom where the contract is and select "deposit." Metamask will then ask you to confirm the transaction. Select "confirm." Metamask will give a positive confirmation that the transaction has gone through. Now, open Ganache and you will see that the wei was split across the three accounts that you originally input when deploying the contract which is an indiacation that the contract is operating correctly.

Testnet Contract Address - CREATED CONTRACT ADDRESS 0x0dcbFad78eFe1528D724829B643dFf2E14901a18 




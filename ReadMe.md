# Unit 21 - Advance Solidity Assignment Token CrowdSale

## The parameter of the crowdsale are as follows:
* The crowdsale last 5 minutes
* The goal of the crowdsale is to raise 2 ETH
* PupperCoin has a 1 to 1 relationship with ETH
* the Crowdsale is capped at the goal meaning only 2eth can be raised
![parameters](Images/PupperCoinSale_Parameters.PNG?raw=true)

## Running the sale
* The metamask account at the beginning of the crowdsale: 

![beg](Images/MetaMask_Beg.PNG?raw=true)

* Deploying the deployer: 

![Deployed_deployer](Images/Deploying_PupperCoinSaleDeployer.PNG?raw=true)

* Deploying the Coin: 

![Deployed_token](Images/Deploying_PupperCoin.PNG?raw=true)

* Deploying the Sale: 

![Deployed_sale](Images/Deploying_PupperCoinSale.PNG?raw=true)

* Transaction made for 2 ETH for 2 PUPP, as you can see 2 ether went from the metamask account to the coin sale address and 2 PUPP was transferred

![Transaction](Images/transaction.PNG?raw=true)

* Te crowdsale is over:

![end](Images/end.PNG?raw=true)

* attempting another transaction afterwards leads to a timesaleopen: not open and the amount is reverted:

![Failed](Images/amount_reverted.PNG?raw=true)

## Adding the token to myCryptoWallet:
* the PUPP stayed at 0 after the transaction for MyCryptoWallet and MetaMask, going back to the initial transaction you can see that the address that the token was sent to was not the one on metamask

![MyCrypto_end](Images/MyCrypto_end.PNG?raw=true)

![MyCrypto_end](Images/MetaMask_end.PNG?raw=true)

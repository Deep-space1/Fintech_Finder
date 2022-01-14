# Fintech_Finder

![19-4-challenge-image](https://user-images.githubusercontent.com/86626839/149586168-5645fd7c-60b6-4b83-bc32-e929ffb05bba.png)

This project demonstrates a startup that is building a new disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I am integrating the Ethereum blockchain network into the application in order to enable the customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

The code contained in the crypto_wallet.py script file consists Ethereum transaction functions including wallet, wallet.derive_acount, get_balance, fromWei, estimateGas, sendRawTransaction, and others—have now been incorporated into Python functions that allows to automate the process of accessing them.

Using streamlit and fintech_finder.py following operations are executed,


-Fetching and displaying the account balance associated with your Ethereum account address.

-Calculating the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

-Digitally signing a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

-Reviewing the transaction hash code associated with the validated blockchain transaction.

### Image 1 illustrates account balance associated with the ethereum account, selected fintech professional wage per hour and total hours.

<img width="959" alt="p1" src="https://user-images.githubusercontent.com/86626839/149591186-4168a75c-6c29-43da-9f79-946e8523429b.png">



### Image 2 illustrates total wage in ether and validated transaction hash.

<img width="958" alt="p2" src="https://user-images.githubusercontent.com/86626839/149591346-2cf94302-bffc-4d87-9f16-fbec1cb21e29.png">



### Image 3 illustrates updated balances in both senders and receivers wallet addresses after the transaction is successfully initiated.

<img width="994" alt="p3" src="https://user-images.githubusercontent.com/86626839/149591485-668a8821-9c26-4839-9e4b-253f540a7f7c.png">



### Image 4 illustrates reviewing of transaction hash on local blockchanin Gnache.

<img width="1094" alt="p4" src="https://user-images.githubusercontent.com/86626839/149591612-968b58b2-b8cb-44e4-a3c7-91e14c3d0f40.png">



### Image 5 illustrates updated account balance on streamlit. 

<img width="959" alt="p5" src="https://user-images.githubusercontent.com/86626839/149591686-ee6148d0-5701-4a82-87a6-67facded8bb6.png">

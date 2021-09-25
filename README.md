# Associate Profit Splitter

## Smart Contract
- Goal is to deploy a contract that will accept ether and divide evenly among associate level employees

Step 1) Defining Public Variables
![Public Variables](PublicVariables.png)

Step 2) Creating Constructor that Accepts Payable Addresses
![Constructor](Constructor.png)

Step 3) Balance Function
    - already defined by StarterCode

Step 4) Deposit Function
![Deposit](DepositFuntion .png)
    - Uses Global Variables "msg.sender" and "msg.value"

Step 5) External Payable Function
![External Payable](ExternalPayableFunction.png)

## Deploying Contract
    1. Enviornment set to "Injected Web3" to connect to LocalHost to wallet
    2. Initial value set to 0 wei
    3. Addresses taken from Ganache

![Deploying Contract](DeployingContract.png)

## Test Transaction

![Pre-Transaction Amounts](preTransactionBalance.png)
    - Account information for the sending account and 3 recipient accounts

    1. After deploying contract, set up transaction parameters 

![Test Transcation](TestTransac.png)

    2. Confirm transaction

![Transaction Confirmation](Confirmation.png)

    3. Updated Account Figures in Ganache

![Updated Amounts](GanacheNewBlance.png)

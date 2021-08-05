# accialcli

## GENERAL INFORMATION

[accialcli](https://pypi.org/project/accialcli/) its a command line interfaces that uses APIs to create a client that send to our API 1 Borrower, 1 Application, 1 Loan and 1 Payment.

## INSTALLATION

- To install this library we must execute the following command in our terminal

### **pip install accialcli**

## HELP

-  If for any reason this doesn't work you can clone [this github repository](https://github.com/yud-cumba/accialcli), go to project folder and usage `python3 entry.py` instead of`accialcli` with the same options

## OPTIONS  **accialcli**

### - **create** 

- To create 1 Borrower, 1 Application, 1 Loan and 1 Payment.
-  You need to complete all requests made by the cli

###### Example:

![create.png](https://raw.githubusercontent.com/yud-cumba/accialcli/main/img/create.png)


#### `--help`

- To show the search options 

![createhelp.png](https://raw.githubusercontent.com/yud-cumba/accialcli/main/img/createhelp.png)

### - **search** 

#### `--help`

- To show the search options 

![searchhelp.png](https://raw.githubusercontent.com/yud-cumba/accialcli/main/img/searchhelp.png)

#### `--borrower [ExternalBorrowerId]`

- This option get the borrower information using externalBorrowerId if it exits

- [ExternalBorrowerId] is the id which was placed to create the borrower

#### `--application [BorrowerId] [ApplicationId]`

- This option get the application information using the BorrowerId and ApplicationId if it exits
- [BorrowerId] is the id which was generated after creating the borrower
- [ApplicationId] is the id which was placed to create the application

###### Example:

![search1.png](https://raw.githubusercontent.com/yud-cumba/accialcli/main/img/search1.png)

#### `--loan [ExternalLoanId]`

- This option get the loan information using externalLoanId if it exits

- [ExternalLoanId] is the id which was placed to create the loan

#### `--payment [LoanId] [ExternalPaymentId]`

- This option get the payment information using LoanId and ExternalPaymentIdif it exits
- [LoanId] is the id which was generated after creating the loan
- [ExternalPaymentId] is the id which was placed to create the payment

###### Example:

![search2.png](https://raw.githubusercontent.com/yud-cumba/accialcli/main/img/search2.png)
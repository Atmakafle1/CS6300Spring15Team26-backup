# Traceability Information

**Author**: **Team26**

The following table maps from a use case to the design elements that realize that use case, the corresponding code, and the tests that were derived from it.

The root directory of the code is 6300Spring15Team26/Project2/StallManager/src/edu/gatech/seclass/prj2/


| USE CASE NO. | USE CASE DESCRIPTION| DESIGN ELEMENT | CORRESPONDING CODE<br> | TEST CASE NO. |
|---------------------------|------------------------------------------|---------------------|-----|----|
| UC1 | ADD CUSTOMER | manageCustomer;<br>addCustomer(firstName,lastName,zip,email) |MainActivity.java<br>CustomerAddActivity.java  | T001<br>T002 |
| UC2 | EDIT CUSTOMER | manageCustomer;<br>editCustomer(firstName,lastName,zip,email) | CustomerDetailActivity.java | T003 |
| UC3 | GET CUSTOMER | manageCustomer;<br>getCustomer(firstName,lastName):Customer | CustomerDetailActivity.java | T004<br>T005 |
| UC4 | GET TRANSACTION HISTORY | getCustomer;<br>getTransactionHistory(customer):List | HistoryActivity.java | T006 |
| UC5 | SEND DOLLAR REWARD EMAIL | getCustomer;<br>sendEmail(rewardsType,email,subject,content) | CustomerDetailActivity.java | T012<br>T013 |
| UC6 | SEND GOLD STATUS EMAIL | sendEmail(rewardsType,email,subject,content) | CustomerDetailActivity.java | T014<br>T015 |  
| UC7 | PERFORM TRANSACTION WITHOUT DISCOUNT | processPayment();<br>readSwipedCard();<br>createTransaction(amount:Double) | TransactionActivity.java | T008 |
| UC8 | PERFORM TRANSACTION WITH 5% DISCOUNT | processPayment();<br>processDiscounts;<br>createTransaction(amount:Double)  | TransactionActivity.java | T010 |
| UC9 | PERFORM TRANSACTION WITH MONEY DISCOUNT | processPayment();<br>processDiscounts;<br>createTransaction(amount:Double);<br>resetAbsoluteDiscount | TransactionActivity.java | T009 |
| UC10 | PERFORM TRANSACTION WITH 5% DISCOUNT & MONEY DISCOUNT | processPayment();<br>processDiscounts;<br>createTransaction(amount:Double);<br>resetAbsoluteDiscount | TransactionActivity.java | T011 |



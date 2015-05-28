# Traceability Information

**Author**: **Team26**

The following table maps from a use case to the design elements that realize that use case, the corresponding code, and the tests that were derived from it.

The root directory of the code is 6300Spring15Team26/Project2/StallManager/src/edu/gatech/seclass/prj2/


| USE CASE NO. | USE CASE DESCRIPTION| DESIGN ELEMENT | CORRESPONDING CODE<br> | TEST CASE NO. |
|---------------------------|------------------------------------------|---------------------|-----|----|
| UC1 | ADD CUSTOMER | Customer<br>CustomerFactory<br>CustomerAdapter<br>CustomerAddActivity |MainActivity.java<br>CustomerAddActivity.java  | T001<br>T002 |
| UC2 | EDIT CUSTOMER | Customer<br>CustomerDetailActivity | CustomerListActivity.java<br>CustomerDetailActivity.java | T003 |
| UC3 | GET CUSTOMER | Customer<br>CustomerDetailActivity | SearchActivity.java<br>CustomerListActivity.java<br>CustomerDetailActivity.java | T004<br>T005 |
| UC4 | GET TRANSACTION HISTORY | Customer<br>SearchActivity<br>HistoryActivity | SearchActivity.java<br>CustomerDetailActivity.java<br>HistoryActivity.java | T006 |
| UC5 | SEND CASH REWARD EMAIL | Transcation<br>TranscationActivity | TransactionActivity.java | T012<br>T013 |
| UC6 | SEND GOLD REWARD EMAIL | Transcation<br>TranscationActivity | TransactionActivity.java | T014<br>T015 |  
| UC7 | PERFORM TRANSACTION WITHOUT REWARD | Transcation<br>TranscationFactory<br>TranscationAdapter<br>TransactionActivity<br>CreditCard<br>CreditCardException | TransactionActivity.java<br>CreditCard.java<br>EmailStatus.java| T008 |
| UC8 | PERFORM TRANSACTION WITH GOLD REWARD | Transcation<br>TranscationFactory<br>TranscationAdapter<br>TransactionActivity<br>CreditCard<br>CreditCardException  | TransactionActivity.java<br>CreditCard.java<br>EmailStatus.java<br>TransactionFactory.java | T010 |
| UC9 | PERFORM TRANSACTION WITH CASH REWARD | Transcation<br>TranscationFactory<br>TranscationAdapter<br>TransactionActivity<br>CreditCard<br>CreditCardException | TransactionActivity.java<br>CreditCard.java<br>EmailStatus.java<br>TransactionFactory.java | T009 |
| UC10 | PERFORM TRANSACTION WITH GOLD & CASH REWARD | Transcation<br>TranscationFactory<br>TranscationAdapter<br>TransactionActivity<br>CreditCard<br>CreditCardException | TransactionActivity.java<br>CreditCard.java<br>EmailStatus.java<br>TransactionFactory.java | T011 |



# Fraud-Detection Project for Financial Transactions

<p>
  <img  src="1.jpeg"  width="70%  height="50% />
  <div>  <h3>About Data : </h3>This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.</div>
</p>
<div>
  <ul>
    <b>Columns: </b>
    <li>trans_date_trans_time : here the transaction datetime</li>
    <li>cc_num : the number of CreditCard</li>
    <li>merchant : name of trader</li>
    <li>category : kind of service that user want to pay it</li>
    <li>amt : the amount the ser want to pay </li>
    <li>first : first name of user</li>
    <li>last : last name of user</li>
    <li>gender : the gender of user</li>
    <li>street, city , state ,zip: address info</li>
    <li>lat , long : location of user</li>
    <li>city_pop : population of each city</li>
    <li>job : the job of user</li>
    <li>dob : date of birth of user</li>
    <li>trans_num : id of each transaction</li>
    <li>unix_time : the time that transaction happen</li>
    <li>merch_lat , merch_long : location of trader</li>
    <li>is_fraud : is the process fraud or not</li>
  </ul>
</div>
<h3>Problem Statement : to make a model that classify of a specific transaction is fraud or not !</h3>
<p>
<b>Result : </b><div>after i use a preprocessing process and make data ready to using classificaion model to predict if the transaction are fraud or not i get these results :
<h4>Accuracy Score : 0.96 %</h4>
<h4>confusion matrix :
  [[1737   65]
 [  67 1735]] </h4>
<h4>classification report : 
        precision    recall  f1-score   support

         0.0       0.96      0.96      0.96      1802
         1.0       0.96      0.96      0.96      1802

    accuracy                           0.96      3604
   macro avg       0.96      0.96      0.96      3604
weighted avg       0.96      0.96      0.96      3604</h4>
</div>
<h2>Thank you</h2>
</p>

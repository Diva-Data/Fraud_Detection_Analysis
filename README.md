<body>
<h1>Fraudulent Transactions Data</h1>
Fraudulent transactions data for a financial company

<h2>About Dataset</h2>
<h3>Context</h3>
Develop a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan. Data for the case is available in CSV format having 6362620 rows and 10 columns.

<h3>Content</h3>
Data for the case is available in CSV format having 6362620 rows and 10 columns.

<h3>Data Dictionary:</h3>

<b>step</b> - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

<b>type</b> - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

<b>amount</b> - amount of the transaction in local currency.

<b>nameOrig</b> - customer who started the transaction

<b>oldbalanceOrg</b> - initial balance before the transaction

<b>newbalanceOrig</b> - new balance after the transaction

<b>nameDest</b> - customer who is the recipient of the transaction

<b>oldbalanceDest</b> - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

<b>newbalanceDest</b> - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

<b>isFraud</b> - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

<b>isFlaggedFraud</b> - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

<h3>Inspiration</h3>
Following tasks & questions can be answered using the data,

<li>Data cleaning including missing values, outliers and multi-collinearity.</li>
<li>Describe your fraud detection model in elaboration.</li>
<li>How did you select variables to be included in the model?</li>
<li>Demonstrate the performance of the model by using best set of tools.</li>
<li>What are the key factors that predict fraudulent customer?</li>
<li>Do these factors make sense? If yes, How? If not, How not?</li>
<li>What kind of prevention should be adopted while company update its infrastructure?</li>
<li>Assuming these actions have been implemented, how would you determine if they work?</li>
</body>

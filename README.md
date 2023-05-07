Download Link: https://assignmentchef.com/product/solved-eecs738-lab-7-midterm
<br>
Acme Telephonica (AT) is a mobile phone operator that  has customers across every state of the U.S.A.

AT struggles with customer <strong>churn prediction</strong>—customers  leaving AT for other mobile phone operators.

AT hired us to take a new approach to reducing customer  churn.

This case study is to develop a machine learning solution to this business  problem.

AT did not approach us with a well-specified machine learning problem. Instead, the company approached us with a business problem—reducing customer churn.Our first goal is to convert this business problem into a machine learning problem and develop a concrete solution.

To evaluate the available data, we have the data definitions.




<table width="408">

 <tbody>

  <tr>

   <td width="137">Feature</td>

   <td width="272">Description</td>

  </tr>

  <tr>

   <td width="137">BILLAMOUNTCHANGEPCT</td>

   <td width="272">The percent by which the customer’s bill has changed from  last</td>

  </tr>

  <tr>

   <td width="137">CALLMINUTESCHANGEPCTAVGBILLAVGRECURRINGCHARGEAVGDROPPEDCALLSPEAKRATIOCHANGEPCTAVGRECEIVEDMINSAVGMINSAVGOVERBUNDLEMINSAVGROAMCALLSPEAKOFFPEAKRATIO</td>

   <td width="272">month to thismonthThe percent by which the call minutes used by the customer has  changed from last month to this monthThe average monthly bill amountThe average monthly recurring charge paid by the customer  The average number of customer calls dropped each monthThe percent by which the customer’s peak calls to off-peak calls ratio has changed from last month to this monthThe average number of calls received each month by the customerThe average number of call minutes used by the customer each monthThe average number of out-of-bundle minutes used by the customer eachmonthThe average number of roamingcallsmade by the customer each monthThe ratio between peak and off peak calls made by the customer  thismonth</td>

  </tr>

  <tr>

   <td width="137">NEWFREQUENTNUMBERS</td>

   <td width="272">How many new numbers the customer is frequently calling   this month?</td>

  </tr>

 </tbody>

</table>




<table width="408">

 <tbody>

  <tr>

   <td width="137">Feature</td>

   <td width="272">Description</td>

  </tr>

  <tr>

   <td width="137">CUSTOMERCARECALLS</td>

   <td width="272">The number of customer care calls made by the customer last</td>

  </tr>

  <tr>

   <td width="137">NUMRETENTIONCALLSNUMRETENTIONOFFERSAGECREDITRATINGINCOMELIFETIMEOCCUPATIONREGIONTYPEHANDSETPRICEHANDSETAGENUMHANDSETSSMARTPHONECHURN</td>

   <td width="272">monthThe number of times the customer has been called by the retentionteamThe number of retention offers the customer has acceptedThe customer’sageThe customer’s credit ratingThe customer’s incomelevelThe number of months the customer has been with ATThe customer’soccupationThe type of region the customer lives inThe price of the customer’s current handsetThe age of the customer’s current handsetThe number of handsets the customer has had in the past 3 yearsIs the customer’s current handset a smart phone?The targetfeature</td>

  </tr>

 </tbody>

</table>

<h1>Midterm analysis</h1>

<ul>

 <li>Understand the data. Note any issues with missing or damaged data and how you handle it. Comment on whether normalization of features would be helpful. One paragraph.</li>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="10"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Develop an analysis of the churn data using two different classifiers. First, justify why you chose each classifier. Provide a description of your classifiers. More than one paragraph.</li>

 <li>Compare the performance of the classifiers. Determine which is preferable and justify your decision. More than one paragraph.</li>

 <li>Extra credit. The company now tells you new information. Adjust your analysis for the case where giving service to a churner costs the company $700 and excluding a customer who is not a churner costs $100, while other cases are 0. Now optimize for the least cost. Describe how this changed your classifier performance.</li>

</ul>
# House-Prediction
House Grade Prediction Data Analysis
![house_pred_photo](https://github.com/Bobby-Rawat/House-Prediction/assets/147500429/4c3a1c3f-dba6-49b2-8622-7ce38516c522)
# Overview
Find The Best House: The 1234ABC Realtors limited is in great losses due to the autmoation in the industry and the new innovations and players in the real estate market . So they have hired a Data Science Team to give them a business solution so as to help regain their place in the market.

In order to do that, the group thought of a compiled way of grading the houses in order from a toe with respect to different aspects in mind. This would help them to rate the houses as well as different areas as well. So gear up and help the realtors get back their place in the market.

# Objective 
The objective of the problem is to predict values “Grade” attribute from the given features of the Test data.

# About the Dataset
<pre>Training File --> All features and the target variable is present in this file. Machine learning model 
                  would trained using this file. This file is to be used for training and validation.
Test File -->  This file has all the information we need to check how well the model works, based on 
               what it learned during training</pre>

<h1>Data Dictionary :</h1>
<h3>

*   Area(total) : Total area of the plot
*   Trooms : Total Number of rooms in the house
*   Nbedrooms : Number of bedroom in the house
*   Nbwashrooms : Number of washroom attached with bedroom
*   washrooms : total number of washroom in the house
* Roof : Does the house has roof(yes or no)
* Roof(Area) : Total area of the terrace
* Lawn(Area) : Area of the lawn including garden and parking
* Nfloor : Number of floors in the house
* API : Air purity index api is in percentage for example if api is 85 it means its 85% of the standard api for the city.
* ANB : Amenities near by amenities like hospital, park , multiplex , malls etc within 2 miles.
* Expected price : price expected by seller.
* Grade : Grade provided by company that depends on the condition and other features mentioned in the data. *(Note A is best garde and E is worst.)*</h3>

<h1>Summary: House Grade Prediction</h1>

<h3><p>We made our house grade predictions super accurate. We found that Support Vector Classification (SVC) worked really well for us and achieving an impressive accuracy of 98.6% on the test data.</p>
<p>By smartly removing a column and filling in missing info cleverly, we boosted our accuracy a lot. We tried out different methods, but SVC was the star. Even though our current method is doing great, we suggest trying more approaches. Who knows, there might be an even better way to predict house grades!</p></h3>

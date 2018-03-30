# Car-Popularity-Prediction

<h1> Problem Statement </h1>
<p> A car company has the data for all the cars that are present in the market. They are planning to introduce some new ones of their own, but first, they want to find out what would be the popularity of the new cars in the market based on each car's attributes.

We will provide you a dataset of cars along with the attributes of each car along with its popularity. Your task is to train a model that can predict the popularity of new cars based on the given attributes. </p>

<h1> Dataset </h1>
<p>ou are given a training dataset, <b>train.csv</b>. The file is a comma separated file with useful information for this task:</p>
<p><b>train.csv</b> contains the information about a car along with its popularity level. Each row provides information on each car. Information such as buying_price, maintenance_cost, number_of_doors, number_of_seats, etc. The definition of each attribute is as follows:<p>
<ul>
  <li><b>buying_price</b>: The buying_price denotes the buying price of the car, and it ranges from [1...4], where buying_price equal to 1 represents the lowest price while buying_price equal to 4 represents the highest price.</li>
  <li><b>maintenance_cost</b>: The maintenance_cost denotes the maintenance cost of the car, and it ranges from [1...4], where maintenance_cost equal to 1 represents the lowest cost while maintenance_cost equal to 4 represents the highest cost.</li>
  <li><b>number_of_doors</b>: The number_of_doors denotes the number of doors in the car, and it ranges from [2...5], where each value of number_of_doors represents the number of doors in the car.</li>
  <li><b>number_of_seats</b>: The number_of_seats denotes the number of seats in the car, and it consists of [2, 4, 5], where each value of number_of_seats represents the number of seats in the car.</li>
  <li><b>luggage_boot_size</b>: The luggage_boot_size denotes the luggage boot size, and it ranges from [1...3], where luggage_boot_size equal to 1 represents smallest luggage boot size while luggage_boot_size equal to 3 represents largest luggage boot size.</li>
  <li><b>safety_rating</b>: The safety_rating denotes the safety rating of the car, and it ranges from [1...3], where safety_rating equal to 1 represents low safety while safety_rating equal to 3 represents high safety.</li>
  <li><b>popularity</b>: The popularity denotes the popularity of the car, and it ranges from [1...4], where popularity equal to 1 represents an unacceptable car, popularity equal to 2 represents an acceptable car, popularity equal to 3 represents a good car, and popularity equal to 4 represents the best car.</li>
</ul>

<p>We also provide a test set of 100 car along with the above attributes excluding popularity, in test.csv. The goal is to predict the popularity of the car based on its attributes.</p>

    

<h1>Steps I followed:</h1>
<ol>
  <li>First I have an overview on the training data using and seperate the popularity dataset from the training one to the target one</li>
  <li>To import the csv file I uses pandas.read_csv() function</li>
  <li>Now I apply the RandomForestClassifier on the training datset with (n_estimator=20)</li>
  <li>This classifier is imported using : from sklearn.ensemble import RandomForestClassifier</li>
  <li>Now I train the model using this classifier</li>
  <li>And at last we predict the popularity of the test_data</li>
  <li>And check our accuracy by uploading it to the Hackerrank plateform</li>
  <li>I got the accuracy of <b>97.96%</b></li>
</ol>

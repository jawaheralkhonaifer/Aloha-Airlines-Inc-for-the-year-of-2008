# Aloha Airlines Inc for the year of 2008
Data visualization 
<h2>Flights</h2>

<h7>Hello all,

My project is about Aloha Airlines Inc for the year of 2008.

We will start reading the csv files of the flights data. Then 
exploring the data in general.
</h7>

<h5>Here are the columns in the data and there meaning</h5>
<ul>
<li>Year	2005-2008</li>
<li>Month	1-12</li>
<li>DayofMonth	1-31</li>
<li>DayOfWeek	1 (Monday) - 7 (Sunday)</li>
<li>DepTime	actual departure time (local, hhmm)</li>
<li>CRSDepTime	scheduled departure time (local, hhmm)</li>
<li>ArrTime	actual arrival time (local, hhmm)</li>
<li>CRSArrTime	scheduled arrival time (local, hhmm)</li>
<li>UniqueCarrier	unique carrier code</li>

<li>FlightNum	flight number</li>
<li>TailNum	plane tail number</li>
<li>ActualElapsedTime	in minutes</li>
<li>CRSElapsedTime	in minutes</li>
<li>AirTime	in minutes</li>
<li>ArrDelay	arrival delay, in minutes</li>
<li>DepDelay	departure delay, in minutes</li>
<li>Origin	origin IATA airport code</li>

<li>Dest	destination IATA airport code</li>
<li>Distance	in miles</li>
<li>TaxiIn	taxi in time, in minutes</li>
<li>TaxiOut	taxi out time in minutes</li>
<li>Cancelled	was the flight cancelled?</li>
<li>CancellationCode	reason for cancellation (A = carrier, B = weather, C = NAS, D = security)</li>
<li>Diverted	1 = yes, 0 = no</li>
<li>CarrierDelay	in minutes</li>
<li>WeatherDelay	in minutes</li>
<li>NASDelay	in minutes</li>
<li>SecurityDelay	in minutes</li>
<li>LateAircraftDelay	in minutes</li>
</ul>

<h3>Assesting the data</h3>

<h7>
will extract Aloha Airline's rows(Note that the code of Aloha Airlines Inc. is AQ).

While exploring the data, there were many problems needed to be cleaned in order to get better visualization.
which are:</h7>

>fix the data types of the data

>fix the date and combain the year month and date

>fix the time format

>fix the days by changing the number to the actal day name

>drop unneeded columns

>drop time values which are negative

<h3>Exploring the final dataset</h3>

<h7>
Exploring data will give you a good idea of what are the question that you want to ask and how to achive them.
First I started with doing general scatter_matrix to check the relationship between the data.
Second create a histogram for all the data to check the actual relation in the variables inside each column.
Third check the individual column.
    
To conclude the exploring the data

There are few questions need to be answered

1-What is the range of the delays in minutes? 

2-As the flight numbers are actual numerical values, which flight numbers have the most delays?

3-If the plane was delayed, will it has a late arrival?

4-Which are the origins that have the highest delays in minutes?

5-Is there canceled flights?

6-Which are the best places to travel with?
</h7>



# Bicing project

If you live in Barcelona you probably know that Bicing is a system of public bikes. Users can take a bike from numerous stations and use it for 30 mins without paying. The only cost is the annual fee of around 50 euros. That's basically what I spent on transport in Barcelona every year. Bicing is definitely one of the best things that Barcelona can offer their inhabitants. 

Since I am very frequent user of Bicing I started noticing patterns that would occur in certain locations at certain times. 
* It's hard to find a bike next to my house (La Sagrera) after 9.30 AM on weekdays but at the same time it's difficult to park it in Poblenou where I work. 
* All the stations close to the beach are full on weekends (specially on sunny days!)
* It's easier to find a bike on a rainy and cold day
* There are significantly more bikes in August.

There are many of those. That's why I decided to prove it with data.

I was collecting data from Bicing website between 22-Nov-2015 and 24-Dec-2016. A scraper running on PythonAnywhere would connect to the website, parse the json file and record the data in MySQL database.

There are a couple of weak points of my analysis:
* it ignores refills, when Bicing employees put bikes in certain stations
* PythonAnywhere was not always stable so there are few holes in the database

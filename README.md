The main question I want to answer is: How can I make money analyzing the CS2 market?

In the game Counter Strike 2 there are in-game cosmetic items that can be traded for real world money, there is a multi million dollar market revolving around these cosmetics. My plan is to use data APIs for the market and analyze this data to find signals to make money. I also plan on making an automated web scraper, if I'm allowed to use a package not taught in class, to trade skins and make myself some money using the strategies found in my data analysis.

Code description:

First source data analysis:

First I will do analysis on a CS2 market data API

This will require retrieving JSON from an API, cleaning the JSON into a pandas data frame, and analyzing the data frame using matplotlib.

In the data I am looking at short term trading volumes to find popular skins that I can exploit to make profit. Also I could look at unique characteristics of skins that are popular to add to my later automation to snag seemingly unwanted but valuable skins.

Second source data analysis:

Then I'm going to access another source, some type of social media or news site, to get information about game updates and events that could influence market price.

With the social media/news data I will analyze how historical updates and events affected the market prices of skins and make predictions on potential market fluctuations in the future. Using this analysis I could add notification systems to alert when such events may occur so I can make changes to automation scripts, and make more money :).

Third trading automation:

For this code I will use the Selenium, a python package that can be used for headless browsing, allowing python to use an internet browser. I promise to abide by any terms and conditions and respect robots.txt files.

This automation will go to SkinPort, a third party trading service, and pull down information on various items I could buy, filtered based on the analysis I did before, and run them through a series of tests to see if I want to buy it. The main parameters I will look at to determine if my script will purchase an item or not is the base price, and the percent discount from last sold. Once an Item passes the tests I will make selenium purchase the item. Then I will use parameters I will determine through my previous analysis to sell the items at a profit.

Roadblocks:

The main road block is getting permission to use the Selenium package, and getting it to work properly on the website. If any of this occurs I will focus on making a more robust trading strategy and just demonstrate it manually.

# Twitter-Scraper-Analyzer
A fully functional Python Application to scrape and analyze tweets

NOTE: I have only posted my contribution (the application) to a much larger project. This was part of my final capstone for my MS in Data Science at DePaul. I will also include our final report, which includes a large section describing the functonality of this application. Here is a brief summarized version:

The project began as a examination of Covid-19 tweets in relation of changing sentiments over time. I was incharge of finding a way of aquiring this data for the group. In the process of this, I got the idea to create a full fledge application to automate this process and include the analysis portion again. This way, ANYONE, regardless of their data science and computer science knowledge is capable of scaping and analyzing whatever data they please. The key was to create a simple and use to use/understand application.

The application features several different screens. Each screen features a help icon for additional instructions as needed. The home screen allows one to navigate to the scraping page, or the saved data page. The scraping page allows the user to fill in several key parameters such as the keywords to query twitter for, the date range, the number of interactions, etc. The tweets scraped are automatically stored in the data folder and accessible on the saved data page. On the saved data page, you can choose which data you'd like to analyze. This will process and open a 3 screen dashboard showing general information about the data, sentiment change over the time, and a more focused navigation that allows you to examine each individual tweet. 

This application relies on a modified version of the Twint python library to scrape tweets. The UI is created using the Kivy python library. The analysis uses various methods such as NLP.


HOW TO USE:

To use the application, download the folder listed in this repository. Then follow the instructions on the readme.txt.

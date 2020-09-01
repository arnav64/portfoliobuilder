These files are taken from a project created by Arnav Joshi, Sarthak Jain, Anush Chheda and Daniel Ssemanda for a class on Databases and Information Systems.

Problem Statement:
There is a lot of data available through several media outlets about companies that are publicly listed on stock exchanges. However Venture Capitalists, business research analysts and other investors might find it difficult to obtain information about startups and companies not publicly listed.

Project Description
* Our database holds information about startups from the early 1900s to very recent startups in 2014.
* The goal of our website is to ensure that investors can get sufficient information about the trends in the startup space over the years.
* We also want investors to look at company profiles i.e details about the company industry or location and details about the funding rounds that they carried out.
* Investors can then add the companies that they find interesting to their portfolios. Our facts page attempts to highlight some such companies with interesting characteristics.

Project Report: CIS550ProjectReport.pdf

Server-side Files
* db_config.js - Configuration file for connecting with database.
* index.js - Starts the server, links HTTP requests with their handlers in routes.js.
* routes.js - Contains functions that handle HTTP requests and return responses to the client.
* queryExecuter.js - Takes a query from the routes.js file, establishes a connection to the database and then executes the query.

Client-Side Files
* index.js - The javascript file first invoked when the React script is started.
* Home.js, Portfolio,js, and Facts.js - display the three main pages of the application. 
* TableView.js and SingleCompany.js - display the company profile for a single company.
* routes.js - This file declares all the routes to the different pages such as the Home page or the portfolio page.   





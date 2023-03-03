# Webscraping with Pandas

#### Project Overview:
In this project, we will be scraping a table from a website using Python and the pandas library. The website we will be scraping is a Wikipedia page that lists the most populated cities in Brazil. We will extract the data using the pandas library and then save it to a CSV file.

Step 1: Import the Required Libraries
First, we need to import the pandas library. To do this, we use the following code:

![image](https://user-images.githubusercontent.com/86577716/222773863-3ee9cc9d-3c25-430b-ac00-5261f873b646.png)

#### Step 2: Get the URL
Next, we need to specify the URL of the website that we want to scrape. In this case, we will be scraping the following Wikipedia page:

![image](https://user-images.githubusercontent.com/86577716/222774419-6f3aa5e1-9c4c-4b68-806f-6518cf6904fc.png)

#### Step 3: Read the Web Page
We can now read the web page using the read_html() function of the pandas library. This function will extract all the tables present on the web page and return a list of data frames. In our case, we are interested in the first table on the page, so we can use the following code to extract it:

![image](https://user-images.githubusercontent.com/86577716/222774744-f4e10545-96a6-457e-b6c7-2471db7b3ef9.png)

#### Step 4: Save the Data to a CSV File
Now that we have cleaned and processed the data, we can save it to a CSV file using the to_csv() function:

![image](https://user-images.githubusercontent.com/86577716/222774966-8c93aa24-801e-4bd8-b5bd-13b4a634554f.png)

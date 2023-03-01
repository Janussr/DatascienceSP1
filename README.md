# DataScienceMP1
Data Science Mini Project 1

The project is divded into four notebooks, **PS1**, **PS2**, **PS3** and **MP1**.

Data is carried over between notebooks through saving dataframes into files and placed in the data folder.

### Problem Solving 1
The goal of **Problem Solving 1** was to collect company data based on a delivered CSV file containing a list of students and which companies they spent their internships in. This was done through the API, **CVRAPI** where each unique company in the file was passed through. This resulted in a new file containing a broader amount of data for each company.

This data laid ground for further exploration and possibilities. Here we put the data through a geolocation library **GeoPy** based on the companies' addresses so we could get the latitude and longitude.

To conclude the assignment, we then used this latitude and longitude and put it through the **Folium** library to map out each company on a visualised map over Denmark.


### Problem Solving 2
We completed PS2 which involved experimenting with text vectorization and implementing it in Natural Language Processing. We loaded a CSV file with companies' data into a data frame and added a text feature containing the description of companies' activities if it wasn't already present. We applied a popular measure of distance between vectors to find the two closest companies in terms of their activities. We extended this by adding a column containing the web addresses of the companies and scraping information from the web pages. We then used cosine similarity to search for specific information we found relevant and explored the results.

To accomplish this, we used Python and various libraries, including Pandas, Scikit-learn, BeautifulSoup, and SentenceTransformers. We defined a function to calculate the cosine similarity between two vectors and another function to create a word vector from a sentence. We also used a pre-trained SentenceTransformer model to encode the text paragraphs we scraped from the web pages.

Overall, this assignment allowed us to gain hands-on experience with natural language processing techniques and to explore how they can be applied in real-world scenarios.


### Problem Solving 3
The goal of **Problem solving 3** was to explore the data and to get statistical information about the dataset such as mean, median, mode, min, max, range, count etc.

Next step was to prepare the data for further analysis we did this by replacing and removing unnecessary data or missing data. Drilling down/rolling up attributes coding the text data with numeral labels. we did this with the following libraries 
scipy.stats import shapiro
pandas as pd
import statistics

Afterwards we analyzed the correlations between the columns in the dataframe using the pandas corr() method.




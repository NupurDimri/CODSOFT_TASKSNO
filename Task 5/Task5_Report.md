# CODSOFT Internship — Task 5

# Web Scraping and Exploratory Data Analysis

---

## 1. Objective

The objective of this task is to collect publicly available data from a website using Python web-scraping libraries.

The analysis focuses on:

- Collecting structured book information
- Extracting book titles, prices, availability, and ratings
- Cleaning and organizing the scraped data
- Performing exploratory data analysis
- Identifying pricing and rating patterns
- Creating meaningful visualizations
- Exporting the final dataset to CSV and Excel

---

## 2. Website Used

The data was collected from:

**Books to Scrape**

The website provides publicly available book information for practicing web scraping.

The following information was collected:

- Book Title
- Price
- Availability
- Rating

---

## 3. Tools and Technologies

The following Python libraries were used:

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- OpenPyXL

---

## 4. Data Collection Method

The `requests` library was used to send HTTP requests to the website.

BeautifulSoup was then used to parse the HTML content and identify the required elements.

The scraper collected data from multiple pages of the website.

A total of:

**100 books**

were collected from the first five pages.

---

## 5. Web Scraping Process

The scraping process followed these steps:

1. Send an HTTP request to the website.
2. Retrieve the HTML page.
3. Parse the HTML using BeautifulSoup.
4. Locate individual book containers.
5. Extract the book title.
6. Extract the price.
7. Extract availability.
8. Extract the rating.
9. Store the information in a Python list.
10. Convert the list into a Pandas DataFrame.

---

## 6. Dataset Structure

The final dataset contains:

**100 records**

and:

**4 features**

| Column | Description |
|---|---|
| Title | Name of the book |
| Price | Book price in pounds |
| Availability | Stock availability |
| Rating | Rating from 1 to 5 |

---

## 7. Sample Dataset

| Title | Price | Availability | Rating |
|---|---:|---|---:|
| A Light in the Attic | £51.77 | In stock | 3 |
| Tipping the Velvet | £53.74 | In stock | 1 |
| Soumission | £50.10 | In stock | 1 |
| Sharp Objects | £47.82 | In stock | 4 |
| Sapiens: A Brief History of Humankind | £54.23 | In stock | 5 |

---

## 8. Data Cleaning

The scraped price values initially contained currency symbols and encoding characters.

For example:

`Â£51.77`

was cleaned to:

`51.77`

The price column was converted from text into a numerical data type.

Ratings were originally represented using text values such as:

- One
- Two
- Three
- Four
- Five

These were converted into numerical values:

| Rating | Numerical Value |
|---|---:|
| One | 1 |
| Two | 2 |
| Three | 3 |
| Four | 4 |
| Five | 5 |

---

## 9. Data Quality Check

The final dataset was checked for missing values.

Results:

| Column | Missing Values |
|---|---:|
| Title | 0 |
| Price | 0 |
| Availability | 0 |
| Rating | 0 |

Therefore, the final dataset contains **no missing values**.

Dataset shape:

**(100, 4)**

---

## 10. Descriptive Statistics

The `describe()` function was used to examine numerical variables such as price and rating.

The analysis included:

- Mean
- Standard deviation
- Minimum
- Maximum
- Quartiles

This helped understand the overall distribution of book prices and ratings.

---

## 11. Price Analysis

Book prices in the scraped dataset vary considerably.

The dataset contains books priced from relatively low values to prices above £50.

The most expensive book identified in the dataset was:

**The Death of Humanity: and the Case for Life**

Price:

**£58.11**

Rating:

**4 stars**

---

## 12. Rating Analysis

The rating column contains ratings from:

**1 to 5 stars**

The distribution of ratings was visualized using a bar chart.

This allows the distribution of book quality ratings in the scraped sample to be easily compared.

---

## 13. Average Price by Rating

The average price was calculated separately for each rating category.

The visualization showed that:

- 3-star books had the highest average price.
- 5-star books had the lowest average price.
- Prices were relatively similar across the rating categories.

This suggests that higher ratings do not necessarily correspond to higher prices.

---

## 14. Price and Rating Correlation

The Pearson correlation between price and rating was calculated.

Correlation:

**-0.1217**

This represents a **very weak negative relationship**.

Therefore, rating does not appear to be a strong predictor of book price in this dataset.

A higher rating does not necessarily mean that a book is more expensive.

---

## 15. Top 10 Most Expensive Books

The ten most expensive books were identified by sorting the dataset according to price.

| Rank | Book | Price | Rating |
|---:|---|---:|---:|
| 1 | The Death of Humanity: and the Case for Life | £58.11 | 4 |
| 2 | Slow States of Collapse: Poems | £57.31 | 3 |
| 3 | Our Band Could Be Your Life | £57.25 | 3 |
| 4 | The Past Never Ends | £56.50 | 4 |
| 5 | The Pioneer Woman Cooks: Dinnertime | £56.41 | 1 |
| 6 | Masks and Shadows | £56.40 | 2 |
| 7 | The Secret of Dreadwillow Carse | £56.13 | 1 |
| 8 | The Electric Pencil | £56.06 | 1 |
| 9 | Birdsong: A Story in Pictures | £54.64 | 3 |
| 10 | Sapiens: A Brief History of Humankind | £54.23 | 5 |

---

## 16. Visualization 1 — Price Distribution

A histogram was created to visualize the distribution of book prices.

The histogram helps identify:

- Common price ranges
- Spread of prices
- Concentration of books within particular price ranges

---

## 17. Visualization 2 — Rating Distribution

A bar chart was created showing the number of books for each rating from 1 to 5.

This visualization provides an easy comparison of rating frequencies.

---

## 18. Visualization 3 — Average Price by Rating

A bar chart was created to compare average prices across rating categories.

The visualization showed that 3-star books had the highest average price, while 5-star books had the lowest average price.

---

## 19. Visualization 4 — Price vs Rating

A scatter plot was created to examine the relationship between book price and rating.

The scatter plot, together with the correlation value of **-0.1217**, indicates that there is no strong linear relationship between the two variables.

---

## 20. Visualization 5 — Top 10 Expensive Books

A horizontal bar chart was created to display the ten most expensive books.

This makes it easy to compare the highest-priced books in the dataset.

---

## 21. Key Findings

The major findings from the analysis are:

1. A total of **100 books** were scraped.

2. The final dataset contains **4 columns**.

3. There were **0 missing values** in the final dataset.

4. Book prices vary across the scraped products.

5. The most expensive book was **The Death of Humanity: and the Case for Life**, priced at **£58.11**.

6. 3-star books had the highest average price among the rating groups.

7. 5-star books had the lowest average price.

8. The correlation between price and rating was **-0.1217**.

9. The relationship between price and rating is therefore very weak.

10. Higher-rated books are not necessarily more expensive.

---

## 22. Business Insights

The analysis provides several useful insights for an online bookstore or book marketplace.

### Pricing

Price does not appear to depend strongly on customer-facing rating.

Therefore, pricing decisions should consider additional factors such as:

- Book category
- Author popularity
- Publisher
- Demand
- Edition
- Production cost

### Ratings

A high rating does not necessarily correspond to a high price.

This means customers may find highly rated books across different price ranges.

### Product Strategy

A bookstore could promote highly rated books at competitive prices because rating and price appear to be relatively independent in this sample.

---

## 23. Exported Files

The final cleaned dataset was exported into two formats:

### CSV

`scaped_books.csv`

### Excel

`scraped_books.xlsx`

The notebook containing the complete scraping and analysis process is:

`Task5_Web_Scraping_Analysis.ipynb`

---

## 24. Conclusion

This task demonstrated how Python can be used to collect and analyze publicly available web data.

Requests was used to retrieve webpage content, while BeautifulSoup was used to extract structured information from HTML pages.

Pandas was used for data cleaning, transformation, and exploratory analysis. Matplotlib was used to create visualizations.

The analysis of 100 scraped books showed that book ratings and prices have only a very weak relationship, with a correlation of **-0.1217**.

The project demonstrates the complete data-analysis workflow:

**Web Scraping → Data Extraction → Data Cleaning → Exploratory Analysis → Visualization → Business Insights → Data Export**

---

## Project Structure

```text
Task 5/
│
├── Task5_Web_Scraping_Analysis.ipynb
├── scraped_books.csv
├── scraped_books.xlsx
└── Task5_Report.md
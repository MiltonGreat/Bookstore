# Bookstore

### Summary and Recommendations

#### 1. Overview

This project demonstrates the use of web scraping techniques to extract information from the website Books to Scrape. Using Python libraries like requests and BeautifulSoup, the project retrieves book details such as titles, prices, ratings, and categories, and visualizes the scraped data. The goal is to practice and learn web scraping, data analysis, and visualization.

#### 2. Data

Toscrape.com offers various websites that simulate real-world web scraping scenarios. You can practice your skills on books, quotes, login, viewstate, random and more endpoints with different challenges and features.

#### 3. Features

- Scraping Total Number of Books: Retrieves the total number of books available on the website.
- Book Categories and Counts: Scrapes all book categories and counts the number of books in each.
- Book Ratings and Prices: Extracts star ratings and prices for each book.
- Top 10 Highest-Rated Books: Displays the top 10 books based on ratings and price.
- Data Visualization: Visualizes: Distribution of book ratings, Distribution of book prices, Relationship between book prices and ratings
- Saving Data: The scraped data can be saved to CSV for further use.

#### 4. Data Scraped

- Categories: All book categories from the website.
- Books: Titles, ratings, and prices for individual books.
- Book Counts: Number of books in each category.

#### 5. Data Visualization

- Ratings Distribution: Displays the number of books per rating (1 to 5 stars).
- Price Distribution: Shows a histogram of book prices.
- Price vs. Rating Scatter Plot: Plots the relationship between book prices and ratings.

#### 6. Web Scraping Process
   
   1. Make Requests to the Website
   2. Scrape Total Number of Books
   3. Scrape Book Categories
   4. Count Books in Each Category
   5. Scrape Book URLs and Ratings
   6. Top 10 Highest-Rated Books
   7. Analyze Book Categories and Counts
   8. Visualize Data
   9. Save Data to CSV

#### 7. Key Findings
      
- Total Number of Books: The website contains 1000 books, as confirmed by the output of the get_total_books() function.
- Books per Category: Categories like Mystery, Fiction, Nonfiction, Fantasy, and Childrens have 20 books each. Some categories have significantly fewer books, such as Paranormal (1 book), Parenting (1 book), and Suspense (1 book).
- Top 10 Highest-Rated Books: The top 10 books, sorted by rating, show a mix of popular titles and high prices. The book Sapiens: A Brief History of Humankind is the most expensive among the top-rated books at £54.23, while other books like Set Me Free and The Coming Woman are more affordable.
- The distribution of books across categories shows a concentration of books in popular categories like Fiction and Nonfiction.
- The output also suggests that there are niche categories with very few books, such as Crime, Cultural, and Paranormal, which might indicate less content in these genres.

#### 8.  Source

https://books.toscrape.com/

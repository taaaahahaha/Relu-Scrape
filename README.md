# Relu Assignment Task - Amazon Scraping

### How i approached the problem :-

- I subdivided the problem into subproblems (Excel Reading/Url Forming and Web Scraping).
- Used modules : 
1. openpyxl for reading the data.
2. bs4 and requests for web scraping.
3. json for converting list of dictionaries to json.
4. time for calculating every set of 100 scraped urls.
- I noticed there was a different page structure for every amazon page with differenct country. Hence, i ran a sample script to get unique country codes. ({'de', 'it', 'es', 'fr'})
- I made observations and scraped data.


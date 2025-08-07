# Jumia Smartwatch Web Scraper 

This project uses **Playwright** to scrape smartwatch product data from [Jumia Egypt](https://www.jumia.com.eg). It extracts:

- Product Name
- Price
- Discount
- Rating
- Link
- Image URL

##  Output
Scraped data is saved to `jumia_smartwatches_playwright.csv`.

##  Notes
- Scraping speed is limited to under 200 requests/minute (1s delay).
- Only safe URLs are used (no filters).




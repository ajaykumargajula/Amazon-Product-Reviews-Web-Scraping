# Amazon-Reviews-Web-Scraping

Python code to extract user reviews and ratings from https://www.amazon.in

## Input : ASIN 
  - Every product in amazon has a unique identification number. This number is called ASIN — Amazon Standard Identification Number. Using the ASIN number, we can directly access every individual product.
- For an example https://www.amazon.in/Apple-iPhone-13-128GB-Starlight/dp/B09G9D8KRQ/ref=sr_1_3?keywords=iphone&qid=1658069332&sr=8-3. Here the ASIN for the URL mentioned  is B09G9D8KRQ
## Output: csv file with review data
The objective is to extract the following details from the Amazon Review web pages for a list of products
- Author Name
- Review Title
- User Rating
- Review Description
- Review Body
- Reviewed in Country
- Verified Purchase
- Information on how many people found the review helpfull

# Amazon_Scraper
Products and reviews scraper for Amazon.in

Usage:  
```
$ python scrape.py categories/sports.txt
```

Depends on:
- selenium
- pymongo

Modify the pymongo connection parameters within the scraper as per requirements  
The data structure mined by the scraper is defined within the scraper file itself.  

scrape.py: Scrape reviews
scrape_profile.py: Scrape User profiles
scrape_missing_brands.py: Scrape reviews for products on missing brands in the existing data

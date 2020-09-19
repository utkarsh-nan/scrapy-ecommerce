# Scrapy project for E-Commerce websites

This is a scrapy application with spiders to automate searching from e-commerce websites.


### Spiders included:

> The existing spiders are page-follower bots - retrieving all the listings from websites for the specified search term.

* craigslist_in (India)
* craigslist_us (USA)
* craigslist_ca (Canada)
* kijiji


### Usage:

```
$ cd ecommerce
$ pip install -r requirements.txt
$ scrapy crawl <spider-name> -a query="<search-term>" -o output.csv
```

### Possible feature enhancements:

- [ ] Price comparison from multiple websites
- [ ] Cron script - Price change notifier
- [ ] Integrate proxy switching

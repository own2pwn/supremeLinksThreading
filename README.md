# supremeLinksThreading
Supreme Threaded Bot that will scrape every links from supreme website and then export it as JSON

Uses BeautifulSoup, Requests, JSON, time, threading

This bot will use threading module to scrape URL from Supreme webshop and output it in JSON format ('item':'itemURL')

You can choose how many threads will scrape at the same time. There's a delay between every thread launching, so every thread will most likely looking to another page.

TO,DO:

- Handle exceptions. --- < 20%
- Delete colors from JSON data.  --- < DONE
- Add non stop scraping until user decides to end it. 
- Proxy support.
- Save it to a file for educational purpose only.   --- < DONE

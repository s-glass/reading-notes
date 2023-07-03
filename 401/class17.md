# 401 class 17 notes

**Why this matters**: This information matters because web scraping allows devs to collect, look at, and potentially manipulate large data sets from websites.

------------------------------------

**1. What are the key differences between scraping static and dynamic websites?**

Dynamic websites can update or load content after the initial HTML load, usually through AJAX or Single-Page Application (SPA) tech. Static websites display all the requested content on the page load.

[Source](https://scrapingant.com/blog/scrape-dynamic-website-with-python)

**2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.**

- **1. Make the crawling slower, do not slam the server, treat websites nicely**: Put some random programmatic sleep calls in between requests, add some delays after crawling a small number of pages and choose the lowest number of concurrent requests possible. Ideally, put a delay of 10-20 seconds between clicks and not put much load on the website, treating the website nice. Use auto throttling mechanisms which will automatically throttle the crawling speed based on the load on both the spider and the website that you are crawling. Adjust the spider to an optimum crawling speed after a few trial runs.


- **2. Don't follow the same crawling pattern**: Sites that have intelligent anti-crawling mechanisms can easily detect spiders by finding patterns in their actions and can lead to web scraping getting blocked. Incorporate some random clicks on the page, mouse movements and random actions that will make a spider look like a human.

- **3. Make requests through Proxies and rotate them as needed**: Multiple requests coming from the same IP will lead you to get blocked, which is why we need to use multiple addresses. When we send requests from a proxy machine, the target website will not know where the original IP is from, making the detection harder.

[Source](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

**3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.**

Playwright is a library that automatically controls browsers; it is a web sceraping tool that facilitates data extratction. Playwright could help with projects like price comparison, content aggregation, data mining, web analytics, and other vital business and marketing purposes.

[Source](https://scrapingant.com/blog/playwright-web-scraping-guide)

**4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.**

XPath is a technology that uses path expressions to select nodes or node-sets in an XML document. It allows you to write an expression which can directly point to a specific HTML element, or even tag attribute, without the need to manually iterate over any element lists.

The following expression selects the text content of <title>:

```/html/head/title/text()```

[Source](https://www.scrapingbee.com/blog/practical-xpath-for-web-scraping/)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!
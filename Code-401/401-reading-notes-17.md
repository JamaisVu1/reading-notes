# Reading 17

1.  What are the key differences between scraping static and dynamic websites?


Scraping static websites is simpler as it involves pulling data from fixed web pages, whereas dynamic websites require interacting with the page like a user to get the data that changes.

2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

To avoid being blocked when scraping websites, you should: Space out your requests to not overload the site, change your user identity and IP address often to avoid detection, and follow the site's rules for automated access, as listed in their robots.txt file.

3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

Playwright automates web browsers to help scrape websites that change or need actions like logging in. For example, it's great for getting data from a site where you must log in first to see the information.

4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.

XPath helps you pick out exact parts of a webpage when scraping, even if they don't have unique names. It's like giving directions to find a specific spot on a page. "//div[@class='content']/h1[1]" finds the first headline inside a section labeled 'content'.

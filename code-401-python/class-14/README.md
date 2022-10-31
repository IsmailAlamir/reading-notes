# Web Scraping

**Web Scraping**  is a technique to extract large amounts of data from websites.

### Web Scraping in Python(main steps)

In order to start we need the following libraries:

    import requests
    import urllib.request
    import time
    from bs4 import BeautifulSoup

Then we need to access the website:

    web_url = http://example.com
    res = requests.get(url)

After that we parse it with BeautifulSoup:

    soup = BeautifulSoup(res.text, “html.parser”)

Finally we can deal with the data

Don't make load on the website, by constantly downloading from it, as you might get blocked.
and to avoid getting blocked while web scraping:

- Try not to make so much load, you can do that by slowing the speed of downloading from these websites.
- Keep changing your scraping patterns.
- Use a headless browsers.
- Check if Website is Changing Layouts.
Avoid scraping data behind a login

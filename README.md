# mdb_crawler
## Prerequisites
1. The mdb_crawler uses selenium and BeautifulSoup to download all social media links from the bundestag.de website. You can use pip to install the two packages <code>pip install selenium bs4</code>.
2. Selenium needs a webdriver to navigate the website. Chromedriver is used in the notebook and you would therefore need to download chromedriver on your system. Please download chromedriver from <https://chromedriver.chromium.org/>, unzip the file and copy the path to chromedriver into the notebook.

## Chromedriver configuration
Chromedriver might not run unless the quarantine on the file is lifted. If you run <code>which chromedriver</code> an error might occur.\
Navigate to the directory of chromedriver on your machine in terminal and run <code>xattr -d com.apple.quarantine chromedriver</code> to lift the quarantine.\
Verify the success by running <code>which chromedriver</code> again without error.

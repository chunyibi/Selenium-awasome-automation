# Selenium-awasome-automation
This repository contains code and my thoughts while using selenium <br>
I learn Selenium on my own. It is a great tool to automate browsers and parse information on website. However, I encountered several probelms while using it and cound not always find solutions online. I post my solution here in order to help others with same problem. 
<ul>
<li>How to keep scrolling down to the bottom:
<ul>
from selenium import webdriver<br>
    browser = webdriver.Chrome("C:\Program Files (x86)\Google\Chrome\Application\chromedriver")<br>
    browser.get("https://www.kickstarter.com/discover/advanced?woe_id=23424977&sort=magic&seed=2619898&page=1")<br>
for i in range(100):<br>
<ul>
    browser.execute_script("window.scrollTo(0, document.body.scrollHeight);")<br>
    time.sleep(2)</ul>
</ul>
</ul>

# Selenium-awasome-automation
This repository contains code and my thoughts while using selenium <br>
I learn Selenium on my own. It is a great tool to automate browsers and parse information on website. However, I encountered several probelms while using it and cound not always find solutions online. I post my solution here in order to help others with same problem. 
<ul>
<li>How to keep scrolling down to the bottom:
<ul>
for i in range(100):<br>
<ul>
    browser.execute_script("window.scrollTo(0, document.body.scrollHeight);")<br>
    time.sleep(2)</ul>
</ul>
</ul>

# Selenium-awasome-automation
This repository contains code and my thoughts while using selenium <br>
I learn Selenium on my own. It is a great tool to automate browsers and parse information on website. However, I encountered several probelms while using it and cound not always find solutions online. I post my solution here in order to help others with same problem. 
<ul>
<li>How to keep scrolling down to the bottom: 1. scroll doen.ipnb
<li>When I tried to locate multiple elements using ".find_elements_by_class_name", it supposed to return a list of locations. However, it keeps return enpmty list. There are several reasos this will happen.
    <ol>
        <li>Limited response time
        <li>
         <li>frame issue
          <li> In my situation, the item I want to locate is in a table. Turns out you have to locate the row and column of table first, and use row/column index to locate target information. 
    </ol>
</ul>

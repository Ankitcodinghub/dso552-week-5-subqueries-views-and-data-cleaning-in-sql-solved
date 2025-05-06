# dso552-week-5-subqueries-views-and-data-cleaning-in-sql-solved
**TO GET THIS SOLUTION VISIT:** [DSO552 Week 5-Subqueries, Views, and Data Cleaning in SQL Solved](https://www.ankitcodinghub.com/product/dso552-week-5-subqueries-views-and-data-cleaning-in-sql-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96353&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSO552 Week 5-Subqueries, Views, and Data Cleaning in SQL Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Week 5: Subqueries, Views, and Data Cleaning in SQL

Subqueries and Views

<ol>
<li>What is the lifetime average amount spent in USD for the top 10 total spending accounts?</li>
<li>For the customer/account that spent the most (in total over their lifetime as a customer) total_amt_usd, how many web_events did they have for each channel?</li>
<li>Which channel was the most frequently used by different accounts?</li>
<li>YOUR TURN Provide the name of the sales_rep in each region with the largest amount of to- tal_amt_usd sales.</li>
</ol>
Subqueries using ‘WITH’

<ol start="5">
<li>What is the lifetime average amount spent in terms of total_amt_usd for the top 10 total spending accounts?</li>
<li>For the customer/account that spent the most (in total over their lifetime as a customer) total_amt_usd, how many web_events did they have for each channel?</li>
<li>Provide the name of the sales_rep in each region with the largest amount of total_amt_usd sales.</li>
</ol>
Data Cleaning LEFT and RIGHT

<ol start="8">
<li>In the accounts table, there is a column holding the website for each company. The last three digits specify what type of web address they are using. Pull these extensions and provide how many of each website type exist in the accounts table.</li>
<li>There is much debate about how much the name (or even the first letter of a company name) matters. Use the accounts table to pull the first letter of each company name to see the distribution of company names that begin with each letter (or number).</li>
<li>Use the accounts table and a CASE statement to create two groups: one group of company names that start with a number and a second group of those company names that start with a letter. What proportion of company names start with a letter?</li>
</ol>
POSITION &amp; STRPOS

11. Use the accounts table to create first and last name columns that hold the first and last names for the primary_poc.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CONCAT

12. Each company in the accounts table wants to create an email address for each primary_poc. The email address should be the first name of the primary_poc last name primary_poc @ company name .com.

13. You may have noticed that in the previous solution some of the company names include spaces, which will certainly not work in an email address. See if you can create an email address that will work by removing all of the spaces in the account name, but otherwise your solution should be just as in the previous question. (Hint: lookup replace)

14. We would also like to create an initial password, which they will change after their first log in. The first password will be the first letter of the primary_poc’s first name (lowercase), then the last letter of their first name (lowercase), the first letter of their last name (lowercase), the last letter of their last name (lowercase), the number of letters in their first name, and then the name of the company they are working with, all capitalized with no spaces.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>

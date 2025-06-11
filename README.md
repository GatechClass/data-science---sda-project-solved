# data-science---sda-project-solved
**TO GET THIS SOLUTION VISIT:** [Data-Science – SDA Project Solved](https://mantutor.com/product/data-science-sda-project-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114949&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Data-Science - SDA Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
Project description

You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.

Description of the plans

Surf

Monthly charge: $20

500 monthly minutes, 50 texts, and 15 GB of data

After exceeding the package limits: – 1 minute: 3 cents – 1 text message: 3 cents – 1 GB of data: $10

Ultimate

Monthly charge: $70

3000 monthly minutes, 1000 text messages, and 30 GB of data

After exceeding the package limits: – 1 minute: 1 cent – 1 text message: 1 cent – 1 GB of data: $7

Instructions on completing the project

Step 1. Open the data file and study the general information

File path:

/datasets/megaline_calls.csv

/datasets/megaline_internet.csv

/datasets/megaline_messages.csv

/datasets/megaline_plans.csv

/datasets/megaline_users.csv

Step 2. Prepare the data

Convert the data to the necessary types

Find and eliminate errors in the data

Explain what errors you found and how you removed them.

For each user, find:

The number of calls made and minutes used per month

The number of text messages sent per month

The volume of data per month

The monthly revenue from each user (subtract the free package limit from the total number of calls, text messages, and data; multiply the result by the calling plan value; add the monthly charge depending on the calling plan)

Step 3. Analyze the data

Describe the customers’ behavior. Find the minutes, texts, and volume of data the users of each plan require per month. Calculate the mean, variance, and standard deviation. Plot histograms. Describe the distributions.

Step 4. Test the hypotheses

The average revenue from users of Ultimate and Surf calling plans differs.

The average revenue from users in NY-NJ area is different from that of the users from other regions.

You decide what alpha value to use.

Explain:

How you formulated the null and alternative hypotheses.

What criterion you used to test the hypotheses and why.

Step 5. Write an overall conclusion

Description of the data

Megaline rounds seconds up to minutes, and megabytes to gigabytes. For calls, each individual call is rounded up: even if the call lasted just one second, it will be counted as one minute. For web traffic, individual web sessions are not rounded up. Instead, the total for the month is rounded up. If someone uses 1025 megabytes this month, they will be charged for 2 gigabytes.

The users table (data on users):

user_id â€” unique user identifier first_name â€” user’s name last_name â€” user’s last name age â€” user’s age (years)

The calls table (data on calls):

duration â€” call duration (in minutes) user_id â€” the identifier of the user making the call

The messages table (data on texts):

The internet table (data on web sessions):

The plans table (data on the plans):

plan_name â€” calling plan name

usd_monthly_fee â€” monthly charge in US dollars minutes_included â€” monthly minute allowance messages_included â€” monthly text allowance

mb_per_month_included â€” data volume allowance (in megabytes) usd_per_minute â€” price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)

usd_per_message â€” price per text after exceeding the package limits

usd_per_gb â€” price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)

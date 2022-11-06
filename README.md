<h1>Project description</h1>
You've done beautifully in the Practicum course, and you've been offered an internship in the analytical department at Yandex.Afisha. Your first task is to help optimize marketing expenses.

<br><b>You have:</b>
<ul><li>Server logs with data on Yandex.Afisha visits from June 2017 through May 2018</li>
<li>Dump file with all orders for the period</li>
<li>Marketing expenses statistics</li></ul>

<br><b>You are going to study:</b>
<ul><li>How people use the product</li>
<li>When they start to buy</li>
<li>How much money each customer brings</li>
<li>When they pay off</li></ul>

<h2>Instructions for completing the project</h2>
<h3>Step 1. Download the data and prepare it for analysis</h3>
Store the data on visits, orders, and expenses in variables. Optimize the data for analysis. Make sure each column contains the correct data type.
Download dataset

<h3>Step 2. Make reports and calculate metrics:</h3>
<ol><li>Product</li></ol>
<ul><liHow many people use it every day, week, and month?</li>
<li>How many sessions are there per day? (One user might have more than one session.)</li>
<li>What is the length of each session?</li>
<li>What's the user retention rate?</li></ul>
Sales
When do people start buying? (In KPI analysis, we're usually interested in knowing the time that elapses between registration and conversion — when the user becomes a customer. For example, if registration and the first purchase occur on the same day, the user might fall into category Conversion 0d. If the first purchase happens the next day, it will be Conversion 1d. You can use any approach that lets you compare the conversions of different cohorts, so that you can determine which cohort, or marketing channel, is most effective.)
How many orders do they make during a given period of time?
What is the average purchase size?
How much money do they bring? (LTV)</li></ul>
Marketing
How much money was spent? Overall/per source/over time
How much did customer acquisition from each of the sources cost?
How worthwhile where the investments? (ROI)
Plot graphs to display how these metrics differ for various devices and ad sources and how they change in time.
Step 3. Write a conclusion: advise marketing experts how much money to invest and where.
What sources/platforms would you recommend? Back up your choice: what metrics did you focus on? Why? What conclusions did you draw after finding the metric values?
Format: Complete the task in Jupyter Notebook. Enter the code in code cells and text explanations in markdown cells. Apply formatting and headings.
Description of the data
The visits table (server logs with data on website visits):
Uid — user's unique identifier
Device — user's device
Start Ts — session start date and time
End Ts — session end date and time
Source Id — identifier of the ad source the user came from
All dates in this table are in YYYY-MM-DD format.
The orders table (data on orders):
Uid — unique identifier of the user making an order
Buy Ts — order date and time
Revenue — Yandex.Afisha's revenue from the order
The costs table (data on marketing expenses):
source_id — ad source identifier
dt — date
costs — expenses on this ad source on this day

<h1>Project description</h1>
You've done beautifully in the Practicum course, and you've been offered an internship in the analytical department at Yandex.Afisha. Your first task is to help optimize marketing expenses.

<br><b>You have:</b>
<ul><li>Server logs with data on Yandex.Afisha visits from June 2017 through May 2018</li>
<li>Dump file with all orders for the period</li>
<li>Marketing expenses statistics</li></ul>

<b>You are going to study:</b>
<ul><li>How people use the product</li>
<li>When they start to buy</li>
<li>How much money each customer brings</li>
<li>When they pay off</li></ul>

<h2>Instructions for completing the project</h2>
<h3>Step 1. Download the data and prepare it for analysis</h3>
Store the data on visits, orders, and expenses in variables. Optimize the data for analysis. Make sure each column contains the correct data type.

Download dataset

<h3>Step 2. Make reports and calculate metrics:</h3>
<b>Product</b>
<ul><li>How many people use it every day, week, and month?</li>
<li>How many sessions are there per day? (One user might have more than one session.)</li>
<li>What is the length of each session?</li>
<li>What's the user retention rate?</li></ul>

<b>Sales</b>
<ul><li>When do people start buying? (In KPI analysis, we're usually interested in knowing the time that elapses between registration and conversion — when the user becomes a customer. For example, if registration and the first purchase occur on the same day, the user might fall into category Conversion 0d. If the first purchase happens the next day, it will be Conversion 1d. You can use any approach that lets you compare the conversions of different cohorts, so that you can determine which cohort, or marketing channel, is most effective.)</li>
<li>How many orders do they make during a given period of time?</li>
<li>What is the average purchase size?</li>
<li>How much money do they bring? (LTV)</li></ul>

<b>Marketing</b>
<ul><li>How much money was spent? Overall/per source/over time</li>
<li>How much did customer acquisition from each of the sources cost?</li>
<li>How worthwhile where the investments? (ROI)</li></ul>

Plot graphs to display how these metrics differ for various devices and ad sources and how they change in time.
  
<h3>Step 3. Write a conclusion: advise marketing experts how much money to invest and where</h3>

What sources/platforms would you recommend? Back up your choice: what metrics did you focus on? Why? What conclusions did you draw after finding the metric values?

Format: Complete the task in Jupyter Notebook. Enter the code in code cells and text explanations in markdown cells. Apply formatting and headings

<h4>Description of the data</h4>
The visits table (server logs with data on website visits):
<ul><li>Uid — user's unique identifier</li>
<li>Device — user's device</li>
<li>Start Ts — session start date and time</li>
<li>End Ts — session end date and time</li>
<li>Source Id — identifier of the ad source the user came from</li></ul>

All dates in this table are in YYYY-MM-DD format

The orders table (data on orders):
<ul><li>Uid — unique identifier of the user making an order</li>
<li>Buy Ts — order date and time</li>
<li>Revenue — Yandex.Afisha's revenue from the order</li></ul>

The costs table (data on marketing expenses):
<ul><li>source_id — ad source identifier</li>
<li>dt — date</li>
<li>costs — expenses on this ad source on this day</li></ul>

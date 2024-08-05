User-Login-Analysis-Using-SQL

User_Login_Analysis_Using_SQL
Introduction
The following analysis involves a detailed examination of user login behavior and activity patterns within our system. The insights derived from this analysis will aid in understanding user engagement, identifying trends, and making data-driven decisions to enhance user retention and activity.

Objective
The primary objectives of this analysis are:

Identify users who have not logged in within the last 5 months.
Evaluate quarterly user activity, including user counts and session counts.
Identify users who logged in during January 2024 but did not log in during November 2023.
Calculate the percentage change in sessions from the last quarter.
Determine the user with the highest session score for each day.
Identify best users who have logged in every single day since their first login.
Identify dates with no login activity.

Analysis & Recommendations:

The percentage change in session count from one quarter to the next is calculated. This metric is crucial for
understanding growth or decline in user activity over time.
The query identifies users who have logged in every single day since their first login. These users are
considered the most consistent and engaged, valuable for loyalty programs and rewards.
This analysis identifies dates with no login activity at all. Understanding these patterns can help in
recognizing periods of low engagement and addressing potential underlying issues.
This analysis determines the user with the highest session score for each day. This can help in identifying
highly engaged users on a daily basis.
The query identifies users who were active in January 2024 but inactive in November 2023. This helps in
understanding seasonal or month-to-month variations in user activity.
This analysis calculates the total number of distinct users and sessions for each quarter. It returns the first
day of each quarter along with these counts, providing insights into user engagement trends over time.
The query identifies users who have not logged into the system in the past 5 months. This helps in targeting
re-engagement campaigns to bring these users back to the platform

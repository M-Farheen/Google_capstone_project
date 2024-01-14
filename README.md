![alt text](https://images.ctfassets.net/p6ae3zqfb1e3/56CyOlsd059elNkbFv8W3J/1125288367133cb3c55d2766be02f581/Divvy_Homepage_Reinvent_your_routine_2x.png?w=1500&q=60&fm=webp)


# Google_capstone_project
Cyclistic bike share dataset

Google Data Analytics Capstone Project
Cyclistic Dataset

Case Study: How Does a Bike-Share Navigate Speedy Success?

Introduction

Welcome to the Cyclistic bike-share analysis case study! In this case study, you will perform many real-world tasks of a junior data analyst. You will work for a fictional company, Cyclistic, and meet different characters and team members. In order to answer the key business questions, you will follow the steps of the data analysis process: ask, prepare, process, analyze, share, and act. Along the way, the Case Study Roadmap tables — including guiding questions and key tasks — will help you stay on the right path.

Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations. Characters and teams

add Codeadd Markdown
Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.

Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. You joined this team six months ago and have been busy learning about Cyclistic’s mission and business goals — as well as how you, as a junior data analyst, can help Cyclistic achieve them.

Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

This project will be completed using the 6 stages of Data Analysis 

Ask: In this stage the key business questions will be identified along with the stakeholders
Prepare: Collect the data, identify how it’s organized, determine the credibility of the data.
Process: Select the tool for data cleaning, check for errors and document the cleaning process.
Analyze: Organize and format the data, aggregate the data so that it’s useful, perform calculations and identify trends and relationships.
Share: Use design thinking principles and data-driven storytelling approach, present the findings with effective visualization. Ensure the analysis has answered the business task.
Act: Share the final conclusion and the recommendations.
STAGE 1
ASK

Task: Identify the types of membership and analyse them to figure out their modes of use and prepare a marketing strategy to convert casual rider into annual members.

Stakeholders: Lily Moreno: Director of marketing and manager Cyclistic Executive Team: A team who will decide whether to approve the recommended marketing program or not Cyclistic marketing analytics Team: A team of data analysts responsible for collecting, analyzing, and reporting data

STAGE 2
Prepare

For this project, I will use the public data of Cyclistic’s historical trip data to analyze and identify trends. The data has been made available by Motivate International Inc. under the license.

I downloaded the dataset zip file from Jan 2023 to Dec 2023 , the same dataset has been made available in the input section of this Notebook.

Data overview

ride_id: It is a distinct identifier assigned to each individual ride.
rideable_type: This column indicates the type of bikes used for each ride.
started_at: This column denotes the timestamp when a particular ride began.
ended_at: This column represents the timestamp when a specific ride concluded.
start_station_name: This column contains the name of the station where the bike ride originated.
start_station_id: This column represents the unique identifier for the station where the bike ride originated.
end_station_name: This column contains the name of the station where the bike ride concluded.
end_station_id: This column represents the unique identifier for the station where the bike ride concluded.
start_lat: This column denotes the latitude coordinate of the starting point of the bike ride.
start_lng: This column denotes the longitude coordinate of the starting point of the bike ride.
end_lat: This column denotes the latitude coordinate of the ending point of the bike ride.
end_lng: This column denotes the longitude coordinate of the ending point of the bike ride.
member_casual: This column indicates whether the rider is a member or a casual user.
I have used Microsoft Excel to get a glimpse of the data . the data set use each file for each month.

STAGE 3 & STAGE 4
Process & Analyze

I will be using kaggle notebook to present my analysis and documenting EDA , Vizualization and Insight. I will be using python as a data processing language throughout this notebook, starting with installing and importing necessary libraries in this notebook.


STAGE 5
Share

As per the data members share a high percentage of riders than casual.

Average ride durations vary across different days of the week for both casual and member riders. Casual riders have longer average ride durations than members.

Top 10 stations preferred by riders are somewhat same for casuals and members .


STAGE 6
ACT

Three Recommendation as per the analysis would be:

Implement targeted marketing campaigns around Top Stations to further increase engagement. Implement station-specific enhancements during the evenings, such as additional amenities, events, or promotions.

Create targeted marketing messages that address the longer ride durations experienced by casual riders and showcase how an annual membership can offer cost-effective and convenient solutions for their longer rides.

Highlight exclusive benefits such as member-only events, priority access, or special discounts to encourage casual riders to convert to annual memberships & loyalty programs or rewards for members who use the service frequently

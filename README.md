# engagementAnalysis
A key indicator of engagement for a mobile app is session length. This repository contains two SQL queries to track average session length on a weekly basis, as well as total number of sessions over the course of the week.

# Sample Data Set
The sample data set is reflective of a common analytics data format. 

# Assumptions
1. I have considered a user session to still be active if subsequent event takes place within 5 minutes of the previous event. 
2. For the sake of the analysis, I have also excluded sessions that last under 2 minutes in length, as these are not representative of actual product engagements.
3. Also excluded Email and Push notification events.



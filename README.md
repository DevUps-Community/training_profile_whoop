# Client Profile with Metrics Mini Project

## Objective
Build a client profile system with metrics and graphical views for tracking weight and other metrics.

## Features to Implement
1. **User Registration and Login:**
   - Create user accounts with registration and authentication.
2. **Profile Creation:**
   - Allow users to create and update their profiles.
3. **Metrics Tracking:**
   - Track various metrics such as weight, body fat percentage, etc.
4. **Graphical View:**
   - Display metrics in graphical format for easy tracking.

## Description
This project aims to build a client profile system with metrics and graphical views for tracking weight and other metrics.

**Aspects to Consider:**

- **Schema Design:**
  - Plan how to store user profiles, metrics data, and historical records.
  - Consider how to efficiently aggregate and query data for reporting.

- **React App Design:**
  - Design components for profile creation, metrics input, and graphical visualisation.
  - Use a graphing library to display metrics trends over time.

- **Best Practices:**
  - Ensure data privacy and security for user profiles and metrics.
  - Implement clear and accurate data visualisations.
  - Provide a responsive and intuitive user interface for profile and metrics management.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React
- **Graphing Library:** Chart.js or similar

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement user registration and login with Supabase Auth.
3. **Profile and Metrics API:**
   - Create endpoints to add, update, delete, and fetch profile details and metrics.
4. **Frontend:**
   - Build React components for registration, login, profile creation, and metrics tracking.
   - Use a graphing library to visualise metrics.


## Challenge
 - Integrate Whoop metrics if the user has a Whoop subscription.
Documentation: https://developer.whoop.com/api/

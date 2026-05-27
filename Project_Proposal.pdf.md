Capstone Project Proposal
Gym & Fitness Education App
Project Overview

The Gym & Fitness Education App is designed to help users improve their fitness by providing workout plans, exercise tutorials, nutrition guidance, and progress tracking tools. The application will support users in achieving fitness goals such as weight loss, muscle gain, strength improvement, and healthier lifestyles.

The goal is to create a platform that makes fitness education and workout planning accessible through mobile and web applications.

1. Tech Stack
Frontend (Mobile & Web)
React Native
Cross-platform mobile app development (iOS & Android)
React.js
Web application development
Responsive and interactive UI
Backend
Node.js + Express.js
REST API development
Authentication
Server-side logic
Database
MongoDB
Store workouts, nutrition plans, user data, and progress tracking
Hosting / Deployment
Backend: Render / Heroku
Frontend: Vercel / Netlify
Database: MongoDB Atlas
2. Project Focus

This project will be an evenly focused full-stack application.

Frontend focus:

User-friendly fitness dashboard
Workout tracking UI
Exercise browsing
Progress charts

Backend focus:

User accounts
Workout storage
Progress tracking
APIs and database management
3. Project Type

The project will include:

Mobile App

Available on:

Android
iOS

Built using React Native.

Website

Accessible through browsers for users who prefer desktop access.

4. Project Goal

The main goal is:

Help users achieve fitness goals through workout plans, exercise education, and progress monitoring.

Additional goals:

Encourage healthy habits
Provide exercise guidance
Track fitness progress
Support beginners and experienced gym users
5. Target Users (Demographic)

Primary users include:

Beginners

Users starting fitness journeys.

Gym Members

People looking for workout routines and progress tracking.

Athletes & Fitness Enthusiasts

Users focused on strength training, bodybuilding, or performance improvement.

Personal Trainers

Professionals wanting to manage or share workout plans.

6. Data and API Plan

The application may use:

Workout Data

Examples:

Exercise names
Sets
Reps
Difficulty level
Muscle groups
Nutrition Data

Examples:

Calories
Protein
Meal suggestions
Progress Data

Examples:

Weight changes
Workout history
Fitness goals
Data Collection

Data may come from:

Custom-built APIs
Fitness APIs
User-generated workout records
Project Development Approach
Database Schema
Users
User
-id
-name
-email
-password
-age
-weight
-fitnessGoal
-createdAt
Workouts
Workout
-id
-exerciseName
-muscleGroup
-sets
-reps
-duration
-difficulty
Progress Tracking
Progress
-id
-userId
-weight
-workoutCompleted
-date
Potential API Challenges

Possible issues:

Large Data Handling

Workout libraries can become large.

Real-Time Updates

Progress tracking requires accurate updates.

Data Accuracy

Exercise information must remain reliable.

Security Considerations

Sensitive data may include:

User accounts
Emails
Passwords
Fitness progress records

Security measures:

JWT authentication
Password hashing
Environment variables
HTTPS encryption
Planned Features
Must Have Features

✔ User registration/login
✔ Workout plans
✔ Exercise search
✔ Progress tracking
✔ Nutrition guidance
✔ Mobile responsive design

User Flow

Typical journey:

Step 1

User creates account

↓

Step 2

Select fitness goal

Examples:

Weight loss
Muscle gain
Strength

↓

Step 3

Receive workout recommendations

↓
Step 4

Track workouts and progress

↓

Step 5

View improvement reports

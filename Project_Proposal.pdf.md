Capstone Step 2 – Project Proposal
Project Title:

DevTrack – Learning & Project Management Platform for Beginner Developers

1. Tech Stack

Frontend

React (Vite)
CSS / Tailwind CSS
React Router
Axios

Backend

Node.js
Express.js

Database

MongoDB with Mongoose

Authentication

JWT (JSON Web Tokens)
bcrypt for password hashing

Deployment

Frontend: Vercel
Backend: Render
Database: MongoDB Atlas

Version Control

Git + GitHub
2. Focus of Project

This will be an evenly focused full-stack application.

Frontend focus:

User-friendly dashboard
Responsive design
Progress visualization

Backend focus:

Authentication
Database management
API creation
User data storage
3. Project Type

This project will be a:

✓ Website (responsive desktop + mobile)

Future stretch goal:

✓ Mobile app using React Native

4. Goal of Project

The goal is to help beginner programmers organize:

Learning progress
Coding projects
Notes
Tasks
Deadlines
Resources

Users can create accounts and monitor their growth over time.

5. User Demographic

Target users:

Beginner developers
Coding bootcamp students
Computer science students
Self-taught programmers

Age group:

16–35 years old

6. Data & API Plan

Data stored:

Users:

Name
Email
Password (hashed)

Projects:

Title
Description
Status
Deadline

Tasks:

Completion state
Priority
Due date

Resources:

URLs
Notes

Data collection:

User-generated data through forms.

Potential external APIs:

GitHub API
Coding challenge APIs
Project Breakdown
Database Schema
Users Collection
User
_id
name
email
password
createdAt
Projects Collection
Project
_id
userId
title
description
status
deadline
Tasks Collection
Task
_id
projectId
title
completed
priority

Relationships:

One User → Many Projects

One Project → Many Tasks

Potential API Issues

Possible challenges:

Authentication errors
Expired JWT tokens
Slow API responses
Invalid data submissions
MongoDB connection problems

Solutions:

Validation
Error handling
Loading states
Retry mechanisms
Sensitive Information

Need to secure:

Passwords
Emails
Authentication tokens

Security methods:

bcrypt hashing
JWT auth
Environment variables (.env)
HTTPS
Functionality

Must-have features:

✓ Register account

✓ Login/logout

✓ Create projects

✓ Add tasks

✓ Edit/delete tasks

✓ Track progress

✓ Dashboard

✓ Search functionality

✓ Responsive UI

User Flow

Typical user journey:

Homepage

↓

Create Account

↓

Login

↓

Dashboard

↓

Create Project

↓

Add Tasks

↓

Track Progress

↓

Edit/Delete Tasks

Features Beyond CRUD

Additional features:

Progress charts
Learning streak tracking
Notifications
Dark mode
GitHub integration

These make the project more advanced than standard CRUD operations.

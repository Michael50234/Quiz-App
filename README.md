# Quiz App

## Introduction

Welcome to the Github repository for my project **Quiz App**! Quiz App is a web application that allows users to create, share, and play quizzes. Users can browse quizzes, create, edit, and delete their own quizzes, upload images (e.g., quiz cover images and question images), view past quiz attempts, and create a personalized profile.

## Project Overview

The core functionality of the application is centered around CRUD operations for quizzes, enabling users to create, view, update, and delete quiz content. The app also features a user-friendly user interface that gives users access to these operations, displays data retrieved from the database, such as quizzes and past attempts, and provides an interactive environment for users to play quizzes.

### Frontend
- **Technologies Used**: TypeScript, MUI (Material UI), React, Next.js
- **Description**: The frontend provides an interactive interface that allows users to create and manage their own quizzes, search for other user's quizzes, and play quizzes. It also lets users customize their profile information and view their past quiz attempts. It uses a protected page component and a global user state for authentication and authorization.

### Backend
- **Technologies Used**: Python, Django, DRF (Django Rest Framework)
- **Description**: The backend saves data to the database, serves data from the database to the frontend, and enforces authentication and authorization. Authentication is implemented using JWT tokens, verifying user identity and securing API requests, and authorization logic is enforced through DRF permission classes, allowing control to access to resources based on user roles and ownership. In addition, the backend issues Firebase Custom Tokens, allowing the frontend to authenticate with Firebase services such as Cloud Storage. Request input validation is handled using DRF serializers, ensuring ensuring incoming data is safe and usable.

### Database
- **Technologies Used**: MySQL
- **Description**: The database allows for the persistence of quizzes, user information, and quiz attempts. It also defines relationships between different models/tables, such as quiz ownership, allowing for efficent data retrival and connecting related data. 

### Cloud Storage
- **Technologies Used**: Firebase
- **Description**: Firebase, specifically firebase cloud storage, is used for the persistence of user uploaded images. 

### Key Features
- Creating, updating, viewing, and deleting quizzes
- Playing quizzes
- Searching and filtering for quizzes
- Viewing past quiz attempts
- Creating a personalized profile

## Demo
[Test the app here](https://quiz-app-frontend-production-b8c1.up.railway.app/)


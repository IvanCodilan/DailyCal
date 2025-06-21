# DailyCals

![Calorie Tracker Banner](![Image](https://github.com/user-attachments/assets/c3cef0ab-05c7-4f8e-808d-e1148252c2d9)) 

**DailyCals** is a calorie and activity tracking Android application. It helps users log meals, exercises, and compute their BMI while tracking nutritional insights. Built in Java, the app offers an intuitive interface and offline support using SQLite.

## Overview

DailyCals is a mobile app designed to assist users in monitoring daily food intake, physical activities, and progress. It consolidates data into a user-friendly dashboard, allowing users to stay on top of their nutrition and fitness goals without an internet connection.

## Requirements

- Android Studio (Arctic Fox or later)
- Android SDK 21+
- A physical Android device or emulator
- USB debugging enabled
- Gradle 7.0+ (Kotlin DSL compatible)

## Features

### 1. Add Food Intake
Log meals and snacks by specifying food names, calorie amounts, and timestamps.  
> Activity: `AddFoodActivity.java`

### 2. Track Physical Activity
Record exercises with calorie burn estimates and activity duration.  
> Activity: `ActivityAddActivity.java`, `ActivityLogActivity.java`

### 3. Dashboard Summary
Displays total calorie intake, burned calories, and nutritional breakdown (e.g., fats, carbs, proteins) for the day.  
> Activity: `MainActivity.java`

### 4. View History
Browse historical data of both food and activity logs for better trend tracking.  
> Activity: `HistoryActivity.java`

### 5. BMI Calculator
Compute your Body Mass Index using your weight and height inputs.  
> Activity: `BMIActivity.java`

### 6. Login System
Provides a simple login interface to secure user access.  
> Activity: `LoginActivity.java`

### 7. SQLite Local Database
All records are stored and retrieved locally using a structured SQLite database.  
> Class: `DatabaseHelper.java`

## Sample Screenshots

*(Insert UI screenshots here to showcase main screens)*

## Demo Video
*Coming soon…*

## Developer
- Ivan Codilan

## Adviser
- [Insert Adviser Name]

## School Name
[Insert School Name]  
College of Computer Studies / IT Department  
[Insert School Address or Campus Name]

## Course
- Bachelor of Science in Computer Science

## Date
- June 2025

# Bet Web Application

## Overview
Bet is a web application built for Gen Z thrill-seekers where users can post challenges for other users to take on. The application is developed using React and Supabase.

## Features
### Required Features
- **CRUD Operations**: Users can create, read, update, and delete challenges.
- **Homepage Display**: All submitted challenges are displayed on the homepage.
- **Create Form**: Users can submit a new challenge via a create form.
- **Update Challenge**: Challenges can be updated after submission.
- **Delete Challenge**: Challenges can be deleted after submission.

### Stretch Features
- **Bet Count Tracking**: The application tracks the bet count for each challenge. When a user clicks the bet button, the count is updated and saved to the database.
- **User Acceptance Display**: The total number of users who have accepted each challenge is displayed.

## 🎯 Goals
By completing this lab, you will be able to:
- Set up a database for an application using Supabase.
- Perform CRUD operations to manage data for a web application.

## Resources
- [MDN Web Docs Glossary: CRUD](https://developer.mozilla.org/en-US/docs/Glossary/CRUD)
- [Supabase Documentation](https://supabase.io/docs)

## Lab Instructions
### Required Features

#### Step 0: Explore the Starter Code
- Download the starter code from the provided GitHub repository and explore the interface.

#### Step 1: Sign Up for Supabase
- Sign up for Supabase and create a new project named "bet".

#### Step 2: Set Up the Database
- Create a new table named "Posts" in the Supabase database to store challenge data.

#### Step 3: Connect to the Database
- Install the Supabase library and set up the Supabase client in the React application.

#### Step 4: Create Database Entry
- Update the event handler to add a new challenge post to the database upon form submission.

#### Step 5: Read Database Entries
- Make a request to the database to read all challenge entries and display them on the homepage.

#### Step 6: Update Database Entries
- Update the application to allow users to update challenge entries, reflecting changes in the database.

#### Step 7: Delete Database Entries
- Implement functionality to delete challenge entries from the database and homepage.

### Stretch Features

#### Step 8: Save Bet Count to Database
- Update the application to track and save the bet count for each challenge in the database.

## Congratulations!
You've successfully created a full-stack web application using React and Supabase. If time permits, you can explore and implement additional features to customize and enhance your app further.

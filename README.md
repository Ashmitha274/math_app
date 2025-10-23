# LEETCODE INSPIRED COMPETITIVE MATH LEARNING PLATFORM FOR STUDENTS

This project is a Flask-based assessment and problem-solving platform designed to manage user profiles, host coding or quiz problems, track submissions, and display leaderboards for individual performance.Built on Python's Flask framework, the app enables user authentication, problem viewing and submission, quiz attempts, and real-time ranking based on performance.


## Overview

This project provides a web application for managing online assessments, coding/quizzing problems, user profiles, and leaderboards. Built on Python's Flask framework, the app enables user authentication, problem viewing and submission, quiz attempts, and real-time ranking based on performance.

## Features

- **User Authentication:** Secure login and registration support.
- **User Profile:** View and edit user details, bios, interests, and track your solved problems and quizzes.
- **Problem Dashboard:** Browse, filter, and solve coding or quiz problems categorized by topic and difficulty.
- **Submission Handling:** Submit answers to problems and receive instant feedback on correctness.
- **Assessment Module:** Attempt quizzes/tests, auto-evaluated, with scores and statistics stored locally.
- **Class-wise Leaderboards:** Track top performers overall and within each class or group.
- **Recent Activity Display:** See recently solved problems on your profile.

## Installation

1. **Clone the repository**

   ```
   git clone <your-repo-url>
   cd <project-folder>
   ```

2. **Set up and activate a virtual environment**

   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   - Create a `.env` file and configure as needed (e.g., for database URI, Flask secret key).

5. **Initialize the database**

   ```
   flask shell
   >>> from extensions import db
   >>> db.create_all()
   >>> exit()
   ```

6. **Run the application**

   ```
   flask run
   ```


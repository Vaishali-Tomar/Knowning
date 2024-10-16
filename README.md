Quiz Application
A dynamic, timed quiz application built with React and Tailwind CSS. This project includes user authentication (Signup & Login), quiz functionality with multiple-choice questions, a countdown timer, and a scoring system.

Features
User Signup & Login: Users can sign up with a username and password, which are saved in localStorage. Upon successful signup, users can log in with their credentials.
Quiz Functionality: The application presents users with a series of multiple-choice questions. Users can select answers, and their score is calculated based on correct answers.
Timer: A 10-minute countdown timer automatically submits the quiz when time runs out.
Responsive Design: The app is styled using Tailwind CSS, making it look modern and responsive on different devices.
Retry Option: Users can retry the quiz after submitting it.
Tech Stack
Frontend: React.js
Styling: Tailwind CSS
User Data: localStorage for storing user login information and answers.
Components
Signup Component
Allows users to create an account by entering a username and password, which are stored in localStorage. After successful signup, the user is redirected to the login page.

Login Component
Users can log in with their previously created credentials. Upon successful login, they are redirected to the quiz page.

Quiz Component
Presents a set of multiple-choice questions, each with 4 options. The user selects answers, and the quiz is auto-submitted when time runs out. The score is displayed at the end, and users have the option to retry the quiz.

How It Works
User Authentication
User credentials (username and password) are stored locally in localStorage upon signup.
During login, the app checks the stored credentials to authenticate the user.
Quiz Flow
Timer: The quiz starts with a 10-minute countdown. If time runs out, the quiz is automatically submitted.
Answer Selection: Users can select an answer for each question. Their answers are stored and used for score calculation.
Submit Quiz: After answering all the questions or when the time runs out, the quiz is submitted, and the score is calculated.
Available Scripts
In the project directory, you can run:


npm run build
Builds the app for production in the build folder.
It correctly bundles React in production mode and optimizes the build for best performance.

Deployment
I can deploy this project using Vercel.
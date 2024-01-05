# CashLens - Focus, Track, Thrive
CashLens is a web application built with the MERN stack (MongoDB, Express.js, React, Node.js) that helps users manage and track their income, expenses, and savings. The app is designed to provide a clear financial overview, enabling users to focus on their financial goals, track their spending, and thrive financially.

# Features
## User Authentication:

- Secure user authentication using JWT (JSON Web Tokens).
- User registration and login with hashed password storage.
- Reset password via a generic password reset code/link in the user's inbox (nodemailer)

## Dashboard:

- Overview of income, expenses, and savings.
- Add savings portfolio with reason, percentage of income to be saved in the portfolio, target amount, and deadline
- track progress toward savings goals
- Graphical representation of spending patterns.
- Pie chart showing savings portfolios and their respective amounts
- A table showing savings history, and sources of income.

## Expense Tracking:
  
- Log and categorize expenses for a comprehensive view.
- Track how much you spend in each category.
- Track your monthly expenses in a comprehensive chart

  ## Account info and settings:

-  View your personal information including your sources of income, amount borrowed, total amount saved, total amount spent,
-  View monthly graphs and charts comparing expenses, debt, and savings.
-  Change personal information such as phone, email, and password.
-  Get information about your income and track your financial growth in a monthly chart.

  # Installation

 ## For Android users.
 - Install the latest version of Google Chrome browser
 - Open your Chrome browser and visit [the landing page](www.mycashlens.netlify.app)
 - Once the page has fully loaded, click on the three vertical dots at the top right corner of the browser's window.
 - Click on the option that says "Install app".

## For desktop users
- Make sure you have installed the latest version of Google Chrome browser on your desktop.
- Open your Chrome browser and visit [the landing page](www.mycashlens.netlify.app)
- Once the page has fully loaded, click on the three vertical dots at the top right corner of the browser's window.
- Select "Save and Share"
- Click on "Create shortcut".
- When the dialogue pops up, check the open as a window checkbox and click create to complete.
- The app would be installed and can be accessed from your taskbar or desktop.

  
  ## Prerequisites

  - [Node.js](https://nodejs.org/en/download/) installed on your machine.
  - [MongoDB](https://www.mongodb.com/try/download/community) installed locally or a [MongoDB Atlas](https://account.mongodb.com/account/login) account.

    ## Setup
1. Clone the repository:
        `git clone https://github.com/your-username/cashlens.git`
       
3. Navigate to the project directory:
       `cd cashlens`
4. Install server dependencies:
       `cd api`
       `npm install`
5. Install client dependencies:
         `cd client`
         `npm install`
6. Create `.env` file in api directory with the following variables:
       ``` mongodb_uri=your_uri_string_here
           system_email=your_system_email_here
           system_email_password=your_system_email_password_here
           verification_token=your_verification_token_here```
7. Run the development server:
       `npm run dev`
8. Run client:
       `npm start
9. Access the application at http://localhost:3000 in your browser.
   
  # Usage
  1. Register for a new account on the cashlens app.
  2. Log in using your credentials.
  3. Navigate through the dashboard, income, expenses, and savings sections to manage your financial data.
  4. Add, edit, and delete income sources, expenses, and savings goals.

# Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the application.

# License
This project is licensed under the [MIT License](https://dougneiner.mit-license.org/).
---
CashLens - Focus, Track, Thrive

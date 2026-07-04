# WiseWallet
![image]()

## Overview 📝

This repository contains a finance management web application built with **Django** and **React.js**. The main goal of this project is to provide a user-friendly solution for managing your personal finances, tracking transactions, and gaining insights into your earnings and expenses.

While we don't host this on a cloud solution, you can try this app following the steps described [here](#installation-%EF%B8%8F).

## Features 🚀

### Transaction Management 💸

- Create transactions for transfers, earnings, and expenses.
- Track transaction details such as date, amount, and description.
- Create your own personalized labels for transactions for easier filtering.
- Import payment invoices (Brazilian PIX only)
- Create recurrent transactions ❗

### Monthly Earnings and Expense Analysis 📈

- Visualize your earning and expenses using interactive graphs and charts.
- Get a clear overview of your financial trends over time.
- Analyze your spending habits and identify areas for improvement.

### SavingPlans 🐖 ❗

- Create personalized saving plans tailored to your specific goals.
- Set savings targets and monitor your progress.
- Get reminders and notifications to stay on track with your savings.

#### Items followed by an ❗ are items that already started being implemented, but are yet to be released for usage

## Installation ⚙️

To run the application locally, please follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ayushkumar9122006/wise-wallet
   ```

2. Install dependencies for the Django backend:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. Set up the Django database:

   ```bash
   python manage.py migrate
   ```

4. Install dependencies for the React.js frontend:

   ```bash
   cd ../frontend
   npm install
   ```

5. Start the development server:

   ```bash
   npm start
   ```

6. Access the application in your browser at `http://localhost:5173`.

## About the project 🧑‍🎓



Another thing worth being said is that we are both undergrad compsci students, and we try to allocate time to work on this whenever we can. Along with that, we also want to add that we have an initial UML modelling made on Visual Paradigm that is being made for studying purposes and can be accessed through `backend/modelling`.

Last but not least, stars are appreciated! 🤩

## Usage 💡

Once the application is up and running, you can perform the following tasks:

- Register a new user account or log in with an existing account.
- Create transactions by specifying the type (earning or expense) and categorize them as you wish, creating your own labels.
- View and analyze your monthly earnings and expenses through interactive graphs and charts.

## Roadmap 🗺️

The following features are planned for future development:

- Report generation and advanced insights for better financial analysis.
- Budgeting tools to help you plan and manage your expenses effectively.
- Recurrent transactions to facilitate expenses that happen every month





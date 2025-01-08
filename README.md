# Manual-Testing
This repository includes the manual testing project's deliverables, such as test cases, problem reports, answers to different testing queries, and supporting materials like images and videos. A full analysis of each file and its contents is provided below.

# Test Case Scenario
<h3>Feature 1 : EasyPay Merchant and Utility Bill Payment</h3>

- Customers can pay merchant and utility bills using the EasyPay mobile app.
- Merchant bill payment, <b>1% service charge</b> will be deducted from the customer's balance, with a minimum transaction fee of 5 TK.
- Customer makes a transaction of more than 5000 TK, they will get a 10% cashback.
- Customer makes a transaction of more than 10,000 TK, they will receive a maximum of 20% cashback
- Maximum cashback amount being 3000 TK over the 10000 TK.
- No cashback will be applied for the utility bills payment.

<h3>Feature 2 : EasyPay Bank Loan System</h3>

- Customers with balance below 100 TK can apply for loans up to 20,000 TK.
- Loan repayment policy:
   - No interest if the loan is repaid within 30 days.
   - A daily compound interest of 1.8% is applied for overdue amounts.
   - Customers who repay at least 50% of the remaining loan balance are eligible to apply for another loan.

# Testing Environment Details
- URL : [EasyPayLogin](https://master.d1zgfbpp372908.amplifyapp.com/login)
- Admin Login
   - Email : `admin@roadtocareer.net`
   - Password : `1234`
- System User Login
   - Email : `system@roadtocareer.net`
   - Password : `1234`

# General activities can perform:
1. Login using the following user creds as admin
2. Admin can
   - Create Customer, Agent, another admin or merchant.
3. System user can
   - Deposit to agent.
4. Agent can
   - Deposit or payment to a merchant.
5. Customer can
   - withdraw and payment.
6. Merchant can
   - Only see transaction history of received payment.

# File Description
<h2>1. Question 1, 4, 5</h2>

- <h3>Content :</h3>

   - Question Answer 1: Features 1 and 2 acceptance criteria.
   - Question Answer 4: Priority sequence for identified tasks.
   - Question Answer 5: Checklist for validating Features 1 and 2.
     
For Better Understand [View the link](https://docs.google.com/document/d/1aFA0F8cF7iI10bR7s7VqFDnKV7pGKF9O/edit?usp=sharing&ouid=101261480016291433708&rtpof=true&sd=true)

<h2>2. Question 2</h2>

- <h3>Content :</h3>

  - Test cases (Positive and Negative) for Feature 1 and Feature 2.
  - Detailed scenarios for validating the features under different conditions, including:
     - Test case IDs
     - Modules/Test Scenario
     - Test Case Title
     - Perequisties
     - Steps to execute
     - Test Data
     - Expected result
     - Actual result
     - Status (Pass/Fail)

 For Better Understand [View the Link](https://docs.google.com/spreadsheets/d/1TrgE-LgDYqXd-Ik1GPABb0LDWB01uuaD/edit?usp=sharing&ouid=101261480016291433708&rtpof=true&sd=true)

 
<h2>3. Question 2</h2>

- <h3>Content :</h3>

   - Bug reporting sheet containing at least 10 identified bugs/improvements.
   - Includes : 
       - Bug ID
       - Steps to reproduce
       - Expected vs. actual results
       - Severity and priority
       - Screenshots or videos as evidence for each bug
    
[Bug Report in Excel Sheet](https://docs.google.com/spreadsheets/d/1kjwBN5UHOb61qYtFQWoKEXXmPvOoU9gx/edit?usp=sharing&ouid=101261480016291433708&rtpof=true&sd=true)
 




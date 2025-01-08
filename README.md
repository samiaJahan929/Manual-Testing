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


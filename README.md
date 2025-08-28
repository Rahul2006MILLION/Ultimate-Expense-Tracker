# Ultimate-Expense-Tracker
ExpenseTracker is a simple and interactive command-line tool to help you record, manage, and analyze your daily expenses. Built in Python, it allows you to keep track of all your spending in various categories and provides an easy way to review and organize your financial data


💸 ExpenseTracker

ExpenseTracker is a simple and interactive Python CLI tool to help you track, manage, and analyze your daily expenses. Keep your spending organized by category, add notes, and see totals at a glance!

📝 Features

Add Expenses 💰
Record expenses under Food 🍔, Travel ✈️, Shopping 🛍️, Others 📝.
Each expense includes amount and note.
Records are saved in q.txt for persistence.

View All Expenses 👀
See all your recorded expenses with total expenditure.

Search by Category 🔍
View expenses and total spending per category.

Clear All Records 🧹
Clear memory and the saved file for a fresh start.

Input Validation ✅
Handles invalid inputs gracefully.

-----------------------------------
Python 3 🐍
File Handling 📄
Lists & Loops 🔁
Exception Handling ❗

💻 --Example Usage--
1️⃣ Add Expense

Input Example (Food):
Choice: 1
Expense Type: Food
Number of Food Expenses: 2
Amount $: 150
Note: Lunch at Cafe
Amount $: 200
Note: Dinner at Restaurant

Choice: 1
Expense Type: Travel
Number of Travel Expenses: 1
Amount $: 500
Note: Train ticket

Choice: 1
Expense Type: Shopping
Number of Shopping Expenses: 2
Amount $: 1200
Note: New Shoes
Amount $: 800
Note: T-Shirt

Choice: 1
Expense Type: Others
Number of Other Expenses: 1
Amount $: 300
Note: Books

Expenses added successfully! 🎉

Choice: 2
1. Note: Lunch at Cafe | $150/-
2. Note: Dinner at Restaurant | $200/-
3. Note: Train ticket | $500/-
4. Note: New Shoes | $1200/-
5. Note: T-Shirt | $800/-
6. Note: Books | $300/-
------------------------------
Total Expenditure: $3150

Input:
Choice: 3
Enter Category:
1. Food
2. Travel
3. Shopping
4. Others
Enter (1/2/3/4): 1

Output:
Note: Lunch at Cafe | $150/-
Note: Dinner at Restaurant | $200/-
------------------------------
Total Expenditure on Food: $350

Example for Travel:
Note: Train ticket | $500/-
------------------------------
Total Expenditure on Travel: $500

Example for Shopping:
Note: New Shoes | $1200/-
Note: T-Shirt | $800/-
------------------------------
Total Expenditure on Shopping: $2000

Example for Others:
Note: Books | $300/-
------------------------------
Total Expenditure on Other Items: $300

4️⃣ Clear All Records
Choice: 4
---MEMORY CLEARED--- 🧹

5️⃣ Exit Program;
Choice: 5
---EXPENSE TRACKER EXITING--- 👋


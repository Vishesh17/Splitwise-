Splitter C++ Program
Overview
Splitter is a C++ program designed to manage group expenses and settle debts within a group of people. The program allows users to create and manage groups, add expenses, transfer money, and settle debts efficiently.

Features
Group Management:

Users can create new groups, specifying the group name and the number of people in the group.
People in the group are identified by unique names.
Expense Tracking:

Users can add expenses to a group, specifying the payer, the amount, and the people for whom the expense is paid.
The program calculates each person's share of the expense and updates the internal data structures.
Money Transfer:

Users can transfer money between individuals in the group.
The program updates the group's financial graph based on the transfers.
Debt Settlement:

Users can settle debts within the group, minimizing the number of transactions needed.
Instructions
Creating a New Group:

Choose option 1 from the main menu.
Enter the name of the group and the number of people in the group.
Provide the names of individuals in the group.
Managing an Existing Group:

Choose option 2 from the main menu.
Enter the name of the existing group.
Adding Expenses:

Inside a group, choose option 1.
Enter the expense amount, the person who paid, and the people for whom the expense is shared.
Transferring Money:

Inside a group, choose option 2.
Specify the person who transferred money, the recipient, and the amount.
Settling Debts:

Inside a group, choose option 3.
The program minimizes transactions to settle debts within the group.
Exiting the Program:

Choose option 4 to exit the program.
Notes
The program uses a graph-based approach to efficiently settle debts within the group.
Ensure accurate and case-sensitive entry of names while interacting with the program.

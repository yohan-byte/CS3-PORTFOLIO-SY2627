Annex A
Computational Thinking Exercise: "Smart School Canteen Queue"

Section: 9-Lithium                          Score:____________

C# / Name: Yohan Seth Abdul, Zuriel Elnathan Basa     Date:August 9, 2026


Scenario

The PSHS school canteen is small and often gets crowded during lunch break. Students line up to buy food, but the process is slow because:

Some students take too long to decide what to order.
The cashier has to manually calculate totals and give change.
There is no system to track which food items are running out.
Your group’s task is to decompose this problem into smaller, manageable parts that could be solved with computational thinking (CT) Skills.

Step 1: Identify the Big Problem

Main Problem:  The canteen service is slow and disorganized, causing long waiting times and crowding during lunch break.
Step 2: Identify three to four Sub-Problems
Please list possible sub-problems:

1. Students take too long to decide what to order.
2. Manual calculation of bills and change is slow and error‑prone.
3. No automatic tracking of available food stock.
4. No orderly or pre‑arranged system for ordering and queueing.
 

Step 3: Define Computational Thinking Approaches
For each sub-problem, apply CT skills:

Sub-Problem

1. Slow Decision-making
2. Manual Calculation
3. No Stock tracking
4. No queue system

CT Skill

1. Decomposition/ Pattern Recognition
2. Algorithmic Design / Automation
3. Data Representation / Abstraction 
4. Sequencing / Algorithm 

Example Solution

1. Show a simple daily menu with pictures and prices; suggest popular combinations so students choose faster. 
2. Create a program that multiplies quantity by price, adds total, and computes change instantly. 
3. Keep a list or table of available items and update counts automatically as orders are placed. 
4. Assign queue numbers or accept pre‑orders; serve customers in exact order received. 

 Step 4: Draw a flowchart or write a pseudocode for the identified sub-problem

START
  DISPLAY Menu with item names and prices
  SET total_cost = 0
  REPEAT
    ASK item_number and quantity
    ADD (price × quantity) to total_cost
    ASK "Add more items? (Y/N)"
  UNTIL answer = "N"
  DISPLAY "Total amount: " + total_cost
  ASK cash_given
  COMPUTE change = cash_given − total_cost
  DISPLAY "Change: " + change
END
 


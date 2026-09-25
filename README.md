# Expense-Tracker-CSV-or-JSON-
import csv  with open("expenses.csv","a",newline="") as f:     w=csv.writer(f)     w.writerow([input("Item: "), input("Amount: ")])  print("Expense saved!")   or  import json  d={"item":input("Item: "), "amount":float(input("Amount: "))} with open("expenses.json","w") as f:     json.dump(d,f)  print("Expense saved!")

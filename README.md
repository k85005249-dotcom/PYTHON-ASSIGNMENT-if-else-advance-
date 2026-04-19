🚀 Python If-Else Advanced Assignment

📘 This repository contains solutions to advanced Python If-Else condition problems, covering real-world scenarios like billing systems, pricing logic, eligibility checks, and more.

📌 Features
✅ Real-life problem-based questions
✅ Beginner to intermediate logic building
✅ Clean Python implementations
✅ Input/Output examples included
📂 Assignment Topics
🏥 1. Hospital Emergency Room Triage

Classifies patients into priority levels based on temperature & pain level.

a=int(input("enter your tempreture in Fahrenheit(F)"))
b=input("enter your pain level none, moderate or severe")
if(a>102 and b=="severe"):
    print("High Priority")
elif(a>=99 and a<=102 and b=="moderate"):
    print("Medium Priority")
elif(b=="none"):
    print("Low Priority")
🛒 2. Shopping Cart Free Delivery

Determines if delivery is free based on cart value & membership.

a=int(input("ENTER YOUR CART VALUE :"))
b=input("DO YOU HAVE A MEMBERSHIP? yes or no :")
if(a>2000 or b=="yes"):
    print("free delivery")
else:
    print("the delivery fee is ₹100")
📚 3. Library Fine System

Calculates fine based on overdue days.

a=int(input("DAYS OF OVERDUE :"))
if(a<=5):
    print(a*2)
elif(a<=10):
    print(a*5)
else:
    print(a*10)
✈️ 4. Airport Luggage Check

Calculates excess luggage charges based on class type.

🏨 5. Hotel Room Pricing

Applies discounts based on customer type.

⚡ 6. Energy Consumption Billing

Calculates electricity bill based on usage slabs.

🚖 7. Ride Fare Calculation

Fare based on time (day/night) and distance.

🎟️ 8. Event Entry Rules

Entry pricing based on age and student ID.

🚗 9. Parking Lot Charges

Parking fees based on vehicle type and duration.

🏦 10. Real Estate Loan Eligibility

Loan eligibility based on income and existing loans.

🧠 Concepts Used
if, elif, else
Logical Operators (and, or)
User Input Handling
Conditional Logic
🛠️ How to Run
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to folder
cd your-repo-name

# Run any file
python filename.py
📊 Sample Output
ENTER YOUR CART VALUE :1500
DO YOU HAVE A MEMBERSHIP? yes
free delivery
📎 Author

👤 Krishna Vishwakarma

⭐ Support

If you found this helpful:

⭐ Star the repo
🍴 Fork it
📢 Share with friends

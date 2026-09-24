print("Tourism Management System")

place = input("Enter destination: ")
days = int(input("Enter number of days: "))
budget = int(input("Enter budget: ₹"))

print("\n--- Your Trip ---")
print("Destination:", place)
print("Duration:", days, "days")
print("Budget: ₹", budget)

if budget >= 20000:
    print("Trip Status: Recommended ✓")
else:
    print("Trip Status: Budget too low")

# Problem.3
# Problem 3: Tip Calculation

# Input total for a meal
total_meal = float(input("Enter total for the meal: "))

# Calculate tips at 15%, 18%, and 20%
tip_15 = total_meal * 0.15
tip_18 = total_meal * 0.18
tip_20 = total_meal * 0.20

# Calculate total with tips
total_with_tip_15 = total_meal + tip_15
total_with_tip_18 = total_meal + tip_18
total_with_tip_20 = total_meal + tip_20

# Display results
print(f"\nWith 15% Tip:\nTotal: {total_meal}\nTip: {tip_15}\nTotal with Tip: {total_with_tip_15}\n")
print(f"With 18% Tip:\nTotal: {total_meal}\nTip: {tip_18}\nTotal with Tip: {total_with_tip_18}\n")
print(f"With 20% Tip:\nTotal: {total_meal}\nTip: {tip_20}\nTotal with Tip: {total_with_tip_20}")

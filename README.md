
name = input("Enter Student Name: ")
sub1 = int(input("Enter Subject 1 Marks: "))
sub2 = int(input("Enter Subject 2 Marks: "))
sub3 = int(input("Enter Subject 3 Marks: "))
print("\nStudent Name:", name)
print("Subject 1 Marks:", sub1)
print("Subject 2 Marks:", sub2)
print("Subject 3 Marks:", sub3)

# Calculate results
total = sub1 + sub2 + sub3
average = total / 3
highest = max(sub1, sub2, sub3)
lowest = min(sub1, sub2, sub3)

# Display calculations
print("\nTotal Marks:", total)
print("Average Marks:", average)
print("Highest Mark:", highest)
print("Lowest Mark:", lowest)

# Comparison operations
print("\nIs Subject 1 mark greater than Subject 2 mark?", sub1 > sub2)
print("Is Subject 3 mark equal to Subject 1 mark?", sub3 == sub1)

# Logical operation
print("\nAre all three marks greater than or equal to 40?",
      sub1 >= 40 and sub2 >= 40 and sub3 >= 40)

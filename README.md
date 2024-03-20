# Numbers-Project
This is a loop iteration for a Numbers Project
# Define array of numbers
numbers = [15, 9, 11, 7, 3]
max_number = numbers[0]
# Iterate through numbers to find greatest number
for num in numbers:
  if num > max_number:
    max_number = num

print("Greatest number is:", max_number)

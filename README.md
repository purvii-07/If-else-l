# If-else-l
age = int(input("Enter age: "))

if age < 13:
    print("The person is child")
elif age >= 13 and age < 20:
    print("The person is Teen")
elif age >= 20 and age < 60:
    print("The person is Adult")
else:
    print("The person is dead")

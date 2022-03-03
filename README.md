# Basic-calculator
**Code example for a basic calculator with python language **
```sql
print("""******************************

PROGRAM OF CALCULATOR

Choices;

1.Sum process

2.Extraction process

3.Multiplication

4.Division process

****************************** """)

a = int(input("First number:"))
b = int(input("Second number:"))

choice = input("Please enter your choice:")

if choice =="1":
    print("The sum of {} and {} is {} .".format(a,b,a+b))

elif choice == "2":
    print("The extraction of {} and {} is {} .".format(a,b,a-b))

elif choice =="3":
    print("The product of {} and {} is {} .".format(a,b,a*b))

elif choice =="4":
    print("The division of {} and {} is {} .".format(a, b, a/b))
else:
    print("invalid choice!")
```





















```

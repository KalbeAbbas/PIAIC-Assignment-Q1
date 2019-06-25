PIAIC Q1 ASSIGNMENT

Name : Kalb E Abbas
Roll No: AIC034719
Teacher Name: Sir Noman Islam
Institute Name: Saylani Head Office (Bahadurabad)


1. Calculate Area of a Circle

Code
from math import pi
r = float(input("Enter radius of circle"))
a = pi * r**2
print("Area of circle:",a);

Result
Enter radius of circle10
Area of circle: 314.1592653589793

2.Check Number either positive, negative or zero

Code
num = int(input("Enter any number :"))
if(num > 0):
    print("Positive")
elif(num < 0):
    print("Negative")
elif(num == 0):
    print("Zero")

Result
Enter any number :10
Positive

Enter any number :-10
Negative

Enter any number :0
Zero

3. Divisibility Check of two numbers

Code
num1 = int(input("Enter first number :"))
num2 = int(input("Enter second number :"))
if(num1 % num2 == 0):
    print("Completely divisible")
else:
    print("Not completely divisible")
Result
Enter first number :6
Enter second number :2
Completely divisible

Enter first number :100
Enter second number :3
Not completely divisible

4. Calculate Volume of a sphere

Code
from math import pi
r = int(input("Enter radius of Sphere :"))
v = (4/3) * pi * r**3
print("volume of Spehere is: ",v);

Result
Enter radius of Sphere :1
volume of Spehere is:  4.1887902047863905


5. Copy string n times

Code
word = input("Enter any word :")
rpt = int(input("Enter number of repetition :"))
print(word*rpt)

Result
Enter any word :Pakistan
Enter number of repetition :5
PakistanPakistanPakistanPakistanPakistan

6. Check if number is Even or Odd

Code
num = int(input("Enter number to check, Even or Odd :"))
if(num % 2 == 0):
    print("Even")
elif(num % 2 == 1):
    print("Odd")

Result
Enter number to check, Even or Odd :2
Even

Enter number to check, Even or Odd :9
Odd

7. Vowel Tester

Code
vowel = "aeiou"
letter = input("Enter letter to test, vowel or not: ")
if(letter in vowel):
    print("Vowel")
else:
    print("Not vowel")
Result
Enter letter to test, vowel or not: a
Vowel

Enter letter to test, vowel or not: z
Not vowel

8. Triangle area

Code
base = float(input("Enter value of triangle base: "))
height = float(input("Enter value of triangle height: "))
area = 0.5 * base * height

print("Area of triangle is: ",area)

Result
Enter value of triangle base: 1
Enter value of triangle height: 2
Area of triangle is:  1.0

9. Calculate Interest

Code
value = float(input("Enter your Principal value: "))
rate = float(input("Enter interest rate: "))
years =  int(input("Enter number of years to grow: "))

for i in range(years):
    value += value * (rate)

print("Final value is:",value)


Result
Enter your Principal value: 10000
Enter interest rate: 0.1
Enter number of years to grow: 5
Final value is: 16105.1

Enter your Principal value: 50
Enter interest rate: 10
Enter number of years to grow: 10
Final value is: 1296871230050.0




10. Euclidean distance

Code
x1 = input("Enter X1: ")
y1 = input("Enter Y1: ")

x2 = input("Enter X2")
y2 = input("enter Y2")

distance = ( (x1-x2)**2 + (y1-y2)**2 )**0.5

Result
Enter X1: 2
Enter Y1: 5
Enter X2: 2
enter Y2: 5
Distance is: 0.0

Enter X1: 1
Enter Y1: 2
Enter X2: 3
enter Y2: 4
Distance is: 2.8284271247461903

11. Feet to cm
Code
feet = float(input("Enter your feet: "))
cm = feet * 30.48
print(feet," Feet are ",cm, "cm")

Result
Enter your feet: 5.5
5.5  Feet are  167.64000000000001 cm


12. BMI Calculator

Code
height = (float(input("Enter height in cm: "))/ 100)**2
mass = float(input("Enter your mass in Kg: ")

bmi = mass/height
print("Your BMI is", bmi)

Result
Enter height in cm: 180
Enter your mass in Kg: 75
Your BMI is 23.148148148148145


 

13. Sum of n Positive IntegersCode
num = int(input("Enter numbe to sum to: "))
Sum = 0
for i in range(num+1):
    Sum += i
print("Sum is: ",Sum)

Result
Enter numbe to sum to: 10
Sum is:  55





14. Digits Sum of a Number
Code
num = input("Enter any digit number: ")
Sum = 0
for i in range(len(num)):
    Sum += int(num[i])

print("Sum of digits: ",num," is", Sum)

Result
Enter any digit number: 12345
Sum of digits:  12345  is 15

















# Conditions
number = int(input("enter number to check:"))
print("number to be checked:", number)
if number%2==0 :
    print("This is an even number")

else:
    print("This is an odd number")

height= float(input("enter your height in cm"))
weight= float(input("Enter your weight in kg "))
BMI = weight / (height/100)**2
print("Your BMI is", BMI)

if BMI <=18.4:
 print("You are underweight")
elif BMI <= 24.9:
 print("you are healthy")
elif BMI <=29.9:
 print("you are over weight")
elif BMI <=34.9:
 print("You are severely over weight")
elif BMI <=39.9:
 print("You are obese")
else:
 print("You are severely obese")
 num = int(input("Enter number to check"))

if num>50:
  print("number is greater than 50")
if num%2==0:
  print("and it is even too")
else:
  print("and it is odd")

  import: datetime
current_time = datetime.datetime.now()
print("time now at greenwhich meridian is:", end = "")
import calendar
print("\n", calendar.calendar (2024))

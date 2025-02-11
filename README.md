# Sanyam_Python
Python Casestudy 1

a = int(input("Enter the cost of 1st item: "))
q1 = int(input("Enter the quantity of 1st item: "))
b = int(input("Enter the cost of 2nd item: "))
q2 = int(input("Enter the quantity of 2nd item: "))
c = int(input("Enter the cost of 3rd item: "))
q3 = int(input("Enter the quantity of 3rd item: "))
t = (a*q1) + (b*q2) + (c*q3)
if(t>50):
  total = t-((1/10)*t)
  print(total)
else:
  print(t)


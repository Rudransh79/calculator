# calculator
coding a calculator
a=int(input("Enter the first number:"))
b=int(input("Enter the second number:"))
choice=int(input("Enter operator")) 
if choice==1:
  print(a+b)
elif choice==2:
  print(a-b)
elif choice==3:
  print(a*b)
elif choice==4:
  print(a/b)
elif choice==5:
  print(a//b)
elif choice==6:
  print(a**b)
elif choice==7:
  print(a%b)
else:
  print("Invalid choice")

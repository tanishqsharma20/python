# python
this is my notes of python
science_marks=int(input("enter marks in science ;"))
lang_marks=int(input("enter marks in language ;"))
math_marks=int(input("enter marks in maths ;"))
obtained_percentage=((science_marks + lang_marks + math_marks) / 300 * 100)
if obtained_percentage>=65:
    print(obtained_percentage,"first division")
elif  obtained_percentage>=50:
    print(obtained_percentage,"second division")
elif  obtained_percentage>=33:
    print(obtained_percentage,"third division")
else:print(obtained_percentage,"fail")

print("obtained percentage" , obtained_percentage,"%")

print("obtained marks" , science_marks + lang_marks + math_marks)



a=int(input("enter lenght a :"))
b=int(input("enter lenght b :"))
c=int(input("enter lenght c :"))
if a+b>c and b+c>a and c+a>b:
      if a==b==c:
          print("it is a equilateral triangle")
      elif  a==b or b==c or c==a:
          print("it is an isosceles")
      else:
          print("scalene triangle")
else:
    print("its not a triangle")


    #leap year( to check weather its a leap year or not?
year=int(input("enter any year"))
if year%4==0:
    if year%100==0:
        if year%400==0:
            print(year, " it is  a leap year")
        else: print(year, " it is not a leap year")
    else: print(year, " it is a leap year")
else:
    print(year, " it is not a leap year")
      n=int(input("enter the nth term  :"))
a=0
b=1
for i in range(2,n):
    c=a+b
    a,b=b,c
print(c)

start=10
end=20
for i in range(start,end+1):
    for j in range(2,i):
        if i%j==0:
            break
    else:
        print(i,end=" ")


        #febonacci it is the sum of 2 consicutive number before that number
a=0
b=1
x=int(input("enter the term :"))
for i in range(2,x):
    c=a+b
    print(c,end=" ")
    a=b
    b=c
print(c,"output")

#febonacci it is the sum of 2 consicutive number before that number
a=0
b=1
x=int(input("enter the term :"))
for i in range(2,x):
    c=a+b
    print(c,end=" ")
    a=b
    b=c
print(c,"output")


            #leap year( to check weather its a leap year or not?
year=int(input("enter any year")) if year%4==0: if year%100==0: if year%400==0: print(year, " it is a leap year") else: print(year, " it is not a leap year") else: print(year, " it is a leap year") else: print(year, " it is not a leap year") n=int(input("enter the nth term :")) a=0 b=1 for i in range(2,n): c=a+b a,b=b,c print(c)

start=10 end=20 for i in range(start,end+1): for j in range(2,i): if i%j==0: break else: 


#wapp to print factorial of n(user input) ?
n=int(input("enter the nth factorial number  :"))
n_f=1
for i in range(1,n+1):
    n_f=n_f*i
print(n_f)
year=int(input("enter any year")) if year%4==0: if year%100==0: if year%400==0: print(year, " it is a leap year") else: print(year, " it is not a leap year") else: print(year, " it is a leap year") else: print(year, " it is not a leap year") n=int(input("enter the nth term :")) a=0 b=1 for i in range(2,n): c=a+b a,b=b,c print(c)

start=10 end=20 for i in range(start,end+1): for j in range(2,i): if i%j==0: break else: print(i,end=" ")
function and method!

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
      


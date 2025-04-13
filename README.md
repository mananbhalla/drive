a= (input("enter name :- "))
if a.lower()== "":
    print(a.upper())
else:
    print(a.upper())
c = int(input("enter you birth year "))
d = int(input("enter your birth month "))
e = int(input("enter your birth day "))
c1 = int(input("enter you cureetn year "))
d2 = int(input("enter your current mounth month "))
e3 = int(input("enter your current day  day "))
c3=[(c1-c)-1]

d3=(d2-d)
if d3<0 :
 d4 = (-d3)
else:
     d3
e2=(e3-e)
if e2 <0: 
 e4 = (-e2)
else:
     e2
e3=(e3-e)
print("your age is ",c3,"years",d4,"months",e2,"days")
if (d3>18):
    print("you are minor")
    print("you are not allowed to frive ")
else:
    print("you are adult")
    print("you are allowed to drive")

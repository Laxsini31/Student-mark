name = input("Enter Student Name: ")
roll = input("Enter Roll Number: ")
course = input("Enter Course Name: ")
print("\nEnter marks out of 100:\n")
s1 = int(input("Subject 1: "))
s2 = int(input("Subject 2: "))
s3 = int(input("Subject 3: "))
s4 = int(input("Subject 4: "))
s5 = int(input("Subject 5: "))
total = s1 + s2 + s3 + s4 + s5
percentage = total / 5
if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B+"
elif percentage >= 60:
    grade = "B"
elif percentage >= 50:
    grade = "C"
else:
    grade = "Fail"
print("\n============== STUDENT MARKSHEET ==============")
print("Name        :", name)
print("Roll Number :", roll)
print("Course      :", course)
print("-----------------------------------------------")
print("Subject 1   :", s1)
print("Subject 2   :", s2)
print("Subject 3   :", s3)
print("Subject 4   :", s4)
print("Subject 5   :", s5)
print("-----------------------------------------------")
print("Total Marks :", total)
print("Percentage  :", percentage, "%")
print("Grade       :", grade)
print("===============================================")

Output :
Enter Student Name: ARCHANA
Enter Roll Number: 08
Enter Course Name: COMPUTER SCIENCE

Enter marks out of 100:

Subject 1: 80
Subject 2: 71
Subject 3: 85
Subject 4: 77
Subject 5: 86

============== STUDENT MARKSHEET ==============
Name        : ARCHANA
Roll Number : 08
Course      : COMPUTER SCIENCE
-----------------------------------------------
Subject 1   : 80
Subject 2   : 71
Subject 3   : 85
Subject 4   : 77
Subject 5   : 86
-----------------------------------------------
Total Marks : 399
Percentage  : 79.8 %
Grade       : B+
===============================================




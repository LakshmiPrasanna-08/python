# python
list=[2,6,9,20,15]
roll_no=int(input("Enter the roll number:"))
if roll_no in list:
    print("Roll number is found")
else:
    print("Roll number is not found")
    new_rollno=int(input("Enter the new roll number:"))
    list.append(new_rollno)
    print("The new roll number to add")
    print(list)

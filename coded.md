# In this place I will place some code I have done for IT1040
This code gathered information from the gradebook and then calculated the average grade of each student and of each assignment.

```

    # gradebook.py

    # Display the average of each student's grade.
    # Display tthe average for each assignment.

    gradebook = [[61, 74, 69, 62, 72, 66, 73, 65, 60, 63, 69, 63, 62, 61, 64],
                 [73, 80, 78, 76, 76, 79, 75, 73, 76, 74, 77, 79, 76, 78, 72],
                 [90, 92, 93, 92, 88, 93, 90, 95, 100, 99, 100, 91, 95, 99, 96],
                 [96, 89, 94, 88, 100, 96, 93, 92, 94, 98, 90, 90, 92, 91, 94],
                 [76, 76, 82, 78, 82, 76, 84, 82, 80, 82, 76, 86, 82, 84, 78],
                 [93, 92, 89, 84, 91, 86, 84, 90, 95, 86, 88, 95, 88, 84, 89],
                 [63, 66, 55, 67, 66, 68, 66, 56, 55, 62, 59, 67, 60, 70, 67],
                 [86, 92, 93, 88, 90, 90, 91, 94, 90, 86, 93, 89, 94, 94, 92],
                 [89, 80, 81, 89, 86, 86, 85, 80, 79, 90, 83, 85, 90, 79, 80],
                 [99, 73, 86, 77, 87, 99, 71, 96, 81, 83, 71, 75, 91, 74, 72]]

    student1 = gradebook[0]
    student1a1 = student1[0]
    student1a2 = student1[1]
    student1a3 = student1[2]
    student1a4 = student1[3]
    student1a5 = student1[4]
    student1a6 = student1[5]
    student1a7 = student1[6]
    student1a8 = student1[7]
    student1a9 = student1[8]
    student1a10 = student1[9]
    student1a11 = student1[10]
    student1a12 = student1[11]
    student1a13 = student1[12]
    student1a14 = student1[13]
    student1a15 = student1[14]




    student2 = gradebook[1]
    student2a1 = student2[0]
    student2a2 = student2[1]
    student2a3 = student2[2]
    student2a4 = student2[3]
    student2a5 = student2[4]
    student2a6 = student2[5]
    student2a7 = student2[6]
    student2a8 = student2[7]
    student2a9 = student2[8]
    student2a10 = student2[9]
    student2a11 = student2[10]
    student2a12 = student2[11]
    student2a13 = student2[12]
    student2a14 = student2[13]
    student2a15 = student2[14]

    student3 = gradebook[2]
    student3a1 = student3[0]
    student3a2 = student3[1]
    student3a3 = student3[2]
    student3a4 = student3[3]
    student3a5 = student3[4]
    student3a6 = student3[5]
    student3a7 = student3[6]
    student3a8 = student3[7]
    student3a9 = student3[8]
    student3a10 = student3[9]
    student3a11 = student3[10]
    student3a12 = student3[11]
    student3a13 = student3[12]
    student3a14 = student3[13]
    student3a15 = student3[14]

    student4 = gradebook[3]
    student4a1 = student4[0]
    student4a2 = student4[1]
    student4a3 = student4[2]
    student4a4 = student4[3]
    student4a5 = student4[4]
    student4a6 = student4[5]
    student4a7 = student4[6]
    student4a8 = student4[7]
    student4a9 = student4[8]
    student4a10 = student4[9]
    student4a11 = student4[10]
    student4a12 = student4[11]
    student4a13 = student4[12]
    student4a14 = student4[13]
    student4a15 = student4[14]

    student5 = gradebook[4]
    student5a1 = student5[0]
    student5a2 = student5[1]
    student5a3 = student5[2]
    student5a4 = student5[3]
    student5a5 = student5[4]
    student5a6 = student5[5]
    student5a7 = student5[6]
    student5a8 = student5[7]
    student5a9 = student5[8]
    student5a10 = student5[9]
    student5a11 = student5[10]
    student5a12 = student5[11]
    student5a13 = student5[12]
    student5a14 = student5[13]
    student5a15 = student5[14]

    student6 = gradebook[5]
    student6a1 = student6[0]
    student6a2 = student6[1]
    student6a3 = student6[2]
    student6a4 = student6[3]
    student6a5 = student6[4]
    student6a6 = student6[5]
    student6a7 = student6[6]
    student6a8 = student6[7]
    student6a9 = student6[8]
    student6a10 = student6[9]
    student6a11 = student6[10]
    student6a12 = student6[11]
    student6a13 = student6[12]
    student6a14 = student6[13]
    student6a15 = student6[14]

    student7 = gradebook[6]
    student7a1 = student7[0]
    student7a2 = student7[1]
    student7a3 = student7[2]
    student7a4 = student7[3]
    student7a5 = student7[4]
    student7a6 = student7[5]
    student7a7 = student7[6]
    student7a8 = student7[7]
    student7a9 = student7[8]
    student7a10 = student7[9]
    student7a11 = student7[10]
    student7a12 = student7[11]
    student7a13 = student7[12]
    student7a14 = student7[13]
    student7a15 = student7[14]

    student8 = gradebook[7]
    student8a1 = student8[0]
    student8a2 = student8[1]
    student8a3 = student8[2]
    student8a4 = student8[3]
    student8a5 = student8[4]
    student8a6 = student8[5]
    student8a7 = student8[6]
    student8a8 = student8[7]
    student8a9 = student8[8]
    student8a10 = student8[9]
    student8a11 = student8[10]
    student8a12 = student8[11]
    student8a13 = student8[12]
    student8a14 = student8[13]
    student8a15 = student8[14]

    student9 = gradebook[8]
    student9a1 = student9[0]
    student9a2 = student9[1]
    student9a3 = student9[2]
    student9a4 = student9[3]
    student9a5 = student9[4]
    student9a6 = student9[5]
    student9a7 = student9[6]
    student9a8 = student9[7]
    student9a9 = student9[8]
    student9a10 = student9[9]
    student9a11 = student9[10]
    student9a12 = student9[11]
    student9a13 = student9[12]
    student9a14 = student9[13]
    student9a15 = student9[14]

    student10 = gradebook[9]
    student10a1 = student10[0]
    student10a2 = student10[1]
    student10a3 = student10[2]
    student10a4 = student10[3]
    student10a5 = student10[4]
    student10a6 = student10[5]
    student10a7 = student10[6]
    student10a8 = student10[7]
    student10a9 = student10[8]
    student10a10 = student10[9]
    student10a11 = student10[10]
    student10a12 = student10[11]
    student10a13 = student10[12]
    student10a14 = student10[13]
    student10a15 = student10[14]

    assignment1total = student1a1 + student2a1 + student3a1 + student4a1 + student5a1 + student6a1 + student7a1 + student8a1 + student9a1 + student10a1
    assignment1average = assignment1total / 10


    assignment2total = student1a2 + student2a2 + student3a2 + student4a2 + student5a2 + student6a2 + student7a2 + student8a2 + student9a2 + student10a2
    assignment2average = assignment2total / 10

    assignment3total = student1a3 + student2a3 + student3a3 + student4a3 + student5a3 + student6a3 + student7a3 + student8a3 + student9a3 + student10a3
    assignment3average = assignment3total / 10

    assignment4total = student1a4 + student2a4 + student3a4 + student4a4 + student5a4 + student6a4 + student7a4 + student8a4 + student9a4 + student10a4
    assignment4average = assignment4total / 10

    assignment5total = student1a5 + student2a5 + student3a5 + student4a5 + student5a5 + student6a5 + student7a5 + student8a5 + student9a5 + student10a5
    assignment5average = assignment5total / 10

    assignment6total = student1a6 + student2a6 + student3a6 + student4a6 + student5a6 + student6a6 + student7a6 + student8a6 + student9a6 + student10a6
    assignment6average = assignment6total / 10

    assignment7total = student1a7 + student2a7 + student3a7 + student4a7 + student5a7 + student6a7 + student7a7 + student8a7 + student9a7 + student10a7
    assignment7average = assignment7total / 10

    assignment8total = student1a8 + student2a8 + student3a8 + student4a8 + student5a8 + student6a8 + student7a8 + student8a8 + student9a8 + student10a8
    assignment8average = assignment8total / 10

    assignment9total = student1a9 + student2a9 + student3a9 + student4a9 + student5a9 + student6a9 + student7a9 + student8a9 + student9a9 + student10a9
    assignment9average = assignment9total / 10

    assignment10total = student1a10 + student2a10 + student3a10 + student4a10 + student5a10 + student6a10 + student7a10 + student8a10 + student9a10 + student10a10
    assignment10average = assignment10total / 10

    assignment11total = student1a11 + student2a11 + student3a11 + student4a11 + student5a11 + student6a11 + student7a11 + student8a11 + student9a11 + student10a11
    assignment11average = assignment11total / 10

    assignment12total = student1a12 + student2a12 + student3a12 + student4a12 + student5a12 + student6a12 + student7a12 + student8a12 + student9a12 + student10a12
    assignment12average = assignment12total / 10

    assignment13total = student1a13 + student2a13 + student3a13 + student4a13 + student5a13 + student6a13 + student7a13 + student8a13 + student9a13 + student10a13
    assignment13average = assignment13total / 10

    assignment14total = student1a14 + student2a14 + student3a14 + student4a14 + student5a14 + student6a14 + student7a14 + student8a14 + student9a14 + student10a14
    assignment14average = assignment14total / 10

    assignment15total = student1a15 + student2a15 + student3a15 + student4a15 + student5a15 + student6a15 + student7a15 + student8a15 + student9a15 + student10a15
    assignment15average = assignment15total / 10


    ################break
    student1total = student1a1 + student1a2 + student1a3 + student1a4 + student1a5 + student1a6 + student1a7 + student1a8 + student1a9 + student1a10 + student1a11 + student1a12 + student1a13 + student1a14 + student1a15
    student1average = student1total / 15

    student2total = student2a1 + student2a2 + student2a3 + student2a4 + student2a5 + student2a6 + student2a7 + student2a8 + student2a9 + student2a10 + student2a11 + student2a12 + student2a13 + student2a14 + student2a15
    student2average = student2total / 15

    student3total = student3a1 + student3a2 + student3a3 + student3a4 + student3a5 + student3a6 + student3a7 + student3a8 + student3a9 + student3a10 + student3a11 + student3a12 + student3a13 + student3a14 + student3a15
    student3average = student3total / 15

    student4total = student4a1 + student4a2 + student4a3 + student4a4 + student4a5 + student4a6 + student4a7 + student4a8 + student4a9 + student4a10 + student4a11 + student4a12 + student4a13 + student4a14 + student4a15
    student4average = student4total / 15

    student5total = student5a1 + student5a2 + student5a3 + student5a4 + student5a5 + student5a6 + student5a7 + student5a8 + student5a9 + student5a10 + student5a11 + student5a12 + student5a13 + student5a14 + student5a15
    student5average = student5total / 15

    student6total = student6a1 + student6a2 + student6a3 + student6a4 + student6a5 + student6a6 + student6a7 + student6a8 + student6a9 + student6a10 + student6a11 + student6a12 + student6a13 + student6a14 + student6a15
    student6average = student6total / 15

    student7total = student7a1 + student7a2 + student7a3 + student7a4 + student7a5 + student7a6 + student7a7 + student7a8 + student7a9 + student7a10 + student7a11 + student7a12 + student7a13 + student7a14 + student7a15
    student7average = student7total / 15

    student8total = student8a1 + student8a2 + student8a3 + student8a4 + student8a5 + student8a6 + student8a7 + student8a8 + student8a9 + student8a10 + student8a11 + student8a12 + student8a13 + student8a14 + student8a15
    student8average = student8total / 15

    student9total = student9a1 + student9a2 + student9a3 + student9a4 + student9a5 + student9a6 + student9a7 + student9a8 + student9a9 + student9a10 + student9a11 + student9a12 + student9a13 + student9a14 + student9a15
    student9average = student9total / 15

    student10total = student10a1 + student10a2 + student10a3 + student10a4 + student10a5 + student10a6 + student10a7 + student10a8 + student10a9 + student10a10 + student10a11 + student10a12 + student10a13 + student10a14 + student10a15
    student10average = student10total / 15





    ####Formatingaisnldkghalsdjg;lah;sdg
    print("Assigment averages:")
    print("Assignment1:" + str("{:.2f}".format(assignment1average)))
    print("Assignment2:" + str("{:.2f}".format(assignment2average)))
    print("Assignment3:" + str("{:.2f}".format(assignment3average)))
    print("Assignment4:" + str("{:.2f}".format(assignment4average)))
    print("Assignment5:" + str("{:.2f}".format(assignment5average)))
    print("Assignment6:" + str("{:.2f}".format(assignment6average)))
    print("Assignment7:" + str("{:.2f}".format(assignment7average)))
    print("Assignment8:" + str("{:.2f}".format(assignment8average)))
    print("Assignment9:" + str("{:.2f}".format(assignment9average)))
    print("Assignment10:" + str("{:.2f}".format(assignment10average)))
    print("Assignment11:" + str("{:.2f}".format(assignment11average)))
    print("Assignment12:" + str("{:.2f}".format(assignment12average)))
    print("Assignment13:" + str("{:.2f}".format(assignment13average)))
    print("Assignment14:" + str("{:.2f}".format(assignment14average)))
    print("Assignment15:" + str("{:.2f}".format(assignment15average)))
    print()
    print("Student averages:")
    print("Student1:" + str("{:.2f}".format(student1average)))
    print("Student2:" + str("{:.2f}".format(student2average)))
    print("Student3:" + str("{:.2f}".format(student3average)))
    print("Student4:" + str("{:.2f}".format(student4average)))
    print("Student5:" + str("{:.2f}".format(student5average)))
    print("Student6:" + str("{:.2f}".format(student6average)))
    print("Student7:" + str("{:.2f}".format(student7average)))
    print("Student8:" + str("{:.2f}".format(student8average)))
    print("Student9:" + str("{:.2f}".format(student9average)))
    print("Student10:" + str("{:.2f}".format(student10average)))
    print()
    input("Press ENTER when finished viewing")

```

##Links to other pages
- [Home](/README.md)
- [Writings](/Writings.md)

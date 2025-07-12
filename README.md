# python36
Subject Marks
total=0
def add_subject_marks():
    global total
    marks=int(input("Enter marks of a subject:"))
    total+=marks
    return marks
print("subject1 marks :",add_subject_marks() )
print("subject2 marks :",add_subject_marks() )
print("subject3 marks :",add_subject_marks() )
print("total marks stored in global:",total)

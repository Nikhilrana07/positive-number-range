# positive-number-range
Completely by nikhil rana
import CSV
Def write_info_CSV(info_list):
    with open('student_info.CSV','a',newline='') as CSV_file:
    writer = CSV.writer(CSV_file) 
    writer.writerow(CSV_file)

condition = True
While(condition):
    student_info=input("enter information of student in the following format(Name Age Contact_Number Email_id):")
    Print("entered information"+student_info)
    Student_info_list = student_info.split(' ')
    Print("entered split up information:"+str(student_info_list))

    Write_into_CSV(student_info_list)

    condition_choice=input("enter (yes/no) if you want information of another student:")
    if condition_choice=="yes"
        Condition=true
    elif conditions_choice=="no"
        condition=false

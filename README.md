# Algorithm to print the grade obtained by a student:


Step 1: Start StudentGrade.
Step 2: Take input, marks of student in five subjects as ‘m1’,’m2’,’m3’,’m4’,’m5’.
Step 3: Add all marks, sum:=m1+m2+m3+m4+m5
Step 4: Calculate percentage of sum as marks_per:=(sum/500)*100
Step 5: if marks_per >= 90 
                print "Grade-A"
                then goto Step 9
Step 6: else if    80<=marks_per<90
                print "Grade-B"
                then goto Step 9 
Step 7: else if  70<=marks_per<80
                print "Grade-C"
                then goto Step 9
Step 8: else if 60<=marks_per<70
                print "Grade-D"
                then goto Step 9
Step 8: else if 50<=marks_per<60
                print "Grade-E"
                then goto Step 9
Step 9: else 
                print "Fail"
                then goto Step 9
Step 10: End StudentGrade.



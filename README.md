Carny
==================

Python script to aid in date string conversion to UNIX time. 
The main function in carny is guess(str). The function takes
in an arbitrary date, represented as a string, and makes an
attempt to convert the string into UNIX time. The secondary
method in carny is get_epoch(date_str,format). This function
takes in the date string as well as a time.strptime format
string and returns UNIX time. 


Usage
==================
import carny

date_string = "2006-10-01T17:24:44"
epoch = carny.guess(date_string)

print(epoch)



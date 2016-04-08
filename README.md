# attendance-app
Basic app to scan student IDs and add attendance to a dictionary. 
The student data is stored via the `shelve` module in the file `my_students.db`.
Student IDs are the key for each item in the `shelve`, with each student represented by a dictionary with the format
`{'name': 'student full name', 'attendance':[list of unix timestamps], 'lates':[list of unix timestamps]}`.

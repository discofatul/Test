# Test

This aplication read a list of clients from https://jsonplaceholder.typicode.com/users
and move it into a Microsoft Acces database (I tired to connect PostgreSQL database, bu i did not succeed)
also at each run aplication delete all data from database because data recived from json is identical every time.

I do:
-Store the users and the data connected to them in a database
-Validate all the user emails

I didn't do
- Check if it was a successful http call and you get back the response correctly (same count of users every time and 200 OK http status)
- Create a log file automatically which contains the details of the api calls and the response statuses. 

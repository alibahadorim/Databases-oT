# Databases-oT
Sensor Data Collection Program :At this point, your database and underlying table is ready to receive data and respond to any SQL- based search requests. Write your program that will insert data in a timed loop (infinite escapable loop with a sleep() function call) or use your operating system’s scheduler (aka “cron”). 
Before executing your Sensor Data Collection Program :At this point, your database and underlying table is ready to receive data and respond to any SQL- based search requests. Write your program that will insert data in a timed loop (infinite escapable loop with a sleep() function call) or use your operating system’s scheduler (aka “cron”). Before executing your
In this part , we need to use python code to generate the data base and using db brows to display them

Output of there sensed sensors which are red every 5. Minutes showing by db brows for SQLite
RESTful Service :Write a separate flask program that will respond with the last 10 database sensor data row “inserts” in JSON format. This program will return a JSON data structure of your sensor’s data. Design your restful service with the following URL: /assignment6/api/ sensors/. This program should return your data when requested on demand. Use SQL “SELECT” statements to get the data you need.
In this part , we need to use flask to send the generated database to client via insomnia, in this case we have used 5 seconds instead of 5 minutes to save the time and sensor_id is counting to track the last 10 database easier.
By sending the order by Insomnia API, the flask on raspberry can send the data
Output of there sensed sensors which are red every 5 Seconds showing by db brows for SQLite


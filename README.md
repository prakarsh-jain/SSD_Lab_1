Question1
We have a log file named access.log containing HTTP request data, with each line in the
following format:
127.0.0.1 - - [08/Aug/2024:14:55:02 +0000] "GET /index.html HTTP/1.1" 200 1043
Task: Write a bash script to extract all lines from access.log where the request method is POST
and the HTTP status code is 404.

Solution-
Using awk we can seperate the lines according to the given task.
The 2024201055_q1.sh file contails the bash command for the task.
we can run this file on bash terminal- ./2024201055_q1.sh

Question 2
Write a bash script to calculate the total power level of all the seniors in
power_levels.txt.
using awk seperator and sum action we have computed the power.
The 2024201055_q2.sh file contails the bash command for the task.
we can run this file on bash terminal- ./2024201055_q2.sh



# Large_and_Social_Networks
This is a project I made to analyse queing systems.\
It works with the a CSV file in the format of the "example" file i have in the repo.\
+ Collumn 0: Ticket Number <ins>_(Not Used)_</ins>
+ Collumn 1: Server responsible for the ticket
+ Collumn 2: Day the ticket was assigned <ins>_(Not Used)_</ins>
+ Collumn 3: Time and Date the ticket was resolved
+ Collumn 4: Day the ticket was completed <ins>_(Not Used)_</ins>
+ Collumn 5: Time and Date the ticket was resolved
+ Collumn 6: A tuple that represents the total working hours and minutes until it was resolved. Tuple -> (hours, minutes)

(This was calculated while the data were beeing collected)

Additionally there are some Queueing models I implemented in python.
- M/G/10/FCFS
- M/G/K/FCFS
- M/M/K/FCFS

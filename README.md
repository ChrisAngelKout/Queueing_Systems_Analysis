# Queueing Systems Analysis
This is a project I made to analyse queing systems.\
It works with the a CSV file in the format of the "example" file i have in the repo.\
+ Collumn 0: &emsp; Ticket Number <ins>_(Not Used)_</ins>
+ Collumn 1: &emsp; Server responsible for the ticket
+ Collumn 2: &emsp; Day the ticket was assigned <ins>_(Not Used)_</ins>
+ Collumn 3: &emsp; Time and Date the ticket was resolved
+ Collumn 4: &emsp; Day the ticket was completed <ins>_(Not Used)_</ins>
+ Collumn 5: &emsp; Time and Date the ticket was resolved
+ Collumn 6: &emsp; A tuple that represents the total working hours and minutes until it was resolved. <ins>*__Tuple -> (hours, minutes)__*</ins> <br/>
  &emsp; &emsp; &emsp; &emsp; &emsp;(This was calculated while the data were beeing collected)

Additionally there are some Queueing models I implemented in python:
- M/G/10/FCFS
- M/G/K/FCFS
- M/M/K/FCFS

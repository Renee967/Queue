# Queue

To use classes for a solution to a real-world problem. Get familiar with data structure Queue. The practice of dynamic array application.
Instructions
In this program, you will implement a FIFO or FCFS Queue.

 

The data:

 Define a class named Customer with four private attributes:

CustomerName: string which is the name of the customer

ArrivalTime: integer, which is the arrival time of the customer

ServiceTime: integer, which is the time point that the customer starts to be serviced

FinishTime: integer, which is the leaving time of the customer

 

And two public methods:

method setCustomer that takes 3 parameters: customer name as a character array or a string, arrival time as an integer, and service time as an integer
method displayCustomer will display a customer name, arrival time, service time, and finish time.
 

 

Define a class named FCFSQueue with two private attributes:

CustomerList: an array of 100 elements of type Customer;

length: integer, which is the number of customers in the queue.

 

And four public methods:

 

method IsEmpty checks whether the queue is empty or not. Return true if empty, otherwise, return false;
method GetLength will return the number of customers in the queue;
method Enqueue will insert a new customer to the tail of the queue;
method Dequeue will remove a customer from the head of the queue and display the removed customer's info if the queue is not empty otherwise display “The queue is empty”.
Test:

Declare an object of type FCFSQueue.

Enqueue 5 different customers

Display length of the queue ( 5 should be displayed)

Dequeue 5 customers

Display length of the queue  ( 0 should be displayed)

Dequeue 1 customer (Message should be displayed “The queue is empty”)

Display length of the queue  ( 0 should be displayed)

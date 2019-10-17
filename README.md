# Stacks
## Aim
To execute push, pop and display functions in a Stack.
## Theory
A stack is an Abstract Data Type (ADT). Stacks use the princliple of LIFO, i.e, Last in, First out. There are 2 main functions of stacks, that are- PUSH and POP. Push is a function that is used to insert or input an element in the stack. Pop is a function that is used to delete or remove an element from the top of the stack. Whenever the stack is empty, the value of top is -1. When the stack is full, the value of top is max-1. If the stack is empty, no element can be poped or removed and the stack represents "Stack Underflow". If the stack is full, no element can be pushed or inserted into the stack and the stack represents "Stack Overfull". The display function displays all the elements present in the stack at that given time. Stacks find applications in the following: Reversing a string, Checking the proper opening and closing of paranthesis etc. 
## Algorithm
Step 1:Start. 
Step 2:Initialize a array, max value and tos = -1 as global variables. 
Step 3:Initialize the functions, push, pop and display. 
Step 4:Get choice from user for the operation to be performed. 
Step 5:Using switch cases, call the functions for the operation to be executed. 
Step 6:In the push function, first we check if the stack overflow condition is satisfied or not. If it is not satisfied, take input of the element and insert into the stack. Increment the value of top. 
Step 7:In the pop function, first we check if the stack underflow condition is satisfied or not. If it is not satisfied, remove the element from the stack. Decrement the value of top. 
Step 8:In the display function, first the value of top is checked. If it is -1, the output displays "Empty". If not, the stack is printed. 
Step 9:End. 
## Conclusion
In this practical, we learnt about Stacks and their basic fucntions such as push and pop. We learnt how to implement a program to perform operations on stacks. We learnt about its principle and the method in which stacks functions. We also learnt about the applications of stack.

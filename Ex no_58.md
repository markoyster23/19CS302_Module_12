# EX 58 C Function to display queue elements using Linked List.(use integer data in the queue)
## DATE:
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to display queue elements using linked list. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End
## Program:
```
struct Node 
{ 
int data; 
struct Node *next; 
}*front=NULL,*rear=NULL; 
void display() 
{ 
struct Node *temp=front; 
if(temp==NULL) 
{ 
printf("queue is empty\n"); 
} 
else 
{ 
while(temp!=NULL) 
{ 
printf("%d\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:
10.01\
20.01



## Result:
Thus the program was executed and the output was verified successfully.

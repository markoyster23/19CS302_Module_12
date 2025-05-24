# EX 59 C functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.(use character data in Queue).
## DATE:
## AIM:
To write a C functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.

## Algorithm
1. 
2. 
3. 
4.  
5.   

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
30.01


## Result:
Thus the program was executed and the output was verified successfully.

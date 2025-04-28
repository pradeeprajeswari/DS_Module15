# Ex15 Largest Element in BST
## DATE:17/03/2025
## AIM:
To Write a c program to find the largest value in a Binary Search Tree.

## Algorithm

1. Start the program.
2.  Create or input the root node of the Binary Search Tree.
3. Initialize a pointer to the root node.
4. Traverse to the right child repeatedly until the rightmost node is reached.
5.The node with no right child contains the largest value.
6.Print the value of that node.
7.End.



## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: PRADEEP E
RegisterNumber:  212223230149
*/
```
```
void largest(struct node *root)
{
   while (root != NULL && root->right != NULL)
   {
       root = root->right;
   }
   printf("\nLargest value is %d", root->info);
}
```
## Output:

![image](https://github.com/user-attachments/assets/e687c766-891f-4338-90e3-b8549feeacc7)


## Result:
Thus, the C program to find the largest value in a Binary Search Tree is implemented successfully.

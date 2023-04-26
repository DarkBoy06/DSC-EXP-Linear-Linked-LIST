# DSC-EXP-Linear-Linked-LIST
Description: This program creates a linked list of three nodes, where each node contains an integer data value and a pointer to the next node in the list. The last node points to NULL indicating the end of the list.

Algorithm:

Declare a struct node with two members, an integer 'data' and a pointer to the next node 'next' Create three nodes of the struct type using malloc function Assign values to the 'data' member of each node Assign the address of the second node to the 'next' pointer of the first node Assign the address of the third node to the 'next' pointer of the second node Assign NULL to the 'next' pointer of the third node Print the data value, self address, and next address of each node.

Output: data=20 selfaddr=9447648 nextaddr = 9447680 data=30 selfaddr=9447680 nextaddr = 9447712 data=40 selfaddr=9447712 nextaddr = 0

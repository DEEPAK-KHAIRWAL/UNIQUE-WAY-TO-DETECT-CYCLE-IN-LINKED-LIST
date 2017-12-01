/*
Detect a cycle in a linked list. Note that the head pointer may be 'NULL' if the list is empty.

A Node is defined as: 
    struct Node {
        int data;
        struct Node* next;
    }
*/

bool has_cycle(Node* head) {
    if( head==NULL)
        return false;
    else
    {
        struct Node* target = new Node;
        struct Node* temp=head;
        struct Node* temp1;
        while(temp->next!= target && temp->next !=NULL)
        {
            temp1=temp->next;
            temp->next=target;
            temp=temp1;
         }
        if(temp->next==target)
            return true;
        else
            return false;
        
}
}

## Linked List

A linked list is a linear data structure where elements are stored in nodes. Each node contains two parts: the data and a reference (or link) to the next node in the sequence. Unlike arrays, linked lists do not store elements in contiguous memory locations, which allows for efficient insertion and deletion operations.

### Types of Linked Lists

1. **Singly Linked List**: Each node points to the next node in the sequence, with the last node pointing to `nullptr`.
2. **Doubly Linked List**: Each node contains two links, one to the next node and one to the previous node, allowing for traversal in both directions.
3. **Circular Linked List**: The last node points back to the first node, forming a circle. This can be implemented for both singly and doubly linked lists.

### Example of a Singly Linked List

Here's a simple example of a singly linked list in C++:

```cpp
#include <iostream>
using namespace std;

// Node structure
struct Node {
    int data;
    Node* next;
};

// Function to print the linked list
void printList(Node* n) {
    while (n != nullptr) {
        cout << n->data << " ";
        n = n->next;
    }
}

int main() {
    // Creating nodes
    Node* head = new Node();
    Node* second = new Node();
    Node* third = new Node();

    // Assigning data and linking nodes
    head->data = 1;
    head->next = second;

    second->data = 2;
    second->next = third;

    third->data = 3;
    third->next = nullptr;

    // Printing the linked list
    printList(head);

    return 0;
}
```

### Operations on Linked Lists

1. **Insertion**: 
    - **At the beginning**: A new node is added before the head, and this new node becomes the new head.
    - **At the end**: A new node is added after the last node, and the last node's `next` is updated to point to this new node.
    - **In the middle**: A new node is inserted between two nodes, with the previous node's `next` pointing to the new node, and the new node's `next` pointing to the subsequent node.

2. **Deletion**: 
    - **From the beginning**: The head node is removed, and the next node becomes the new head.
    - **From the end**: The last node is removed, and the second-last node's `next` is updated to `nullptr`.
    - **From the middle**: A node is removed by updating the previous node's `next` to point to the node after the one being deleted.

3. **Traversal**: 
    - Accessing each node in the list, starting from the head, until the end of the list is reached (where `next` is `nullptr`).

4. **Searching**:
    - Finding a node in the linked list by iterating through the nodes until the desired value is found.

### Advantages of Linked Lists

- **Dynamic Size**: The size of a linked list can grow or shrink as needed, making it flexible compared to arrays.
- **Efficient Insertions/Deletions**: Insertions and deletions are more efficient, especially at the beginning or end of the list, since there is no need to shift elements as in arrays.

### Disadvantages of Linked Lists

- **Memory Usage**: Linked lists use more memory due to the storage of pointers in each node.
- **Sequential Access**: Accessing elements is slower compared to arrays, as it requires traversing the list from the head node to the desired node.
- **Cache Locality**: Due to non-contiguous memory allocation, linked lists do not benefit from locality of reference, making them slower in accessing nodes.

### Applications of Linked Lists

- **Dynamic Data Structures**: Linked lists are used to implement stacks, queues, graphs, and other complex data structures.
- **Memory Management**: They are used in dynamic memory allocation strategies, such as in managing free lists of available memory.
- **Handling Collisions in Hash Tables**: Linked lists are often used to handle collisions in hash tables through chaining.

### Conclusion

Linked lists are a fundamental data structure that offers flexibility in dynamic memory usage and efficient insertions and deletions. However, they come with trade-offs, such as increased memory usage and slower access times. Understanding these pros and cons helps in deciding when to use linked lists in practical applications.

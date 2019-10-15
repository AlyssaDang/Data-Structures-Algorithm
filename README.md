# Data-Structures-Algorithm
Review of Data Structures and Algorithms


0. Linked-List:   A structure containing nodes, which has 1+ pointer variable that references its place in the structure.
                  The first node is called the HEAD and the last node is called the (optional) TAIL.

                  Singly Linked-List: Each node contains a singular pointer to the *next node.

                  Doubly Linked-List: Each node contains a pointer to the *next node and the *previous node

                  Circular Linked-List: This can be singly linked or doubly linked. 
                                        The last node's *next pointer points to HEAD and 
                                        the HEAD's *previous pointer points to the TAIL.
                                        
                  I will be using Linked-Lists and other methods to implement the following data structures:


1. Array: A linear data structure that can hold items of the same type.

                  Static Array: An array where the size is fixed and declared at instantiation.
                  Dynamic Array: An array where the size is growable.
                  Linked-List Implementation: This implements a dynamic array where elements are stored in nodes.
                  
                                      Implementation File: ArrayLL.cpp                Space: O(n)
                                      Public Functions:                               Time Complexity:
                                      Constructor ArrayLL()                           O(1)
                                      insert(item)                                    O(1)
                                      insert(index, item)                             O(n)
                                      getAt(index)                                    O(n)
                                      delete(index)                                   O(n)
                                      getSize()                                       O(1)
                                      Deconstructor ~ArrayLL()

2. Stack: A linear data structure that removes and inserts items from the same end. LIFO (Last In, First Out)

                  Array Implementation:
                  
                                      Implementation File: StackArray.cpp
                                      Public Functions:                               Time Complexity:
                                      Constructor StackArray()
                                      Push(item)
                                      Top()
                                      Pop(item)
                                      getSize()
                                      Deconstructor StackArray()
                                      
                  Linked-List Implementation:
                  
                                      Implementation File: StackLL.cpp
                                      Public Functions:                               Time Complexity:
                                      Constructor StackLL()
                                      Push(item)
                                      Top()
                                      Pop(item)
                                      getSize()
                                      Deconstructor StackLL()
                                      
3. Queue: A linear data structure that removes items the opposite end of the insertion. FIFO (First In, First Out)

                  Array Implementation:
                  
                                      Implementation File: QueueArray.cpp
                                      Public Functions:                               Time Complexity:
                                      
                  Linked-List Implementation:
                  
                                      Implementation File: QueueLL.cpp
                                      Public Functions:                               Time Complexity:

4. Tree

                  Array Implementation:
                  
                                      Implementation File: TreeArray.cpp
                                      Public Functions:                               Time Complexity:

                  Linked-List Implementation:
                  
                                      Implementation File: TreeLL.cpp
                                      Public Functions:                               Time Complexity:
                                      
5. Heap

                  Array Implementation:
                  Linked-List Implementation:
            
6. Hash

                  Array Implementation:
                  Linked-List Implementation:
            
7. Matrix

                  Array Implementation:
                  Linked-List Implementation:

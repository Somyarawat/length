# Linked-Lists

An array is an indexed data structure, which means you can select its elements in arbitrary  order as determined by the 
index value. You can also access the elements in sequence using  a loop that increments the index.  
However, you can’t do the following with an array object:
- Increase or decrease its length, which is fixed.
- Add an element at a specified position without shifting the other elements to make room.
- Remove an element at a specified position without shifting the other elements to fill in the resulting gap.

---

In this package you will find a 'Linked-List' Java class that will perform the following operations:

- Check if the linked-list is empty (isEmpty).
- Add an element at the end of the list (add).
- Remove an element (remove).
- Return the size of the list (size).
- Sequentially access all the list elements without having to manipulate an index (print).
- find a specified target value (search).

---

A Linked-List data structure provides the ability to add or remove items in the list in constant time i.e. O(1).
It is useful in cases when you need to insert and remove elements frequently. Each element in a linked-list, is called
a node, and stores information (data) and a "link" to the next node in the list. After we find the position of a node to
be inserted or removed, the actual insertion or removal is done in constant time and no shifts are required unlike an 
array.

A _node_ is a data structure that contains a data item and (usually) one or more links. A _link_ is a reference to another
node.
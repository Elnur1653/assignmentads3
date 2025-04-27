              MyHashTable<K, V>


This class implements a custom hash table using separate chaining with linked lists to handle collisions. Each bucket is a linked list of HashNode objects.

Key features:

put(K key, V value): Inserts a new key-value pair or updates an existing key with a new value.

get(K key): Retrieves the value associated with the given key.

remove(K key): Removes the key-value pair by the specified key.

contains(V value): Checks if a value exists in the hash table.

getKey(V value): Finds and returns a key associated with a given value.

size(): Returns the number of key-value pairs stored in the table.

printBuckets(): Displays the contents of each bucket to analyze data distribution.


              MyTestingClass

This class is used to generate custom key objects for testing the hash table. 
Each object has two fields: a String name and an int id.

Key features:

Implements a custom equals() method to compare objects based on both name and id.

Implements a custom hashCode() method that manually computes a hash code based on the id and the characters of name.

Provides a toString() method for easy display of the object's contents.


              BST Class

This class implements a generic binary search tree (BST) for storing key-value pairs. Each node in the tree contains a comparable key (`K`) and an associated value (`V`).

Key Features:
- Key-Value Storage: Stores keys and values in a hierarchical structure.
- Custom Operations:
  - `put(K key, V value)`: Inserts or updates a key-value pair.
  - `get(K key)`: Retrieves the value associated with a key.
  - `delete(K key)`: Removes a node by its key while maintaining BST properties.
  - `size()`: Returns the total number of nodes.
- In-Order Iterator: Provides an iterator to traverse the tree in ascending order of keys.
- Dynamic Resizing: Tracks the size of the tree dynamically.

Node Structure:
Each node contains:
- A key (`K`) for ordering.
- A value (`V`) for data storage.
- Pointers to left and right child nodes.

Usage:
Designed for efficient insertion, deletion, and lookup operations, making it suitable for applications requiring sorted key-value storage.
              

             
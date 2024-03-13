## Hashing definition:

Hashing is an effective way to reduce the number of comparisons. It deals with providing the direct address of the record where the record is likely to be stored.

### Basic concepts of hashing:

1. **Hash Table**: Hash table is a data structure used for storing and retrieving data quickly. Every entry in the hash table is made using a hash function.

2. **Hash Function**:
   - A hash function is used to place data in the hash table and retrieve data from it. It's essential for implementing hash tables.
   - For example, consider a hash function as "key mod 5" for a hash table of size 5.

![Hash Table Example](https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313112243.png?raw=true)

3. **Bucket**: The hash function H(Key) is used to map several dictionary entries in the hash table. Each position of the hash table is called a "bucket."

4. **Collision**: Collision is a situation in which the hash function returns the same address for more than one record.

![Collision Example](https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313112642.png?raw=true)

5. **Probe**: Each calculation of an address and test for success is known as a "probe."

6. **Synonym**: The set of keys that hash to the same location are called synonyms. For example, in the given hash table, 25 and 55 are synonyms.

7. **Overflow**: When the hash table becomes full and a new record needs to be inserted, it's called overflow.

![Overflow Example](https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313113424.png?raw=true)

8. **Perfect Hash Function**: A perfect hash function maps distinct key elements into the hash table with no collisions.

### Advantages of the perfect hash function:
1. A perfect hash function with a limited set of elements can be used for efficient lookup operations.
2. There's no need to apply collision resolution techniques.

## Properties of a good hash function:
1. The hash function should be simple to compute.
2. The number of collisions should be minimal while placing the record in the hash table.
3. The hash function should generate keys that distribute uniformly over an array.
4. The hash function should depend on every bit of the key.

## Collision Resolution Technique:
If a collision occurs, it should be handled by applying collision handling techniques.

### Hashing Techniques to Explore:
- [ ] Open Hashing - Chaining
- [ ] Closed Hashing:
  - [ ] Linear Probing
  - [ ] Quadratic Probing
  - [ ] Double Hashing

## Skip List
- Skip list is a variant of the linked list.
- Skip lists are made up of a series of nodes connected one after the other. Each node contains a key and value pair as well as one or more references, or pointers, to nodes further along in the list.
- The number of references each node contains is determined randomly, and it's called its "node level."
- There are two special nodes in the skip list: the head node, which is the starting node of the list, and the tail node, which is the last node of the list.
- Skip lists are an efficient implementation of a dictionary using a sorted chain.
   - [ ] Skip list complete this all
![Skip List Example](https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313124739.png?raw=true)

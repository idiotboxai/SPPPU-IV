## **hashing definition:-** 

Hashing is an effective way to reduce the number of comparisons. Actually hashing deals with the idea of providing the direct address of the record where the record is likely to stored.
Basic concepts of the hashing:-
1) **Hash Table** : Hash table is data structure used for storing and retrieving data quickly. Every entry in the hash table is made using Hash function.
2)  **Hash Function** : 
     - Hash function is a function used to place data in hash table.
     - Similarly Hash function is used to retrieve the data from the hash table.
     - This the use of hash function is to implement hash table.
     - e/q :- consider hash function as key mod 5. The hash table of size 5.
    [Image Description](https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313112243.png)

3)  **Bucket** : The hash function H(Key) is used to map several dictionary entries in the hash table. Each position of the hash table is called as  ==bucket==.
4) **Collision** : Collision is situation in which hash function returns the same address for more than one record.
        For Example: 
      [Image Description]([https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313112642.png])
5) **Probe :** Each calculation of an address and test for the success is known as ==probe==.
6) **Synonym** : The set of key that has to the same location are called ==synonyms==. For example - In above given hash table computation 25 and 55 are synonyms.
   
   7) **Overflow** : When hash table becomes full and new record needs to be inserted then it is called as overflow.
[Image Description]([[https://github.com/idiotboxai/SPPPU-IV/blob/main/DSA/Pasted%20image%2020240313113424.png)
    
8) Perfect hash function : The perfect hash function is a function that maps distinct key elements into the hash table with no collisions.

**Advantages of the perfect hash function** :
        1) A perfect hash function with limited set of the elements can be used for efficient lookup operation.
        2) There is no need to apply collision resolution techniques.
           
## **Properties of the good hash function**
1) The hash function should be simple to compute.
2) Number of collision should be less while placing the record in the hash table.
3) Hash function should generate such keys which will get distributed uniformly over an array.
4) The hash function should depend on every bit of the key. Thus the hash function that simply extracts the portion of a key is not suitable.

## **Collision Resolution Technique **

**Definition**: 
If the collision occur then it should be handled by applying some techniques, such techniques are called as==collision handling techniques==.

        ![[Pasted image 20240313115038.png]]

- [ ] Watch hashing techniques and check this out 
    - [ ]  Open Hashing - Chaining 
    - [ ] Closed Hashing - 
        - [ ] Linear Probing 
        - [ ] Quadratic Probing 
        - [ ] Double Hashing 


## Skip List
 - Skip list is a variable for the linked list.
 - Skip lists are made up of a series of nodes connected one after the other. Each node contains a key and value pair as well as one or more reference, or pointers, to nodes further along in the list.
 - The number of references each node contains in determined randomly. The number of reference a node contains is called its **==node level.==**
 - There are two special nodes in the skip list one is head node while starting node of the list and tail node is the last node of the list.
 - The skip list is efficient implementation of dictionary using sorted chain. This is because in skip list each node consist of forward references of more than one node at a time.
 -  fig :-  
      ![[Pasted image 20240313122826.png]]

- [ ] Skip list complete this all 
- [ ] ![[Pasted image 20240313124739.png]]





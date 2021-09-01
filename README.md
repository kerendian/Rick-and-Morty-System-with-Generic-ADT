# Rick and Morty - Management System
## The idea:
Based on an episode in the series Rick and Morty where a lot of Jerries (Morty's dad) enters through the portal and they do not know who the real Jerry is. They embark on a journey to find the real Jerry, by collecting Jerries and classifying them by certain attributes in the Jerries management system.

## The Data Structures
**Implemented four generic ADT types** - KeyValuePair, LinkedList, HashTable and Multi-ValueHashTable. We used them to implement a management system to manage different types of Jerries.

**Multi-ValueHashTable** - The HashTable must support pairing: Key and Value and deals with collisions by chaining to the linked list. The difference is that each key can have several different values. And they must be kept together so that given a key we return a list of all the values which have the same key in O(1) on average.
## The management system 
Created the structs required for the management system - Jerry, Planet, Physical Property, Origin Each of the data structures performs functions such as create, destroy, add, delete, print, search, and more.
Implemented the four functions needed to implement generic ADT by the user - delete, copy, compare and print.

Reading from a configuration file with a known structure and placing the various structures from the file into the management system. 

The management system is presented in the form of a switch case menu in which the various options for execution - for example adding, deleting, searching according to different properties, printing according to different properties, and additional options - all done according to the user's choices and inputs, and required runtimes.

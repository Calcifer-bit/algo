
 

  Data Structures:

1. Array
2. Linked List : reduce the space wastage Linked List is formed which adds a node only when a new element is introduced. Insertions and deletions also become easier with linked list.One big drawback of linked list is, random access is not allowed
  1->2->3->4->NULL
 NULL<-1<->2<->3->NULL
  1->2->3->1 [The next pointer of last node is pointing to the first]
  
3. Stack: maintaining function calls,in cases where we have to reverse a word, check for balanced parenthesis and in editors where the word you typed the last is the first to be removed when you use undo operation, browser back button
4. Queue :  to the queues of bus stop or train where the person who is standing in the front of the queue(standing for the longest time)
is the first one to get the ticket.
include CPU scheduling, Disk Scheduling. Another application of queue is when data is transferred asynchronously (data not necessarily received at same rate as sent) between two processes. Examples include IO Buffers, pipes, file IO, etc.
 

5. Binary Tree 
each node has at most two children, It is implemented mainly using Links.They are useful in File structures where each file is located in a particular directory and there is a specific hierarchy associated with files and directories.storing heirarchical objects like JavaScript Document Object Model considers HTML page as a tree with nesting of tags as parent child relations.

6. Binary Search Tree
.The left subtree of a node contains only nodes with keys less than the node’s key.
.The right subtree of a node contains only nodes with keys greater than the node’s key.
.. The left and right subtree each must also be a binary search tree.
For example in implementation in E- commerce websites where a new product is added or product goes out of stock and all products are lised in sorted order.

7. Binary Heap
. It’s a complete tree
.A Binary Heap is either Min Heap or Max Heap.
scheduling processes in operating systems. Priority Queues are also used in Dijstra’s and Prim’s graph algorithms.
Order statistics: The Heap data structure can be used to efficiently find the k’th smallest (or largest) element in an array.

9. Hashing
 .function that converts a given big input key to a small practical integer value.
Hashing can be used to remove duplicates from a set of elements. Can also be used find frequency of all items
 in web browsers, we can check visited urls using hashing. In firewalls, we can use hashing to detect spam. We need to hash IP addresses. Hashing can be used in any situation where want search() insert() and delete() in O(1) time.

Time complexity, Math ( permutation, combination) 
Binary Search , String, 
Bit Manuplation
 .A B Swap ... 
   A= A^B 
   B =A^B 
   A =A^B
Linked List, Two potinters , Stacks and Queue
Heap and Maps , Tree 
Graph, 

Insertion sort
Divide & Conquer (   Merge Sort ) 
Backtracking
Tree traverse 
Priority Queue = Heap 
Topology Sorting _ implementing to DFS first, 

#DevOps
Terraform
Ansible, Chef 

#Network 
OSI 7 layer 
Tracert, IPSec, IPConfig, ping , nslookup,, 
SSH , SSL Encryption , Public Key , Cipher, AES256, SHA2  , openssl 

#Cache 
Redis, Memcache, Nginx static Cache 

#Web server 
tomcat session manager 

#DB
Mysql, Ms SQL, Oracle , PL/SQL
PostgreSQL

#NodeJS - Angular
NPM Package, package.json build 

#Maven Web project - Spring Framework 
Maven Build , Tomcat deployment 

#Python 

#System Design 
if you need to design your design carefully, you should focus three requirement topics which are functional, nonfunctional, extended requirements.
Availability is more important than consistency so a user may not see photo for a while, this is fine.
  CAP theorem is quite different from the consistency guaranteed in ACID database transactions.

The system can work based on CAP Theorem for reliability and minimum latency are two main points of consideration.
  – Client
   – Services
   – Web server
   – Application server
   – Picture Storage
   – Database
   – Caching
   – Replication
   – Redundancy
   – Load balancing
   – Sharding


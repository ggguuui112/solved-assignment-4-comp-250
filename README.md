Download Link: https://assignmentchef.com/product/solved-assignment-4-comp-250
<br>
Hash Table

In this Assignment you will implement a hash table as an arraylist of buckets. Each bucket of the hash table contains a singly linked list of nodes containing key-value pairs.

The starter code consists of five classes:

<ul>

 <li>MyHashTable which is a simplified and reduced version of HashMap</li>

 <li>HashNode which stores a key-value pair (i.e. hash table entry); you may add helper methods to this class if you wish. For simplicity of editing, this is a separate java file rather than an inner class of MyHashTable.</li>

 <li>HashLinkedList which is a linked list of HashNode objects with code stubs.</li>

 <li>Song that describes song objects which will be stored in the hash table</li>

 <li>HashTableTester class which uses a MyHashTable to store a list of songs. The key is the song title and the Song object is value. Thus, the key happens also to be one of the fields of value object.</li>

</ul>

You may add additional tests in the HashTableTester class, but you must <strong>not </strong>modify the Song class.

last updated: 22<sup>nd </sup>Nov, 2017 at 13:38                    1

<h1>Your Task</h1>

<h2>(30 points)</h2>

Implement HashLinkedList, which is a simple version of the singly linked list class for the buckets of the hash table. You can start from the linked list implementation provided on the course web site ( <a href="http://www.cim.mcgill.ca/~langer/250/LinkedList_Exercises.zip">Exercises</a> <a href="http://www.cim.mcgill.ca/~langer/250/LinkedList_Exercises.zip">3</a><a href="http://www.cim.mcgill.ca/~langer/250/LinkedList_Exercises.zip">)</a> as a guide. In particular, implement the methods

<ul>

 <li>add(K,V), remove(K), removeFirst(), getListNode(K).</li>

</ul>

Note that you will need to modify the given singly linked list code to use it in your hash table. In particular, the HashLinkedList&lt;K,V&gt; class has two generic types K,V instead of one generic type E in SLinkedList&lt;E&gt; class.

<h2>(70 points)</h2>

Implement the following methods in the MyHashTable class:

<ul>

 <li>the constructor MyHashTable()</li>

 <li>put(K,V), get(K), remove(K), rehash(), keys(), values()</li>

 <li>the constructor for the inner class HashIterator.</li>

</ul>

For the specification of what these methods must do, see the comments in the code.

You may wish to add helper methods to the HashNode class.
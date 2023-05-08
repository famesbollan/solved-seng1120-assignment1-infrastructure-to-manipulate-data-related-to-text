Download Link: https://assignmentchef.com/product/solved-seng1120-assignment1-infrastructure-to-manipulate-data-related-to-text
<br>
You are required to build the infrastructure to manipulate data related to text. Your client further specifies that you are to create a class named LinkedList to store individual tokens. The LinkedList will store each token in a Node of the list, using the class string.

<strong>ASSIGNMENT TASK </strong>

You are required to use a <strong>doubly-linked list</strong>, as discussed in lectures, to create your own implementation of the LinkedList class. It will use instances of Node to store instances of value_type (in this assignment, each Node will be used to store an instance of string).

The LinkedList class will be used by a main program, to be supplied to you, as well as a makefile. You will need to design LinkedList and Node in a way that it communicates seamlessly with the main program and compiles with the makefile also supplied. Please refer to the lecture slides and recordings for guidance on how to implement both classes.

You will need to implement constructors, overloaded operators, and a method that sorts the content of the linked list. You can use any sorting algorithm, but we recommend bubble sort. It is not efficient, but is very easy to implement (<a href="https://www.geeksforgeeks.org/bubble-sort/">https://www.geeksforgeeks.org/bubble-sort/</a><a href="https://www.geeksforgeeks.org/bubble-sort/">)</a>.




<strong>For students in SENG6120, there is an extra requirement:  </strong>

<ul>

 <li>(3.0 marks) Extend the member method void remove(string) inside LinkedList. The extended method removes all occurrences of an input sentence. For instance, if the linked list contains</li>

</ul>

the sentence “The black cat was sitting on the black mat that was on the black floor”, and the input string for remove(string) is “on the black”, then the resulting linked list must be “The black cat was sitting mat that was floor”.
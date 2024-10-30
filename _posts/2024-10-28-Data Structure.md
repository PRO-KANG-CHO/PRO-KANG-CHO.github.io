# Data Structure of basic

The data structure type used in a particular situation is determined by the type of operations that will be required or the kineds of algorithms that will be applied. They includ the following:

---
<pre>
<span style="background-color:darkgreen"> Data structure hierarchy </span>

1. `<span style="color:gold"><strong>Primitive</strong></span>`
   1. integer
   2. float
   3. character
   4. boolean
   
2. `<span style="color:gold"><strong>Non-primitive</strong></span>`
   1. Linear
      1. array
      2. stack
      3. queue
      4. linked list
   
   2. Non-linear
      1. tree
      2. graph
      3. trie
      4. hash table
</pre>
---

### [1] ***_Primitive Data Structure***

#### Basic
* `Boolean` stores are either true or false.  
* `Integer` stores a range on mathematical integers. the kind of bits is various. 8bit, 16bit, 32bit, 64bit. also, represented method of integer has two. signed or unsigned.  
* `Floating-point` store a formulaic representation of real numbers.  
* `Fixed-point` store are used in some programming languages and hold real value. they are managed as digits to the left and right of the decimal point.  
* `Character` uses symbols from a defined mapping of integer values to symbols.  

#### Additional
* `Pointer` are reference values that point to other values. It is related in memory.  
* `String` is an array of characters followed by a stop code "0".

---

### [1] ***_Non-primitive Data Structure***
#### Linear
* `array` stores a collection of items at adjoining memory locations. Items that are the same type are stored toghter. so the position of each element can be calculated or retrieved easily by an index.
* `stack` stores a collection of items in the linear order that operations are aplied. This order could be last in, first out.
* `queue` stores a collection of items like a stack. However, the operation oreder can only first in, first out.
* `Linked list` stores a collection of items in a linear order. Each element like node, in a linked list contains a data item, as well as a reference, to the next item in the list.
* `Tree` stores a collection of items in an abstract, hierarchical way. Each node is associated with a key value, with parent nodes linked to child nodes, or subnodes. There's one root node that is the ancestor of all the nodes in the tree. roots are two, root node and subsequent node
* `Heap` is a tree-based structure in which each parent node's associated key value is greater than or equal to the key values of any of its children's key values

### [1] ***_Array***


<span style="background-color:darkgreen">`1. Array`</span>

https://www.techtarget.com/searchdatamanagement/definition/data-structure
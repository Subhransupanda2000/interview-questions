# 1.What is collection?
* java.utill.collection is the root interface of collection hirarchy.
* java jdk does not provide any classes for it but collection provide classes which is impliment subinterface of collection
* subinterface are set,list
* classes of set-hashset,linkedhashset...etc
* classs of list-Arraylist,linkedlist...etc.
# 2.Which interfaces and classes are most frequently used in Collection framework in java? 
* set,list,map interface are frequently used in java.
* Most frequently used classes in Collection framework are >
* HashSet, LinkedHashSet, TreeSet, ConcurrentSkipListSet classes implements Set interface.
* ArrayList, LinkedList, Vector, CopyOnWriteArrayList classes implements List interface.
* HashMap, Hashtable, ConcurrentHashMap, LinkedHashMap, TreeMap, ConcurrentSkipListMap classes implements Map interface.
# 3.What are subinterfaces of Collection interface in java? Is Map interface also a subinterface of Collection interface in java?
* set,list are subinterfaces of Collection interface in java. Map interface is not a subinterface of Collection interface in java.
# 4. What are differences between ArrayList and LinkedList in java?
# Arraylist
* java.utill.Arraylist is index based datastructure.
* Arraylist is resizeable in java.
* Intial capacity is 10.
* Arraylist is created  with size 10.it increses the size 50%.
* Arraylist impliment random acess to fast acess element fast.
* ArrayList extends AbstractList (abstract class) which provides implementation to  List interface to minimize the effort required to implement this interface backed by 
  RandomAccess interface.
* Get method of ArrayList directly gets element on specified index.
* Use ArrayList when get operations is more frequent than add and remove operations in java.
# Linkedlist
* java.utill.Linkedlist is also a datastructure which has one or more than one node together connecting eachother consisting data and reference to next node in a sequence.
* Linkedlist create new node (if required).
* intial capacity is 0.
* Linkedlist intial size 0. a new node will create size will increase one by one if node created.
* Linkedlist doesnot impliment random acess.
* LinkedList extends AbstractSequentialList (abstract class), AbstractSequentialList extends AbstractList. 
  In LinkedList, data is accessed sequentially, so for obtaining data at specific index, iteration is done on nodes sequentially in java.
* Get method of LinkedList iterates on nodes sequentially to get element on specified index. Hence, offering O(n) complexity in java.
* Use LinkedList when add and remove operations are more frequent than get operations in java.

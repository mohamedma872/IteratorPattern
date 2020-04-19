# IteratorPattern
iterator pattern provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation. It is behavioral design pattern.
<h1>1. When to use iterator design pattern</h1>
Every programming language support some data structures like list or maps, which are used to store a group of related objects. In Java, we have List, Map and Set interfaces and their implementations such as ArrayList and HashMap.

A collection is only useful when it’s provides a way to access its elements without exposing its internal structure. The iterators bear this responsibility.
The key idea is to take the responsibility for access and traversal out of the aggregate object and put it into an Iterator object that defines a standard traversal protocol.

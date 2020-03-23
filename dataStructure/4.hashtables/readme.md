I javascript we have default implementation of hash that is Object


Why hash ?
Main purpose of hash function is to search in O(1).

In javascript hash is implemented by default as object in which we can directly access any element in O(1)

We can also implement custom hash table to create custom hashtable we need to write efficient hash function

Hash function - A hash function is any function that can be used to map data of arbitrary size to fixed-size values.
The values returned by a hash function are called hash values, hash codes, digests, or simply hashes.
The values are used to index a fixed-size table called a hash table. Use of a hash function to index a hash table is called hashing or
scatter storage addressing.

Hash function must have following feature

1. Fast(constant time)

2. Doesnot cluster output at specific indices

3. Deterministic : Same input yeilds same output  always

It is always possible that hash function may have collision, there are many ways to avoid collision

1. Separate chaining - On collision  we store multiple item on same index using array or linked list
2. Linear probing - On collision we find next empty slot and insert


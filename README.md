# MyDailyCoding
My solutions for Daily Coding problems (https://www.dailycodingproblem.com/)


DC__9__.py

    (26.09.2018)   [Not solved yet...]
    
    This problem was asked by <Airbnb>.

        Given a list of integers, write a function that returns the largest sum of non-adjacent numbers. 
        Numbers can be 0 or negative.

        For example, [2, 4, 6, 2, 5] should return 13, since we pick 2, 6, and 5. 
                     [5, 1, 1, 5]    should return 10, since we pick 5 and 5.

        Follow-up: Can you do this in O(N) time and constant space?
        
        
DC__8__.py

    (25.09.2018)   [Not solved yet...]
    
    This problem was asked by Google.

        A unival tree (which stands for "universal value") is a tree where all nodes under it have the same value.

        Given the root to a binary tree, count the number of unival subtrees.

        For example, the following tree has 5 unival subtrees:

           0
          / \
         1   0
            / \
           1   0
          / \
         1   1
    

DC__7__.py

    (24.09.2018)

    This problem was asked by <Facebook>.

        Given the mapping  a=1, b=2, c=3, ... , z=26,  and an encoded message,
        count the number of ways it can be decoded.

        For example, the message, '111' would give <3>, since it could be decoded
        as: 'aaa', 'ak' or 'ka'.

        You can assume that the messages are decodable. For example, '0001' isn't allowed !


DC__6__.py
    
    (23.09.2018)   [Not solved yet...]
    
    This problem was asked by <Google>.

        An XOR linked list is a more memory efficient doubly linked list. 
        Instead of each node holding <next> and <prev> fields, it holds a field named <both>, 
        which is an XOR of the next node and the previous node. 
        Implement an XOR linked list; it has an  <add(element)>  which adds the element to the end, 
        and a  <get(index)>  which returns the node at index.

        If using a language that has no pointers (such as Python), you can assume you have access 
        to <get_pointer> and  <dereference_pointer> functions that converts between nodes and memory addresses.


DC__5__.py
    
    (22.09.2018)

    This problem was asked by <Jane Street>.

        cons(a, b) constructs a pair, and car(pair) and cdr(pair) returns the first and last element of that pair. 
        For example, car(cons(3, 4)) returns 3, and cdr(cons(3, 4)) returns 4.

        Given this implementation of 'cons':

            def cons(a, b):
                def pair(f):
                    return f(a, b)
                return pair

        Implement 'car' and 'cdr'.


DC__4__.py
    
    (21.09.2018)

    This problem was asked by <Stripe>.

        Given an array of integers, find the first missing positive integer in linear time and constant space. 
        In other words, find the lowest positive integer that does not exist in the array. 
        The array can contain duplicates and negative numbers as well.

        For example, the input [3, 4, -1, 1] should give 2. The input [1, 2, 0] should give 3.

        You can modify the input array in-place.


DC__3__.py
    
    (20.09.2018)   [Not solved yet...]

    This problem was asked by <Google>.

        Given the root to a binary tree, implement serialize(root), which serializes the tree into a string,
        and deserialize(s), which deserializes the string back into the tree.

        For example, given the following Node class:

        class Node:
            def __init__(self, val, left=None, right=None):
                self.val = val
                self.left = left
                self.right = right

        The following test should pass:

        node = Node('root', Node('left', Node('left.left')), Node('right'))
        assert deserialize(serialize(node)).left.left.val == 'left.left'


DC__2__.py
    
    (19.09.2018)
    
    This problem was asked by <Uber>.

        Given an array of integers, return a new array such that each element at index i of the new array 
        is the product of all the numbers in the original array except the one at i.
        For example, if our input was [1, 2, 3, 4, 5], the expected output would be [120, 60, 40, 30, 24]. 
        If our input was [3, 2, 1], the expected output would be [2, 3, 6].
        
        Follow-up: what if you can't use division? (Done !)
        

DC__1__.py
    
    (18.09.2018)
    
    This problem was recently asked by <Google>.

        Given a list of numbers and a number k, return whether any two numbers from the list add up to k.
        For example, given [10, 15, 3, 7] and k of 17, return true since 10 + 7 is 17.
        Bonus: Can you do this in one pass? (Done !)


DC__0__.py

    (17.09.2018)

    This problem was asked by <Amazon>:
    
        There's a staircase with N steps, and you can climb 1 or 2 steps at a time. 
        Given N, write a function that returns the number of unique ways you can climb the staircase. 
        The order of the steps matters.

        For example, if N is 4, then there are 5 unique ways:
            1, 1, 1, 1
            2, 1, 1
            1, 2, 1
            1, 1, 2
            2, 2
            
        What if, instead of being able to climb 1 or 2 steps at a time, you could climb any number from a set of positive integers X ? 
        For example, if X = {1, 3, 5}, you could climb 1, 3, or 5 steps at a time. 
        Generalize your function to take in X.

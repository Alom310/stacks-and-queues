# stacks-and-queues

## Stacks

### Stacks: What are they?

A stack is an ordered list where all insertions or deletions happen at one end, called the "top." A stack is also a limited-access data structure since you can only access elements from the top, which means stacks adhere to the "Last-In, First-Out" rule.

![](https://memegene.net/sites/default/files/wallpaper/plates-clipart/188031/plates-clipart-stacked-plate-188031-9504896.jpg)

You can think of a stack like a you might a stack of ceramic plates. In order to access the third plate from the top, you need to safely remove the first two plates. These two plates limit access to the third, and since they were the most recent additions, they are the first that need to be removed.

### Stacks: But how does this pertain to what I'm learning?

The **call stack** is one example of a stack. We've encountered it many times while debugging our JavaScript code, and it looks like this:

![](https://cdn-images-1.medium.com/max/1600/1*LIuELJ2RTtwWExRWGdu_Hw.png)

The call stack records the function calls that are made in a program. Each function creates a frame that is "pushed" to the top of the stack. This frame "pops" off once it returns its value.

### Examples

### Questions Solved Using Stacks

## Queues

### Examples

- A line of customers at the grocery store
- A single-lane one-way road
- Call center phone systems
- Printers print jobs in order they're submitted
- Priority queue - values come out in order by priority, instead of FIFO. An element of highest priority always appears at the front of the queue. Operating systems use priority queues for load balancing on servers.

### Questions Solved Using Queues

Queues can be helpful in any situation where data doesn't need to be accessed immediately and can be held in a buffer (the queue) or when you need to preserve the order of data, like when selling tickets. Some example interview questions regarding queues are:

- How to implement a queue using stacks?
- Which data structure is used for breadth-first search (BFS), traversing a tree?

### Deques

Deque is a queue data structure that allows inserting items and deleting items at both ends. Four basic operations are performed on a deque:

- insertFront(): adds an item at the front of the deque
- insertLast(): adds an item at the rear of the deque
- deleteFront(): deletes an item from the front of the deque
- deleteLast(): deletes an item from the rear of the deque

#### Imnplementation

Deques can be implemented using a doubly linked list or a circular array. Time complexity in both is O(1).

## Additional Resources

- HackerRank video on [Data Structures: Stacks and Queues](https://www.youtube.com/watch?v=wjI1WNcIntg)

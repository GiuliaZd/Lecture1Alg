# Activities

## Task 1

Watch this video (~2min):
https://youtu.be/ohSzM7WtwOk

Discuss the difference between:

- Queue vs Stack
- LIFO vs FIFO

## Task 2

- Use the following link to push/pop data from the stack:
  https://www.cs.usfca.edu/~galles/visualization/StackArray.html
- Use the following tool to enqueue / dequeue data from the queue:
  https://www.cs.usfca.edu/~galles/visualization/QueueArray.html

## Task 3

- What is the difference between Array Implementation and the Linked List Implementation of Stacks. Refer to the following link:
  https://www.cs.usfca.edu/~galles/visualization/StackLL.html
  the answer: in both cases the elements are located one by one in the order of adding, but in the case of LL there we can see the pointer, by which 2 elements connected to each other.
  The main advantage of using a linked list over arrays is that it is possible to implement a stack that can shrink or grow as much as needed. Using an array will put a restriction on the maximum capacity of the array which can lead to stack overflow.
  On the other hand, it equires no extra memory to store the pointers in stack implementation using an array, it is also more efficient in terms of time, compared to stack implementation using linked-list.
- What is the difference between Array Implementation and the Linked List Implementation of Queues. Refer to the following link:
  https://www.cs.usfca.edu/~galles/visualization/QueueLL.html
  the answer: we can see the similarity to the previous case with Array/LL implementation but the difference is QUEUE, not stack, so the enqueue goes from tail and dequeue from the head.
  As the size of a linked list can grow or shrink at runtime, so there is no memory wastage. Only the required memory is allocated. In arrays, we have to first initialize it with a size which we may or may not fully use; hence wastage of memory may occur.
  The linked list versions have better worst-case behavior, but may have a worse overall runtime because of the number of allocations performed. The array versions are slower in the worst-case, but have better overall performance if the time per operation isn't too important.

## Links

- https://www.educative.io/blog/data-structures-stack-queue-java-tutorial

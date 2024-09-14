---
title: "Basics of Commonly Used Data Structures and Algorithms"
date: 2024-09-14 # Adjust the date to when you want the post to be published
categories: [Data Structures, Algorithms]
tags: [arrays, linked lists, stacks, queues, hash tables, trees, graphs, sorting, searching]
toc: true
---


# Basics of Commonly Used Data Structures and Algorithms

## 1. Arrays
- **Definition**: A collection of elements identified by index.
- **Key Operations**:
  - Access: `arr[index]`
  - Insert: `arr.append(value)`
  - Delete: `arr.pop()`

## 2. Linked Lists
- **Definition**: A sequence of nodes where each node points to the next.
- **Types**:
  - **Singly Linked List**: Each node points to the next node.
  - **Doubly Linked List**: Nodes have pointers to both next and previous nodes.
- **Key Operations**:
  - Insert: `new_node.next = current_node.next`
  - Delete: `current_node.next = current_node.next.next`

## 3. Stacks
- **Definition**: A collection of elements with Last In, First Out (LIFO) order.
- **Key Operations**:
  - Push: `stack.push(value)`
  - Pop: `stack.pop()`
  - Peek: `stack.peek()`

## 4. Queues
- **Definition**: A collection of elements with First In, First Out (FIFO) order.
- **Key Operations**:
  - Enqueue: `queue.enqueue(value)`
  - Dequeue: `queue.dequeue()`
  - Front: `queue.front()`

## 5. Hash Tables
- **Definition**: A data structure that maps keys to values using a hash function.
- **Key Operations**:
  - Insert: `hash_table[key] = value`
  - Lookup: `hash_table[key]`
  - Delete: `del hash_table[key]`

## 6. Trees
- **Definition**: A hierarchical data structure with nodes connected by edges.
- **Types**:
  - **Binary Tree**: Each node has at most two children.
  - **Binary Search Tree (BST)**: Nodes are arranged such that left children are smaller and right children are larger.
- **Key Operations**:
  - Insert: `node.left = new_node` or `node.right = new_node`
  - Search: Traverse the tree comparing values.

## 7. Graphs
- **Definition**: A set of nodes connected by edges.
- **Types**:
  - **Directed Graph**: Edges have direction.
  - **Undirected Graph**: Edges do not have direction.
- **Key Operations**:
  - Add Edge: `graph.add_edge(node1, node2)`
  - Remove Edge: `graph.remove_edge(node1, node2)`

## 8. Algorithms
- **Sorting Algorithms**:
  - **Bubble Sort**: Repeatedly swaps adjacent elements if they are in the wrong order.
  - **Quick Sort**: Divides the array into sub-arrays and sorts them.
- **Searching Algorithms**:
  - **Binary Search**: Efficiently searches in a sorted array by dividing the search interval in half.
  - **Linear Search**: Sequentially checks each element until the desired element is found.

## Conclusion
Understanding these basic data structures and algorithms is crucial for efficient programming and problem-solving. Experiment with these concepts and practice coding to reinforce your understanding.

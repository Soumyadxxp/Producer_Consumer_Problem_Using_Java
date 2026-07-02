# Producer Consumer Problem Using Java

This repository contains a Java implementation of the classic **Producer-Consumer Problem**, a fundamental synchronization problem in Operating Systems and Concurrent Programming.

## Problem Statement

The Producer-Consumer Problem involves:
- A **Producer** thread that generates data and places it into a shared buffer.
- A **Consumer** thread that removes and processes data from the shared buffer.

Proper synchronization is required to ensure that:
- The producer does not add data when the buffer is full.
- The consumer does not remove data when the buffer is empty.
- Data consistency is maintained between multiple threads.

## Repository Contents

- `ProducerConsumer.java` – Java implementation of the Producer-Consumer Problem.
- `README.md` – Repository documentation.

## Features

- Demonstrates thread synchronization.
- Uses a shared buffer for communication between threads.
- Suitable for Operating Systems and Java Concurrency laboratory exercises.
- Easy-to-understand implementation for learning purposes.

## Note

- The Java program provided in this repository is designed primarily for educational purposes, emphasizing clarity and comprehension over optimization.
- The implementation prioritizes readability and conceptual understanding rather than production-level performance.
- Users may modify and extend the program according to their academic or project requirements.

## Compilation and Execution

Compile and run the program using:

```bash
javac ProducerConsumer.java
java ProducerConsumer
```
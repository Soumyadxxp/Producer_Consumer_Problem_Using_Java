# Producer-Consumer Problem Using Java

This repository contains a Java implementation of the classic **Producer-Consumer Problem** using **Multithreading**, **Synchronization**, and the **wait()/notify()** mechanism. The program demonstrates inter-thread communication through a shared buffer.

## Algorithm

- Producer-Consumer Problem using Threads
- Synchronization using `synchronized`
- Inter-Thread Communication using `wait()` and `notify()`

## Repository Contents

- `ProducerConsumer.java` – Java implementation of the Producer-Consumer Problem.
- `README.md` – Repository documentation.

## Features

- Fixed-size shared buffer of size 5.
- Producer thread inserts items into the buffer.
- Consumer thread removes items from the buffer.
- Uses `wait()` when the buffer is full or empty.
- Uses `notify()` to wake up the waiting thread.
- Displays the buffer status after every production and consumption.
- Simple and easy-to-understand implementation for Operating Systems laboratory experiments.

## Concepts Covered

- Java Multithreading
- Producer-Consumer Problem
- Synchronization
- Shared Resources
- Critical Section
- Inter-Thread Communication
- `wait()` Method
- `notify()` Method
- Thread Lifecycle

## Note

- This Java program is designed primarily for educational purposes, emphasizing clarity and comprehension over optimization.
- The implementation demonstrates the use of synchronization to prevent race conditions while accessing a shared buffer.
- The program prioritizes readability and conceptual understanding rather than production-level optimization.
- It can be compiled and executed using any standard Java Development Kit (JDK).

## Compilation

Compile and run the program using the Java compiler.

```bash
javac ProducerConsumer.java
java ProducerConsumer
```
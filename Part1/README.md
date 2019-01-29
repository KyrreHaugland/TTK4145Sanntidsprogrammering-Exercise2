# Mutex and Channel basics

### What is an atomic operation?
> *An operation during which a processor can simultaneously read a location and write it in the same bus operation. This prevents any other processor or I/O device from writing or reading memory until the operation is complete.*

### What is a semaphore?
> *Semaphore is a variable is used to solve critical section problems and to achieve process synchronization in the multi processing environment*

### What is a mutex?
> *a mutual exclusion object (mutex) is a program object that allows multiple program threads to share the same resource, such as file access, but not simultaneously. *

### What is the difference between a mutex and a binary semaphore?
> *Mutex can be released only by thread that had acquired it, while you can signal semaphore from any other thread (or process), so semaphores are more suitable for some synchronization problems like producer-consumer.*

### What is a critical section?
> *A Critical Section is the part of a program that accesses shared resources. Only when a process is in its Critical Section can it be in a position to disrupt other processes.*

### What is the difference between race conditions and data races?
 > *A data race occurs when 2 instructions from different threads access the same memory location, at least one of these accesses is a write and there is no synchronization that is mandating any particular order among these accesses. A race condition is a semantic error.*

### List some advantages of using message passing over lock-based synchronization primitives.
> *it allows you to pass messages, i.e. data, between threads or processes*

### List some advantages of using lock-based synchronization primitives over message passing.
> *With locking and shared mutable state it's very hard to avoid concurrency bugs*

# Mutex and Channel basics

### What is an atomic operation?
> *Program operations that run completely independently of other processes.*

### What is a semaphore?
> *A variable that controls access to resources used by multiple processes in a concurrent system.*

### What is a mutex?
> *Property used to prevent race conditions. Keeps threads from entering their critical section at the same time*

### What is the difference between a mutex and a binary semaphore?
> *The difference is ownership. The mutex is have ownership and needs a mutex function to be locked/unlocked, while the binary semaphores does not.*

### What is a critical section?
> *The part of a program that access shared resources. It is at this stage that a process can disturb other processes.*

### What is the difference between race conditions and data races?
 > *Race conditions is error in the running of the program due to timing errors. This can come from data races, but doesn't have to. Data races are when two or more threads try to access the same resource at the same time.*

### List some advantages of using message passing over lock-based synchronization primitives.
> *Easier to protect resources. Avoid locking down resources and keeping them unsuable.*

### List some advantages of using lock-based synchronization primitives over message passing.
> *More work, and if done right can give better preformance.*

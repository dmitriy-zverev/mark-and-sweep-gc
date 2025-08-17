# Mark and Sweep Garbage Collector (GC)
Basic garbage collector for non-existing language SnekLang

## Purpose of this project
I wanted to learn how to build garbage collector from scratch. I used simpler version of the gc that uses counting each object that we create and then incrementing total number of usage of this object. When we don't need the object anymore we just decrement the counter and free the objects if the counter reaches 0. 

This version of garbage collector uses the Mark and Sweep algorithm where we store references to objects in frames and then tracing and marking them when they created and in use. When we no longer need the object we track it and free using implemented algorithm and its methods.

The code is no good for usage. It is an educational project.

## Certificate for completion
<img width="915" height="558" alt="bootdev_certificate" src="https://github.com/user-attachments/assets/61c5783e-7a30-4360-99b8-66625a5b7f44" />



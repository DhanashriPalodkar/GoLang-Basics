## Intro
* Concurrency in go in acheived using `go routines`
* For usage of `goroutines`, see goroutines.go 


### Concurrency vs Parallelism
* Concurrency is when tow or more tasks can start, run, and complete in overlapping time periods. It doesn't necessarily mean they'll ever both be running at the same instant. For example, multitasking on a single-core machine.
* Parallelism is when tasks literally run at the same time, e.g., on a multicore processor.

For better understanding, see passport analogy [here](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism) 
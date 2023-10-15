Async programming allows you to write concurrent code that runs in a single thread. The first advantage compared to multiple threads is that you decide where the scheduler will switch from one task to another, which means that sharing data between tasks it's safer and easier.

Concurrency vs Parallelism
Concurrency and parallelism can sound really similar but in programming there is an important difference. Immagine you are writing a book while cooking, even if it seems like you are doing both tasks at the same time, what you are doing is switching between the two tasks, while you wait for the water to boil you are writing your book, but while you are chopping some vegetables you pause your writing. This is called concurrency. The only way to do these two tasks in parallel is having two people, one writing and one cooking, which is what multicore CPU do.



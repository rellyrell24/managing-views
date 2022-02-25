1. What parameters is passed into the `HttpServer::new` function and what does the parameter return?
    - closure is passed into function
    - returns `App` struct to use with `bind` and `run`
2. How is a closure different from a function?
    - A closure can interact with variables outside of the scope of the closure
3. What is the difference between a process and thread?
    - process: program that is executed with its own memory stack, registers, and variables
    - thread: lightweight process that is manages independently by shares data from other threads and the main program
4. What is the difference between an `async` function and a normal one?
    - `async` function is a promise, and has to be executed with a blocking function
5. What is the difference between `await` and `join`?
    - `await`: blocks the program to wait for the future to be executed
    - `join`: run multiple threads or futures concurrently
        - `await` can be executed on a `join` function
6. What is the advantage of chaining factories?
    - flexibility on how modules are constructed, and they are orchestrated
    - inside: constructed, outside: orchestrated
7. What is the advantage of having a utility struct such as the `Path` struct?
    - reduces typos and makes it easier to maintain and change configurations
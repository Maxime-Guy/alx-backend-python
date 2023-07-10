# Asynchronous Python Projects

This repository contains asynchronous Python projects that demonstrate the use of asyncio and tasks.

## Project 0: Basic Async Syntax

The `0-basic_async_syntax.py` file contains an asynchronous coroutine called `wait_random`. It takes in an integer argument `max_delay` (with a default value of 10) and waits for a random delay between 0 and `max_delay` seconds. The coroutine returns the delay as a float value.

To run the project:

```shell
$ python3 0-main.py
```

## Project 1: Execute Multiple Coroutines Concurrently

The 1-concurrent_coroutines.py file demonstrates executing multiple coroutines concurrently. It imports the wait_random coroutine from the previous project and defines an async routine called wait_n. This routine takes in two integer arguments: n (the number of times to execute wait_random) and max_delay (the maximum delay for each execution). It spawns wait_random n times with the specified max_delay and returns the list of delays in ascending order.

To run the project:

```shell
$ python3 1-main.py
```
## Project 2: Measure Runtime
The 2-measure_runtime.py file introduces a function called measure_time. It measures the total execution time for wait_n(n, max_delay) and returns the average time per execution. The function takes in two integers: n (the number of executions) and max_delay (the maximum delay for each execution).

To run the project:

```shell
$ python3 2-main.py
```

## 
Certainly! Here's the consolidated version of the README.md file with all the projects in one markdown code:

markdown
Copy code
# Asynchronous Python Projects

This repository contains asynchronous Python projects that demonstrate the use of asyncio and tasks.

## Project 0: Basic Async Syntax

The `0-basic_async_syntax.py` file contains an asynchronous coroutine called `wait_random`. It takes in an integer argument `max_delay` (with a default value of 10) and waits for a random delay between 0 and `max_delay` seconds. The coroutine returns the delay as a float value.

To run the project:

```shell
$ python3 0-main.py
Project 1: Execute Multiple Coroutines Concurrently
The 1-concurrent_coroutines.py file demonstrates executing multiple coroutines concurrently. It imports the wait_random coroutine from the previous project and defines an async routine called wait_n. This routine takes in two integer arguments: n (the number of times to execute wait_random) and max_delay (the maximum delay for each execution). It spawns wait_random n times with the specified max_delay and returns the list of delays in ascending order.

To run the project:

shell
Copy code
$ python3 1-main.py
Project 2: Measure Runtime
The 2-measure_runtime.py file introduces a function called measure_time. It measures the total execution time for wait_n(n, max_delay) and returns the average time per execution. The function takes in two integers: n (the number of executions) and max_delay (the maximum delay for each execution).

To run the project:

shell
Copy code
$ python3 2-main.py
Project 3: Using Tasks
The 3-tasks.py file demonstrates the usage of asyncio tasks. It imports the wait_random coroutine from the first project and defines a regular function task_wait_random. This function takes an integer max_delay and returns an asyncio task.

To run the project:

```shell
$ python3 3-main.py
```

## Project 4: Using Tasks in a Complex Example
The 4-tasks.py file showcases a more complex example using tasks. It defines an asynchronous function task_wait_n which is similar to the wait_n function from the second project, but uses tasks for concurrent execution. It spawns wait_random tasks n times with the specified max_delay and returns the list of delays in ascending order.

To run the project:

```shell
$ python3 4-main.py
```

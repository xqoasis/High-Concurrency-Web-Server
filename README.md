# High-Concurrency-Web-Server

## Introduction
- A multi-threaded web server to parse GET and HEAD requests, handle static resources, support HTTP long connection, and support Request Pipeline using Ubuntu 18 OS.
- A distributive server by non-blocking IO and asynchronous IO, Epoll, Pthread Pool via reactor mode.
- Designed Finite State Machine to parse HTTP messages, support GET/POST requests, long/short connections.
- Built a Min Heap timer to close timeout requests to solve timeout-related resource consumption problem.
- Utilized RAII (smart pointer etc.) to solve Memory Leak and Double Buffering for Asynchronous Logging.

## Tech Stack
C++, Linux, TCP/IP, Multi-thread, ...


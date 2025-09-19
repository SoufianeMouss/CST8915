## LAB 1 CST8915

## Video
https://www.awesomescreenshot.com/video/44334064?key=53b2675ca5df02ce7f613d5f750e8a1d

## RabbitMQ
Acts as the message broker that routes work between producers and consumers via exchanges → queues.
It will help us to communicate between other services, and queue the orders.
In microservice architecture, we need to detach services, so they do not communicate directly with each other.

## Vue JS
In our store front microservice, we are using Vue js becuase it is a lightweight JavaScript framework and in this app it will helps us render data into HTML, react to user input, and keep the UI in sync with state—without manual DOM manipulation.

## Rust
In product service, we will rely on Rust as it is a memory-safe compiled programming language for building high-performance systems. It has the simplicity of high-level languages such as Go and Python, but the control of low-level languages like C, C++, it memory effiencient which means it doesn't have the garbage collector, it relies on a concept which is ownership and borrowin.
It will allow us to load the product list.

## Node JS
In Order service we will install Node JS with the help of npm which is node package manager.
It will help us to receive orders by communcating with RabbitMQ where the orders are pending
It has an event-driven architecture capable of asynchronous I/O. These design choices aim to optimize throughput and scalability in web applications with many input/output operations, as well as for real-time Web applications
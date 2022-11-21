# WebSocket in Flask
How would you achieve permanent, bi-directional communication between a client and server?

By permanent I mean that both client and server get to send and receive data in real time, without the constrainsts of the request/response cycle of HTTP.

This is made possible by the [Websocket](https://datatracker.ietf.org/doc/html/rfc6455) protocol. Unfortunately or fortunately, Flask being a minimalist web framework does not have built-in WebSocket support.

This repo explores the use of [Flask-Sock](https://github.com/miguelgrinberg/flask-sock), an extension in Flask 2, that provides WebSocket support.

## Getting Started
1. Install dependencies
```
$ pip install -r requirements
```

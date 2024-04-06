# 🤖 Gochat 🤖

A TCP chat application built using GoLang's net package. This application lets users connect to port 8888, assign themselves a username, and join chat rooms to send messages to other clients.

## How to Use
### 1. Clone the Repository
```
$ git clone https://github.com/jonathanguven/gochat/
```
### 2. Run the App
```
$ ./gochat
```
### 3. Connect the Client
#### MacOS
`$ nc ::1 8888`
#### Linux
`$ telnet localhost 8888`

## Commands 
- `/name [name]`: set your name to `[name]`, or stay anonymous
- `/join [name]`: join an existing room called `[name]`, otherwise create new room called `[name]`
- `/rooms`: show list of availible rooms
- `/msg [message]`: send a message to everyone in the room
- `/quit`: leave the chat server

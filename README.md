# ListServer
This repository is for the [List](https://github.com/HoldenErnest/List) application but it is also used as a ground to create my LupuServer as it will need setup before the project can be underway.

Read [notes](notes.md) for more information on startup of the System as a whole

## Setup
- Clone the repo
- Install Java JDK
- Find all files to compile `find -name "*.java" > compileIt.txt`
- Compile them `javac @compileIt.txt`

## Running
- `java ClassFileServer <port> <rootDir?>`
- connect :)

## Goals:
- get ssh working ✔
- get certbot working ✔
- get apache working? ✔
- generate a working ssl socket ✔
- generate a client in js that can connect to this ✔
- configure the server to accept specific requests from the client

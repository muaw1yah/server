# server

Course base project. A server written in C that follows w3.org protocols in accepting requests and sending back a response

## Features

* Accept and proccess HTTP request
* Serve static content to client (ie. HTML, CSS, Javascript, Images etc)
* Process PHP code

## Usage

1. Compile:
    1. from the root folder run 
    ```bash
    make server  
    ```
2. Run the server:
    ```bash
    ./server [-p port] /path/to/root
    ```
    -p, (optional) provide the port on which the server will run and receive requests on with the -p flag. ie to make the server listen on port 8080
    ```bash
    ./server -p 8080
    ```

    provide path of the servers root folder, default is current directory. ie
    ```bash
    ./server ~/sites/hello
    ```

## Authors

* Mu'awiyah Namadi
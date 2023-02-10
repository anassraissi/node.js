# node.js

# socket
socket is a chanel between server and computer contains information to handel server with computer


# port 
>A program running on computer can listen for request sent to a particular port number.

>is the add information to the http a perpus to make the cmputer listen to a port only

exp 
>172.24.86.76:3000 => 3000 is the port number


`Responce headers   `
---
> Client =>  request +request headers  => server
>server => response data + response headers => client
## response headers
>Content-type : `text/plain` 

>Status : `Ok : 200`

## buffers and Streams
> A buffer is a temporary memory that a stream takes to hold some data until it is consumed.

>Streams work on a concept called buffer.

![alt text](https://cdn.codeforgeek.com/wp-content/uploads/2021/07/streams_buffers_in_nodejs_diagram-1024x457.png.webp
)

# streams
## writable streams:
> Allow node js to write data to a stream
## Readable streams:
> Allow node js to read data from a stream
## Readable streams:
> can Read and Write to a stream

## readable.pipe() methode

>The readable.pipe() method in a Readable Stream is used to attach a Writable stream to the readable stream so that it consequently switches into flowing mode and then pushes all the data that it has to the attached Writable. 

Syntax:
```
readable.pipe( destination, options )
Parameters: This method accept two parameters as mentioned above and described below:
```

>destination: This parameter holds the destination of writing data.
options: This parameter holds the pipe options.
Return Value: It returns the stream.Writable destination, allowing for a chain of pipes if it is a Duplex or a Transform stream. Below examples illustrate the use of readable.pipe() method in Node.js: 



# express 
## features

- Robust routing
- Focus on high performance
- Super-high test coverage- Robust routing
- HTTP helpers (redirection, caching, etc)
- View system supporting 14+ template engines
- Content negotiation
- Executable for generating applications quickly


>The Express philosophy is to provide small, robust tooling for HTTP servers, making it a great solution for single page applications, websites, hybrids, or public HTTP APIs.

>Express does not force you to use any specific ORM or template engine. With support for over 14 template engines via Consolidate.js, you can quickly craft your perfect framework. 

# install/unistall npm express

 `npm install express`

 `npm uninstall express`

# package.json file
>this a file a purpus to keep trace to the all dependecy{package} in our project. 
when we install a new package it save in package.json file in dependecy object.

=> install the package.json file in project

`npm init`   
## install a package express in our project and save it in package.json dependecy object.

 `npm install express -save` 
 # nodemon 
## nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.

## install nodemon in project

```
npm install -g nodemon
```
## uninstall nodemon
```
 npm uninstall nodemon
```
```
and add this script below in file->setting->extention->setting.json

"terminal.integrated.profiles.windows": {
  "PowerShell": {
    "source": "PowerShell",
    "icon": "terminal-powershell",
    "args": ["-ExecutionPolicy", "Bypass"]
  }
},
"terminal.integrated.defaultProfile.windows": "PowerShell",
```


 

 











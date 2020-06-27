# README.md

This git comes from [github](https://github.com/afdolriski/golang-docker)

There is [an excellent article that goes with it](https://levelup.gitconnected.com/complete-guide-to-create-docker-container-for-your-golang-application-80f3fb59a15e)

To illustrate what this container does use curl:
```
    curl http://localhost:3000/ping
```
You'll get
```
    {“message”:”pong”}
```

To test the use of the 'database' aspect of the application use curl again:
```
    curl http://localhost:3000/animal/cat
```
You'll get
```
    {"name":"cat","sound":"meow"}
```

And if you try 
```
    curl http://localhost:3000/animal/bird
```
You'll get
```
    No animal found.
```
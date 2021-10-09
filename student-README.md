# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?
=> because server dosen't care about client buffer.
2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?
=> the message divides
3. What happens if you run the client when the server is not running? 
=>  a connection error will occur
4. What happens if you run the server while the server is already running?
=> an os error will occur
5. What changes did you make to finish this assignment?
=> changed server.py 
6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.
=> [Python Network Programming Cookbook](https://subscription.packtpub.com/book/networking_and_servers/9781849513463/1/ch01lvl1sec21/writing-a-simple-echo-client-server-application)s
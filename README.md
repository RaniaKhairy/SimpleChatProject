# SimpleChatProject

This is Simple Chat Phase 1. 
To run the SimpleChat, you must first install ocsf, and make sure ocsf is in your classpath (or is a subdirectory of simplechat1).
Then you must compile the .java files, including those in the subdirectories.

To run the SimpleChat you must first start a server: "java EchoServer". 
Then you start one or more clients: "java ClientConsole". To run a client on a different machine, you enter 
"java ClientConsole serveraddress", where serveraddress is the IP address or host name of the machine where the server is runing. 
Once a client is running, you can type some text; the text will be echoed to any other clients that are running.

To learn how this code works, consult the book "Object-Oriented Software Engineering: Practical Software Development using UML and
Java" by Lethbridge and Laganière. The book contains many exercises where you will add features to SimpleChat.

If the server won't start, it might be because the default 'port' number of 5555 is already in use. Follow the exercises in the book to improve the code and solve this problem.

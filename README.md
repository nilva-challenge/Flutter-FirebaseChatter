# In name of Allah

Flutter chat application with firebase for backend. 

## Introduction

We want a simple chat app which uses firebase messaging for connection between two devices. First one should register himself & provide a username to be able to use chat. Then he can connect to another device with providing a username he wants to connect with. For chat messages, only text messages suffice. We do **not** want you to implement reply or forwarding messages as well. 
**Note** that you to store history of chat messages in database and should be available with restarting app. Also no messages should be lost due to network connection (you have to queue messages).

#### complementary notes

UI should be desirable, but we don't want a prefect design either. As for state management, you have to use BLoC pattern. As for database use Hive.

## Test scenario

1. open application
2. provide username & register
3. provide peer username & connect
4. go to chat page (here you can see previous & incomming chat messages & also you are able to send messages)
5. send a sample message to your peer
6. send a sample message from you peer 
7. close app
8. open app again (you should see your ongoing chat page)
9. end chat
10. provide peer username & connect
11. go to chat page
12. disconnect network
13. send message to peer (should be queued)
14. connect network (message should automatically be sent to peer)
15. close app


## Expectations

So What does matter to us?
- a clean structure of codebase
- clean code practices
- state management practices & patterns
- well use of database & remote data source together
- finally & most important, ability to learn 

## Tasks

1. Fork this repository
2. Estimate the develop & send it to us
3. Break and specify your tasks in project management tool (provide us your self specified tasks in Readme.md)
4. Learn & Develop 
5. Push your code to your repository
6. Send us a pull request, we will review and get back to you
7. Enjoy

**Finally** don't be afraid to ask something from us, you can create issue on this repo for further questions.

***Best wishes for you***

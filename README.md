# Talk-a-Tive-
It is a clone of the popular chat app Discord. Users are able to create and join room, send and accept/reject friend requests, create rooms with audio call possibility and message each other through text channels or through direct messaging.

##  Technologies Used
Server Side:
-  MongoDB: Our Main Database
- Express: Our NodeJS framework
- NodeJS: Used to create the server
- Socket.io: Used for real-time communication
 
Client Side:
 - ReactJS: Our Js Library to create UI components.
 - Socket.io: Used for real-time communication (client side)
 - Web RTC: Used for videochat and audio call possibilities.
 
 ##  Features: 🚀

- Local Authentication
- Loads User Data upon login (Rooms, Channels, Private Messages)
- Creation and Joining Rooms
- Room Settings (Changes between Camera, Mic, ScreenShare and deletion of room)
- Persistent channel history
- Private messaging
- Timestamps for messages
- Show current active users in given Room
- Voice Chat (Buggy, but main features work)



#### Friend Requests 
- Users can accept or reject friend requests
- Friend requests are sent in real time
- Users can cancel outgoing friend requests
- Users can see who is online/offline 
- Users can accept or cancel incoming friend requests
- Users can remove friends from their friends list (TBC)




#### Servers
- Users can create a new Room (the user is then the admin of that Room)
- Rooms are created with audio call possibility
- Users can join an existing Room
- Users can close & delete the room if they are admin.
- Users can see all the other members in the room. 

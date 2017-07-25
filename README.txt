WHAT IS MRPT:

MRPT (or Madcomm RP Tools) is my current project. It is a c++ based client-server software which does the following:
 > Socket based client / server.
 > Socket based chatroom, server managed.
 > Client Socket management (users will show up in the "users" for both clients and server)
 > Stat management and storage system.
 > Seeded random dice roller (both for dice rolls and the stat roller)
 > Relatively simplistic homebrew stat system.
 > Randomized quick action messages
 > Class based object creation (the stats of each users are stored in an object once stats are confirmed)

MRPT current version: Alpha 0
What can be done with the application at the moment:
    > Up to 25 users can be connected at once.
    > If a server is running, users can connect via using the client. When this is done, they can all communicate.
    > Stat system automatically verified for balance.
    > Quick actions can be clicked for, well, click actions.
    > Rolls can be made in chatroom or offline.
    > All rolls are randomised using a time based seed.
    > Connect and disconnect safely.

Planned features:
    >> Sending and receiving the stats of each users. (the code is already done for this, essentially the sending and decoding of a string of numbers on detected request during reading. Looking for a user interface friendly way to implement this. Maybe right click on user to get options, which will include sending the request for stats?)
    >> Ability to save a session's chatting externally, and re-open it.
    >> Cleaner, more original interface.
    >> Ability to use different stat systems. (current is homebrew. Looking into legal

HOW TO USE MRPT:
> Start the Madcomm Rp Tools server program, then press on the start server button.
> Provide users with IP of server host.
> Clients enter IP, port and their prefered username, then connect.
> Users can use software.


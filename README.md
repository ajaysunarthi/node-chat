# node-chat
Basic chat client using express and socket.io

Each user is marked as a socket. If any socket emits any msg i.e. submits some value in form it is then gets catched by the server, which 
then emits the received msg to every other socket. 

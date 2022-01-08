# grpc

For Server :-

go run server/server.go


For Client:-

go run client/client.go -sender {your_name} -channel {channel_name_you_want}


Connect multiple clients in one channel using same channel name.

*Closing server will disconnect clients too.*

For sending message only to server from client, send in format "Server: {your_Message}",this message will only be recieved by server.

// merge conflict comment
// Testing Commit
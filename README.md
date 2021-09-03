# grpc

For Server :-

go run server/server.go


For Client:-

go run client/client.go -sender {your_name} -channel {channel_name_you_want}


Connect multiple clients in one channel using same channel name.

*Closing server will disconnect clients too.*

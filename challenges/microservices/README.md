# Microservices Coding Challenge

### Service to Service messaging via gRPC
Create a gRPC client and server that uses a bidirectional channel allowing push and consumption of messages from either side. The gRPC server should not be able to connect directly to the client, yet it should be able to push messages down once the client connects. You can be creative about the types of messages sent and the reason(s) for the server and client to communicate.

Make sure to consider:
- Network blips/issues —i.e., what happens if there are issues sending messages due to network issues?
- Code style/organization
- Performance and scalability
- Tests are important and if time allows it, we'd like to see some test coverage.


### Technology
Please write the coding challenge in the programming language [Go](https://go.dev/).

Bonus points for:
- Containerization in Docker (or any container technology)
- Use of Helm/Kubernetes

### Helpful links
- [gRPC](https://grpc.io/)
- [A Tour of Go](https://go.dev/tour/welcome/1)

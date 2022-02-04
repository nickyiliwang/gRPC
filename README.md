# google Remote Procedure Call (gRPC)

## What
- Part of the Cloud Native Computation Foundation (CNCF) - like Docker and Kubernetes
- Allows you to define REQUEST and RESPONSE for RPC and handles the rest
  - RCP is like calling a function directly on the SERVER
- Modern fast and efficient, built on top of HTTP/2, low latency, supports streaming, language independent
- Easy implementation of auth, LB, logging, and monitoring

## How
- Define the messages and services using Protocol Buffers
  - Protocol Buffers are language agnostic (independent of any specific programming language)
  - Data is binary and serialized
  - easy API change with rules
  - Efficient data transfers
- gRPC generates template code
- One .proto file works for over 12 languages (server and client)


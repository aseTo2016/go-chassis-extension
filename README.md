# go-chassis-extension

include plugins of go chassis. to enhance your application functionality or replace the default module of go chassis

Plugins includes:
- protocol: protocol plugin for service communication
- registry: service discovery plugin

# Supported go chassis version
| go chassis version | go-chassis-extension|
| ---------- | ------------ |
| v2.1.0 | v2.1.0 | 
| v2.1.1 | v2.1.1 | 
| v1.8.3 | v1.8.3 |

# Extensions
| Name     |description    |
|----------|:-------------:|
|registry/kubernetes |use kubernetes for service discovery |
|tracing/zipkin |an opentracing implementation |
|protocol/grpc | grpc communication between services |
|protocol/gin | support native gin programing model|

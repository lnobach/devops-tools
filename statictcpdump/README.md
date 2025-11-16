

Creates a statically-linked tcpdump binary Useful e.g. in Kubernetes.

```
docker build -t tcpdump builder .
docker run -v $(pwd)/out:/out tcpdump-builder
```

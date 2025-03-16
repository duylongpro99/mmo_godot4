```markdown
[Godot 4](https://godotengine.org/)
```

```markdown
[Protobuf](https://github.com/protocolbuffers/protobuf)
```

Protoc gen Go:
```bash
    go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
```
Set GOPATH for .zshrc
```bash
    export GOPATH=$HOME/go
    export GOBIN=$GOPATH/bin
    export PATH=$PATH:$GOBIN
```

Gen go code from .proto file
```bash
protoc -I="shared" --go_out="server" "shared/packets.proto"
```

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

## Add project to Godot4
Open godot4.exe
Create -> Select Current Project -> Naming Client

## Add client folder from https://github.com/oniksan/godobuf to project

Go to https://github.com/oniksan/godobuf
Download release .tar.gz
Unpack and Copy addons folder to client folder of project 

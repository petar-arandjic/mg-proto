# mg-proto
Protobuf definition for mg profiles. This definition also contains generated golang code

### Generate
to generate new version from files
```bash
protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative profile/profile.proto
```
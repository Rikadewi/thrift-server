# Apache Thrift Server

## Installation

### Compile IDL File
```
thrift -r --gen go mythrift.thrift
```

Moved generated file to shared directory.
```
mv gen-go/mythrift/ .. 
```

### Install Dependencies
```
go mod download
```

## Run 
```
go run main.go
```
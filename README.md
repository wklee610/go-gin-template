# What is Gin?
Gin is a HTTP web framework written in Go (Golang).  
Visit [Github](https://github.com/gin-gonic/gin) for more information.

# Go Version 
* 1.23.1  

# Before start  
* Download Gin Framework
```bash
go get -u github.com/gin-gonic/gin
```
* Download Viper  
```bash
go get -u github.com/spf13/viper
```

* Download Gorm
```bash
go get -u gorm.io/gorm
go get -u gorm.io/driver/mysql      # for MySQL
```

# Folder Structure
```bash
.
├── README.md                       
├── apis                            # API (Service Logics)
│   └── api.go
├── cmd                             # Main (Application Start)
│   └── main.go
├── configs                         # Config
│   └── config.env
├── db                              # Database Connection
│   └── mysql.go
├── go.mod
├── go.sum
├── models                          # Data Model
│   └── model.go
├── routers                         # Router Setting
│   └── router.go
└── utils                           # Common Util Function
    └── util.go
```

# How to Start
```bash
# Test 1
go run cmd/main.go

# Test 2
go build cmd/main.go
./main
```

# Reference
1. [Go Official Website](https://go.dev/doc/modules/layout)
2. [Golang-Standards](https://github.com/golang-standards/project-layout)
3. ChatGPT (Go Folder Structure)

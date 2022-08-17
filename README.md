# distributed
A simple distribute system for Go.

## architecture
```
- biz/
    - grades/
        - grades.go 
        - mockdata.go
        - server.go 
    - portal/
        - handlers.go
        - student.html
        - students.html
        - templates.go
- cmd/
    - gradingservice/
        - main.go
    - logservice/
        - distributed.log
        - main.go
    - portal/
        - main.go 
    - registryservice/
        - main.go 
- log/
    - client.go
    - server.go 
- registry/
    - client.go
    - registration.go
    - server.go
- service/ 
    - service.go
- runtime/
```

## TODO

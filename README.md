# distributed
A simple distribute system for Go.

architecture
```
- biz/ 业务逻辑
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
    - gradingservice/ 分级服务
        - main.go
    - logservice/ 日志服务
        - distributed.log
        - main.go
    - portal/ 
        - main.go 
    - registryservice/ 注册服务
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

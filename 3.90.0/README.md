### 部署说明

采用 `solo server model` 部署方式，元数据默认存放在内置的 `H2` 数据库中，需要手动下载 `derby` 

``` bash
wget https://mvnrepository.com/artifact/org.apache.derby/derby/10.14.2.0
```

将其放在 `azkaban-solo-server-0.1.0-SNAPSHOT/lib` 目录下。
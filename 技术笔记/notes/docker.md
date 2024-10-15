>  [返回列表](../index.md)

---

### 目录：
+ [docker命令](#docker命令)
+ [nginx命令](#nginx命令)
+ [Dockerfile语法](#Dockerfile语法)

---

#### docker命令
| 命令 | 用途 |
| ----- | -----|
| docker pull | 获取image |
| docker build | 创建image | 
| docker images | 列出image |
| docker run | 运行 container |
| docker ps | 列出container |
| docker rm | 删除container |
| docker rmi | 删除image |
| docker cp | 在host和container之间拷贝文件 |
| docker commit | 保存改动为新的image |

#### nginx命令
| 命令 | 用途 |
| ----- | -----|
| sudo nginx -s reload | 修改配置后重新加载生效 |
| sudo nginx -s reopen | 重新打开日志文件 |
| sudo nginx -s stop | 快速停止nginx |
| sudo nginx -s quit | 完整有序的停止nginx/优雅关闭（先服务完已打开的连接） |

#### Dockerfile语法
| 命令 | 用途 |
| ----- | -----|
| FROM | base image |
| RUM | 执行命令 |
| ADD | 添加文件 |
| COPY | 拷贝文件 |
| CMD | 执行命令 |
| EXPOSE | 暴露端口 |


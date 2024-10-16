>  [notes](../index.md)->docker

---

### 目录：
+ [docker命令](#docker命令)
+ [Dockerfile语法](#Dockerfile语法)
+ [docker-compose.yml命令](#docker_compose_yml)
+ [docker-compose命令](#docker_compose)

---

#### docker命令
| 命令 | 用途 |
| :--- | :--- |
| docker pull | 获取image |
| docker build | 创建image | 
| docker images | 列出image |
| docker run | 运行 container |
| docker ps | 列出container |
| docker rm | 删除container |
| docker rmi | 删除image |
| docker cp | 在host和container之间拷贝文件 |
| docker commit | 保存改动为新的image |

#### Dockerfile语法
| 命令 | 用途 |
| :--- | :--- |
| FROM | base image |
| RUM | 执行命令 |
| ADD | 添加文件 |
| COPY | 拷贝文件 |
| CMD | 执行命令 |
| EXPOSE | 暴露端口 |
| WORKDIR | 指定路径 |
| MAINTAINER | 维护者 |
| ENV | 设定环境变量 |
| ENTRYPOINR | 容器入口 |
| USER | 指定用户 |
| VOLUME | mount point |

#### <span id='docker_compose_yml'>docker-compose.yml常用命令</span>
| 命令 | 用途 |
| :--- | :--- |
| build | 本地创建镜像 |
| command | 覆盖缺省命令 |
| depends_on | 连接容器 |
| ports | 暴露端口 |
| volumes | 卷 |
| image | pull镜像 |

#### <span id='docker_compose'>docker-compose命令</span>
| 命令 | 用途 |
| :--- | :--- |
| up | 启动服务 |
| stop | 停止服务 |
| rm | 删除服务中的各个容器 |
| logs | 观察各个容器的日志 |
| ps | 列出服务相关的容器 |

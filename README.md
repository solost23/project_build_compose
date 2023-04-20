# project_build_compose
项目部署docker-compose

数据库(eg: MySQL, Redis, Es, Consul) 不参与容器化，即有数据状态的不参与容器化，容器化只针对无状态应用进行。

镜像仓库采用Docker Hub
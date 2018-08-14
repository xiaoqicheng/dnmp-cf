# 使用docker 部署LNMP+redis 服务器
# 安装docker 在centos 7 Redhat 7 等7.0系统以上直接使用yum安装docker
  ```
  # yum install docker
  ```
# 安装docker-compose
# https://github.com/docker/compose/releases 仓库中寻找docker-composer 的二进制文件
```angular2html
# curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
# chmod +x /usr/local/bin/docker-compose
```
#执行docker-compose up -d 之前 请检查是否写入SELinux规则或是否关闭SELinux ，否则容器将不能正常启动

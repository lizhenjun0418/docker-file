# 关于

基于centos8镜像 , nginx-1.18.0, naxis-1.1编写的dockerfile 的文件

 nginx-1.18.0, naxis-1.1 需要和dockerfile 在同一目录下

# 编译命令

docker build -f dockerfile -t nginx:1.0 .  

 编译成功后,启动即可

docker run -itd -p 8085:80 nginx:1.0




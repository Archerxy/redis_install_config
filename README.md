## 下载解压  
  wget http://download.redis.io/releases/redis-5.0.4.tar.gz   
## 安装
  make PREFIX=/installdir  --安装到指定目录    
  编译后的文件出现在src目录下 包括有 redis-server  redis-cli 等   
  运行 ./redis-server 即可开启redis服务
## make出错
  一般是要安装gcc编译库  yum -y install gcc-c++
### redis-server后台运行
  打开 redis.conf文件 vim redis.conf   
  设置 daemonize yes   
  

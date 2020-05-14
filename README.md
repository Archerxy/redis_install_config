## 下载解压  
  wget http://download.redis.io/releases/redis-5.0.4.tar.gz   
## 安装
  make PREFIX=/installdir  --安装到指定目录    
  makeinstall
## make出错
  一般是要安装gcc编译库  yum -y install gcc-c++
### redis-server后台运行
  打开 redis.conf文件 vim redis.conf   
  设置 daemonize yes   
  

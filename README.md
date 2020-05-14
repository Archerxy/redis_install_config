## 下载解压  
  wget http://download.redis.io/releases/redis-6.0.1.tar.gz   
## 安装
  make PREFIX=/installdir  --安装到指定目录    
  makeinstall
## make出错
  一般是要安装gcc编译库  yum -y install gcc-c++

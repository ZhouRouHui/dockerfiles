### 构建镜像
1. `docker build hyperf8.0 .` 会在本地生成一个 hyperf8.0 的镜像
2. `docker images` 检查生成的镜像是否存在

### 创建容器
1. `docker run --name hyperf8.0 -v /d/dnmp/www:/www -p 9501:9501 -it hyperf8.0`
	* /d/dnmp/www 宿主机目录，/www 容器挂载目录
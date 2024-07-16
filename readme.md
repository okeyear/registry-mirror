### 简介

这是为了方便大家做各个镜像仓库代理的

### 使用教程
```shell
git clone https://github.dev/okeyear/registry-mirror.git
cd registry-mirror
bash deploy.sh
```


### 注意

大家可以看下(registry-mirror/docker)目录下的配置文件

默认168h小时之后会清理缓存，也就是你拉取的镜像缓存

腾讯云的虚拟机 https://mirror.ccs.tencentyun.com
azure中国的虚拟机 https://dockerhub.azk8s.cn
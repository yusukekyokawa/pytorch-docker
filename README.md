# pytorch-docker
## About

A100, RTX3090のために作った．
## 想定環境
`docker --version`
```
Docker version 20.10.3, build 48d30b5
```
`docker-compose --version`
```
docker-compose version 1.28.4, build cabd5cfb
```
`sudo nvidia-docker version`
```bash
NVIDIA Docker: 2.5.0
Client: Docker Engine - Community
 Version:           20.10.3
 API version:       1.41
 Go version:        go1.13.15
 Git commit:        48d30b5
 Built:             Fri Jan 29 14:33:13 2021
 OS/Arch:           linux/amd64
 Context:           default
 Experimental:      true
Server: Docker Engine - Community
 Engine:
  Version:          20.10.3
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.13.15
  Git commit:       46229ca
  Built:            Fri Jan 29 14:31:25 2021
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.4.3
  GitCommit:        269548fa27e0089a8b8278fc4fc781d7f65a939b
 runc:
  Version:          1.0.0-rc92
  GitCommit:        ff819c7e9184c13b7c2607fe6c30ae19403a7aff
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0
```


## Update
2021/03/06

https://hub.docker.com/layers/pytorch/pytorch/1.8.0-cuda11.1-cudnn8-devel/images/sha256-f915e85ca58c8d6c072de080288dd66965ca623744a8392cf5ea0c2df485b23c?context=explore

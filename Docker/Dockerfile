# https://hub.docker.com/layers/pytorch/pytorch/1.8.0-cuda11.1-cudnn8-devel/images/sha256-f915e85ca58c8d6c072de080288dd66965ca623744a8392cf5ea0c2df485b23c?context=explore
# 
FROM pytorch/pytorch:1.8.0-cuda11.1-cudnn8-devel

# Install vim
RUN apt-get update && apt-get install -y vim


WORKDIR /workspace
ADD requirements.txt /workspace

# install python modules
RUN pip intall -r requirements.txt


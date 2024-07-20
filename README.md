# 简介

使用方式：

ALIYUNUSER：私库用户
ALIYUNPASS：私库密码
ALIYUNREGISTRY：私库地址
ALIYUNNAMESPACE：私库项目名

- eg
docker push $ALIYUNREGISTRY/$ALIYUNNAMESPACE/<imagename>:<imagetag>


将需要同步的镜像放置在image.txt文件中，即可出发自动同步。
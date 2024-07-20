# 使用方式
1. fork我的项目

2. 配置变量：
- ALIYUNUSER：私库用户
- ALIYUNPASS：私库密码
- ALIYUNREGISTRY：私库地址
- ALIYUNNAMESPACE：私库项目名

- eg
```bash
docker push $ALIYUNREGISTRY/$ALIYUNNAMESPACE/<imagename>:<imagetag>
```

3. 将需要同步的镜像放置在image.txt文件中，即可出发自动同步。
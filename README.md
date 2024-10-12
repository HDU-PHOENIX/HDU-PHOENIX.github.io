# PHOENIX Blog

## 前提
+ 实验室的内网

## 准备
```shell
ssh phoenix@10.2.20.113
cd HDU-PHOENIX,github.io
```

## 编写
```shell
hexo new '文章名‘
```
### 推送
```shell
hexo clean
hexo g
hexo d
```

**如果你要传送图片**
你需要 cd ``` img-host``` 把你的图片放在image文件夹，然后
```shell
git add .
git commit -m 'update'
git push
```
## 查看设备状态，为设备添加新的服务
```shell
http://10.2.20.113:8086/a5c7c1cb59
```

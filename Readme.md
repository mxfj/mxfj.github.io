# 快速部署使用
```
npm install hexo -g #安装Hexo
npm update hexo -g #升级
```
# 部署测试
```
hexo server -s -p 8080 -i 127.0.0.1
```
# hexo 三剑客
```
hexo clean   
# 清除缓存，若是网页正常情况下可以忽略这条命令
hexo g
# 生成站点 hexo generate 
hexo d
# hexo deploy 就是部署网站
```

# 更换主题

如果你不喜欢Hexo默认的主题，可以更换不同的主题，主题传送门：Themes 我自己使用的是Next主题，可以在blog目录中的themes文件夹中查看你自己主题是什么。现在把默认主题更改成Next主题，在blog目录中（就是命令行的位置处于blog目录）打开命令行输入：

git clone https://github.com/iissnan/hexo-theme-next themes/next

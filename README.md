# 1024china.github.io



- npm安装(node安装等省略)


```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```


- 继续执行

```
hexo init

npm install -g hexo-cli
```
- 安装主题

```
git clone https://github.com/iissnan/hexo-theme-next themes/next
```
- 配置

修改hexo根目录下的 _config.yml ： 
```
theme: next
```
 , 注意yelee前面留一个空格

```


deploy:
  type:   git
  repo:   https://github.com/it80/it80.github.io.git
  branch:  master
```



## 初始化hexo项目 

hexo官网：https://hexo.io/zh-cn/docs/ 

hexo主题：https://hexo.io/themes/

```bash
//安装hexo-cli
npm install hexo-cli -g

//查看hexo版本
hexo -v

//初始化hexo项目
hexo init <folder>

//进入项目文件夹
cd <folder>

//安装依赖
npm install

//新建页面
hexo new <title>

//效果预览
hexo server

```

## 更换主题

```bash

//安装相应主题
npm install --save <theme>

```
修改博客目录中的`_config.yml`
```yaml
theme: fluid  # 指定主题
language: zh-CN  # 指定语言，会影响主题显示的语言，按需修改
```


## 一键部署 
安装一键部署工具
```bash
npm install hexo-deployer-git --save
```
修改博客目录中的`_config.yml`
```yaml
deploy:
  type: git
  repo: <repository url> #https://bitbucket.org/JohnSmith/johnsmith.bitbucket.io
  branch: [branch]
  message: [message]
```





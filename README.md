# 项目说明

	关耳听风的心路之旅

1. 熟悉hexo，修改出自己风格的hexo博客

2. 使用叶落阁的hexo-3主题写自己的私人日记，但都可以看，不鄙视就行

3. 核心：写写自己的想法，认知自己，认知世界

## 关于项目使用

1. 直接clone下来

2. npm安装依赖

3. 看package.json文件，npm run serve运行

## 关于项目部署

1. npm run deploy命令就能打包，首先是打包到根目录的.deploy_git文件中，可直接放置到服务器运行，本质是html文件

2. 如果需要部署到github中，需要配置_config.yml文件的最后的deploy相关内容，主要是repo：github的项目地址和branch推送到哪个项目分支，所以这里开发在dev分支，推送到master分支

> 注意：如果要部署到github的 git page 直接运行，那么这个项目的项目名必须是 xxx.github.io（github名.github.io），所以每个github账号只有一个可用部署

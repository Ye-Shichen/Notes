# Vue-CLI 3.0

### 与2.0大不同
- @vue-cli =>@vue/cli

### @vue/cli-service-global
- vue serve 可为单个文件启动服务器
- vue build 可为单个文件打包

### vue create
- Git Bash命令行方向键交互无法使用
- vue ui
- 若仍需要使用2.0，需要按照桥接工具

> npm install -g @vue/cli-init
>
> `vue init` 的运行效果将会跟 `vue-cli@2.x` 相同
>
> vue init webpack my-project

### vue/cli-service
- vue-cli-service serve
- vue-cli-service build
- vue-cli-service inspect 审查项目的webpack config


### 问题
1. @vue   @foo   scope是啥
2. 项目移植时，vue create使用preset和npm使用package.json 用哪个？ √

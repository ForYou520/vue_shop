1.vue-cli 脚手架初始化项目
node + webpack + 淘宝镜像

2.1 项目运行起来的时候，让浏览器自动打开
---package.json
"scripts":{
"serve":"vue-cli-service --open"
}

2.2 eslint 校验功能关闭
在 vue.config.js 中添加：lintOnSave: false,

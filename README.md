# fis3 release 退出进程插件

FIS 部署七牛云存储插件，提供静态资源部署能力，CDN加速。

## 安装

```
npm install fis3-deploy-exit --save-dev
```

## 使用方法

也可以使用统一的 deploy 插件配置方法

```js
fis.match('*.js', {
    deploy: fis.plugin('exit' ,null ,'append')
})
```

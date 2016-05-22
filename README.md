# max-deploy-local-deliver

## 说明

FIS 默认的部署插件，提供本地部署

## 使用方法

也可以使用统一的 deploy 插件配置方法

```js
fis.match('*.js', {
    deploy: fis.plugin('local-deliver', {
        to: './output',
        relative: 'src' // 相对文件夹名字，比如你的源码都统一放在src文件夹下，但release的路径不想包含src文件夹
    })
})
```

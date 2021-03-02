在dom里使用别名要加上~ ------- src="~assets/img/tabbar/home.svg" 

vue.config.js文件为别名配置

```javascript
module.exports = {
    configureWebpack: {
        resolve: [],
        alias: {
            'assets' : '@/assents',
            'common' : '@/common',
            'components' : '@/components',
            'network' : '@/network',
            'views' : '@/views',
        }
    }
}
```


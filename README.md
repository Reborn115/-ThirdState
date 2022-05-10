# vue_pro

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

这个项目我优化了以下几点：
1.登录失败时阻止弹出信息提示；
2.数据提交前，对一些数据进行了验证；
3.请求都改成了axios；
4.给登录后的界面加入了路由守卫，没token无法跳转；
5.增加了退出登录的功能；
6.几乎把能改成elementui的地方都进行了一定的修改，把原始代码改成了elementui式代码
7.移除了大部分打印信息；
PS.我为了用elementui的表单验证而把报名界面的原来的三个组件合在了一个页面里，但忘删原来组件了，然后我想重新上传项目时报了未知的bug，导致我没能删掉没用的三个组件。我尝试了美化界面，但是出现了一些不太好的bug，就没有应用美化，所以到最后我的界面还是很丑

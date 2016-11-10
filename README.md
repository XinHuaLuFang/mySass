# mySass
把sass/style.scss转译出来的style.css放入了css目录之下：
```
sass sass\style.scss css\style.css
```

sass/style.scss自动转译到sass/style.css下：
```
sass --watch sass\style.scss
```

sass中所有的.scss文件都可以转译成.css文件，并且都放在了css目录中：
```
sass -watch sass\:css\
```

# 参考资料

### 基础
* [SASS用法指南](http://www.ruanyifeng.com/blog/2012/06/sass.html)
* [理解Sass的选择占位符%placeholder](http://www.w3cplus.com/preprocessor/understanding-placeholder-selectors.html)
* [Sass:Mixin还是Placeholder](http://www.w3cplus.com/preprocessor/sass-mixin-placeholder.html)
* [Sass初级：定义好的变量名](http://www.w3cplus.com/preprocessor/beginner/variable-naming.html)

### 进阶
* [Sass进阶](http://www.w3cplus.com/preprocessor/sass-advanced.html)
* [管理Sass项目文件结构](http://www.w3cplus.com/preprocessor/architecture-sass-project.html)
* [Sass编写组件](http://www.w3cplus.com/preprocessor/sass-component-10-minutes.html)

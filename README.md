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
#ntrf-build使用
##简介
基于gulp的前端构建工具
+ less编译, css压缩, 添加样式prefix, sourcemap 
+ js压缩
+ swig编译
+ 自动刷新

>环境配备:  
>nodejs 4.0.0+ `node官网下载`  
>gulp全局 `npm install -g gulp`  

##使用
1. clone或下载代码，在当前目录下执行`npm install`安装依赖模块。  

2. 可将完整内容拷贝至项目目录直接`gulp`使用，或则`gulp --path PATH`(PATH为自定义路径)。

3. `gulp --debug`将输出未压缩代码。

4. `gulp --ip IP`可以绑定特定的地址，如`gulp --ip localhost:3000`以自动刷新node项目。 

项目代码文件夹参考:  
    
    codeRoot
        |- css.src      #css源码
            |- main.less
        |- css
        |- js.src       #js源码
            |- main.js
        |- js
        |- tpl
            |- index.html #swig模板
        |- index.html


>参考资料:  
>build-script(icaife): [https://github.com/icaife/build-script](https://github.com/icaife/build-script)  
>build-script(gucong): [https://github.com/gucong3000/build-script](https://github.com/gucong3000/build-script)
####AngularJS实战 学习实例####

本工程是我学习都是来自《AngularJS实战》一书的学习笔记

**问题总结**
1. 如何让webstorm 提示angular关键字 
答案: https://segmentfault.com/q/1010000000656330
    
    如果曾经添加过 angular 库，那么打开当前项目之后，进入设置里：Languages & Frameworks -> JavaScript -> Libraries；你会看到右边有你需要的 angular 以及其他相关的库，打对勾就好。
    如果之前没有添加过 angular，有一种非常简单的方法：
    在 head 里面添加：<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.15/angular.js"></script>鼠标放到这行 URL 上面后，你会发现这行代码的开头会出现一个灯泡，点击它之后会出现 download 选项，下载完成之后这个库就会自动添加到当前项目
# docker-build-solution
> 利用docker，配置，搭建一个统一的前端的build/prd/本地，虚拟机持续集成(CI)环境


## 安装的软件（centos/ubuntu）：
+ ruby 2.4+
+ nodejs
+ git
+ vim
+ bower
+ jenkins

## 建立dir mapping
```conf
docker run --name rcc-dev-leads -i -t -p 3000:3002 -v ~/webs/:/var/www
```

## resouces:
+ https://www.zhihu.com/question/30129756
+ http://www.jianshu.com/p/653f99c32f66
+ https://segmentfault.com/a/1190000007336706
+ http://www.cnblogs.com/freefei/p/5311294.html
+ http://www.cnblogs.com/52fhy/p/5991344.html
+ http://dockone.io/article/834

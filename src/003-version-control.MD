# 版本管理(推荐使用GIT)
> 以下所有的规范，示例都是以git进行

## 工具：
+ 统一使用git
+ mac版GUI工具，推荐sourceTree
+ windows版也可以用sourceTree

## 版本管理方案：
+ master:一般线上运行稳定的代码会在master上，但不保证最新
+ dev_1.0.0 会根据版本演进, 版本号按 dev_1.0.0 -> dev_1.0.1 方式手动更新
+ tag 每个版本上线，更新tag，命名参考：v1.0.0

## 版本号(默认写3位)：
+ 第1位：大的版本，大的功能更新 (dev_1.0.0 --> dev_2.0.0)
+ 第2位：一般的版本，功能新增 (dev_1.1.0 --> dev_1.2.0)
+ 第3位：一般是bug的更新，或者很小的功能迭代，需要快速上线，上线周期小于7天的迭代  (dev_1.1.1 --> dev_1.1.2)
+ 第4位：线上项目有bug需要立即修复  (dev_1.1.2 --> dev_1.1.2.1)

## 版本上线
+ 新的版本上线，稳定运行1天，合代码到master上
+ 保留最近10-20个dev分支的代码
+ 新拉分支，永远从master上进行

## 关于提交git的一些备注信息：原则上，必须
> [v版本号(去掉点的-统一四位)]动词:  备注信息/bug-编号

+ 功能相关：[issue/feature]
```conf
[v1022]issue: add validation for add lot
[v1022]issue: xxx
```
+ bug修复：[bugfix]
```conf
[v1020]bugfix: bug-6512
[v1020]bugfix: ios7 crash when images too much.
```
+ 性能优化：[optimize]
```conf
[v1023]optimize: lazyLoading for swiper
[v1023]optimize: bug-6752
```

## resouces:
+ http://www.jianshu.com/p/860fdd8860cc

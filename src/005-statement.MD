# 语句

## if..else/for/whire都推荐带{}
+ 常规的C风格
```javascript
if(condition){

}else{

}
```

+ C#程序员风格：
```javascript
if(condition){

}
else{

}
```

+ 团队不推荐的风格
```javascript
if(condition)
//
else
//
```

## swich/case
+ 这个语句可以帮助写出清晰的分支，强制写default

## 三元表达式：
+ 一般最多一层嵌套
+ 原则上：不要做编译器，或者压缩工作帮你做的事情

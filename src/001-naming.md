# 命名:
> 宁可花10分钟想一个方法名，因为这真的很重要

## 变量命名:
- 一般情况下,取有意义的英文单词作为变量名
- 尽量短,语义准确(如:status/state这种情况)
- 希望别人忽略的变量，可以 _ 开头，或者干脆就以 _ 为名

## 方法命名:
- 传入参数以:'in'开头,如inOptions/inConfig (个人习惯不强求)
- 命名可以长一点,但一定语义准确,不要去做代码压缩工具帮你做的事情

## 文件命名：
- 以中划线分割，如:tabbar.js 或者 `user-info.js`
- 如果user-info.js里的是class，则以`UserInfo`的方式来命名
- 有种文件，是这个模块里的private模块，可以以`_`开头
- 在一些编辑器里，模块的配置文件，希望显示在第一个，也会以`_`开头，如：`_config.js`

## 类命名:
- 大写，有意义
- 几个单词的组合
- 宁可名字长，也要一目了然（当然，尽量不要生僻）
- 收回上一点，这种名字还是算了：CheckWhenTimeIsEqualZero

## 常用方法名

### 序列化，反序列化：
> 灵感来源： slate

| name        | description    |
|-------------|----------------|
| serialize   | 序列化         |
| deserialize | 反序列化       |
| serializer  | 序列化的具体类 |

### 编码，反编码：
> 灵感来源： isomorphic-base64

| name   | description |
|--------|-------------|
| encode | 编码        |
| decode | 反编码      |

### 转换器：
> jquery.cookie 源码

| name      | description |
|-----------|-------------|
| converter | 转换器      |

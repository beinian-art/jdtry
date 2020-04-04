# 京东试用 Chrome 拓展
本拓展自动获取所有可申请的商品，并可一键申请指定的试用商品。

## 界面截图
![1.png](quiver-image-url/F6DAF232AEBD8040A9B43EBDBE95AA62.png =1131x520)

## 主要功能
* 获取关注商铺数量
* 清空关注商铺
* 检索京东试用所有商铺
* 检索是否有成功申请试用的商铺
* 一键申请试用商品

## 安装
```js
# 安装依赖
yarn
# 生成拓展文件
yarn build
# chrome 打开开发者模式加载拓展（位于build文件）
```

## 说明
* 每天可申请的试用商品上限为300个
* 每人可关注的店铺上限为500个
>所以需要及时清理
* 定时启动以及自动登录还未完成，**TODO**
* 使用者多的时候再考虑加入谷歌商店

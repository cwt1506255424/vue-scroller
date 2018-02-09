# vue-scroller

## it is...
- 下拉刷新, 上拉加载的vue插件
- 那个vue-scroller感觉好像不适合我的项目...好吧其实就是不会用

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## options

Props|Type|Description | Default
:-:  |:-: |:-: | :-:
onInfinite| Function | 上拉callback | 延迟.5s
onRefresh | Function | 下拉callback | 引用上拉callback
isFirstLoad| Boolean | 第一次进入是否加载 | false
bottomPosition | Number | 上拉加载动画与底部的距离 | 0

Slot | Description
:-: | :-:
top | 顶部动画
bottom | 底部动画
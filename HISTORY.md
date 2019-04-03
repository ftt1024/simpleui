## 更新日志

### version 1.4

+ 由于django无法自定义图标，所以采用猜测的方式来给菜单显示图标
+ 修复select下拉框bug
+ 修复错误提示不显示bug
+ 图标使用最新版layui 2.4.4
+ 导入jieba分词，用于猜测图标

## version 1.4.1
+ 取消日志输出

## version 1.4.2
+ 修复布尔类型下拉框无法显示bug

## version 1.4.3
+ 修正登录页面标题显示

## version 1.4.4
+ 修复pip 安装失败bug
    > 部分用户设置的pip，是Python2的版本，导致安装失败
+ 去掉首页代码库标识     

## version 1.4.5
+ 增加自定义首页功能
## version 1.4.6
+ 加入 `# -*- coding: utf-8 -*-` 以支持python2

## version 1.4.7
- [x] 标题页点击刷新菜单无效
- [x] 列表页的过滤条件下拉框，如果类型为普通字段，内容不能被正确显示
- [x] 所有的搜索，在第一页显示正常，但是在第二页的时候就丢失了搜索关键字，也就是说这个第二页就是当前页面所有数据分页之后的第二页
- [X] 在list_filter中，不能按时间过滤(增加了时间区域选择，由于django的限制，暂时不能很好的发挥作用)

## version 1.4.8
- [X] 修复日期bug     
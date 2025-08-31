# 我的博客是怎么搭建的

## 废话

本来打算从windows server 的安装开始

说起，作为我赛博仓库的开端。

但一直拖着未动笔，今天草草用cf-pages 搭建了这个博客，就先写点吧。

## 准备

1. 一个cloudflare的账号[]()**https://dash.cloudflare.com**
2. 一个Github的账号[]()**https://github.com**

## 开始

1. 选择一个合适的Hugo主题[]()**https://themes.gohugo.io/**
2. 点击Download会跳转Github仓库
3. 直接fork一份
4. 在Cloudflare左侧面板找到计算（Workers）\>Workers and Pages
5. 点击创建\>Pages\>导入现有的Git储蓄库
6. 绑定Github后选择你fork的仓库\>开始设置\>在框架预设选择Hugo\>在环境变量（高级）
7. 变量名称填入HUGO*VERSION*
8. 值填入[]()**https://github.com/gohugoio/hugo/releases**显示的最新版本即可，如0.149.0
9. 保存并部署
10. 🎉🎉🎉

## 后续

毛坯房有了

了解主题配置[]()**https://stack.jimmycai.com** ，修改站点信息。

日常发文在 content/post 文件夹下新增 md 文件即可。


# daily-check-in

 一个打卡小程序, 基于 leancloud 数据存储。所以不需要建立额外的 webapp 和数据库。

# 开始

1. 注册小程序

去小程序官网注册。

1. 注册 leancloud 

注册地址 https://leancloud.cn

2. zai leancloud 创建一个应用

开发版本即可。

3. 下载 daily-check-in 项目

```
git clone https://github.com/xugy0926/daily-check-in.git
```

4. 将 leancloud 的 id 填入 daily-check-in 项目

修改 app.js 中的 appId 和 appKey，这两个 id 就是你在 leancloud 上创建的项目的 id。

```
AV.init({
  appId: 'xxxxxxxxxx',
  appKey: 'xxxxxxxxxx',
});
```

5. 将 小程序的 id 填入到 leancloud 新项目中。

在 leancloud 进入到你创建的项目中。

选择 **组件** -> **社交**, 在 微信小程序菜单那填入你的小程序的 ID 和 Secret Key。

6. 用微信开发者工具导入项目
7. 运行项目


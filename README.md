# 尚硅谷 谷粒商城后台管理系统前端项目

> 后端项目地址 [gmall](https://github.com/FuQingGuan/gmall)

![](https://oss.yiki.tech/img/202304260018256.png)

## 下载依赖&运行项目

```shell
// 下载依赖
npm i
```

![](https://oss.yiki.tech/img/202304260018035.png)

## 可能导致的异常以及解决方案

```shell
// 异常: 这个错误是由于在安装 node-sass 模块时，执行了 postinstall 脚本（node scripts/build.js）时出现了错误，导致安装过程失败。
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! node-sass@4.9.0 postinstall: `node scripts/build.js`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the node-sass@4.9.0 postinstall script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Administrator\AppData\Roaming\npm-cache\_logs\2023-04-14T16_40_38_149Z-debug.log
```

![](https://oss.yiki.tech/img/202304260018537.png)

```shell
// 下载指定版本的 node-sass
npm install node-sass@4.14.1
```

![](https://oss.yiki.tech/img/202304260018859.png)

![](https://oss.yiki.tech/img/202304260018741.png)

## 运行&停止

```shell
// 运行
npm run dev
```

![](https://oss.yiki.tech/img/202304260018071.png)

![](https://oss.yiki.tech/img/202304260018181.png)

```shell
// 停止
ctrl + c
```

![](https://oss.yiki.tech/img/202304260018743.png)

## 更改后端验证码地址

![](https://oss.yiki.tech/img/202304260018626.png)

![](https://oss.yiki.tech/img/202304260018656.png)

![](https://oss.yiki.tech/img/202304260018615.png)

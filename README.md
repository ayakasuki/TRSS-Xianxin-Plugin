<p align="center">
  <a href="https://gitee.com/xianxincoder/xianxin-plugin">
    <img width="200" src="https://gitee.com/xianxincoder/xianxin-plugin/raw/master/resources/img/rank/top.png">
  </a>
</p>

<h1 align="center">TRSS-Yunzai专用 · Xianxin-plugin</h1>

<div align="center">

是 <a href="https://gitee.com/TimeRainStarSky/Yunzai" target="_blank">TRSS-Yunzai</a> 闲心修复版 -（未完全）

[![访问量](https://profile-counter.glitch.me/TRSS-Xianxin-plugin/count.svg)](https://github.com/ayakasuki/TRSS-Xianxin-Plugin)


<img src="https://cdn.jsdelivr.net/gh/ayakasuki/Cocowwy/assets/github-contribution-grid-snake.svg">

</div>
<br />
<br />

## 最新使用说明（重要）
 ### 1. B站最新需要配置：
 - 目前插件已支持配置自定义Cookie 配置在`/config/bilibili.set.yaml`下的`customCookie`处
 - 插件目前也有临时cookie的自动获取，但依然会出现-352错误，若频繁出错，请改用自己的cookie。

**cookie的获取与设置：**
```base
1. 在浏览器中登录自己的b站账号
2. 处于bilibili首页 -> F12 -> 找到调试台（Console） -> 在下方输入`document.cookie`并回车 -> 复制输出的文本
3. 将输出的文本粘贴到`/config/bilibili.set.yaml`下的`customCookie`处，保存
注意：cookie不带冒号
```
 ### 2. 此插件已测试的主要功能：

- ✅: 完全支持
- 🟨: 部分支持，由于平台限制会偶发报错
- 🚧: 未知-未测试
- ❌: 不支持，通常是Oicq和Icqq依赖在主体去除后不兼容

|               | 适配器 | B站推送 | woc（神秘指令） | cos | 搜索up | 群战 | 赞我 | 转发 | 小视频 | 潜水 |
|   :--------: | :--:     | :---: | :---: | :----------: | :--: | :---: | :---: | :--: | :---: | :------: |
|              | trss-QQguild  |  ✅   |  ✅   |      ✅      |  ✅   |  ❌   |  ❌   |  ✅  |  🟨   |    ❌    |
|             |   icqq-plugin |  🟨   |  ✅   |      ✅      |  ✅    |  ✅  |  ❌   |  ✅  |  🟨   |     ✅    |
| TRSS-Yunzai  |   go-cqhttp |  ✅   |  🟨   |      ✅      |  ✅     |  🚧   |  ❌   |  🟨  |  🟨   |     ✅    |
|              |   KOOK        |  ✅   |  ✅   |      ✅     |  ✅    |  🚧  |  ❌    |  ✅  |  🟨  |   ❌     |
|              |   Discord       |  🚧  |  🚧  |      🚧      |  🚧  |  ❌   |  ❌  |  🚧  |  🚧   |    ❌   |

### 3. 此插件虽经测试可在ICQQ内同样兼容Miao-Yunzai,但仍未PR，仍然属于TRSS专属修复，无必要Miao版还是回原版就好~


##


## 安装与更新
推荐使用 git 进行安装，以方便后续升级。在TRSS-Yunzai根目录打开终端，运行如下命令进行安装。

Gitee

```base
git clone https://gitee.com/ayakasuki/xianxin-plugin.git ./plugins/TRSS-Xianxin-Plugin/
```

Github

```base
git clone https://github.com/ayakasuki/TRSS-Xianxin-Plugin.git ./plugins/TRSS-Xianxin-Plugin/
```


## ⌨️ todo
- [x] 已测试-除频道外Miao-Yunzai功能共存 （主要是萌新频道的guild_id和channel_id还没搞懂post的验证，也有可能频道ID被主体拦截成群号）
- [ ] 偶尔维护


##
**本人出于用在KOOK与QQ频道重新小纠错，如不喜可不用，勿喷**
**用了几个B站推送，闲心是比较好用的那款，大佬喜欢也欢迎pr，一起维护蒙尘的闲心插件**

## 🔗 链接
- [原版闲心](https://gitee.com/xianxincoder/xianxin-plugin)
- [TRSS-yunzai](https://gitee.com/TimeRainStarSky/Yunzai)
- [云崽](https://gitee.com/Le-niao/Yunzai-Bot)
- [插件库](https://gitee.com/Hikari666/Yunzai-Bot-plugins-index)
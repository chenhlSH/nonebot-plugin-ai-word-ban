<div align="center">
  <a href="https://nonebot.dev/store/plugins/"><img src="https://raw.githubusercontent.com/fllesser/nonebot-plugin-template/refs/heads/resource/.docs/NoneBotPlugin.svg" width="310" alt="logo"></a>
  <br>
<div align="center">

# nonebot-plugin-sell-poor（前面是我拿来改写的样本）
</div>
_✨ 基于 LLM 的捣蛋鬼清除插件 ✨_<br>


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/XTxiaoting14332/nonebot-plugin-sell-poor.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-sell-poor">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-sell-poor.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="python">

</div>



## 📖 介绍

基于 LLM 的捣蛋鬼清除插件，使用API<br>


## 💿 安装（别看，没用

<details open>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令安装

    nb plugin install nonebot-plugin-sell-poor

</details>

<details>
<summary>pip安装</summary>

    pip install nonebot-plugin-sell-poor

打开 nonebot2 项目根目录下的 `pyproject.toml` 文件, 在 `[tool.nonebot]` 部分追加写入

    plugins = ["nonebot_plugin_sell_poor"]
</details>
<details>
<summary>Github下载</summary>

手动克隆本仓库或直接下载压缩包，将里面的 `nonebot_plugin_sell_poor` 文件夹复制到 `src/plugins` 中,并安装以下依赖

    httpx  PyJWT

</details>


</details><br>


## 🔧配置项（别看，还在改）
### 必填项

```
#智谱清言的API Key
sell_poor_token = xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

启用的群聊
sell_poor_group = ["123456789","987654321"]
```

### 非必填项

```
#触发的概率（默认为0.5）
sell_poor_probability = 0.5

# 卖若文案
sell_poor_text = "诶，还是太菜了，学不来，我也想有本领😭"

```


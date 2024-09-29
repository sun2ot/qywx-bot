## 介绍

作用：向企业微信群机器人发送信息

使用方式：

```Python
from qyex_bot import Bot
bot = Bot(key="...") # 企业微信 webhook key
bot.send_text(content="hello world")
```

## 环境

```
pip install requests
```
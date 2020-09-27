# kiwawa

LINE／Discord 訊息同步機器人。一個機器人只能服務一組 LINE 群組／Discord 文字頻道，已知不支援 LINE 貼圖、跨平台標記（@）。

## 使用教學

總共有 5 個環境變數要設定： 
```
LINEBOT_SECRET
LINEBOT_ACCESS_TOKEN
LOTIFY_TOKEN
DISCORDBOT_TOKEN
DISCORD_WEBHOOK
```

### LINE bot

建立 Messaging API，設定環境變數 `LINEBOT_SECRET` 及 `LINEBOT_ACCESS_TOKEN`。

### LINE Notify

https://notify-bot.line.me/my/ => 發行權杖（權杖名稱是顯示在 `【 】` 中的文字）=> 設定環境變數 `LOTIFY_TOKEN`。

### Discord bot

https://discord.com/developers/applications => `New Application` => `Bot` => `Add Bot` => 往下拉設定權限 => Username 下方複製 token => 設定環境變數 `DISCORDBOT_TOKEN`

### Discord webhook

Discord 伺服器 => `伺服器設定` => `整合` => `建立 Webhook` => `複製 Webhook 網址` => 設定環境變數 `DISCORD_WEBHOOK`

## Author

- CA-Lee

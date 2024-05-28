# PiCord
將Discord與Raspberry Pi做結合，做到智慧家電的功能。
比如說

．**控制電燈開關**

．**濕度感測通知**

．**家庭監控系統**

# 作者
本專案由 **羽迭 Yuday Project** 製作，過程中遇到了很多問題，要感謝 **Sch** 大大提供協助！

# 指南
在Raspberry Pi中，似乎遇到了無法直接安裝discord.py與RPi.GPIO的問題，你需要創造一個虛擬環境(venv)才能夠運作。

如果你需要讓讓Raspberry Pi啟動時自動運行腳本的話，需要寫一個.service的檔案，這邊感謝 **sch** 協助我完成這件事！

# 指令
```
用戶皆可進行的操作
/picord_help
列出PiCord所有的指令與其效果

只能由伺服器管理者進行的操作
/light_perm + @成員
創建並給予指定成員"打光師"身分組
/light_unperm + @成員
移除指定成員的"打光師"身分組
/light_perm_search
查詢擁有"打光師"身分組的成員

/light_on/off
開啟/關閉電燈
/light_time_on/off + 時間 + 定時任務的名字
定時開啟/關閉電燈
/light_delete + 定時任務的名字
刪除指定的定時任務
/light_search
查詢所有定時任務
```

# 支持作者
可以的話，希望你們能夠來支持我~

我平常會在Twitch與YouTube開台，也會發布貼文在Twitter(我就愛叫Twitter怎麼樣!!!)，請務必來跟我聊聊天講講話！

Twitch：https://twitch.tv/yuday_project

YouTube：https://youtube.com/channel/UC2PpwLseMmkEOuvai2nxlqw

Twitter：https://twitter.com/LimoluKing

Donate：https://p.ecpay.com.tw/F171A1B

# 更新時間

```
2024/05/29
完成指令提示、創建與給予身分組、操作燈光。
```

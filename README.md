# 柴妹的中州韻輸入法引擎配置
[![Commit](https://img.shields.io/github/last-commit/bs10081/Rime-Cx330/main?color=red)](https://github.com/bs10081/Rime-Cx330/archive/main.zip)
[![GitHub Tag](https://img.shields.io/github/tag/bs10081/Rime-Cx330)](https://github.com/bs10081/Rime-Cx330/releases)
![Star](https://img.shields.io/github/stars/bs10081/Rime-Cx330)
[![GitHub issues](https://img.shields.io/github/issues/bs10081/Rime-Cx330)](https://github.com/bs10081/Rime-Cx330/issues)

## 感謝使用本Rime配置文件

本輸入法適配小鶴雙拼、全拼、五筆
支持中英混合輸入、Emoji輸入、簡繁轉換、傳承字標準字轉換、UTF-8 GBK編碼轉換、200萬詞庫覆蓋日常絕大多數場景。

## 使用方法
前往 [Release](https://github.com/bs10081/Rime-Cx330/releases) 下載最新版本的配置檔案，解壓縮後將所有文件覆蓋到用戶資料夾

- Linux： `~/.config/ibus/rime/`
- Windows： `%APPDATA%\Rime`
- macOS：`~/Library/Rime/`

然後點擊輸入法中的[重新部署](https://github.com/rime/home/wiki/CustomizationGuide#%E5%BF%85%E7%9F%A5%E5%BF%85%E6%9C%83)來完成編譯，這樣就大功告成了，是不是很簡單呢？😁


> 在「部署」操作時，將用到輸入方案源文件、並結合上述資料夾的定製的內容來編譯輸入方案。

### 個別文件的用途
- 〔全局設定〕 `default.custom.yaml`
- 〔小鶴雙拼輸入方案〕`double_pinyin_fly.custom.yaml`
- 〔小鶴雙拼輸入方案副本〕`double_pinyin_fly.schema.custom.yaml`
- 〔朙月拼音輸入方案〕`luna_pinyin_simp.custom.yaml`
- 〔朙月拼音輸入方案副本〕`luna_pinyin_simp.schema.yaml`
- 〔五筆拼音混合輸入方案〕`wubi_pinyin.custom.yaml`
- 〔五筆拼音混合輸入方案副本〕`wubi_pinyin.schema.yaml`
- 〔自然碼輸入方案副本〕`doubal_pinyin.schema.yaml`
- 〔用戶狀態訊息〕`user.yaml`
- 〔配置同步〕 `installation.yaml`
- 〔快捷鍵〕`key_bindings.yaml`
- 〔詞庫管理〕`luna_pinyin.extended.dict.yaml`
- 〔BetterRime詞庫增強包〕`luna_pinyin.*.dict.yaml`
- 〔基礎詞庫〕`*.dict.yaml`
- 〔自定義碼表〕`custom_phrase.txt`
- 〔符號管理〕`symbols.yaml`
- 〔Windows版外觀〕`weasel.custom.yaml`
- 〔macOS版外觀〕`squirrel.custim.yaml`
- 〔emoji〕`/Opencc/emoji*`
> 編輯時請使用Tab，禁止使用空格，否則配置文件將失效，甚至導致編譯失敗。

具體配置修改方法請詳讀 [官方wiki](https://github.com/rime/home/wiki)

---

## Rime::Home

[![Join the chat at https://gitter.im/rime/home](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rime/home?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
​
## Rime Bug Report
[![GitHub issues](https://img.shields.io/github/issues/rime/home.svg)](https://github.com/rime/home/issues)

## 本倉庫依賴 [Rime](https://github.com/rime/home)

### [![Rime網站](https://img.shields.io/badge/Website-Rime-9cf)](https://rime.im)

# 請柴妹喝杯咖啡

LBC錢包地址：`bc2FpeaknTyveZhzTatj6VWjshmxVYPfC5`

BTC錢包地址：`38Hv6BwFgwLPb94FCA8piBZXYNewgW9csu`

USDT錢包地址：`0xea9e9129063b9f10836c6234b079b1926a7665bf`
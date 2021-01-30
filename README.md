# 柴妹的中州韻輸入法引擎配置
[![Download](https://img.shields.io/badge/Download-0.2.0-blue)](https://github.com/bs10081/Rime-Cx330/archive/0.2.1S.zip)
[![GitHub Tag](https://img.shields.io/github/tag/bs10081/Rime-Cx330)](https://github.com/bs10081/Rime-Cx330/releases)
## 感謝使用本Rime配置文件

本輸入法適配小鶴雙拼、全拼、五筆

支持中英混合輸入、Emoji輸入、簡繁轉換、傳承字標準字轉換、UTF-8 GBK編碼轉換、200萬詞庫覆蓋日常絕大多數場景。

## 使用方法
前往 [Release](https://github.com/bs10081/Rime-Cx330/releases) 下載最新版本的配置檔案，解壓縮後將所有文件覆蓋到用戶資料夾

- Linux： `~/.config/ibus/rime/`
- Windows： `%APPDATA%\Rime`
- macOS：`~/Library/Rime/`

在「部署」操作時，將用到輸入方案源文件、並結合上述資料夾的定製的內容來編譯輸入方案。

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

---

## 問題&建議回饋
[![GitHub issues](https://img.shields.io/github/issues/bs10081/Rime-Cx330)](https://github.com/bs10081/Rime-Cx330/issues)

---

## 打賞

LBC錢包地址：`bc2FpeaknTyveZhzTatj6VWjshmxVYPfC5`

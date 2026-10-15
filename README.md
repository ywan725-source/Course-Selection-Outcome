# Course-Selection-Outcome

目前狀態：專案起始骨架，尚未實作產品功能。

本儲存庫先建立可維護的工作基礎，供後續釐清需求與分階段實作使用。儲存庫名稱不代表已確認的選課流程、結果計算規則或交付形式。

## 已確認範圍

- 建立清楚的文件、合理的目錄與最小維護設定。
- 記錄假設、未決事項及分階段實作計畫。
- 不根據專案名稱自行決定功能、資料模型或技術框架。

## 開始使用

可直接在 GitHub 閱讀與編輯文件，或在已安裝 Git 的環境執行：

```sh
git clone https://github.com/ywan725-source/Course-Selection-Outcome.git
cd Course-Selection-Outcome
```

先閱讀 [需求與未決事項](docs/requirements.md)，再查看 [實作計畫](docs/plan.md)。
目前不需要安裝套件；尚無應用程式啟動、建置或自動測試指令。

## 目錄

| 路徑 | 用途 |
| --- | --- |
| [docs/requirements.md](docs/requirements.md) | 已知範圍、暫定假設、待確認問題與需求紀錄格式 |
| [docs/plan.md](docs/plan.md) | 各階段工作與完成條件 |
| [docs/decisions.md](docs/decisions.md) | 起始結構決策與後續決策紀錄格式 |
| [src/](src/README.md) | 後續程式碼的暫定位置 |
| [tests/](tests/README.md) | 後續驗證與測試的暫定位置 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 變更與檢查方式 |
| [.editorconfig](.editorconfig) | 通用文字格式設定 |
| [.gitattributes](.gitattributes) | 文字檔換行設定 |
| [.gitignore](.gitignore) | 常見本機暫存與本機環境設定排除 |

## 維護原則

先確認問題與驗收條件，再選擇最小必要的工具。新功能需能追溯到已確認需求；未定案的提議應保留其狀態與確認來源。

本儲存庫為公開內容，不應提交真實個人資料、帳密、金鑰或內部文件。若需要範例，使用明確標示的合成資料。

## 授權

尚未選定授權條款，因此暫不加入 LICENSE 檔案。授權選擇列於未決事項，公開儲存庫不等於已選定開源授權。

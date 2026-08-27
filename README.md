# 好寫 Howrite・法律文件

這個 repo 只放「好寫 Howrite」App 的對外法律文件，並透過 GitHub Pages 公開發布，
供 App 內連結與 App Store Connect 的 metadata 欄位使用。

| 頁面 | 網址 |
|---|---|
| 首頁 | https://bortyng.github.io/howrite-legal/ |
| 隱私權政策 | https://bortyng.github.io/howrite-legal/privacy.html |
| 服務條款 | https://bortyng.github.io/howrite-legal/terms.html |

## 為什麼獨立成一個 repo

主 repo（`howriting-composition`）是**私有的**，而它的 `docs/` 資料夾裡還有內部文件
（上架清單、App Store 文案、內部審查報告、廠商盡職調查信稿）。
若直接在主 repo 開 Pages 發布 `/docs`，那些內部文件會一併變成公開網址。
所以法律文件另外放在這個**只含公開內容**的 repo。

## 改動須知

`privacy.html` 與 `terms.html` 在主 repo 的 `docs/` 底下也各有一份副本
（歷史原因，且 `docs/ios-launch-tutorial.md` 等文件會引用）。
**兩邊要一起改**，否則 App 內連到的版本會與 repo 內的版本不一致。

改完之後：commit、push，GitHub Pages 約一分鐘後自動更新，不需要額外操作。

# Character Design Views｜Node 的角色出圖教室

![Node 教學封面](images/01-cover.png)

從一張角色參考圖，製作環境主圖＋三視圖，以及六張獨立透明 PNG。包含繁體中文教學、Node 第一人稱配圖與可下載技能。

## 先看教學

[閱讀完整文章：給我一張圖，別給我六個分身](blog.md)

## 安裝

下載 [技能 ZIP](downloads/character-design-views.zip)，將解壓縮後的 `character-design-views/` 整個資料夾放進專案的 `.agents/skills/`。保留 assets 和 agents 子資料夾。在支援圖片生成的 Codex 工作環境使用；沒有圖片生成工具的環境無法只靠此技能出圖。

專案技能路徑與呼叫方式：[OpenAI 官方文件](https://learn.chatgpt.com/docs/build-skills)。

附上你的角色圖，輸入：

```text
使用 $character-design-views，依附圖製作環境＋三視圖，
以及正面、左側面、右側面、背面、上面、下面六張獨立透明 PNG。
保持角色設定一致，全部完成後再逐張檢查。
```

若允許精確排版，可另外加上：

```text
比例線可使用程式遮罩與圖層合成，僅處理合成圖排版與線的遮擋。
```

## 預設成果

- 一張直式角色環境主圖＋Front、Side、Back 三視圖。
- 三條比例線，僅在側面與背面後方，被完整角色輪廓遮住。
- 六張無文字、具有 Alpha 透明背景的獨立 PNG，以及 ZIP。
- 提示詞與複查記錄。

這是設計參考圖流程，未建立真正 3D 模型；圖像生成仍可能出現造型、角度與材質差異。

## 檔案

- `blog.md`：官網或 GitHub 可使用的文章。
- `article.html`：同內容的可攜式文章預覽，可在瀏覽器開啟。
- `images/`：三張教學插畫、實際合成圖與原始參考圖。
- `examples/node/`：本次示範的六張透明 PNG。
- `skills/character-design-views/`：可分發的技能副本，以 Node 成品作排版參考。
- `downloads/`：技能 ZIP。

官網發文時，將相對路徑映射至網站媒體與下載路徑。此專案提供技能、教學與範例，未包含網站部署設定。


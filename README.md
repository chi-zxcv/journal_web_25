# journal_web_25
Initial commit: Jekyll activities starter
=======
# GitHub Pages Starter：玩樂與活動筆記

一個能直接在 GitHub Pages 上運作的 Jekyll Starter：
- 小縮圖列表風格（Inter＋Playfair 字體、卡片樣式）
- `posts.json` + 前端進階搜尋（類型、國家→縣市、日期、標籤 AND/OR、關鍵字）
- Hero 粒子背景（可移除）
- GitHub Actions 自動部署

## 快速上線
1. 建立 GitHub Repo（建議 `yourname.github.io`；若是一般 repo 也可）。
2. 上傳整個專案內容到該 Repo。
3. 進 **Settings → Pages**：Source 選擇 **GitHub Actions**（本專案已附 workflow）。
4. 等待 Actions 完成後，至 Pages 網址查看。

> 若不是根網域（例如 `yourname.github.io/your-repo`），請：
> - `_config.yml`：`baseurl` 改為 `/your-repo`
> - `url` 保持你的主機網域（如 `https://yourname.github.io`）

## 發文格式（Front Matter 範例）
```yaml
---
title: 華山設計展・快閃一日遊
date: 2025-09-22
type: event          # event / trip / game ...
country: TW
city: 台北市
tags: [設計展, 朋友聚, 台北]
location: 台北｜華山文創園區
mood: happy
rating: 4
cover: /assets/images/sample/cover.jpg
gallery:
  - /assets/images/sample/p1.jpg
  - /assets/images/sample/p2.jpg
summary: 用半天密集看展，收集靈感，最後在附近咖啡店作結。
---

內文...
```

- 若是行程/展期，亦可加：`start_date`, `end_date`。搜尋會採「區間相交即可」。

## 本地測試（可選）
```bash
gem install bundler
bundle install
bundle exec jekyll serve
# 開啟 http://localhost:4000
```

## 關閉粒子效果
- 刪除 `_layouts/default.html` 裡的 `<script src="tsparticles...">` 與初始化程式碼。
- 或在 `index.html` 移除 `#particles-hero` 容器。


步驟（Mac / Windows 都適用）
1. 安裝 Ruby + Bundler
Jekyll 是 Ruby 寫的，所以要先有 Ruby。
macOS（建議用 Homebrew）
brew install ruby
gem install bundler


Windows（建議裝 RubyInstaller）
下載安裝 RubyInstaller
，安裝後再執行：

gem install bundler

2. 進入專案資料夾

解壓縮 play-notes-starter.zip，進去資料夾：

cd play-notes-starter

3. 安裝相依套件

專案裡我已經幫你放了 Gemfile，直接跑：

bundle install

4. 啟動 Jekyll Server

執行：

bundle exec jekyll serve


成功的話會顯示：

Server running... http://127.0.0.1:4000/

5. 打開瀏覽器

到 http://localhost:4000
 就能看到網站啦！


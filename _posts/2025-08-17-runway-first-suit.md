---
layout: post
title: "第一次穿上西裝走秀｜突破自己"
date: 2025-08-17
type: event
tags: [西裝, 走秀, 自信, 成長]
summary: 第一次在那麼多人的場合走秀，穿上西裝的瞬間被自己帥到。怦然心跳、腎上腺素拉滿——原來勇敢踏出去，就會看到全新的自己。
cover: /assets/images/2025-08-17-runway/cover.jpg
gallery_dir: /assets/images/2025-08-17-runway/
---

# 第一次穿上西裝，在眾人面前走秀

一開始其實很緊張，腦袋裡反覆演練步伐、眼神、停點。  
換上西裝的那刻，鏡子裡的自己突然**站直**了——肩線被撐起、腰線被收好，連呼吸都更穩了。

上台前深呼吸三次，心裡默念節奏：**步、步、停**。  
燈光打下來，耳邊只剩下腳步與掌聲，像是開了一扇門——**被自己帥到**。  
原來所謂的台風，是一種「我知道自己在這裡」的平靜。


# 🕴️ 第一次穿上西裝走秀：被自己帥到的瞬間

我的第一套正式西裝、第一個真正的舞台、第一條實戰的動線。  
燈亮的剎那，心跳超快，但腳步踏出去後，節奏就回來了。  
原來所謂「帥」，不是鏡子裡那個角度，而是台上那個**穩住的自己**。

---

## 心境｜從急促呼吸到找到步伐
- 開場前在側台做了三次深呼吸，默念「步伐慢、目光穩、肩線放鬆」。  
- 第一個轉身點穩住後，整個人就放開了：台下視線像海浪，但我像在浪上走。

## 現場｜燈光、步點、鏡頭
- 路線：主跑道 → 定點 A（停 2 拍）→ 右側邊台 → 回中線收場。  
- 小撇步：**走慢一點**，每步腳跟先落地，肩與骨盆保持一條線，照片比較利落。  
- 眼神：看遠點的位置（攝影棚門框上方），臉會比較挺，避免往下看。

## 我學到的
- 西裝合身 > 品牌：肩寬0.5公分的差距，照片裡就是**氣場差距**。  
- 口袋巾與領帶夾只要一個亮點就夠，配件過多會搶戲。  
- 上台前把手機、錢包都清空，口袋線條才會乾淨。

## 我的突破
今天不是把自己變成別人，而是把**最好狀態的自己**放上台。  
回看照片的那一瞬間，我真的被自己帥到——  
原來自信不是靠別人給，而是靠**一次次站上去**。

---

### 致未來的我
記得這種心跳、這種專注。  
下次換更難的舞台，也一樣走穩第一步。

---

## 小結
- 走秀不是逞強，是把練習過的每個細節交給當下。  
- 自信不是來自掌聲，而是每個停點回頭看見**自己真的有在進步**。  
- 下一次，想嘗試不同色系與更俐落的剪裁。

---

## 相片

{% assign gallery_path = page.gallery_dir %}
{% assign files = site.static_files | where_exp: "f", "f.path contains gallery_path" %}

<div class="gallery">
  {% for file in files %}
    {% if file.extname == ".jpg" or file.extname == ".png" or file.extname == ".jpeg" %}
      <a href="{{ file.path | relative_url }}" target="_blank">
        <img src="{{ file.path | relative_url }}" alt="Tamsui Photo {{ forloop.index }}" loading="lazy">
      </a>
    {% endif %}
  {% endfor %}
</div>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 10px;
  margin-top: 1.5em;
}
.gallery img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 10px;
  transition: transform 0.3s ease;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}
.gallery img:hover {
  transform: scale(1.05);
}
</style>


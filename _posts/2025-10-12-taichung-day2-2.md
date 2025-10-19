---
layout: post
title: "【台中兩天一夜·Day2】海的鹹味與公路的風：梧棲漁港與清水休息站的午後"
date: 2025-10-12
type: travel
country: TW
city: 台中市
tags: [台中, 梧棲漁港, 清水休息站, 旅行, 海鮮, 公路]
summary: 在梧棲的海風裡、清水的午後陽光下，旅行不再是目的地，而是一種呼吸。那些鹹味、笑聲與微風，成了此行最自然的節奏。
cover: /assets/images/2025-10-12-taichung-day2-2/cover.jpg
gallery_dir: /assets/images/2025-10-12-taichung-day2-2/
video_dir: /assets/videos/2025-10-12-taichung-day2-2/
---

# 🌊 海的鹹味與公路的風：梧棲漁港與清水休息站的午後  

旅途繼續。  
結束了早晨的悠閒與笑鬧，我們再次上路。  
窗外的風景開始轉變——  
城市退到後方，取而代之的是海岸線與陽光。  

---

## 🐟 梧棲漁港：午餐的海味  

車子停在梧棲漁港，空氣裡瀰漫著海的鹹味。  
市場裡人聲鼎沸，攤販的吆喝與海浪聲交錯，  
那是一種屬於海邊的節奏，熱鬧又自在。  

我們挑了幾道海鮮——  
新鮮的花枝、炒螃蟹、香煎魚、蒸蛤蜊。  
每一口都帶著海的味道，也帶著旅程的真實。  

> 「這才叫旅行啊。」  
有人邊吃邊笑著說。  
確實，離開城市後的我們，  
彷彿也被海風洗去疲憊，變得更像自己了。  

吃著吃著，話題也慢了下來。  
只剩浪聲、風聲、還有湯匙敲碗的清脆。  
那是一種被時間溫柔包裹的寧靜。  

---

## ☀️ 清水休息站：午後的放空  

離開漁港後，我們驅車前往清水休息站。  
這裡被稱為「台中最美的休息站」，  
遠方可望見海，近處有草地與風。  

有人坐在長椅上曬太陽、  
有人拿著飲料發呆、  
有人靜靜地看著遠方的天空。  

旅行的意義，有時就在這些「不做什麼」的時刻。  
沒有目的，沒有行程，  
只有風在臉上輕撫、陽光在手上閃爍。  

我想起一句話：  
> 「最美的風景，不一定要拍下來，  
> 有時只要閉上眼，就能記住它。」  

那天的清水，風很溫柔，  
像是在替旅程收一個不說再見的句號。  

---

## 🌇 小結  

梧棲的鹹、清水的風，  
成了這趟旅程裡最自然的一段呼吸。  

我們沒有特別去哪裡，  
卻在平凡的景色裡，  
感受到「活著」的真實。  

或許，旅行不只是為了遠方，  
也是為了在途中，  
重新找回那份對世界的溫柔。  

---

## 📸 旅途花絮  

{% assign gallery_path = page.gallery_dir %}
{% assign files = site.static_files | where_exp: "f", "f.path contains gallery_path" %}
<div class="gallery">
  {% for file in files %}
    {% if file.extname == ".jpg" or file.extname == ".png" or file.extname == ".jpeg" %}
      <a href="{{ file.path | relative_url }}" target="_blank">
        <img src="{{ file.path | relative_url }}" alt="Taichung Day4 {{ forloop.index }}" loading="lazy">
      </a>
    {% endif %}
  {% endfor %}
</div>



<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 10px;
  margin-top: 1rem;
}
.gallery img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  transition: transform .25s ease;
}
.gallery img:hover { transform: scale(1.05); }
.video-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 16px;
  margin-top: 1rem;
}
.video-gallery video {
  width: 100%;
  border-radius: 12px;
  background: #000;
  transition: transform .25s ease, box-shadow .25s ease;
}
.video-gallery video:hover {
  transform: scale(1.02);
  box-shadow: 0 4px 12px rgba(0,0,0,0.25);
}
</style>

---
layout: post
title: "【台中兩天一夜·Day1】從竹圍出發：一路向南的晨光與重逢"
date: 2025-10-11
type: travel
country: TW
city: 台中市
tags: [台中, 旅行, 友情, 慶生, 泰式料理, 龍貓]
summary: 清晨六點的竹圍，天還沒亮，心卻早已在路上。這趟從中壢出發的台中之旅，是一場久違的重逢，也是一場與自己節奏和記憶的對話。
cover: /assets/images/2025-10-11-taichung-day1/cover.jpg
gallery_dir: /assets/images/2025-10-11-taichung-day1/
video_dir: /assets/videos/2025-10-11-taichung-day1/
---

# 🌅 一路向南的晨光與重逢  

清晨六點，竹圍的海風還帶著夜的涼意。  
天未亮，街燈的光灑在空無一人的路上，  
那一刻，我知道——旅程開始了。  

拖著背包上了第一班車，  
一路從淡水到台北，再轉往桃園。  
窗外的城市逐漸甦醒，  
車廂裡卻是一種靜謐的期待。  

也許每一次啟程，  
都像是在對自己說：「去感受吧。」

---

## 🚗 桃園出發：久違的再見  

在桃園會合的那一刻，  
時間彷彿退回到那些年一起瘋狂的時光。  
笑聲、寒暄、彼此打趣——  
那些熟悉的節奏，讓人感覺歲月其實沒有走遠。  

一輛車、幾個人，  
我們穿過城市的灰與綠，  
沿著國道往南，  
陽光從雲縫間探出臉，  
像是特地為這場重逢獻上的祝福。  

---

## 🥥 第一站：泰式料理的香氣  

抵達台中後，我們選了一間泰式料理餐廳。  
那碗椰奶湯香氣濃郁、帶著微辣的熱氣，  
酸、甜、辣交錯在味蕾上，  
像是異國風情裡的一場小冒險。  

有人被辣到皺眉、有人笑著添飯、  
整桌的喧鬧，是友情最真實的樣子。  
原來美食的意義，  
不只是味道，而是一起體驗「當下」。  

---

## 🐾 龍貓與午後的安靜  

飯後我們在一處小巷裡發現了「龍貓」。  
不是真的那隻，而是藏身在店裡的一角——  
一個龍貓主題空間，柔軟、溫暖、充滿童心。  

我們坐在那裡許久，  
看著陽光透過窗簾灑落在木桌上，  
時間好像慢了下來。  

有人輕聲說：「這感覺，好久沒有了。」  
是啊，在忙碌的生活裡，  
這樣純粹的安靜與陪伴，  
竟變得那麼珍貴。  

---

## 🎂 為久違的朋友慶生  

傍晚時分，  
我們悄悄拿出藏好的蛋糕與蠟燭。  
「驚喜！」  
那一刻，笑聲與掌聲在小屋裡回蕩。  

看著朋友閉上眼許願，  
我忽然覺得——  
生日不只是慶祝年歲的增加，  
更像是一次「生命被重新擁抱」的儀式。  

也許我們都在成長，也都在改變，  
但友情，就是那道不變的光。  

---

## 🌇 小結  

這天的行程不算緊湊，  
卻有種「被時間溫柔對待」的感覺。  
從竹圍到桃園，再到台中，  
每一段路都帶著故事的重量。  

第一天結束時，  
我們笑著說：「這趟旅行，好像才剛開始。」  
而我心裡想的卻是——  
**或許真正的旅程，是重新找回那份心裡的平靜。**

---

## 📸 旅途剪影

{% assign gallery_path = page.gallery_dir %}
{% assign files = site.static_files | where_exp: "f", "f.path contains gallery_path" %}
<div class="gallery">
  {% for file in files %}
    {% if file.extname == ".jpg" or file.extname == ".png" or file.extname == ".jpeg" %}
      <a href="{{ file.path | relative_url }}" target="_blank">
        <img src="{{ file.path | relative_url }}" alt="Taichung Day1 {{ forloop.index }}" loading="lazy">
      </a>
    {% endif %}
  {% endfor %}
</div>

## 🎬 旅途影片剪影

<div class="video-gallery">
  <video controls playsinline preload="metadata" style="width:100%;border-radius:12px;box-shadow:0 2px 8px rgba(0,0,0,.2);margin-bottom:12px;">
    <source src="{{ '/assets/videos/2025-10-11-taichung-day1/4e5ee8e1-3893-4086-9424-4264e2855194.mp4' | relative_url }}" type="video/mp4">
  </video>
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

---
layout: home
title: "歡迎來到 Aster 的模擬作品集"
excerpt: "建築模擬 × 大氣科學 × 綠建築設計"
---

🌱 這裡是我記錄模擬學習、環控思考與綠建築實作的地方。  
你可以在這裡看到我的作品集、筆記、實驗紀錄，還有我正在學習的軌跡。

---
layout: home
title: "Aster 的模擬世界"
excerpt: "建築 × 環控 × 大氣 × 綠建築｜記錄我的作品與學習旅程"
header:
  overlay_image: /assets/images/header.jpg
  overlay_filter: 0.3
  caption: "📷 Photo by Aster"
---

歡迎來到我的模擬實驗室 🧪  
這裡紀錄著我跨領域學習的過程：  
建築模擬、室內環控、大氣科學與永續設計的交會點。

---

### 🌿 近期更新
{% for post in site.posts limit:3 %}
- 📌 [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%Y/%m/%d" }}
{% endfor %}

---

📬 [聯絡我](/contact/) ｜ 💼 [關於我](/about/)

---
layout: single
title: "關於我"
permalink: /about/
author_profile: true
---

嗨，我是 Aster。  
我目前主修大氣科學，正在往建築環境模擬的方向探索。

我熱愛模擬與資料視覺化，也正在自學綠建築設計、環控、能源模擬工具（像 EnergyPlus、Ladybug Tools）。  

目前目標是結合我在氣候與環境的專業，實作出具有永續性的建築模擬設計🌱

---

🧭 現在的我：
- 🌏 正在準備赴日交換與修士考試
- 📊 進行模擬工具的自學計畫
- 📖 練習中日英三語表達與筆記

---

🎯 想在這個網站紀錄：
- 我的模擬作品與過程
- 實作過的專案記錄
- 綠建築與環控筆記

# Navigation
nav:
  - title: "首頁"
    url: /
  - title: "關於我"
    url: /about/
  - title: "作品集"
    url: /portfolio/
  - title: "聯絡"
    url: /contact/

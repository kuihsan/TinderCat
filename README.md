# 🐾 Paw Preferences (TinderCat)

**Paw Preferences** (also known as *TinderCat*) is a fun, lightweight Unity WebGL game inspired by swipe-based apps.  
Swipe **right** if you like the cat, swipe **left** if you don’t — simple, cute, and addictive!

Built using **Unity** and powered by the **CATAAS (Cat as a Service) API**, the game dynamically loads random cat images from the internet.

---

## 🎮 Play the Game

👉 **Play it here:**  
https://kuihsan.github.io/TinderCat/

---

## ✨ Features

- 🐱 Random cat images loaded from CATAAS API  
- 👉 Swipe left / right mechanics (mouse & touch supported)
- 👍 Live Like / Dislike visual indicators
- 🔊 Sound effects for like & dislike actions
- 📊 End summary panel with animation (DOTween)
- 🔄 Restart button to replay
- 🌐 Built and deployed as **Unity WebGL**

---

## 🛠️ Built With

- **Unity** (C#)
- **Unity WebGL**
- **CATAAS API** – https://cataas.com
- **DOTween** (for UI animations)
- **Unity UI System**

---

## 📁 Project Structure (Key Scripts)

- `CatService.cs` – Handles cat image fetching from CATAAS
- `SwipeCard.cs` – Swipe logic for like/dislike
- `GameManager.cs` – Game flow and state handling
- `EndPanelController.cs` – Summary panel animation & restart
- `AudioManager.cs` – Like/Dislike sound effects

---

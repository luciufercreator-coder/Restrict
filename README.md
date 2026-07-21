# 🚀 𝓤𝓵𝓽𝓲𝓶𝓪𝓽𝓮 𝓣𝓮𝓵𝓮𝓰𝓻𝓪𝓶 𝓢𝔂𝓷𝓬 & 𝓑𝔂𝓹𝓪𝓼𝓼 𝓔𝓷𝓰𝓲𝓷𝓮 🚀

> *"Aise tools roz nahi bante. Yeh sirf ek bot nahi, Telegram files ka ek poora ecosystem hai!"* 

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB_Powered-green?style=for-the-badge&logo=mongodb)
![Pyrogram](https://img.shields.io/badge/Framework-Pyrogram_V2-red?style=for-the-badge&logo=telegram)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ultra_Fast-brightgreen?style=for-the-badge)

---

## 🤔 𝙒𝓱𝓪𝓽 𝓲𝓼 𝓽𝓱𝓲𝓼 𝓑𝓸𝓽? (Aasan Bhasha Me)
Maan lijiye aapke paas ek Telegram channel hai jisme **30 Lakh (3 Million)** files hain. Ab aapko woh saari files apne doosre channel me copy karni hain, lekin:
1. Puraana channel **Restricted** hai (Forwarding band hai).
2. Files ke naam me bohot saara **kachra (spam links/tags)** bhara hai.
3. Agar light chali gayi ya server band hua, toh aapko **shuru se** shuru karna padega.

**🦸‍♂️ Yeh Bot In Sabka Superhero Hai!**
Yeh bot restricted channels se files nikalega, unka naam ekdum saaf karega, aur unhe aapke channel me copy kar dega. Agar beech me bot band bhi ho gaya, toh **MongoDB** ki taqat se yeh wahi se resume karega jahan ruka tha!

---

## 💎 𝙆𝓮𝔂 𝙁𝓮𝓪𝓽𝓾𝓻𝓮𝓼 (Isme Kya Khas Hai?)

*   🔓 **Restricted Content Bypasser:**
    *   *Simple words:* Jo channel bolte hain *"You cannot forward this message"*, yeh bot unki files ko araam se download/upload karke aapko de dega.
*   🧠 **Smart Auto-Resume (Yadashat/Memory):**
    *   *Simple words:* Imagine aap TV par movie dekh rahe ho aur light chali jaye. Jab light aayegi, toh movie wahi se shuru hogi jahan ruki thi! Bot ka MongoDB bilkul waisa hi kaam karta hai. **Zero Duplicates, Zero Data Loss.**
*   🤖 **Multi-Instance Ready (Cloning):**
    *   *Simple words:* Ek akela insaan 30 lakh file uthayega toh thak jayega. Is bot ki aap 10 copy bana sakte ho. Bot-1 shuru ki files uthayega, Bot-2 beech ki, Bot-3 aage ki. Sab ek hi database se jude rahenge!
*   ✨ **Kachra Saaf Karnewala (Smart Renamer):**
    *   *Simple words:* Agar file ka naam hai `[Join @MySpam] Avengers.mp4`, toh bot isko khud padhega, kachra hatayega aur naya naam dega 👉 `Avengers (2012) [1080p].mp4`.
*   ⚡ **Live Watcher (Auto-Forwarding):**
    *   *Simple words:* Aap so rahe ho, aur source channel me kisi ne nayi movie daali. Yeh bot turant jaag jayega, file uthayega, naam change karega, aur aapke channel par bhej dega!

---

## 📋 𝓟𝓻𝓮-𝓡𝓮𝓺𝓾𝓲𝓼𝓲𝓽𝓮𝓼 (Shuru Karne Se Pehle Kya Chahiye?)

Is bot ko chalane ke liye aapke paas yeh 3 cheezein honi zaroori hain:

1.  **Telegram API ID & HASH** 🔑
    *   Jao [my.telegram.org](https://my.telegram.org) par.
    *   Apna phone number dalo aur login karo.
    *   "API development tools" par jao aur wahan se `API_ID` aur `API_HASH` copy kar lo.
2.  **Bot Token** 🤖
    *   Telegram par jao aur [**@BotFather**](https://t.me/BotFather) ko message karo.
    *   Type karo `/newbot` aur apne bot ka naam do.
    *   Woh aapko ek lamba sa password dega (jaise `12345:ABCDEF...`). Ise `BOT_TOKEN` kehte hain.
3.  **MongoDB URI** 🍃
    *   Jao [mongodb.com](https://www.mongodb.com/) par aur free account banao.
    *   Ek naya Database banao aur uska connection link copy kar lo (jo `mongodb+srv://...` se shuru hota hai). Yeh bot ki **Memory (Dimag)** hai.

---

## 🛠️ 𝓔𝓷𝓿𝓲𝓻𝓸𝓷𝓶𝓮𝓷𝓽 𝓥𝓪𝓻𝓲𝓪𝓫𝓵𝓮𝓼 (Settings Kaise Karein?)

Agar aap Render, Koyeb, ya VPS use kar rahe hain, toh aapko yeh settings (variables) dalni hongi:

| Variable Name | Iska Matlab Kya Hai? (Description) | Example (Kaise Dikhta Hai?) |
| :--- | :--- | :--- |
| `API_ID` | Telegram se mili hui apki ID | `1234567` |
| `API_HASH` | Telegram se mila hua lamba code | `0123456789abcdef0123456789abcdef` |
| `BOT_TOKEN` | @BotFather se mili hui chabi | `123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11` |
| `DB_URI` | MongoDB ka lamba link | `mongodb+srv://admin:pass@cluster0...` |
| `DB_NAME` | **Bahut Zaroori:** Har bot ka apna alag naam hona chahiye! | `SyncBot_1` ya `Worker_A` |
| `ADMINS` | Jo log is bot ko control kar sakte hain (unki User ID) | `123456789, 987654321` |
| `LOG_CHANNEL` | Ek private channel jahan bot saari report bhejega (ki kya copy hua, kya fail hua) | `-1001234567890` |

---

## 🎮 𝓑𝓸𝓽 𝓒𝓸𝓶𝓶𝓪𝓷𝓭𝓼 (Bot Ko Control Kaise Karein?)

### 👑 Admin / Setup Commands (Pehla Kadam)
*   ➡️ **`/login`**
    *   **Kaam:** Restricted channels se file nikalne ke liye aapko apna account bot me login karna padega. Yeh command aapse apka number aur OTP mangega.
    *   *Note: Yeh ekdum safe hai, data sirf aapke server par rehta hai.*
*   ➡️ **`/logout`**
    *   **Kaam:** Agar aap chahte ho ki bot ab aapke account ko use na kare, toh yeh type karo. Yeh aapki details safely delete kar dega.
*   ➡️ **`/status`**
    *   **Kaam:** Check karna ki bot ka pet (RAM) toh nahi bhar gaya? Server par kitni memory bachi hai, yeh sab yahan dikhega.
*   ➡️ **`/botstats`**
    *   **Kaam:** Dekhna ki kaun-kaun se users bot ko use kar rahe hain aur kitni downloading chal rahi hai.

### 📥 Processing & Syncing (Kaam Ki Baatein)
*   ➡️ **`/dl`** (Ya kisi link par reply karna)
    *   **Kaam:** Ek file ya hazaron files ko ek sath copy karna. 
    *   *Example Single:* `/dl https://t.me/c/123456/101`
    *   *Example Batch:* `/dl https://t.me/c/123456/101 - 500` (Iska matlab msg id 101 se lekar 500 tak sab utha lo!)
*   ➡️ **`/cancel`**
    *   **Kaam:** Galti se galat channel ka link de diya? Is command ko dabao, ek list khulegi, aur aap downloading ko beech me rok sakte ho!

### 👀 Live Watcher Engine (Jaasoos Bot)
*   ➡️ **`/watch [link]`**
    *   **Kaam:** Bot ko bolo ki is channel par nazar rakhe. Jaise hi admin wahan movie daalega, bot usko aapke channel me chura layega! 🥷
*   ➡️ **`/watchers`** (ya `/list`)
    *   **Kaam:** Check karna ki bot ne kahan-kahan apni aankhein gadhayi hui hain.
*   ➡️ **`/unwatch [source_id]`**
    *   **Kaam:** Kisi channel se nazar hatana (monitoring band karna).
*   ➡️ **`/removetarget`**
    *   **Kaam:** Agar aapne bot ko kaha tha ki file 3 alag-alag group me bhejo, aur ab ek group ko hatana hai, toh yeh command use karo.

---

## 🏗️ 𝓜𝓾𝓵𝓽𝓲-𝓑𝓸𝓽 𝓢𝓽𝓻𝓪𝓽𝓮𝓰𝔂 (30 Lakh Files Ka Jadoo)

Telegram ki ek limit hoti hai. Ek single account din me hazaron files transfer nahi kar sakta. **Toh hum kya karein?** Hum banayenge Bot ki Sena (Army of Bots)! 🤖🤖🤖

**Step-by-Step Magic Guide:**
1. Render ya Koyeb par 5 alag-alag Apps (Web Services) banao.
2. Sabme yahi same GitHub ka link daal do.
3. Sabme `API_ID`, `API_HASH` aur `DB_URI` ekdum **SAME** dalo.
4. **CHAMATKAR YAHAN HAI:** Har app ko ek naya `@BotFather` token do aur sabse zaroori baat... **Har app ka `DB_NAME` alag do!**
    *   Bot 1 = `DB_NAME=Cluster_1`
    *   Bot 2 = `DB_NAME=Cluster_2`
    *   Bot 3 = `DB_NAME=Cluster_3`
5. Ab Bot 1 ko command do: *File 1 se 50,000 copy karo.*
6. Bot 2 ko command do: *File 50,001 se 1,00,000 copy karo.*
7. **BHOOM! 💥** Paancho bots ek sath daudenge, aapas me nahi takrayenge, aur mahino ka kaam kuch dino me khatam ho jayega!

---

## 🚨 𝓣𝓻𝓸𝓾𝓫𝓵𝓮𝓼𝓱𝓸𝓸𝓽𝓲𝓷𝓰 (Agar Kuch Gadbad Ho Jaye?)

1.  **Bot ruk-ruk kar chal raha hai?**
    > Iska matlab Telegram ne aapko **"FloodWait"** de diya hai (bata diya ki bahut tez chal rahe ho). Darna nahi, bot khud thodi der so jayega aur phir wapas shuru ho jayega!
2.  **`AuthKeyUnregistered` Error aa raha hai?**
    > Iska matlab aapka Telegram Session expire ho gaya hai ya aapne account se bot ko nikal diya hai. Bas `/logout` type karo aur dobara `/login` karo.
3.  **Logs me `DUPLICATE SKIPPED` dikh raha hai?**
    > Yeh koi error nahi hai! Yeh bot ki smartness hai. Woh bata raha hai ki *"Bhai, yeh file main pehle hi copy kar chuka hu, toh main aage badh raha hu apna time bacha kar!"*

---

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20By-A%20Pro%20Developer-ff69b4?style=for-the-badge">
  <br>
  <b><i>"Code is poetry, and this bot is a masterpiece."</i></b>
</p>

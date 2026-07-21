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

<div align="center">
  
# 🌟 𝕿𝖍𝖊 𝖀𝖑𝖙𝖎𝖒𝖆𝖙𝖊 𝕿𝖊𝖑𝖊𝖌𝖗𝖆𝖒 𝕾𝖞𝖓𝖈 & 𝕭𝖞𝖕𝖆𝖘𝖘 𝕰𝖓𝖌𝖎𝖓𝖊 🌟
### 𝓨𝓸𝓾𝓻 𝓟𝓮𝓻𝓼𝓸𝓷𝓪𝓵, 𝓣𝓲𝓻𝓮𝓵𝓮𝓼𝓼 𝓓𝓪𝓽𝓪-𝓜𝓸𝓿𝓲𝓷𝓰 𝓢𝓾𝓹𝓮𝓻𝓱𝓮𝓻𝓸! 🦸‍♂️

<br>

[![Python Version](https://img.shields.io/badge/🐍_Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![MongoDB](https://img.shields.io/badge/🍃_Database-MongoDB_Atlas-green?style=for-the-badge&logo=mongodb)](https://www.mongodb.com/)
[![Pyrogram](https://img.shields.io/badge/✈️_Framework-Pyrogram_V2-red?style=for-the-badge&logo=telegram)](https://docs.pyrogram.org/)
[![License](https://img.shields.io/badge/📜_Licence-MIT-purple?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Server](https://img.shields.io/badge/☁️_Server-Render_%7C_Koyeb-orange?style=for-the-badge)](https://render.com/)
[![Uptime](https://img.shields.io/badge/⚡_Uptime-99.9%25-brightgreen?style=for-the-badge)]()

<br>

> *"Imagine possessing a robotic assistant that never sleeps, never complains, and can seamlessly shift colossal datasets for you with absolute zero errors. That is precisely what you are looking at right now."*

</div>

---

<br>

## 📖 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 1: 𝓦𝓱𝓪𝓽 𝓘𝓼 𝓣𝓱𝓲𝓼 𝓜𝓪𝓰𝓲𝓬? (Explained Simply) 🍼

Let us paint a picture. Imagine you have a massive treasure chest (a Telegram Channel) filled with countless gold coins (movies, documents, and files). You want to move all of these into your very own, brand-new VIP vault. 

However, you immediately face three massive headaches:
1. **The Vault is Locked (Restricted Content) 🔒:** The old channel has disabled forwarding. You cannot simply select and share the files. They are trapped.
2. **The Coins are Filthy (Spam Filenames) 🗑️:** Every single file has a hideous name attached to it, filled with spam links, adverts, and rubbish text (e.g., `[Join @SpamHub] The_Matrix_1080p.mkv`).
3. **The Threat of Blackouts (Server Crashes) 😴:** If you start copying these manually or using a basic script, and your server crashes or loses power, you have to start all over again from file number one. It is an absolute nightmare!

**🔥 𝔈𝔫𝔱𝔢𝔯 𝔗𝔥𝔢 𝔖𝔶𝔫𝔠 𝔅𝔬𝔱! (Our Magical Solution) 🔥**
This bot is your bespoke digital superhero. It covertly infiltrates that restricted treasure chest, downloads each file directly from Telegram's servers, gives it a "smart wash" (scrubbing away all the spam and renaming it beautifully), and safely deposits it into your new channel. 

The most brilliant part? It has a photographic memory powered by **MongoDB**. If the server crashes halfway through, the bot doesn't panic. When it wakes up, it remembers *exactly* where it left off and resumes instantaneously. **No missing files. No duplicates. Total peace of mind.**

<br>

---

<br>

## ✨ 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 2: 𝓣𝓱𝓮 𝓢𝓾𝓹𝓮𝓻𝓹𝓸𝔀𝓮𝓻𝓼 (Deep Dive Into Features) 🦸‍♂️

This is not merely a script; it is a fully-fledged data ecosystem. Let us break down its core capabilities so you understand exactly what is happening under the bonnet.

### ❶ 🛡️ 𝕿𝖍𝖊 𝕭𝖞𝖕𝖆𝖘𝖘𝖊𝖗 𝕾𝖍𝖎𝖊𝖑𝖉 (Restricted Content Unlocker)
Telegram's privacy restrictions are notoriously strict. If an admin disables forwarding, standard users cannot even screen-record the content. 
*   **How it works:** This bot acts on behalf of your account (using a Userbot session). It streams the locked files directly from Telegram's binary data servers, bypassing the front-end restrictions entirely. Telegram remains completely unaware that the file has been cloned! 🕵️‍♂️

### ❷ 🧠 𝕿𝖍𝖊 𝕸𝖔𝖓𝖌𝖔𝕯𝕭 𝕭𝖗𝖆𝖎𝖓 (Stateful Auto-Resume)
Imagine transferring an immense dataset, only for your server to randomly restart right near the end. Older bots would force you to start from zero. 
*   **How it works:** After every single successful transfer, this bot logs a tiny note in its cloud brain (MongoDB): *"I have successfully processed this specific message ID."* 
*   When it boots back up, it asks the database, *"Where were we, mate?"* and resumes seamlessly from the very next ID. **100% Reliability.** 🧘‍♂️

### ❸ 🤖 𝕸𝖚𝖑𝖙𝖎-𝕮𝖑𝖔𝖓𝖊 𝕬𝖗𝖒𝖞 (Parallel Scaling Architecture)
If you attempt to move a monumental amount of files using just one account, Telegram will throw a fit and temporarily ban you (known as a `FloodWait` error).
*   **How it works:** You can deploy multiple clones of this bot across different servers. You assign Bot A to handle the first half of a channel, and Bot B to handle the second half. Because they are all connected to the same database, they work together in perfect harmony. It is scaling made simple! ⚡

### ❹ 🧼 𝕿𝖍𝖊 𝖂𝖆𝖘𝖍𝖎𝖓𝖌 𝕸𝖆𝖈𝖍𝖎𝖓𝖊 (Extreme Smart Renamer)
We have all seen horrendous filenames like: `@RubbishChannel_The_Dark_Knight_2008_Hindi_1080p_Join_Now.mkv` 🤢
*   **How it works:** Hidden within this bot is a highly advanced Regex Engine (a smart text-recognition tool). It automatically scans the filthy filename and extracts:
    *   *The actual title:* 👉 The Dark Knight
    *   *The release year:* 👉 (2008)
    *   *The resolution:* 👉 [1080p]
    *   *The audio language:* 👉 [Hindi]
*   **The Final Result:** `The Dark Knight (2008) [Hindi] 1080p.mkv` 😍 (Absolutely spotless, giving your channel a premium Netflix-style aesthetic).

### ❺ 👀 𝕿𝖍𝖊 𝕷𝖎𝖛𝖊 𝖂𝖆𝖙𝖈𝖍𝖊𝖗 (Instant Auto-Routing)
*   **How it works:** You can command the bot to keep a permanent, 24/7 watch on any source channel. The very second a new file is uploaded there, your bot will detect it, clean the metadata, and instantly route it to your target channels. 

<br>

---

<br>

## 🎒 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 3: 𝓖𝓪𝓽𝓱𝓮𝓻𝓲𝓷𝓰 𝓣𝓱𝓮 𝓘𝓷𝓯𝓲𝓷𝓲𝓽𝔂 𝓢𝓽𝓸𝓷𝓮𝓼 (Prerequisites) 💎

Before we can awaken the bot, you need to collect three essential digital keys. Do not worry; this is incredibly straightforward. Just follow these steps:

### 🔴 Stone 1: API_ID & API_HASH (Your Telegram VIP Pass)
1. Open a web browser on your phone or PC and head over to: [👉 my.telegram.org](https://my.telegram.org/)
2. Log in using your mobile number (ensure you include the country code, e.g., `+447123456789`).
3. Telegram will send a login code to your app. Pop that code into the browser.
4. Click on the section titled **"API development tools"**.
5. You will see a form. Fill in the "App Title" and "Short Name" with anything you fancy (e.g., `MySyncBot`).
6. Click submit. You will instantly be rewarded with your `API_ID` (a short string of numbers) and your `API_HASH` (a long mix of letters and numbers). Keep these safe and secret! 🤫

### 🟢 Stone 2: BOT_TOKEN (The Remote Control)
1. Open your Telegram app and search for the official [👉 @BotFather](https://t.me/BotFather).
2. Start a chat with him and type the command: `/newbot`
3. He will ask you for a name. Call it something cool like: `Super Sync Engine`
4. Next, he wants a username (it MUST end in 'bot'). Try something like: `MySync_bot`
5. If successful, BotFather will hand you a long, secure token (e.g., `1234567:AAxyz...`). This is your **BOT_TOKEN**! 🔑

### 🍃 Stone 3: MongoDB URI (The Bot's Cloud Brain)
1. Head over to [👉 mongodb.com](https://www.mongodb.com/cloud/atlas/register) in your browser.
2. Sign up for a free account (using Google is the fastest way).
3. Create a new "Cluster" (ensure you select the `M0 Free` tier so you don't pay a penny).
4. It will prompt you to create a "Database User". Make a simple username and a password. **Write this password down!**
5. For "Network Access", select the option that says **"Allow Access from Anywhere"** (which looks like `0.0.0.0/0`). This ensures your bot can connect from any server in the world.
6. Finally, click **"Connect"** ➔ **"Drivers"** ➔ and copy the long connection string provided.
7. *Crucial step:* In that string, replace the word `<password>` with the actual password you just created. This entire link is your **DB_URI**! 🧠

<br>

---

<br>

## ⚙️ 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 4: 𝓣𝓱𝓮 𝓜𝓪𝓼𝓽𝓮𝓻 𝓒𝓸𝓷𝓽𝓻𝓸𝓵 𝓟𝓪𝓷𝓮𝓵 (Environment Variables) 🎛️

When you deploy this bot on a cloud service like Render, Koyeb, Heroku, or a VPS, you will be asked to fill in "Environment Variables". Think of this as the bot's settings menu. You must fill these out accurately!

| 𝕍𝕒𝕣𝕚𝕒𝕓𝕝𝕖 ℕ𝕒𝕞𝕖 | 𝕎𝕙𝕒𝕥 𝔼𝕩𝕒𝖼𝕥𝕝𝕪 𝕀𝕤 𝕀𝕥? (Description) | 𝔼𝕩𝕒𝕞𝕡𝕝𝕖 (What it looks like) |
| :--- | :--- | :--- |
| `API_ID` | Your VIP pass from Stone 1. | `2345678` |
| `API_HASH` | The long secret code from Stone 1. | `abcdef1234567890abcdef1234567890` |
| `BOT_TOKEN` | The remote control key from BotFather (Stone 2). | `1234567890:ABCdefGHIjklMNOpqrSTUvwxYZ` |
| `DB_URI` | The brain connection link from MongoDB (Stone 3). | `mongodb+srv://admin:MyPass123@cluster0.abc.mongodb.net/?retryWrites=true` |
| `DB_NAME` | A unique name for this specific bot's memory sector. <br>**PRO TIP:** If running multiple bots, this MUST be different for each one! | `WorkerBot_1` |
| `ADMINS` | A list of user IDs who are authorised to control the bot. Separate multiple admins with a comma. | `123456789, 987654321` |
| `LOG_CHANNEL` | Create a private Telegram channel and add the bot as an admin. Put the channel ID here. The bot will send all its final invoices and crash reports here! | `-1001234567890` |

<br>

---

<br>

## 🪄 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 5: 𝓣𝓱𝓮 𝓜𝓪𝓰𝓲𝓬 𝓢𝓹𝓮𝓵𝓵𝓼 (Bot Commands In Detail) 📜

To command this robotic marvel, you must utilise specific instructions. Each command triggers a unique function within the ecosystem. 

### 👑 𝕿𝖍𝖊 𝕸𝖆𝖘𝖙𝖊𝖗 𝕶𝖊𝖞𝖘 (Admin Setup Commands)
These commands are strictly reserved for authorised administrators. If an unauthorised user attempts to use them, the bot will silently ignore them.

*   🔑 **`/login` (Present Your Credentials)**
    *   **Purpose:** To extract files from highly restricted private channels, you must log your Telegram account into the bot. This command will politely request your phone number and OTP to generate a secure Userbot session.
    *   **How To Use It:**
        1. Type `/login` and hit send.
        2. The bot will request your phone number. Include your country code (e.g., `+447987654321`).
        3. Telegram will send a 5-digit OTP to your app.
        4. **⚠️ CRUCIAL INSTRUCTION:** You MUST send the OTP with spaces. If the code is `12345`, you must type it as `1 2 3 4 5`. (If you send it without spaces, Telegram's security systems will block the attempt).
        5. If your account possesses a Two-Step Verification Password, the bot will request it. Enter it, and you are successfully authenticated! 🎉

*   🚪 **`/logout` (Terminate Session)**
    *   **Purpose:** If you wish to revoke the bot's access to your account, or if you simply wish to switch accounts, execute this command. It safely and permanently wipes your login credentials from the database. 🛡️

*   📊 **`/status` (Hardware Health Check)**
    *   **Purpose:** Curious about how the server is holding up? This command provides a real-time dashboard displaying:
        *   *RAM Usage:* Is the memory overflowing?
        *   *CPU Load:* Is the processor overheating?
        *   *Uptime:* How long has the bot been running continuously?
        *   *Active Tasks:* A live list of every ongoing download and upload.

*   📈 **`/botstats` (User Analytics)**
    *   **Purpose:** If you have permitted colleagues or friends to utilise the bot, this command will generate a comprehensive report of who is currently logged in and precisely what tasks they are executing. 👀

<br>

### 📥 𝕿𝖍𝖊 𝕿𝖗𝖆𝖓𝖘𝖕𝖔𝖗𝖙𝖊𝖗𝖘 (Processing Commands)
These are your primary tools for shifting vast quantities of data.

*   🚀 **`/dl` (Direct Download/Forward)**
    *   **Purpose:** Your absolute best friend. You can use this in two highly effective ways:
        *   **Single File:** Copy the link of any restricted file and send it to the bot (or reply to a link with `/dl`). The bot will instantly fetch it, clean it, and present it to you.
        *   **Batch Processing (The True Magic ✨):** If you require a massive sequential scrape! Simply send a link formatted with a numerical range:
            👉 `https://t.me/c/12345678/101 - 500`
        *   The bot will ask where you want the files deposited. Once selected, it will systematically harvest all 400 files, scrub their metadata, and deliver them. Put the kettle on and relax! ☕

*   🛑 **`/cancel` (Emergency Stop)**
    *   **Purpose:** Did you accidentally input the wrong channel link or specify an incorrect range? Do not panic. Simply type `/cancel`. A beautifully structured menu will appear, displaying all active tasks. Tap the one you wish to terminate, and the bot will safely halt the process. 🛑

<br>

### 🦉 𝕿𝖍𝖊 𝕾𝖎𝖑𝖊𝖓𝖙 𝕲𝖚𝖆𝖗𝖉𝖎𝖆𝖓𝖘 (Live Watcher Engine)
These commands allow for total automation. Set them up once, and the bot will work tirelessly in the background.

*   👀 **`/watch [Link]` (Install a Digital CCTV Camera)**
    *   **Purpose:** Provide the bot with a source channel link. The bot will embed itself as a silent listener. The absolute second an administrator uploads a new file, the bot will intercept it, clean it, and instantly route it to your specified destination!
    *   *During setup, you will configure:*
        1. The Target Destination.
        2. The Forwarding Delay (3 seconds is highly recommended to prevent bans).
        3. Content Filters (e.g., Ignore images and text, only forward Videos and Documents).

*   📋 **`/watchers` or `/list` (View Active Surveillance)**
    *   **Purpose:** Have you forgotten which channels you are currently monitoring? This command generates a pristine list of all active watchers and their corresponding routing configurations. 📷

*   🗑️ **`/unwatch [Source_ID]` (Dismantle Camera)**
    *   **Purpose:** If you wish to cease monitoring a specific channel, locate its ID via the `/watchers` command and execute `/unwatch -100XXXXX`. Surveillance terminated.

*   🎯 **`/removetarget` (Sever a Routing Path)**
    *   **Purpose:** If a single source channel was routing files to three separate destinations, and you wish to sever one of those connections, use `/removetarget [Source_ID] [Dest_ID]`. 

<br>

---

<br>

## 🏗️ 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 6: 𝓣𝓱𝓮 𝓒𝓵𝓸𝓷𝓮 𝓐𝓻𝓶𝔂 (Deployment Strategy) 🤖🤖🤖

Telegram enforces strict rate limits. A solitary account simply cannot transfer immense datasets in a single day. 
**The Solution?** We construct an Army of Bots! ⚔️

**𝔖𝔱𝔢𝔭-𝔟𝔶-𝔖𝔱𝔢𝔭 𝔐𝔲𝔩𝔱𝔦-𝔅𝔬𝔱 𝔊𝔲𝔦𝔡𝔢:**

1.  **Multiple Accounts:** Acquire access to 3-5 separate Telegram accounts. (Distributing the workload prevents any single account from facing a ban).
2.  **Multiple Bots:** Visit @BotFather and create distinct bots (Bot1, Bot2, Bot3). Keep their unique tokens handy.
3.  **Deploy Instances:** Wherever you are hosting (Render, VPS, Koyeb), create separate application instances for each bot.
4.  **The Secret Sauce (DB_NAME):** When filling out your Environment Variables, pay absolute attention to this:
    *   Use the **EXACT SAME** `DB_URI` for all of them (so they share a unified brain).
    *   However, give each app a **COMPLETELY DIFFERENT** `DB_NAME`. (e.g., `Cluster_Alpha`, `Cluster_Beta`). If they share a `DB_NAME`, they will overwrite each other's progress! 💥
5.  **Attack!** Instruct Bot 1 (using Account 1) to process files *1 to 50,000*. Instruct Bot 2 (using Account 2) to process *50,001 to 100,000*.
    *The Result:* Your cloning speed multiplies exponentially, completing weeks of processing in mere days! 🚀🚀

<br>

---

<br>

## 🚑 𝓒𝓱𝓪𝓹𝓽𝓮𝓻 7: 𝓣𝓱𝓮 𝓔𝓶𝓮𝓻𝓰𝓮𝓷𝓬𝔂 𝓚𝓲𝓽 (Troubleshooting & FAQs) 🛠️

Even the most advanced systems occasionally face hiccups. If something appears to go awry, consult this manual before panicking:

*   **❓ Question:** The bot has suddenly stopped transferring files and the progress bar is frozen. Is it broken?
    *   **💡 Answer:** Absolutely not. This is known as a **"FloodWait"**. When you request thousands of files consecutively, Telegram's servers politely demand that you slow down. The bot is highly intelligent; it will automatically put itself to sleep for the exact duration requested by Telegram, and seamlessly resume the moment the restriction lifts. Grab a biscuit and let it rest! 🍪

*   **❓ Question:** The Log Channel is repeatedly stating `⏭ DUPLICATE SKIPPED!`. What does this mean?
    *   **💡 Answer:** This is a feature, not a bug! If you restart the bot or accidentally submit a duplicate range, the MongoDB brain informs the bot: *"We have already successfully transferred this file."* The bot skips it to save bandwidth and time. Brilliant, isn't it? 👏

*   **❓ Question:** I am seeing a `🧹 CLEANUP ALERT: Deleted stuck files` message in the logs. Should I be worried?
    *   **💡 Answer:** Not at all. During the download process, files are temporarily cached on your server. If a massive file gets stuck or your server is running low on storage space, the built-in watchdog automatically deletes stagnant files to prevent a total server crash. It is actively protecting your infrastructure! ❤️

*   **❓ Question:** The bot is throwing an `AuthKeyUnregistered` or `Session Expired` error. How do I fix it?
    *   **💡 Answer:** This indicates that Telegram has forcefully terminated the Userbot session, or you manually logged the bot out via your active sessions menu. 
    *   *The Fix:* Simply type `/logout` to clear the old corrupted data, and then execute `/login` to generate a fresh, secure session. Done! ✅

<br>

---

<br>

<div align="center">

### 🏆 𝕿𝖍𝖊 𝕸𝖆𝖘𝖙𝖊𝖗𝖕𝖎𝖊𝖈𝖊 𝕮𝖔𝖓𝖈𝖑𝖚𝖘𝖎𝖔𝖓 🏆

*“In a digital landscape filled with endless data, this bot serves as the ultimate, unyielding bridge connecting restricted vaults directly to your open kingdom.”*

<br>

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)]()
[![Open Source Love svg1](https://img.shields.io/badge/Open%20Source-%E2%9D%A4%EF%B8%8F-red.svg?style=for-the-badge)]()

**Engineered with precision, dedication, and copious amounts of ☕ by a Professional Developer.**
<br>
*(You are entirely welcome to fork, clone, or deploy this code, but do prepare yourself to be absolutely astonished by its sheer velocity!)* 🚀🔥

</div>

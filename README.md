<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<p align="center">
  <a href="####"><img src="http://readme-typing-svg.herokuapp.com?color=cyan&center=true&vCenter=true&multiline=false&lines=`🔰𝗥𝗮𝗵𝗮𝘁_𝗕𝗼𝘁🔰`" alt="">
</p>
    <a><img       
src='https://i.imgur.com/LyHic3i.gif'/></a>

-------

<img src='https://i.imgur.com/PB8MNoc.jpeg'/>

-------

_______
### <br>   ❖ DEPLOY_WORKFLOWS ❖
```
name: Node.js CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]
        # See supported Node.js release schedule at https://nodejs.org/en/about/releases/

    steps:
    # Step to check out the repository code
    - uses: actions/checkout@v2

    # Step to set up the specified Node.js version
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v2
      with:
        node-version: ${{ matrix.node-version }}

    # Step to install dependencies
    - name: Install dependencies
      run: npm install

    # Step to run the bot with the correct port
    - name: Start the bot
      env:
        PORT: 8080
      run: npm start
```

___
## ⚙️Installation⚙️

### 1. Repository Clone Karein

```bash
https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX.git
```

### 2. Dependencies Installed

```bash
npm install
```

### 3. Facebook Appstate Add Do it

- Paste your Facebook account's ```appstate.json``` file in the root folder.

- Ensure that the file is valid and updated.

### 4. Run the Bot

```bash
node Xrahat.js
```

---
###  🔰𝗥𝗮𝗵𝗮𝘁_𝗕𝗼𝘁🔰
❖ ***`বট রান দিতে সমস্যা হলে ফেসবুকে যোগাযোগ করো
❖👇নিচে আইডির লিঙ্ক আছে👇❖`** ❖

----------
## Facebook ID:👉 <a href="https://www.facebook.com/share/14N3ACfd4fM/">Link</a>

<p align="center">
  <a href="#"><img src="http://readme-typing-svg.herokuapp.com?color=cyan&center=true&vCenter=true&multiline=false&lines=`🔰𝗥𝗮𝗵𝗮𝘁_𝗕𝗼𝘁🔰`" alt="">
</p>

## License

This project is licensed under the GNU General Public License v3.0 or later - see the [COPYING](./COPYING) file for details.




[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
> ⚠️ This is a modified version. See License section below for usage rights.

---










<br><br>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rxmaria761&langs_count=8&theme=react&bg_color=151515" />
</p>
<p align="center">
<a href="https://github.com/rxmaria761"><img alt="MARIA BOT Github Stats"
    src="https://github-readme-stats.vercel.app/api?username=rxmaria761&show_icons=true&count_private=true&theme=react&bg_color=151515" /></a>
<p align="center"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=rxmaria761&theme=black-ice"
    alt="rX Abdullah"/></p>

<br/>


<br />
<p align="center">
    <a href="https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX">
        <img src="https://i.imgur.com/I0kvVfu.jpeg" alt="Logo">
    </a>

<h3 align="center">MARIA CHATBOT</h3>

<p align="center">
    A simple Facebook Messenger Bot made by me (rX Abdullah).
    <br />
    <br />
    <a href="https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX/issues">Report Bug</a>
    ·
    <a href="https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX/pulls">Request Feature</a>
    </p>
</p>

<p align="center">
	<img alt="size" src="https://img.shields.io/github/repo-size/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX.svg?style=flat-square&label=size">
	<img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=red&label=code%20version&prefix=v&query=%24.version&url=https%3A%2F%2Fraw.githubusercontent.com%2FmiraiPr0ject%2Fmiraiv2%2Fmaster%2Fpackage.json&style=flat-square">
	<a href="https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX/commits"><img alt="commits" src="https://img.shields.io/github/commit-activity/m/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX.svg?label=commit&style=flat-square"></a>
    	<img alt="visitors" src="https://visitor-badge.laobi.icu/badge?page_id=rxabdullah007.MIRAI-MESSENGER-BOT-BY-RX">
	
</p>

## License

This project is licensed under the GNU General Public License v3.0 or later - see the [COPYING](./COPYING) file for details.




[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


## 🚀 Features

-  Chat ai
-  smart telking
- etc

---

##

- Facebook Messenger chatbot functionality
- Facebook login through `appstate.json` (cookies)
- 150+ built-in commands
- Easily customizable structure for developers


## 🧰 Requirements

- **Node.js version 18 or above (18+)**
- Facebook `appstate.json` file (login cookie JSON)


## ⚙️ Installation

### 1. Repository Clone Karein

```bash
https://github.com/rxabdullah007/MIRAI-MESSENGER-BOT-BY-RX.git
```

### 2. Dependencies Installed

```bash
npm install
```

### 3. Facebook Appstate Add Do it

- Paste your Facebook account's `appstate.json` file in the root folder.

- Ensure that the file is valid and updated.

### 4. Run the Bot

```bash
node Rxabdullah.js
```

---

## 🚀 Usage

- The bot will login to your Facebook account as soon as it is launched.

- It listens to Messenger chats in the background.

- You can use available commands like:

```
!help
!up
!song [name]
!info
```
- The bot automatically tracks group and user data (if the database is configured).

---

## 🛠️ Tech Used

- HTML5  
- CSS3  
- JavaScript (vanilla)

---

## 👨‍💻 Owner Info

**Name:** RX Abdullah  
**Age:** 17+  
**Class:** Intermediate  
**Lives in:** Mohammadpur, Dhaka  
**Born in:** Rajshahi  
**Hobbies:** Coding, Riding Bikes  
**Fav Bike:** KTM RC

---

## 🌐 Live Demo

You can preview the page by opening the HTML file in any browser.

🔗 Messenger: [Message RX Abdullah](https://m.me/rxabdullah007)

---

## 📁 File Structure


---

## ✨ OWNAR PHOTO

![Preview](https://i.postimg.cc/nhxxB67n/IMG-0793.jpg)

---

## 💬 Thanks for visiting!

Made with 💚 by **RX Abdullah**

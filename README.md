
<div class="neon-border" align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.herokuapp.com?font=Rockstar-ExtraBold&color=FF10F0&lines=PINK+VENOM+MULTI+DEVICE" alt="Typing SVG">
    </a>
</div>

<p align="center">
    <img src="https://i.postimg.cc/JzHb8pfV/IMG-20241124-WA0139.jpg" width="100%" style="margin-left: auto; margin-right: auto; display: block;">
</p>

<p align="center">
    <a href="https://github.com/ayooh-me">
        <img title="Author" src="https://img.shields.io/badge/AUTHOR-Ayodya%20Vichakshana-red.svg?style=for-the-badge&logo=github">
    </a>
</p>

<hr>

<p align="center">
    <img src="https://img.shields.io/badge/Maintaned%3F-Actively%20Developed-blue?style=flat-square" alt="Maintained?">
</p>

<hr>

<p align="center">
    <a href="https://whatsapp.com/channel/link">
        <img src="https://img.shields.io/badge/CHANNEL-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Whatsapp Channel">
    </a>
    <a href="https://wa.me/94759874797">
        <img src="https://img.shields.io/badge/OWNER%20BOT-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Owner BOT">
    </a>
</p>
<h2>乂 S T E P S - F O R - C R E A T E - T H E - B O T </h2>


1. Fork the repo
    <br>
<a href='https://github.com/ayooh-me/Pink-Venom-MD/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork Repo-100000?style=for-the-badge&logo=scan&logoColor=FF10F0&labelColor=FF10F0&color=black'/></a>


2. Get session id by (SCANNING QR)
    <br>
<a href='https://session-hyper-hackers.vercel.app/qr' target="_blank"><img alt='Q R - C O D E' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=FF10F0&labelColor=FF10F0&color=black'/></a>


2. Get session id by (PAIRING CODE)
    <br>
<a href='https://session-hyper-hackers.vercel.app/pair' target="_blank"><img alt='P A I R - C O D E' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=FF10F0&labelColor=FF10F0&color=black'/></a>

<h2> 乂 N O T E - B E F O R E - U S I N G !!- EN</h2>
<ul>
    <li>🔹 Add Your SESSION ID To Your <code>config.js</code></li>
    <li>🔹 Also Add Your Github Auth Token (without gph_) And Github User Name To <code>config.js</code></li>
</ul>

<hr>

<h2>乂 N O T E - B E F O R E - U S I N G !! -SI</h2>
<ul>
    <li>🔹 </code>Fork</code> / Use This </code>Template</code> button එක Click කරන්න.</li>
    <li>🔹 ඔබේ <code>SESSION ID</code>, Github Auth Token(gph_ නැතිව) සහ Github User Name: <code>config.js</code> එකට එක් කරන්න.</li>
</ul>

### 乂 E D I T - T H E - CONFIG.JS

There are 1 configuration file namely ```config.js``` adjust it before installing.

```Javascript

const fs = require('fs');
if (fs.existsSync('config.env')) require('dotenv').config({ path: './config.env' });

function convertToBool(text, fault = 'true') {
    return text === fault ? true : false;
}

module.exports = {
    SESSION_ID: process.env.SESSION_ID === undefined ? '94759874797' : process.env.SESSION_ID, //ADD YOUR SESSION ID
    GITHUB_USER_NAME: process.env.GITHUB_USER_NAME === undefined ? '' : process.env.GITHUB_USER_NAME, //ADD YOUR GITHUB USERNAME
    GITHUB_AUTH_TOKEN: process.env.GITHUB_AUTH_TOKEN === undefined ? '' : process.env.GITHUB_AUTH_TOKEN, //ADD YOUR GITHUB AUTH TOKEN WITHOUT gph_ ex- G5OxxdvEbiBPWxm4A0xypQGlyCr4FS267ifz
    WORK_TYPE: process.env.WORK_TYPE === undefined ? 'public' : process.env.WORK_TYPE, //ONLYME / ONLYGROUP OR PUBLIC
    AUTO_READ_STATUS: process.env.AUTO_READ_STATUS === undefined ? 'true' : process.env.AUTO_READ_STATUS, //TRUE OR FALSE
    PRESENCE: process.env.PRESENCE === undefined ? `available` : process.env.PRESENCE, //AVAILABLE, COMPOSING, RECORDING OR UNAVAILABLE
    ALIVE: process.env.ALIVE === undefined ? `default` : process.env.ALIVE, //YOUR ALIVE MESSAGE OR SET IT TO defeault
    OWNER: process.env.OWNER === undefined ? `94759874797` : process.env.OWNER, //BOTS OWNER NUMBER
    PREFIX: process.env.PREFIX === undefined ? '.' : process.env.PREFIX, //BOTS PREFIX 
    MAX_SIZE: process.env.MAX_SIZE === undefined ? '200' : process.env.MAX_SIZE, //MAX UPLOAD SIZE
    LOGO: process.env.LOGO === undefined ? `https://i.postimg.cc/JzHb8pfV/IMG-20241124-WA0139.jpg` : process.env.LOGO, //ALIVE IMAGE URL
    ANTI_LINK: process.env.ANTI_LINK === undefined ? 'true' : process.env.ANTI_LINK, //TRUE OR FALSE
    ANTI_BAD: process.env.ANTI_BAD === undefined ? 'true' : process.env.ANTI_BAD, //TRUE OR FALSE
    ANTI_BOT: process.env.ANTI_BOT === undefined ? 'true' : process.env.ANTI_BOT, //TRUE OR FALSE
    READ_MESSAGE: process.env.READ_MESSAGE === undefined ? 'true' : process.env.READ_MESSAGE, //SET cmd FOR ONLY READ COMMANDS OR SET all FOR READ ALL MESSAGES
    ANTI_CALL: process.env.ANTI_CALL === undefined ? 'false' : process.env.ANTI_CALL, //TRUE OR FALSE
    AUTO_BLOCK: process.env.AUTO_BLOCK === undefined ? 'false' : process.env.AUTO_BLOCK //SET cmd FOR ONLY BLOCK INBOX COMMANDS USED USERS OR SET all FOR BLOCK ALL IINBOX USERS
};

```

### 乂 D E P L O Y - P L A T F O R M S

**Option 1: Deploy on Heroku**
1. [Create an Account on Heroku](https://signup.heroku.com/) if you haven’t already.
2. Click the button below to deploy directly on Heroku:
   <br>
   <a href='https://heroku.com/deploy?template=https://github.com//ayooh-me/Pink-Venom-MD' target="_blank">
      <img alt='Deploy on Heroku' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=heroku&logoColor=white'/>
   </a>

**Option 2: Deploy on Koyeb**
1. [Sign Up on Koyeb](https://app.koyeb.com/auth/signup).
3. Deploy your app using the button below:
   <br>
   <a href='https://github.com//ayooh-me/Pink-Venom-MD' target="_blank">
      <img alt='Deploy on Koyeb' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=koyeb&logoColor=white'/>
   </a>

**Option 3: Deploy on Railway**
1. [Create an Account on Railway](https://railway.app/login) if you don’t have one.
2. Click the button below to deploy using Railway:
   <br>
   <a href='https://railway.app/' target="_blank">
      <img alt='Deploy on Railway' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=railway&logoColor=white'/>
   </a>

**Option 4: Deploy on Toystack**
1. [Create an Account on Toystack](https://toystack.ai) if you don’t have one.
2. Click the button below to deploy using Toystack:
   <br>
   <a href='https://toystack.ai' target="_blank">
      <img alt='Toystack' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=toystack&logoColor=white'/>
   </a>

**Option 5: Deploy on Render**
1. [Create an Account on Render](https://dashboard.render.com/register) if you don’t have one.
2. Click the button below to deploy using Render:
   <br>
   <a href='https://dashboard.render.com' target="_blank">
      <img alt='Deploy on Render' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=render&logoColor=white'/>
   </a>
   
   **Option 6: Deploy on Replit**
1. [Create an Account on Replit](https://repl.it) if you don’t have one.
2. Click the button below to deploy using Replit:
   <br>
   <a href='https://repl.it/github/Tohidkhan6332/TOHID-KHAN' target="_blank">
      <img alt='Deploy on Replit' src='https://img.shields.io/badge/-DEPLOY-FF10F0?style=for-the-badge&logo=replit&logoColor=white'/>
   </a>
   
   **Option 7: Github Workflows**
   
   **Option 8: Pterodactly/Control Panel**

   **Option 9: Or Any NodeJS Enviroment**
   
<h2>A Little About This Bot</h2>
<ul>
    <li>✔️ | <strong>Simple</strong></li>
    <li>✔️ | <strong>No Button</strong></li>
    <li>✔️ | <strong>Multi Device</strong></li>
    <li>✔️ | <strong>Plugins</strong></li>
</ul>

<hr>

<hr>

<b>乂 COPY WORKFLOW CODE</b></br>
```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start

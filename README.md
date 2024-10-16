<img src="./upload/ss.jpg">

# Whatsapp Bot

## Support

- Windows
- Linux
- Termux

## Feature
- Self Bot (True/False) Command `config.json`

### Command

| Command      			|  Deskription      |
|-----------------------|-------------------|
|.gemini-ai				|To use Gemini AI, example: `.gemini hello`|
|.gemini-img			|Analyze the quoted image: example quote image `.gemini-img What is this picture?`|
|.sticker       		|Convert images into stickers, example: quote image `.sticker`|
|.to-voice				|Convert text to voice, example: `.to-voice hello words`|
|.wiki-ai				|Get wiki content based on a query, example: `.wiki-ai kucing`|
|.wiki-search			|Get a list of wiki contents based on a query, example: `.wiki-search kucing`|
|.wiki-img				|Get Images from wiki based on query, example: `.wiki-image kucing`|
|.weather				|Get weather data based on city name, example: `.weather jakarta`|
|.translate				|Translate into various languages, example: `.translate-en apa kabar`|
|.surah					|Get the entire surah, example: `.surah 1`|
|.surah-detail			|Get a specific verse from a surah, example: `.surah 1:4`|
|.country				|Get country information, example: `.country indonesia`|
|.seo					|Check SEO status by domain, example: `.seo youtube.com`|
|.words					|Counting words, example: `.words hello words`|
|.mtk					|Multi math addition, example: `.mtk 1-1+1*1:1`|
|.qrcode				|Generate QRcode Image, example: `.qrcode hello words`|
|.{file-type}			|Generate QRcode Image, example: `.pdf javascript`|

**File Type Support**
```
.pdf, .doc, .docx, .xls, .xlsx, .ppt, .pptx, .txt, .html, .htm, .csv, .rtf, .odt, .ods, .odp, .epub, .zip, .gz
```
### Group Command

| Command           |  Deskription      |
|-------------------|-------------------|
|.add               |Adding a new member in group, example: `.add 628xxxxx`|
|.kick              |Kicking members of the group, example: `.kick @mention`|
|.promote           |Promote members in admin group, example: `.promote @mention`|
|.demote            |Demote admins in group members, example: `.demote @mention`|
|.chat-close        |Only admins can send messages in groups|
|.chat-open         |Everyone can send messages in the group|
|.antilink-true     |Enable deleting messages containing links in group|
|.antilink-false    |Disables deleting messages containing links in groups|
|.badwords-true     |Enable deleting messages containing badwords in group|
|.badwords-false    |Disables deleting messages containing badwords in groups|


## Instalation

Please visit the [AI Studio](https://aistudio.google.com) site to get the gemini apikey, Then configure in `config.json`

### Windows

- Install Node.js [Download](https://nodejs.org/id)
- Clone Repository
```
git clone https://github.com/fitri-hy/whatsapp-bot.git
cd whatsapp-bot
```
- Run Bot
```
npm start
```

### Linux

- Install Node.js
```
sudo apt update
sudo apt install nodejs npm
```
- Clone Repository
```
git clone https://github.com/fitri-hy/whatsapp-bot.git
cd whatsapp-bot
```
- Run Bot
```
npm start
```

### Termux

- Install Node.js
```
pkg update
pkg install nodejs git
```
- Clone Repository
```
git clone https://github.com/fitri-hy/whatsapp-bot.git
cd whatsapp-bot
```
- Run Bot
```
npm start
```

Don't forget to Fork and give me a star
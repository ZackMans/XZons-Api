<div align="center">
<img src="https://zackmans.github.io/media/log4.jpg" alt="X-Zons" width="170" />

## XZONS API

</div>

<p align="center">
<a href="##"><img title="xzons-api" src="https://img.shields.io/static/v1?label=package&message=xzons-api&color=red"></a>
</p>
<p align="center">
  <a href="https://github.com/ZackMans"><img title="Author" src="https://img.shields.io/badge/Author-ZackMans-red.svg?style=for-the-badge&logo=github" /></a>
</p>
<p align="center">
<a href="#"><img title="mengapi" src="https://img.shields.io/static/v1?label=FREE&message=xzons-api&color=pink"></a>
</p>

## ```INSTALL And UNINSTALL```ioA
> npm install xzons-api
>  
> npm uninstall xzons-api

## ```Telegram Sticker```
``` 
const xzons = require('xzons-api');
const name = "patrick"

xzons.Telesticker(name)
    .then(result => {
     console.log(result)
});
```

## ```Meta Scrape Downloader```
``` 
const xzons = require('xzons-api');
const link = "https://vt.tiktok.com/ZSdghVaHC/?k=1"

xzons.metaScrape(link)
    .then(result => {
     console.log(result)
});
```

## ```Sticker Search```
``` 
const xzons = require('xzons-api');
const name = "patrick"

xzons.StickerSearch(name)
    .then(result => {
     console.log(result)
});
```

## ```Nickname Mobile Legends```
``` 
const xzons = require('xzons-api');
const userid = "617243212"
const zoneid = "8460"

xzons.nickml(userid, zoneid)
    .then(result => {
     console.log(result)
});
```

## ```Nickname Free Fire```
``` 
const xzons = require('xzons-api');
const userid = "946716486"

xzons.nickff(userid)
    .then(result => {
     console.log(result)
});
```

## ```Google TTs```
```
const xzons = require("xzons-api")
const codB = "id" // kode bahasa indonesia
const tekB = "Salman Ganteng" // Teksnya

xzons.gtts(codB).save("./storage/salman.mp3", tekB, function(err, result) {
if (err) { throw new Error(err); }
console.log(`Berhasil mengsave cek di folder ./storage/salman.mp3`)
});
```

## ```Phootoxy```
``` 
const xzons = require('xzons-api');
const name = "ZackMans"

// One Message
xzons.phootoxy("https://photooxy.com/logo-and-text-effects/shadow-text-effect-in-the-sky-394.html", [name])
    .then(result => {
     console.log(result)
});

// Two Message
xzons.phootoxy(<phootoxy_html>, [name], [name])
    .then(result => {
     console.log(result)
});
```

## ```Text Pro```
``` 
const xzons = require('xzons-api');
const name = "ZackMans"

// One Message
xzons.textpro("https://textpro.me/create-impressive-glitch-text-effects-online-1027.html", [name])
    .then(result => {
     console.log(result)
});

// Two Message
xzons.textpro(<textpro_html>, [name], [name])
    .then(result => {
     console.log(result)
});
```

## ```Mcpedl```
``` 
const xzons = require('xzons-api');
const name = "shader"

xzons.mcpedl(name)
    .then(result => {
     console.log(result)
});
```

## ```Happy Mod```
``` 
const xzons = require('xzons-api');
const name = "freefire"

xzons.happymod(name)
    .then(result => {
     console.log(result)
});
```

## ```Server Minecraft Indonesia```
``` 
const xzons = require('xzons-api');
const page = 1 // https://minecraftpocket-servers.com/country/indonesia/

xzons.servermc(page)
    .then(result => {
     console.log(result)
});
```

## ```Mediafire Downloader```
``` 
const xzons = require('xzons-api');
const link = 'https://www.mediafire.com/file/a61862y1tgvfiim/ZackBotMans+(+Versi+1.0.1+).zip/file'

xzons.mediafire(link)
    .then(result => {
     console.log(result)
});
```

## ```Aiovideo Downloader```
``` 
const xzons = require('xzons-api');
const link = 'https://youtu.be/5C8yvJUVB-0'

xzons.aiovideodl(link)
    .then(result => {
     console.log(result)
});
```

## ```Play Store```
``` 
const xzons = require('xzons-api');
const judul = 'game 8 bit'

xzons.playstore(judul)
    .then(result => {
     console.log(result)
});
```

## ```Link Wa```
``` 
const xzons = require('xzons-api');
const judul = 'Editod bekentod'

xzons.linkwa(judul)
    .then(result => {
     console.log(result)
});
```

## ```Pinterest```
``` 
const xzons = require('xzons-api');
const judul = 'nakano nino'

xzons.pinterest(judul)
    .then(result => {
     console.log(result)
});
```

## ```IG Downloader```
``` 
const xzons = require('xzons-api');
const link = 'https://www.instagram.com/p/CQpUpGvAhWq/?utm_source=ig_web_copy_link'

xzons.igdl(link)
    .then(result => {
     console.log(result)
});
```


## ```IG Story```
``` 
const xzons = require('xzons-api');
const username = 'salman_alfarizi_15'

xzons.igstory(username)
    .then(result => {
     console.log(result)
});
```

## ```IG Stalk```
``` 
const xzons = require('xzons-api');
const username = 'salman_alfarizi_15'

xzons.igstalk(username)
    .then(result => {
     console.log(result)
});
```

## ```Youtube Downloader```
``` 
const xzons = require('xzons-api');
const link = 'https://youtu.be/5C8yvJUVB-0'

xzons.youtube(link)
    .then(result => {
     console.log(result)
});
```

## ```Tiktok Downloader```
``` 
const xzons = require('xzons-api');
const link = 'https://www.tiktok.com/@daniajaa7/video/6980287183517125890?sender_device=pc&sender_web_id=6978811994732938753&is_from_webapp=v1&is_copy_url=0'

xzons.ttdownloader(link)
    .then(result => {
     console.log(result)
});
```

## ```List Code Bahasa```
```
const LANGUAGES = {
  'af': 'Afrikaans',
  'sq': 'Albanian',
  'ar': 'Arabic',
  'hy': 'Armenian',
  'ca': 'Catalan',
  'zh': 'Chinese',
  'zh-cn': 'Chinese (Mandarin/China)',
  'zh-tw': 'Chinese (Mandarin/Taiwan)',
  'zh-yue': 'Chinese (Cantonese)',
  'hr': 'Croatian',
  'cs': 'Czech',
  'da': 'Danish',
  'nl': 'Dutch',
  'en': 'English',
  'en-au': 'English (Australia)',
  'en-uk': 'English (United Kingdom)',
  'en-us': 'English (United States)',
  'eo': 'Esperanto',
  'fi': 'Finnish',
  'fr': 'French',
  'de': 'German',
  'el': 'Greek',
  'ht': 'Haitian Creole',
  'hi': 'Hindi',
  'hu': 'Hungarian',
  'is': 'Icelandic',
  'id': 'Indonesian',
  'it': 'Italian',
  'ja': 'Japanese',
  'ko': 'Korean',
  'la': 'Latin',
  'lv': 'Latvian',
  'mk': 'Macedonian',
  'no': 'Norwegian',
  'pl': 'Polish',
  'pt': 'Portuguese',
  'pt-br': 'Portuguese (Brazil)',
  'ro': 'Romanian',
  'ru': 'Russian',
  'sr': 'Serbian',
  'sk': 'Slovak',
  'es': 'Spanish',
  'es-es': 'Spanish (Spain)',
  'es-us': 'Spanish (United States)',
  'sw': 'Swahili',
  'sv': 'Swedish',
  'ta': 'Tamil',
  'th': 'Thai',
  'tr': 'Turkish',
  'vi': 'Vietnamese',
  'cy': 'Welsh'
}
```

  # Thanks To
* [`MRHRTZ`](https://github.com/MRHRTZ)
* [`XFARR`](https://github.com/xfar05)
* [`YogiPw`](https://github.com/yogipw)
* [`Hexagonz`](https://github.com/Hexagonz)
* [`ZackMans`](https://github.com/ZackMans)
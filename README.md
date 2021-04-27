<p align="center">
<a href="https://github.com/Nitse0"><img title="Nitse" src="https://img.shields.io/badge/github-Nitse-orange.svg?style=social&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/Nitse0"><img title="Author" src="https://img.shields.io/badge/Nitse-BotV2-green?style=for-the-badge&logo=github"></a></a>
</p>
<p align="center">
</a>
</p>


### Test bot
Antes de instalar Bot V.2 primerp prueba el Bot aqui 
<p>
</p>

### Tools
| Apps | Link |
|--------|--------|
| **Termux** | [Download](https://play.google.com/store/apps/details?id=com.termux) |
| **Acode** | [Download](https://play.google.com/store/apps/details?id=com.foxdebug.acodefree) |
<p align="center">
  <div align="center">
 <code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png"></code>
 <code><img height="40" src="https://user-images.githubusercontent.com/72728486/108440991-c9196180-7286-11eb-910e-d95691565ec8.png"></code>

  </div>
  </p>


### Instalar con Termux

```bash
> termux-setup-storage
> apt update && upgrade
> apt install git
> apt install bash
> git clone https://github.com/Nitse0/Nitse-BotV2
> cd Nitse-BotV2
> bash install.sh
> npm start
```

### Setting
* DATA BOT

Tempat : ```./data/setting```

Contoh default :
```
{
	"prefix": ".",
	"ownerNumber": "50373784006",
	"BarBarKey": "YourApiKey",
	"Vhtearkey": "YourApiKey",
	"LolHumanKey": "YourApiKey",
        "Vinzapi": "Yourapikey",
        "Itsmeikyapi": "Yourapikey",
	"limit": "20",
  "memberlimit": "20",
  "cr": "owo",
  "hargalimit": "500",
  "NamaBot": "Bot V.2",
  "Ovo": "50373784006",
  "Pulsa": "50373784006",
  "Donar": "50373784006"
}
```

* Kontak owner

Tempat : ```./index.js/101```

Contoh default :

```
const vcard = 'BEGIN:VCARD\n'
+ 'VERSION:3.0\n'
+ 'FN:Mrf.zvx\n' // Nama
+ 'ORG:Nitse bot;\n' // Nama bot
+ 'TEL;type=CELL;type=VOICE;waid=50373784006:+503 7378 4006\n' // Nomor owner
+ 'END:VCARD' 
```

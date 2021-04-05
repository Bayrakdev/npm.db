![Image](https://img.shields.io/npm/v/foe.db?color=%2351F9C0&label=foe.db) 
![Image](https://img.shields.io/npm/dt/foe.db.svg?color=%2351FC0&maxAge=3600) 
#
![Image](https://nodei.co/npm/foe.db.png?downloads=true&downloadRank=true&stars=true)
<a href="https://discord.gg/zoom"><img src="https://img.shields.io/discord/222078108977594368?color=7289da&logo=discord&logoColor=white" alt="Discord server" /></a>
<br>
## Yüklemek İçin
```npm
npm install foe.db
```

# Uyarı
- Node sürümü 14 gereklidir.
- **KODLAR ALINMASI/ÇALINMASI HALİNDE GEREKLİ YAPTIRIMLAR EN SERT ŞEKİLDE UYGULANACAKTIR.**
## Nasıl Kullanılır?
# JS
```javascript
const { Database } = require("foe.db");
const  db  = new Database("fireofeternity");

// Data ms

db.ping();

// Data set | get
db.set("veri", 31);
db.get("veri");
db.fetch("veri");

// Data exists

db.has("veri");
db.exists("veri");

// Get all data

db.all(31); || db.all();
db.fetchAll(31); || db.fetchAll();

// To JSON

db.toJson(31); || db.toJson();

// Delete data

db.delete("veri");
db.deleteAll();

// Get data type

db.type("veri"); // ---> sayı

// DB Array methods
db.push("veri", 31);
db.pull("veri", 31);
db.arrayHasValue("veri", 31);
db.valueArray();
db.keyArray();

// DB Math metods

db.math("veri","*", 31);
db.add("veri", 31);
db.substr("veri", 31);

// DB Finding methods

db.includes("ve");
db.startsWith("ve");
db.findAndDelete((key,value) => {
    return key.includes("veri");
});

// Infos
console.log(db.size);
console.log(db.totalDBSize);
console.log(Database.DBCollection);

// Version DB
db.version();

// Destroy DB
db.destroy();
```
## Bana ulaşabileceğiniz yerler.
[İnstagram](https://www.instagram.com/bayraakk_/)
[Discord](https://discord.gg/zoom)

[Developed By Bayrak & WenSamita Neiva](https://discord.gg/zoom)

# Nasıl İndirilir?

<code>npm install foe.db
</code>

# Nasıl Kullanılır?

const db = require('foe.db')

# Veri Kaydetme - Çekme

db.set("veri.1") \n
db.get("veri.1")
db.fetch("veri.1")

# Veri Silme

db.delete("veri.1")
db.deleteAll()

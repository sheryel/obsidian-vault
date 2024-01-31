---
cssclasses:
  - dashboard
banner: "[[Media/Banners/home.png]]"
banner_y: 0.088
banner_icon: ❤️
banner_lock: true
---

# Vault Info
- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(10).file.link)`
- 🔖 School notes 
 `$=dv.list(dv.pages('#').sort(f=>f.file.name,"desc").limit(4).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`

---

| Subject | Teacher | Phone no. | Email |
| ---- | ---- | ---- | ---- |
| Form teacher | Allan Low | +65 9115 4929 |  |
| Math | Kenny Ong | +65 9221 3540 |  |
| English | Debbie Tan |  |  |
| Geography | Gen Zhang / Alvin Tan |  |  |
| Social studies | Seth Tan |  | seth_tan@sst.edu.sg |
| Physics | Allan Low | +65 9115 4929 |  |
| Chemistry | Wong KL |  |  |
| Computing | Jovita Tang / Raymond Chng |  |  |
| SnW | Ms Choo |  |  |

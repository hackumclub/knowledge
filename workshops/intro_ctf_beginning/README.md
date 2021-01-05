---
name: My other computer is your computer!
description: Hacking-ийн талаар суурь ойлголтууд
author: "@grimexploit"
img: "https://i.kym-cdn.com/entries/icons/original/000/021/807/ig9OoyenpxqdCQyABmOQBZDI0duHk2QZZmWg2Hxd4ro.jpg"
---	

# My other computer is your computer!

Hello World! Миний бие 10 жилийн сурагч байхдаа "Харуул Занги" гэх тэмцээнд  анх оролцож кинон дээр гардаг Hacker-ийн талаар анх ойлголттой болж байлаа. Өнөөдөр би CTF(Capture The Flag), Attack-Defense болон Machine Hacking-ийн талаар судалж мэдсэн зүйлсийнхээ талаар та бүхнийг мэдээсэй гэсэндээ өчүүхэн ч гэсэн мэдлэгийг олгохыг зорилоо.

![enter image description here](https://i.kym-cdn.com/entries/icons/original/000/021/807/ig9OoyenpxqdCQyABmOQBZDI0duHk2QZZmWg2Hxd4ro.jpg)
# Зорилго
Нэгэнт л та бүхэн Hackum клубын гишүүн болсон болохоор ямар нэг байдлаар кодчилолтой холбогдож ямар нэг зүйл бүтээж, гараас гаргана гэдэгт итгэлтэй байна.

Харин тэр үед хийсэн зүйлийнхээ аюулгүй эсэхийг бид хэрхэн мэдэх вэ?

**CTF-ийн төрөл бүрийн Event-үүдэд оролцсоноороо бид**:

- Системийг төлөвлөхдөө юун дээр анхаарах вэ? Ямар үед аюултай вэ?
- Программчлахдаа юун дээр анхаарах вэ? 
- Эмзэг байдлыг мэдсэн ч хэрхэн яаж засах вэ? 
- Болзошгүй халдлагаас өөрийгөө хэрхэн сэргийлэх вэ ?

гэх мэт асуултуудийн хариултыг та номноос уншаад хаях биш, өөрөө мэдэрч практик дээр ажиллаж өөрийгөө 0.001% ч гэсэн сайжруулах боломж юм шүү :)

# Мэдээллийн аюулгүй байдал тийм чухал уу?
Мэдээллийн аюулгүй байдал хүн төрөлхтний аль ч цаг үед маш чухал байсаар ирсэн. Эртний Ромын хаад Цезар цифр (Caesar Cipher)-ийг ашиглаж мэдээллээ дамжуулдаг байсан бөгөөд энэ нь үсгийн байрыг өөр үсгээр сольж орлуулж нууцладаг арга юм.  Дэлхийн II дайны үеэр Германчууд Enigma Machine гэх мэдээллийг encrypt хийж дамжуулдаг төхөөрөмжийг цэргийн зориулалтаар ашиглаж эхэлсэн нь тэдэнд маш давуу талыг үүсгэж байсан. Тухайн үед Энигма машиныг дайснаас олзолж авах нь нэмэр болохгүй байсан юм. Учир нь Энигма машиныг бүрэн тайлахын тулд 158 сая бүхий боломжит кодыг тайлах хэрэгтэй болсон. Асар өндөр нууцлал бүхий Энигма машины кодыг тайлж чадсан нь дэлхийн хоёрдугаар дайныг 2 жилээр богиносгож 14 гаруй сая хүний амь насыг аварч чадсан билээ.

![Өнөөх гайхал Энигма Машин](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/EnigmaMachineLabeled.jpg/220px-EnigmaMachineLabeled.jpg)

# Jeopardy CTF(Capture The Flag) тухай товч

Capture The Flag тэмцээн нь оролцогчид тодорхой хугацаанд зохион байгуулагчдаас өгөгдсөн даалгавруудыг (Challenge) гүйцэтгэн флаг олж оноо авах замаар өрсөлддөг тэмцээн юм. Хүнд даалгавар биелүүлэх тусам та өндөр оноо авч scoreboard дээр өрсөлдөх юм.

**CTF-ийн даалгавруудын хувьд**: Cryptography, Stegnography, Forensics, Binary explotation, Web Explotation, Pwn, Mobile Security, Secure Programming, IoT гэх төрлүүдтэй. 

- **Cryptography** : Датаг нууцлаж encrypt, decrypt хийдэг төрөл юм
- **Stegnography** : Зураг, бичлэгт мэдээлэл нуух төрөл юм 
- **Forensics** : Дата дээр дүн шинжилгээ хийж мөрдөгч шиг мөшгиж гэмт хэрэгтнийг барих гээд ойлгочиход ер нь болно
- **Binary explotation** : Reverse Engineering гэдэг нь файл дээр задлан  шинжилгээ хийх, Binary exploit гэдэг нь ажиллах зарчмыг доголдуулах маягаар давуу тал эдлэх төрөл  
- **Web Explotation** : Нэрнээсээ л ойлгомжтой байх. Web-ийн эмзэг байдлыг ашиглан даалгаврыг биелүүлдэг төрөл.
- **Pwn**:  System-ийн эмзэг байдлыг ашиглаж давуу байдлыг үүсгэх төрөл

[CTF Event Tracker вэбсайт ](https://ctftime.org/) 

# Attack-Defense CTF төрөл

Энэ төрөл нь Jeopardy төрлийн CTF өөр нэг төрөл юм. Баг бүрт эмзэг байдал бүхий сервер болон server өгөгдөнө. Таны хийх ажил бол өөрсдийн аюулгүй байдлыг хангаж буй багуудруу халдлага үйлдэх маягаар явдаг төрөл юм. Тэмцээн явагдах дүрмийн хувьд гэвэл төв server дээр host хийгдсэн Virtual Machine-тай байна. Бусад багуудад virtual machine уудын IP хаяг өгөгдөх бөгөөд гол хийх юм нь эсрэг багийн machine ийг судалж, эмзэг байдлыг олж илрүүлэн exploit хийх маягаар өрсөлдөнө. 

![enter image description here](https://www.researchgate.net/profile/Crispin_Cowan/publication/4012201/figure/fig1/AS:669986632773635@1536748669171/Defcon-Capture-the-Flag-CtF.png)

## Machine Hacking

Attack чадвараа энэ төрлөөр сайжруулах боложмтой. Live ажиллаж байгаа Machine руу халдлага үйлдэж системийн root-ийг авах замаар даалгаврыг биелүүлдэг. Энэ төрлийн чадвараа хөгжүүлэх бол [**HackTheBox**](https://hackthebox.eu) вэбсайтаар зочилж үзээрэй. Invite code авахын тулд та өөрийн бага ч гэсэн чадвараа харуулж invite code авна гэдгийг анхаараарай. 
![We hacc](https://i.ytimg.com/vi/_pjICT3pdNw/maxresdefault.jpg)

# Let's hack the planet :)) - Практик туршилт

Харуул занги 2018 оны даалгавруудыг жишээ болгон хэдэн даалгавар бүгдээрээ хийцгээе!

## 1-р даалгавар

![enter image description here](https://4.bp.blogspot.com/-8TTMIEq7A3o/W6dzvThW33I/AAAAAAAAGXg/EKmcWnoRX7odNmabdDLg7ELEmpeVU9PHwCLcBGAs/s1600/Capture.PNG)

Даалгаварт өгөгдсөн problem.py файлыг нээж үзвэл:

![enter image description here](https://4.bp.blogspot.com/-N8FoW-_vA0s/W6dz65meikI/AAAAAAAAGXk/2TVdjQH0OwYGkf4XRjtw0LfM-593hzR4QCLcBGAs/s400/Capture.PNG)

Programm-ийн бит ээр нь өөрчилдөг үйлдлийг бүх үсэг тэмдэгтүүдэд хийж үзхээр харгалзах тоонууд нь гарч ирнэ. Тэр тоонуудаа зөв түлхүүрийн тоонуудтай харьцуулаад хархаар боломжит түлхүүрүүд гарж ирнэ. Зарим үсэг боломжит 2-3 боломжтой байж болно.

![enter image description here](https://1.bp.blogspot.com/-P4ta6BgqDBs/W6d1Otq02DI/AAAAAAAAGX0/KtbHtWbO5vA6ueRKRh2tR6vniX6XTIXPACLcBGAs/s400/Capture.PNG)

Энэ дундаас pyth0n_b3st гэсэн боломжит хувилбар нь бидний флаг юм

**Flag буюу бидний олох ёстой нууц үг:** ```HZ{pyth0n_b3st}```

HZ гэж эхэлж буй нь Haruul Zangi тэмцээний товчилсон үг юм. Ихэнх CTF даалгавруудын флаг тухайн платформынхоо нэрээр эхэлсэн байдаг.

--------------------

## 2-р даалгавар

![enter image description here](https://4.bp.blogspot.com/-Fvi3VrjWFxs/W6sQaSYbIMI/AAAAAAAAGYY/j24v5YRcljAVc93VJ7Y8aAAAIYm6vnrMgCLcBGAs/s400/Capture.PNG)

Энэхүү даалгаварын data.txt файл-ыг нээж үзвэл:

```"MTExMDAwMTAxMTExMDAwMDExMDEwMDAxMTEwMTAwMTAxMDAxMTAxMDExMTExMDAwMTExMTAxMDExMTEwMTAwMDExMDAwMDExMTEwMDAxMDAxMTAwMTAxMTExMDExMDAwMTEwMTAwMTExMTExMDEwMTExMTAwMDAxMTAwMTEwMDExMTAxMDAxMTExMDEwMTEx"```

Base64 гарж ирэх бөгөөд үүнийг decode хийвэл binary гарж ирнэ.

Base64 decoded:
```"111000101111000011010001110100101001101011111000111101011110100011000011110001001100101111011000110100111111010111100001100110011101001111010111"```

Үүнийг 1-8 битээр bruteforce хийвэл:

![enter image description here](https://4.bp.blogspot.com/-6FUaWVrWWzE/W6sQ9oq2JII/AAAAAAAAGYg/AvC9rGAHmWABUoPiX7e_vBre7qHwAfgXQCEwYBhgL/s400/Capture.PNG)

**Flag** ```HZ{x0R_Binary_K3y}```

## NO SYSTEM IS SAFE!

**Энэ хүртэл миний нийтлэлийг уншсан таньд маш их баярлалаа!**   [@grim444](https://facebook.com/saruultrade)

Энэ талаар илүү дэлгэрэнгүй ойлголттой болохыг хүсвэл video content тасралтгүй бүтээдэг [**@FantasMM**](https://www.youtube.com/channel/UC0rd3rYEXdSSNtgVj9O8P9Q)-ийн Youtube сувгаар зочлоорой.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=wU4dtWAUOXc" target="_blank"><img src="http://img.youtube.com/vi/wU4dtWAUOXc/0.jpg" 
alt="Fantasm" width="240" height="180" border="10" /></a>

---

WriteUp By **TeamMazala** багийн Top Fragger. HackTheBox World Top10    Instagram: [**@zjzoloo**](https://www.instagram.com/zjzoloo/)

# 🏥 Oilaviy sog'liq kuzatuv

Oila a'zolarining tibbiy tahlil natijalari va shifokor ko'riklari uchun birgalikda foydalaniladigan kuzatuv tizimi.

**Barcha ma'lumotlar shu GitHub repo'da saqlanadi** — hech qanday tashqi server kerak emas.

## Imkoniyatlar

- 👨‍👩‍👧‍👦 Oila a'zolarini qo'shish va boshqarish
- 🧪 Tahlil natijalarini kiritish (normal diapazon bilan)
- 🩺 Shifokor ko'riklari va tashxislarni saqlash
- 📊 Vaqt bo'yicha grafiklar
- 🔄 Oila a'zolari o'rtasida solishtirish
- ⚡ AI tahlil va tavsiyalar (ixtiyoriy)
- 📱 Telefon va kompyuterda ishlaydi
- 🌙 Qorong'u/yorug' rejim avtomatik
- ☁️ GitHub'da markaziy saqlash — barcha oila bitta ma'lumotdan foydalanadi

## O'rnatish (5 daqiqa)

### 1. Repo yarating

1. Yuqoridagi yashil **"Use this template"** tugmasini bosing yoki [github.com/new](https://github.com/new) ga kirib:
   - Repo nomi: `sogliq`
   - **Public** tanlang
   - "Create repository" bosing
2. `index.html` va `README.md` fayllarini repo'ga yuklang

### 2. GitHub Pages'ni yoqing

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main`, papka: `/ (root)` → **Save**
4. 1-2 daqiqa kuting

### 3. Token yarating

1. [github.com/settings/tokens/new](https://github.com/settings/tokens/new?scopes=repo&description=Sogliq%20App) sahifasiga kiring
2. "repo" huquqini tanlang
3. Token yarating va nusxalang

### 4. Ilovaga kiring

1. `https://SIZNING_USERNAME.github.io/sogliq/` sahifasini oching
2. GitHub username, repo nomi va token'ni kiriting
3. Tayyor!

## Oila a'zolariga ulashish

Havola va token'ni oila a'zolaringizga yuboring. Har bir kishi:
1. Havolani ochadi
2. **Bir xil** username, repo va token kiritadi
3. Hammasi bitta ma'lumotni ko'radi va tahrirlaydi

> **Muhim:** Token'ni faqat ishonchli oila a'zolariga bering.

## Qanday ishlaydi

```
📱 Telefon/Kompyuter
     ↕ GitHub API
📂 Bu repo → data.json (barcha ma'lumotlar)
```

- Ma'lumot qo'shsangiz → `data.json` fayliga yoziladi (commit)
- Sahifani yangilasangiz → `data.json`dan o'qiladi
- Har bir o'zgartirish commit sifatida saqlanadi (tarix ko'rinadi)

## AI funksiyasi (ixtiyoriy)

1. [console.anthropic.com](https://console.anthropic.com) da ro'yxatdan o'ting
2. API kalitini oling
3. Ilovada ⚙ → ⚡ AI sozlama → kalitni kiriting

## Xavfsizlik

- GitHub token faqat brauzeringizda saqlanadi (localStorage)
- Ma'lumotlar faqat sizning repo'ngizda
- AI kalit ham faqat brauzerda
- Repo public bo'lsa, ma'lumotlar ochiq — maxfiylik uchun **private** repo ishlating (GitHub Pro kerak)

## Litsenziya

Bepul foydalanish uchun.

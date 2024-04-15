 # 5 - dars | Birinchi dasturni yozish | Tags | YouTube Link
— yozilgan codelarni browserda ko'rish
javob:
Yozilgan kodlarni brauzerda ko'rishning bir nechta usullari mavjud. Ba'zilari yozilgan HTML, CSS, va JavaScript fayllarini brauzerda o'zgarishsiz ko'rishni ta'minlaydi, ba'zilari esa brauzer yoki brauzer kengaytmasi orqali yashirish uchun qo'llaniladi. Quyidagi usullardan biri yoki bir nechta, sizning mahsulotingizni test qilish va yozilgan kodlarning natijasini ko'rish uchun moslashtirilgan bo'lishi mumkin:

1. **Brauzerda lokal faylni ochish**:
   HTML, CSS, va JavaScript fayllarini brauzerda ochish eng oddiy usul. Faylni o'z brauzeringizga yuklash va uni ochish uchun brauzerda faylni tanlash mumkin. Odatda, "File" -> "Open File" ni tanlashingiz va kerakli faylni tanlash orqali bu usulni amalga oshirishingiz mumkin.

2. **VS Code'da Live Server**:
   VS Code'da Live Server kengaytmasini o'rnatib, HTML fayllarini brauzerda yashirish va o'zgarishlarni o'tkazishni osonlashtirishingiz mumkin. Faylni ochib, "Go Live" tugmasini bosish orqali brauzerni ochish uchun xizmat qiladi. Bu usul HTML va JavaScript kodlarini yangilash va natijalarni ko'rish uchun juda qulaydir.

3. **GitHub Pages yoki Netlify kabi to'plam servislari**:
   GitHub Pages yoki Netlify kabi xizmatlar orqali veb saytlarni joriy qilishingiz va brauzerda sinovlashingiz mumkin. Siz yozilgan kodlarni GitHub'ga yuklab, so'ngra "Pages" qismiga kirib, brauzerda saytingizni ko'rish uchun brauzerni ochishingiz mumkin.

4. **Localhost yoki server o'rnatish**:
   Agar sizda xizmat qiluvchi o'rnatilmagan bo'lsa, o'z kompyuteringizda localhost serverini o'rnatib, HTML va JavaScript fayllarini o'z kompyuteringizda ishga tushirib, ularni brauzerda yashirishingiz mumkin. Ushbu usulni amalga oshirish uchun Node.js yoki boshqa server platformalardan foydalanishingiz mumkin.

5. **CodePen, JSFiddle yoki JSBin kabi veb redaktorlar**:
   CodePen, JSFiddle yoki JSBin kabi onlayn veb redaktorlarni ishlatishingiz ham mumkin. Bu veb saytlar orqali HTML, CSS, va JavaScript kodlarni yozib, natijalarni yashirish va boshqa odamlar bilan o'z kodlaringizni ulashish imkoniyatiga egasiz.

Bu usullar yozilgan kodlarni brauzerda ko'rish uchun eng oddiy va oson usullardir. Har birining o'zining afzalliklari va ta'sirchanligi mavjud. Siz uchun eng muhim bo'lgan narsani tanlash va ishga tushirish tavsiya etiladi.

— VS codeda auto save va uning ishlatilish o'rinlari
javob:
Visual Studio Code (VS Code) dasturida "Auto Save" funksiyasi mavjud. Bu funksiya, o'zgarishlar bilan saqlash jarayonini otomatiklashtiradi va faylni saqlashni qulaylashtiradi. Ishlatish o'rinlari va sozlamalari quyidagicha:

1. **Ishlatish o'rinlari**:
   "Auto Save" funktsiyasini yoqish uchun quyidagi qadamalarni amalga oshiring:

   - VS Code dasturini oching.
   - Menyu ichidagi "File" -> "Auto Save" bo'limini tanlang.
   - "Auto Save" ni "onFocusChange" yoki "afterDelay" parametrlaridan birini tanlang.
   - "onFocusChange" tanlovini tanlaganingizda, o'zgarishlar fokusga keltirilgan sahifalarda saqlanadi. "afterDelay" tanlovini tanlaganingizda, o'zgarishlar 300 millisekundga sozlanadi.

2. **Sozlamalar**:
   "Auto Save" sozlamalarini o'zgartirish uchun quyidagi qadamlarni amalga oshiring:
   - Menyu ichidagi "File" -> "Preferences" -> "Settings" ni tanlang.
   - "Settings" sahifasida "Files: Auto Save" qidiruv maydonida "onWindowChange" yoki "afterDelay" ni tanlang.
   - "onWindowChange" tanlovini tanlaganingizda, o'zgarishlar saqlanish uchun brauzerga fokusni o'tkazish kerak bo'ladi. "afterDelay" tanlovini tanlaganingizda, sozlangan vaqt o'tkazilganda saqlanish amalga oshiriladi.

Ushbu sozlamalar sizga qanday vaqtda o'zgarishlar saqlansa bo'ladi va "Auto Save" funktsiyasini qanday ishlatishingiz mumkinligini belgilaydi. Iltimos, bu funktsiyani o'zlashtirishda maqsadlaringiz va foydalanish usullaringizga muvofiq tanlovni tanlang.

— Live server

— Tag nima?
javob:
"Live Server", Visual Studio Code (VS Code) kengaytmasi bo'lib, HTML, CSS, va JavaScript fayllarini brauzerda yashirish va yangilash imkonini beradi. Bu kengaytma sizning veb ilovalaringizni tekshirish va ularga to'liq nazorat qilishda qulayliklar ko'rsatadi. Live Serverni o'rnatib, ishlatish uchun quyidagi qadamlarni amalga oshirishingiz mumkin:

1. **Live Serverni o'rnatish**:
   Live Serverni o'rnatish uchun quyidagi qadamlarni amalga oshiring:

   - VS Code dasturini oching.
   - Extensions (kengaytmalar) panelini oching (Ctrl+Shift+X).
   - "Live Server" ni qidirish uchun qidiruv maydoniga "Live Server" ni kiriting.
   - Natijalardan "Live Server" kengaytmasini tanlang va o'rnatish tugmasini bosing.
   - O'rnatish tugmasini bosganda, kengaytma o'rnatiladi va ishga tushiriladi.

2. **Live Serverni ishlatish**:
   Live Serverni ishlatish uchun quyidagi qadamlarni amalga oshiring:
   - VS Code dasturini oching.
   - Ishlamoqchi bo'lgan HTML faylini oching.
   - Faylni ochganingizdan so'ng, brauzerda "Go Live" tugmasini bosishingiz kerak.
   - "Go Live" tugmasini bosganda, brauzerda HTML faylingiz ochiladi va Live Server ishga tushadi.
   - Endi, HTML faylga o'zgarishlar kiritishingiz yoki yangi kod qo'shishingiz mumkin. Bu o'zgarishlar avtomatik ravishda brauzerda ko'rinadi.

Live Server, brauzerdagi yangilanishlarni real vaqtning o'zida ko'rish uchun qulay va foydali bir vosita hisoblanadi. Bu, veb saytlarni yaratish va ularga to'liq nazorat qilish jarayonlarini yanada sodda qiladi.

— root tagi.
javob:
"Root tagi" dastur yoki kodning boshlanishi va har bir elementning o'rtasida joylashadi. HTML (HyperText Markup Language) dasturlash tili haqida gaplashayotganda, "root tag" yoki "asosiy tag" HTML dokumentining boshidagi bosh tagdir. Bu tag HTML dokumentining boshlang'ich elementini belgilaydi va barcha boshqa elementlarni ichiga olishi mumkin.

Bu "root tag" HTML faylining boshida ko'rsatilishi kerak va ularning birinchi elementi bo'ladi. Oddiy HTML fayllarida, boshlang'ich tag odatda `<html>` tagi bo'ladi.

HTML faylning boshlanishi quyidagi ko'rinishda bo'lishi mumkin:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Document sarlavhasi</title>
  </head>
  <body>
    HTML kodlar shu joyda
  </body>
</html>
```

Bu kodlar `<html>` tagi bilan boshlanadi va `</html>` tagi bilan tugaydi. Barcha HTML kodlari bu taglar ichida joylashadi. `<html>` tagi HTML dokumentining boshlang'ich tagi va "root tagi"dir.

— configuration tag
javob:
"Configuration tag" degan nom HTMLda yoq. Ma'lumotlarni ulash uchun head tagini olish mumkin .

— browser tag
javob:
body tagini ichidayozilgan narsalar browserda ko'ringani uchun uni shunday nomlash mumkin aslida htmlda bunday tag yuq

— Heading tagi
javob:
"Heading tagi" va "Paragraph tagi" HTML (HyperText Markup Language) tilida odatda matnlar va kontentni belgilash uchun ishlatiladigan elementlar haqida gaplashadi.

1. **Heading taglari** (sarlavha taglari):

   - HTML-da sarlavha taglari `<h1>` dan `<h6>` gacha mavjud. Bu taglar sarlavhalarni belgilash uchun ishlatiladi, masalan, boshliqlar yoki muqaddimalar.
   - `<h1>` eng yuqori darajadagi sarlavhani belgilaydi, va `<h6>` esa eng pastki darajadagi sarlavhani belgilaydi.
   - Misol:
     `html
     <h1>Bu HTML sarlavhasi</h1>
     <h2>Bu bir sarlavha tagi</h2>
     <h3>Bu boshqa bir sarlavha tagi</h3>
     `
     — Paragraph tagi
     javob:

2. **Paragraph tagi**:

   - HTML-da paragraf (matn bloklari) `<p>` tagi bilan belgilanadi. Bu tag matn niqtalarini ajratish va ustunlash uchun ishlatiladi.
   - Misol:

     ```html
     <p>Bu bir paragraf tagi orqali belgilangan matn.</p>

     Sarlavha (`
     <h1>
       ` dan `
       <h6>
         `) va paragraf (`
         <p>
           `) taglari HTML-dagi asosiy matn belgilash vositalaridan
           ba'zilaridir. Ular ma'lumotlarni moslashtirish va sahifada muntazam
           tarzda tuzilishini ta'minlaydi.
         </p>
       </h6>
     </h1>
     ```

# 6 - dars | Formatting tags | YouTube Link

— Shoirlar uchun tag <pre>shoirlar tagi</pre>
"Pre tagi" HTML (HyperText Markup Language) tilida matnlar yoki kodlarni konsol yoki faylga yozilgan qilib, ulardagi o'girishlarini saqlash uchun ishlatiladi. "Pre" atamasi "preformatted text" ni ifodalaydi, ya'ni matnni asl ko'rinishida saqlash uchun.

`<pre>` tagi ichidagi matnlar brauzer tomonidan odatiy matn elementlaridan farq qiladi. Masalan, bo'shliq, qatorlar, yoki matndagi bo'sh joylar odatiy matn elementlarida ko'rinmas.

Misol:

```html
<pre>
Bu matn "pre" tagi ichida.
  Bu matnlar ustunlashdiriladi
    va o'girishlar saqlanadi.
</pre>
```

Bu kodlarni brauzerda ko'rishda, matn "pre" tagi ichida saqlangan asl ko'rinishida ko'rinadi. Bu, kodni joylashtirishda va konsoldagi matnlarni o'girishlarni saqlashda juda foydali bo'ladi.

— <b> va <strong>
`<b>` va `<strong>` HTML taglari matn bo'lishi kerak bo'lgan qismi qalin yoki bold qilish uchun ishlatiladi, ammo ulardagi maqsad va ulardagi shakllar ustunliklar yoki ahamiyatni ta'kidlashda farq qiladi.

1. `<b>` tagi:
   - `<b>` (bold) tagi, uning tarkibi qalin ko'rinishga ega bo'lgan matnni belgilaydi.
   - Bu tag qalin yoki bold ko'rinishga ega bo'lgan matnlarni belgilash uchun ishlatiladi, ammo matnning ahamiyatini ta'kidlash uchun emas.
   # SEO  
   Bu tag brauzer uchun sodda matn ko'rinishini o'zgartiradi, lekin SEO (Search Engine Optimization) va aksariyatlar uchun ahamiyatli emas.

Misol:

```html
<b>Yengil qalin matn</b>
```

2. `<strong>` tagi:
   - `<strong>` (kuchli) tagi, matnni kuchli ta'kidlash va uni ahamiyatini ta'kidlash uchun ishlatiladi.
   - Bu tag matnning kuchli yoki ahamiyatli bo'lgan qismini belgilaydi. Buning bilan birga, brauzerlar matnni qalin qiladi.
   # SEO 
   va brauzerlar uchun bu tag matnning ustuvorlik darajasini anglatadi.

Misol:

```html
<strong>Kuchli ta'kidlanayotgan matn</strong>
```

Asosiy farq, `<strong>` tagi matnning ma'nawi kuchini ta'kidlaydi va uni qalin qiladi, `<b>` tagi esa matnni odatiy qalin ko'rinishga o'giradi, ammo ma'noni ta'kidlashda kuchli emas. Agar matnning kuchli bo'lishi, `<strong>` tagidan foydalanish tavsiya etiladi.

 <i> va <em>

`<i>` va `<em>` HTML taglari matnning kursiv ko'rinishga o'tkazish uchun ishlatiladi, lekin ulardagi maqsad va ulardagi ma'nolar farq qiladi.

1. `<i>` tagi:
   - `<i>` (italic) tagi, matnni kursiv (italik) ko'rinishga olib chiqadi.
   - Bu tag ko'p qollaniladi, lekin undan foydalanish har doim kerak emas. Chunki u brauzerlar uchun sodda matn ko'rinishini o'zgartiradi, lekin matnning ma'nasiga emas.
   - Aksincha, `<i>` tagi odamlar uchun ko'rinishni o'zgartirishga mas'ul bo'lmagan qonuniyati ko'rsatadi.

Misol:

```html
<i>Kursiv matn</i>
```

2. `<em>` tagi:
   - `<em>` (emphasis) tagi, matnni ma'niy ta'kidlash va uning ma'nasini ajratib turadi.
   - Bu tag matnning kursiv (italik) ko'rinishiga olib chiqadi, lekin ularning asosiy maqsadi matnni ma'niy ta'kidlashdir.
   # SEO
    (Search Engine Optimization) va brauzerlar uchun `<em>` tagi matnning ustuvorlik darajasini ko'rsatadi.

Misol:

```html
<em>Ma'niy ta'kidlanayotgan matn</em>
```

Asosiy farq, `<i>` tagi matnning sodda kursiv ko'rinishini olish uchun ishlatiladi, `<em>` tagi esa matnning ma'niy ta'kidini bildiradi va uni kursiv qiladi. Agar matnning ma'niy ta'kidi kerak bo'lsa, `<em>` tagidan foydalanish tavsiya etiladi.

— <marker>

`<marker>` HTML tagi SVG (Scalable Vector Graphics) elementlari ichida ishlatiladi va qo'shimcha burchak markerlarni belgilash uchun foydalaniladi. Bu tag quyidagi qo'shimcha xususiyatlar bilan birgalikda ishlaydi:

- `<marker>` tagi `id` atributini olishi mumkin. Bu atribut SVG dokumentida boshqa elementlar bilan ulashish uchun kerak bo'ladi.
- `<marker>` tagi ichida qo'shimcha burchak markerlarni belgilashda qo'llaniladi. Ular chiziq o'zgaruvchilari, yon yo'nalishlari yoki ko'chishlari belgilanadi.

`<marker>` tagi odatda `<path>`, `<line>`, `<polyline>`, `<polygon>`, va boshqa SVG shakllarida ishlatiladi.

Misol:

```html
<svg
  width="100"
  height="100">
  <defs>
    <marker
      id="triangle"
      markerWidth="10"
      markerHeight="10"
      refX="0"
      refY="3"
      orient="auto"
      fill="red">
      <path d="M0,0 L0,6 L9,3 z" />
    </marker>
  </defs>
  <polyline
    points="20,20 80,80"
    style="stroke:black; fill:none;"
    marker-end="url(#triangle)" />
</svg>
```

Bu kodda, `<marker>` tagi burchak markerini belgilaydi va `<polyline>` tagi esa markerdan foydalanadi. Bu marker uchun burchakni va rangni belgilaydi.
— <del> va <ins>
`<del>` HTML tagi matndagi o'chirilgan yoki eskirilgan ma'lumotlarni belgilash uchun ishlatiladi.

Misol:

```html
<p>Ushbu <del>o'chirilgan</del> matn.</p>
```

Bu kod HTML matndagi "o'chirilgan" so'zni brauzerda o'chirilgan qilib ko'rsatadi. Odatda, brauzerlar bu tagni qora yoki qopqon rangida ko'rsatishadi, lekin o'chirilgan ma'lumotlarni haqiqiy ravishda o'chirib tashlamaydi.

`<del>` tagi

# SEO 
(Search Engine Optimization) ni ta'minlashda ham muhimdir, chunki brauzerlar o'chirilgan matnni bir nechta so'rov yorlig'ida ehtiyotkorlik qilish uchun foydalanadi.

`<ins>` HTML tagi matnga qo'shilgan yangi yoki qo'shilgan ma'lumotlarni belgilash uchun ishlatiladi.

Misol:

```html
<p>Ushbu <ins>yangi</ins> matn.</p>
```

Bu kod HTML matndagi "yangi" so'zni brauzerda qo'shilgan qilib ko'rsatadi. Odatda, brauzerlar bu tagni pastli yoki qora rangida ko'rsatishadi.

`<ins>` tagi

# SEO 
(Search Engine Optimization) ni ta'minlashda ham muhimdir, chunki brauzerlar qo'shilgan matnni bir nechta so'rov yorlig'ida ehtiyotkorlik qilish uchun foydalanadi.

— <sub> va <sup>
`<sub>` va `<sup>` HTML taglari, matnning pastlik yoki yuqorilik belgilash uchun ishlatiladi.

1. `<sub>` tagi:
   - `<sub>` (subscript) tagi matndagi tekstni pastlikda ko'rsatadi.
   - Ushbu tag alohida nuqtada yozilgan matnni pastlikda ko'rsatadi.
   - Masalan, kimyoviy formulalarda kimyoviy elementlar indekslarini belgilash uchun foydalaniladi.

Misol:

```html
H<sub>2</sub>O
```

Bu kod HTML matndagi "2" raqamini pastlikda ko'rsatadi, shuningdek, "H2O" so'zining pastligini bildiradi.

2. `<sup>` tagi:
   - `<sup>` (superscript) tagi matndagi tekstni yuqorilikda ko'rsatadi.
   - Ushbu tag alohida nuqtada yozilgan matnni yuqorilikda ko'rsatadi.
   - Masalan, matematik formulalarda darajani belgilash uchun foydalaniladi.

Misol:

```html
x<sup>2</sup>
```

Bu kod HTML matndagi "2" raqamini yuqorilikda ko'rsatadi, shuningdek, "x²" ni yuqorilikda bildiradi.

`<sub>` va `<sup>` taglari brauzerlarda alohida nuqtada yoki belgilangan matnda pastlik va yuqorilikni ko'rsatish uchun foydalaniladi. Bu taglar esa, matning turini ta'kidlash uchun foydalanilmasligi kerak.

— <q> va <blockquote>
`<q>` va `<blockquote>` HTML taglari matndagi sitat (sitos)larni belgilash uchun ishlatiladi.

1. `<q>` tagi: `qoshtirnoq ochadi` 
   - `<q>` (quote) tagi, qisqa matnli sitosni belgilash uchun ishlatiladi.
   - Ushbu tag biror bir sitos (sitatsiya) qisqartmasini belgilaydi, masalan, bir so'z, juft so'z yoki qisqa ibora.
   
Misol:
```html
<p>Bir inson o'z fikrini izohlashga aytib, "Ma'raka <q>erda</q> ketgan odamlar uchun yaxshi emas" dedi.</p>
```
Bu kod HTML matndagi "erda" so'zini qo'shimcha sitat ko'rinishida ko'rsatadi.

2. `<blockquote>` tagi: "`tab`" tashlaydi
   - `<blockquote>` (block quote) tagi uzun sitosni belgilash uchun ishlatiladi.
   - Ushbu tag katta sitosni belgilaydi, masalan, qo'shimcha odam yoki maqolani ko'rsatish uchun yoki bir maqolani to'liq ko'chirish uchun foydalaniladi.
   
Misol:
```html
<blockquote>
  <p>Bir inson o'z fikrini izohlashga aytib, "Ma'raka erda ketgan odamlar uchun yaxshi emas" dedi.</p>
</blockquote>
```
Bu kod HTML matndagi sitosni blok ko'rinishida belgilaydi.

`<q>` va `<blockquote>` taglari brauzerlarda sitatlarni o'zgartirish va aniq ravishda ko'rsatish uchun foydalaniladi. `cite` atributi yordamida asosiy matnning manzili ko'rsatilishi mumkin.


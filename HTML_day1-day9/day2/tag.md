# HTML (`HyperText Markup Language`) - 
bu veb-sahifalarni tuzish va ko'rsatish uchun ishlatiladigan standart markaziyat tili. HTML dastlab 1993-yilda ishlab chiqilgan va veb-sahifalarni tuzishda asosiy vosita bo'lgan.

# HTML (HyperText Markup Language) dasturlash tilida "`tag`" va "`element`" ikki farqli narsa. Bu termlar adashgan, lekin ularning manolari farq qiladi:

1. **Tag**: HTML-da tag (belgi) - bu boshqa HTML elementlarini belgilovchi belgilash. Masalan, `<p>`, `<div>`, `<img>`, `<a>`, va hokazo. Taglar odatda kichik harflar bilan yoziladi va o'qish shaklida yana qatorlar (teglar) orqali yoziladi.

2. **Element**: HTML-da element - bu tag (belgi) bilan birga matn yoki boshqa ma'lumotlarni o'z ichiga olgan to'liq element. Masalan, `<p>` tagi yoki `<a href="https://www.example.com">` tagi. Elementlar taglarning o'qish shakli bilan birga uni ichiga olgan ma'lumotlar to'plami hisoblanadi.

 # Bu ikki ko'rinish HTML-da "`tag`" (belgi)lar haqida:

1. **<tag nomi/>**: Bu samarali ko'rinish HTML-dagi "empty tag" (bo'sh belgi) deb nomlanadi. Bu taglar matn yoki boshqa ma'lumotlarni o'z ichiga olishmaydi va faqat birinchi qismida ishlatiladi. Masalan, `<img>` tagi rasmlarni ko'rsatish uchun ishlatiladi:

   ```html
   <img src="rasm.jpg" alt="Rasm" />
   ```

   Bu misolda `<img>` tagi `src` va `alt` atributlarini o'z ichiga oladi, lekin matn yoki boshqa ma'lumotlarni emas.

2. **<tag nomi>matn</tag nomi>**: Bu esa HTML-dagi oddiy belgilangan tag (element)dir. Bu taglar matn yoki boshqa ma'lumotlarni o'z ichiga oladi va ochiq va yopiq qismida ishlatiladi. Misol:

   ```html
   <p>Salom, dunyo!</p>
   ```

   Bu misolda `<p>` tagi "Salom, dunyo!" matnini o'z ichiga oladi va ochiq (`<p>` va `</p>`) qismida ishlatiladi.

Bu ikkala usul HTML-da ma'lumotlarni strukturallash va ko'rsatish uchun ishlatiladi, lekin ularning foydalanish tartibi va qoidalariga rioya qilish lozim.

Ko'p holatlarda "tag" va "element" so'zlarini bir biriga almashtirish mumkin, lekin ularning manolari aslida farq qiladi. "Tag" - bu belgi, va "element" - bu belgi bilan birga o'z ichiga olgan to'liq ma'lumotlarni (atributlar, matn, va hokazo) to'plami.

HTML-da odatda o'zgaruvchilarni qanday tuzish va matnni qanday ko'rsatish kerakligini aytib beruvchi turli taglar (belgilar) mavjud. Buning tufayli, HTML taglari ko'rsatilayotgan ma'lumotlar strukturasini, shakllantirishini va matnni ko'rsatish usullarini belgilaydi.

Taglar quyidagi xil turdagi bo'lib, har biri o'z vaqti, ko'rsatish usuli va maqsadi bor:

1. **Bloklar**: Bu taglar matnni bloklarga bo'lish uchun ishlatiladi, masalan, `div`, `p`, `header`, `footer`.
2. **Inline**: Ushbu taglar matndagi ma'lum bir qismini ko'rsatish uchun ishlatiladi, masalan, `span`, `strong`, `em`.
3. **Tavsiflash**: Bu taglar matndagi elementni tavsiflash uchun ishlatiladi, masalan, `title`, `alt`, `aria-label`.
4. **Form**: Foydalanuvchidan ma'lumotlarni qabul qilish uchun ishlatiladi, masalan, `input`, `button`, `select`.
5. **Media**: Multimedia elementlarni ko'rsatish uchun ishlatiladi, masalan, `img`, `video`, `audio`.
6. **Table**: Jadvallarni yaratish uchun ishlatiladi, masalan, `table`, `tr`, `td`.
7. **Meta**: Sahifaning ma'lumotlarini belgilash uchun ishlatiladi, masalan, `meta`, `title`.
8. **List**: Ro'yxatlar yaratish uchun ishlatiladi, masalan, `ul`, `ol`, `li`.

Bu, faqat ba'zi taglarning misollaridir. HTML-da ko'p taglar mavjud va har biri o'z xususiyatlari bilan birgalikda foydalaniladi. Raqamli ro'yxatda elementlarni tartiblash uchun `ol`, matn elementlarini ko'rsatish uchun `p` yoki `span`, rasmlarni ko'rsatish uchun `img` va h.k.

HTML taglari veb-sahifalarni shakllantirish va ma'lumotlarini ko'rsatishning asosiy vositasidir.

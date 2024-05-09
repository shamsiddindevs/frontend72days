- **form tagi va atributlari**: `<form>` HTML-dagi formani yaratish uchun ishlatiladi. Ba'zi muhim atributlar:

  - `action`: Formani yuborish kerak bo'lgan url manzilini belgilaydi.
  - `method`: Forma yuborilishi kerak bo'lgan HTTP uslubi (GET yoki POST).
  - `target`: Yuborish natijalarini ko'rsatish uchun boshqa brauzer oynasini belgilaydi.

  Masalan:
  ```html
  <form action="/submit" method="post" target="_blank">
      <!-- Forma elementlari bu yerni o'z ichiga oladi -->
  </form>
  ```

- **form inputlari va ularning typelari**: Formalarning tarkibiy qismi. Turli xil input turlari mavjud, masalan, matn kiriting, tugmachalar, radioknopkalari va boshqalar.

  Masalan:
  ```html
  <input type="text" name="username" />
  <input type="password" name="password" />
  <input type="submit" value="Submit" />
  ```

- **placeholder**: Input maydonchalariga shartnoma matni ko'rsatish uchun ishlatiladi.

  Masalan:
  ```html
  <input type="text" placeholder="Ismingizni kiriting" />
  ```

- **autocomplete**: Brauzer tomonidan formani otomatik to'ldirishni yo'qotish yoki yo'q qilish uchun ishlatiladi.

  Masalan:
  ```html
  <form autocomplete="off">
      <!-- Forma elementlari bu yerni o'z ichiga oladi -->
  </form>
  ```

- **select / option / default select**: `select` elementi ro'yxatdan tanlovni, `option` esa har bir tanlovni belgilaydi.

  Masalan:
  ```html
  <select name="cars">
      <option value="volvo">Volvo</option>
      <option value="saab">Saab</option>
  </select>
  ```

- **fieldset / legend**: `fieldset` HTML formani guruhlarga bo'lishi uchun ishlatiladi, `legend` esa guruhning sarlavhasini belgilaydi.

  Masalan:
  ```html
  <fieldset>
      <legend>Contact Information</legend>
      <!-- Forma elementlari bu yerni o'z ichiga oladi -->
  </fieldset>
  ```

- **input with datalist / list**: `datalist` elementi bilan birgalikda ishlatiladi, foydalanuvchiga input maydonchasi uchun ro'yxat beriladi.

  Masalan:
  ```html
  <input list="browsers" name="browser">
  <datalist id="browsers">
      <option value="Chrome">
      <option value="Firefox">
      <option value="Edge">
      <option value="Safari">
  </datalist>
  ```
  Semantic taglar foydalanishning birinchi sababi, sahifadagi ma'lumotlarni ta'riflash va tuzilishini sodda qilishdir. Bu, brauzerlarga sahifadagi tarkibni yaxshi tushunish va uning maqsadini aniqlashda yordam beradi. Quyidagi sabablar semantic taglardan foydalanish kerak:

1. **Ta'riflash**: Semantic taglar HTML ma'lumotlarini aniqroq ta'riflashga imkon beradi. Masalan, `<header>` sahifaning boshlang'ich qismini, `<footer>` esa sahifaning oxirgi qismini ta'riflaydi.

2. **Akseslar uchun yaxshi**: Brauzerlar, ekran oxiriga qarab, sahifadagi ma'lumotlarni alohida qismga bo'lishi mumkin. Semantic taglar brauzerlarga sahifadagi maqsadni tushunishga yordam beradi va foydalanuvchilarga sahifadagi tartibni yaxshi tushunish imkonini beradi.

3. **SEO uchun yaxshi**: Search engine optimizatsiyasi (SEO) ni o'ylab ko'rishda, semantic taglar ma'lumotlarni qidiruv tizimlari uchun aniqroq ko'rsatadi. Masalan, `<article>` tagi sahifadagi asosiy maqolalarni ta'riflaydi va ularni qidiruv natijalarida ustun joyga olishga yordam beradi.

4. **Ishlab chiqarishni osonlashtirish**: Semantic taglar sahifalarni o'rganish va ularga o'zgartirishni osonlashtiradi. Dasturchilar va dizaynerlar o'zlarining kodlariga tezroq tushishlari va ulardan foydalanshini osonlashtiradi.

5. **Qiziqish uchun yaxshi**: Semantik taglar HTML kodini o'rganishni osonlashtiradi. Yangi dasturchilar uchun, kodni tushuntirish va uni tuzish osonroq bo'ladi.

Bu sabablar bilan, semantic taglardan foydalanish brauzerlar, foydalanuvchilar va dasturchilar uchun bir qancha foydali imkoniyatlarni beradi.
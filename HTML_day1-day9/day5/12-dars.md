— Table nima?
— Table qanchalik muhim? real projectdagi ko'rinishi.
— table border / border-collapse: collapse
— table, tr, td, th.
— Table sizing.
— colspan / rowspan
— Column grouping

Jadval (table) HTML-da ma'lumotlar tizimini ko'rsatish uchun ishlatiladi. Bu ma'lumotlar ustida tuzilgan kvadratlar (qatorlar va ustunlar) orqali ma'lumotlar tartibini ifodalaydi.

Jadvalning muhimligi real proyektlarda ma'lumotlarni o'rganish, tizimlash va ko'rsatishning qulay usuli sifatida qaralgan. Misol uchun, shaxsiy veb sahifalarda ma'lumotlar ro'yxatini, hisob-kitob o'lchovlarini, natijalarni ko'rsatishda juda foydalaniladi.

HTML jadval elementlariga misollar:

1. **Table Border / Border-Collapse: Collapse**:
   - `border` stil atributi jadvalning burchaklarini belgilaydi.
   - `border-collapse: collapse;` stil atributi burchaklarni qoshish yoki birlashtirishni belgilaydi.
   - Misol: `table { border: 1px solid black; border-collapse: collapse; }`

2. **Table, tr, td, th**:
   - `<table>`: Jadvalni boshlanishi.
   - `<tr>`: Qator (satr).
   - `<td>`: Jadvalda ma'lumot (maydon).
   - `<th>`: Jadval ustunining sarlavhasi.
   - Misol: 
     ```html
     <table>
         <tr>
             <th>Column 1</th>
             <th>Column 2</th>
         </tr>
         <tr>
             <td>Data 1</td>
             <td>Data 2</td>
         </tr>
     </table>
     ```

3. **Table Sizing**:
   - Jadvalning kengligi va balandligi `%`, `px`, yoki `em`da belgilanadi.
   - Misol: `<table width="100%" height="200px">...</table>`

4. **Colspan / Rowspan**:
   - `colspan` ustunlar (columns)ni birlashtirish, `rowspan` qatorlarni birlashtirish uchun ishlatiladi.
   - Misol: `<td colspan="2">...</td>`

5. **Column Grouping**:
   - Ustunlarni guruhlash uchun `<colgroup>` va `<col>` elementlari ishlatiladi.
   - Misol: 
     ```html
     <table>
         <colgroup>
             <col span="2" style="background-color: lightblue;">
             <col style="background-color: lightgreen;">
         </colgroup>
         <!-- Jadval ustunlari va ma'lumotlari -->
     </table>
     ```

Jadval HTML-da ma'lumotlar ko'rsatishning keng qo'llaniladigan usullaridan biri hisoblanadi va shuning uchun real proyektlarda ko'p ko'rishiladi.
# 13 - dars | Lists | YouTube Link
— list nima?
— ordered list
— unordered list
— description list
— nested list
— ordered list style
— unordered list style
— list-style-type / css orqali type o'zgartirish
Menga yoqadi! Listlar HTML-da ma'lumotlar tizimini ko'rsatish uchun ishlatiladi. Listlar turlari:

1. **List (Ro'yxat)**:
   - Ma'lumotlar tizimi bo'lishi kerak bo'lgan elementlar.
   - Ro'yxat (list) HTML-da, matnni tartibga keltirish uchun qo'llaniladi.

2. **Ordered List (Tartiblangan ro'yxat)**:
   - Ma'lumotlar tartiblangan holda ko'rsatilishi kerak bo'lsa ishlatiladi.
   - `<ol>` elementi bilan belgilanadi.
   - Tartiblangan ro'yxatda, har bir ma'lumot raqamlandiriladi.

3. **Unordered List (Tartibsiz ro'yxat)**:
   - Ma'lumotlar tartibsiz holda ko'rsatilishi kerak bo'lsa ishlatiladi.
   - `<ul>` elementi bilan belgilanadi.
   - Tartibsiz ro'yxatda, har bir ma'lumot belgilangan belgi bilan ko'rsatiladi, masalan, nuqta (`•`).

4. **Description List (Ta'rif ro'yxati)**:
   - Ma'lumotlar ro'yxati ichida har bir ma'lumotga ta'rif berilishi kerak bo'lsa ishlatiladi.
   - `<dl>` (Description List) elementi bilan belgilanadi.
   - Har bir ma'lumot (`<dt>`) va uni ta'rif (`<dd>`) belgilanadi.

5. **Nested List (Ichki ro'yxat)**:
   - Boshqa ro'yxatning ichida boshqa ro'yxatlar bo'lishi mumkin.
   - Misol: 
     ```html
     <ul>
         <li>Element 1</li>
         <li>Element 2
             <ul>
                 <li>Ichki element 1</li>
                 <li>Ichki element 2</li>
             </ul>
         </li>
     </ul>
     ```

6. **Ordered List Style (Tartiblangan ro'yxat shakli)**:
   - Tartiblangan ro'yxatda, raqamlar (`1`, `2`, `3`, ...) yoki belgilar (`a`, `A`, `i`, `I`, ...) ishlatiladi.
   - Misol: `<ol type="1">...</ol>` yoki `<ol type="A">...</ol>`.

7. **Unordered List Style (Tartibsiz ro'yxat shakli)**:
   - Tartibsiz ro'yxatda, belgilar (`disc`, `circle`, `square`, ...) ishlatiladi.
   - Misol: `<ul style="list-style-type: circle;">...</ul>`.

`list-style-type` CSS stil atributi orqali tartiblangan va tartibsiz ro'yxatlarning shaklini o'zgartirish mumkin.
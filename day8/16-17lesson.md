# 16 - dars | Iframe | YouTube Link
— iframe nima va nima maqsadda ishlatiladi?
— boshqa websitelarni o'zingizda ishlatish.
— YouTube videolarini html  da chiqarish.
- **iframe nima va nima maqsadda ishlatiladi?**
  - `<iframe>` HTML elementi, boshqa veb-sahifalarni yoki hujjatlarni joriy HTML sahifaga joylashtirish uchun ishlatiladi. 
  - Ushbu element yordamida boshqa veb-sahifalarning barcha yoki qismiyini ifodalay olasiz, shuningdek boshqa veb-tizimlardan (masalan, YouTube, Google Maps) olingan kontentni sahifangizga qo'shishingiz mumkin.

- **Boshqa websitelarni o'zingizda ishlatish**:
  - `<iframe>` orqali boshqa veb-sahifalarni o'zingizning sahifangizda ko'rsatishingiz mumkin.
  - Misol:
    ```html
    <iframe src="https://www.example.com" width="600" height="400"></iframe>
    ```

- **YouTube videolarini HTML da chiqarish**:
  - YouTube videolarni HTML sahifangizda chiqarish uchun `<iframe>` elementi ishlatiladi.
  - YouTube videolari avtomatik ravishda HTML5 formatida yuklanadi.
  - Misol:
    ```html
    <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
    ```
  - `VIDEO_ID` qismiga YouTube videoning identifikatsiya raqami (ID) kiritiladi.

# 17 - dars | JavaScript in HTML | YouTube Link
Eslatma! Ushbu mavzuni tushunishga qiynalsangiz keyingi darslikka o'tishingiz mumkin. Bu mavzu JS darslarida batafsil tushuntiriladi.
— javascript nima vazifa bajaradi?
— script tagi haqida
— console.log nima?
— document nima?
— queryselector use case.
— javascript orqali style berish
— onclick / onmousemove
— function
- **JavaScript nima vazifa bajaradi?**
  - JavaScript veb-sahifalarda interaktivlik qo'shish, ma'lumotlarni boshqarish, animatsiyalar yaratish, foydalanuvchilar bilan kommunikatsiya o'rnatish va sairadagi bir nechta vazifalarni bajaradi. Ushbu skript tilining yordamida sahifalar dinamik ravishda ishlaydi va dinamik interfeyslar yaratiladi.

- **Script tagi haqida**:
  - `<script>` HTML elementi JavaScript kodini sahifaga qo'shish uchun ishlatiladi. Bu tagning `src` attributi yordamida har xil fayllardagi JavaScript kodlarini chaqirish mumkin.
  - Misol:
    ```html
    <script>
        // JavaScript kodlar
    </script>
    ```

- **console.log nima?**
  - `console.log()` JavaScript funktsiyasi brauzer konsolida matnlar yoki obyektlarni chiqaradi. Bu, kodni diagnostik qilishda yordam beradi va oshkora xabarlar chiqarish uchun keng foydalaniladi.
  - Misol:
    ```javascript
    console.log("Salom, JavaScript!");
    ```

- **document nima?**
  - `document` JavaScript obyekti HTML dokumentni ifodalaydi. Bu obyekt HTML elementlariga, veb-sahifaning strukturasi va elementlarga dastlabki kirish imkoniyatini beradi. Siz `document` obyekt orqali veb-sahifangizdagi elementlarga kirishingiz, ular ustida amallar bajarishingiz va dinamik tahrirlar kiritishingiz mumkin.

- **querySelector ne ishlatiladi?**
  - `querySelector()` metod HTML dokumentdagi biror elementni topish uchun ishlatiladi. Bu metod CSS selectorlari yordamida elementlarni topib oladi va ularni birinchi topilgan element qaytaradi.
  - Misol:
    ```javascript
    const element = document.querySelector("#myElement");
    ```

- **JavaScript orqali style berish**:
  - JavaScript orqali elementlarga uslubni o'zgartirish uchun, elementning `style` atributiga JavaScript obyektining `style` sifatidan foydalanishingiz mumkin.
  - Misol:
    ```javascript
    const element = document.getElementById("myElement");
    element.style.color = "red";
    ```

- **onclick / onmousemove**:
  - `onclick` va `onmousemove` HTML atributlari, belgilangan element ustida foydalanuvchi amallarini qo'llab-quvvatlaydigan JavaScript funktsiyalarini chaqirish uchun ishlatiladi. `onclick` atributi boshlang'ichma bosinganida, `onmousemove` esa foydalanuvchi element ustida yo'ng'in harakat qilganda ishga tushadi.
  - Misol:
    ```html
    <button onclick="myFunction()">Bosing</button>

    <script>
        function myFunction() {
            alert("Siz tugma bosdingiz!");
        }
    </script>
    ```

- **Function**:
  - JavaScriptda funksiyalar, qayta-qayta qaytariladigan kod bloklarini tuzish uchun ishlatiladi. Funksiyalar kodni boshqa joylarda chaqirish uchun o'zgaruvchilar, matnlarni va boshqa qiymatlar qabul qilish uchun foydalaniladi.
  - Misol:
    ```javascript
    function greet(name) {
        console.log("Salom, " + name);
    }

    greet("Ali"); // "Salom, Ali"
    ```
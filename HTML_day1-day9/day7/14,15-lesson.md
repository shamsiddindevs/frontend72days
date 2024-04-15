 # 14 - dars | Block | Inline  | YouTube Link
— block tagi nima?
— inline tagi nima?
— inline vs block taglarining farqarli.

- **Block tagi nima?**:
  - Blok elementlar, matnni yoki kontentni ekranning bir qatori (qator) bo'ylab to'ldiradigan HTML elementlardir.
  - Misollar: `<div>`, `<p>`, `<h1>`, `<ul>`, `<li>`, `<table>`, `<blockquote>`, `<footer>`, `<header>`.

- **Inline tagi nima?**:
  - Inline (satr) elementlar, matnni o'q qatorlar ichida joylashtirish uchun ishlatiladi.
  - Misollar: `<span>`, `<a>`, `<strong>`, `<em>`, `<img>`, `<b>`, `<i>`, `<input>`.

- **Inline vs Block taglarining farqarli**:
  - Blok elementlar, ekranning butunini egallayadi va bir qator bo'ylab to'ldiradi.
  - Inline elementlar esa faqat matnning ilgari kerak bo'lgan joyini egallaydi va qator bo'ylab o'rnini egallayadi.

# 15 - dars | Media | YouTube Link
— video tagi nima vazifa bajaradi?
— nega autoplay attr ishlamaydi? Izoh.
— video ustiga cover(obloshka) qo'yish
— audio tagi va attributelari.

- **Video tagi nima vazifa bajaradi?**
  - `<video>` HTML tagi video fayllarni ko'rsatish uchun ishlatiladi. Ushbu tag orqali brauzerlar foydalanuvchilarga video oynatish imkoniyatini beradi.

- **Nega autoplay attributi ishlamaydi? Izoh**
  - Bir nechta brauzerlar va mobil qurilmalar ta'rifi yoki eng yuqori amalga oshirish (autoplay)ning foydalanuvchilarga xavfsizlik risqini keltirishi mumkin. Masalan,  foydalanuvchilarning internet tarifi qulay emas yoki ular boshqa vaziyatlarda video avtomatik ravishda ijro etishi kerak emas.

- **Video ustiga cover(obloshka) qo'yish**
  - Video ustiga cover(obloshka) qo'yish uchun, `<video>` elementini o'rtasiga div elementini joylashtirish mumkin. Keyin CSS yordamida divga background rasm (cover) qo'yiladi. Bu usul video hajmini o'zlashtirishda yordam beradi va rasm video bilan birga aylanadi.
  - Misol:
    ```html
    <div class="video-container">
        <video autoplay loop muted>
            <source src="video.mp4" type="video/mp4">
        </video>
    </div>
    ```
    CSS:
    ```css
    .video-container {
        position: relative;
        width: 100%;
        height: 0;
        padding-top: 56.25%; /* 16:9 aspect ratio */
    }
    .video-container video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    ```

- **Audio tagi va attributelari**
  - `<audio>` tagi HTML-da audiolarni ko'rsatish uchun ishlatiladi. Bu tagga turli attributelar qo'shilishi mumkin:
    - `src`: Audio faylning URL manzili.
    - `autoplay`: Audio faylni avtomatik ravishda ijro etishini ta'minlaydi.
    - `loop`: Audio faylni tugagandan so'ng avtomatik ravishda qaytarilishini ta'minlaydi.
    - `controls`: Audio faylni boshqarish uchun nazorat panelini ko'rsatish imkonini beradi.
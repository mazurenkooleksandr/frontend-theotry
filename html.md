<h2>HTML</h2>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке HTML і для чого він використовується?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>
    HTML (HyperText Markup Language) - це мова розмітки, яка використовується для створення веб-сторінок. </br>HTML складається з елементів, які використовуються для розмітки тексту, зображень, таблиць, форм і інших елементів веб-сторінки. Елементи HTML починаються і закінчуються тегами. Теги можуть мати атрибути, які надають додаткову інформацію про елемент.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Яким чином ви визначаєте кодування документу в HTML?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Кодування документу в HTML визначається за допомогою тега meta. Тег meta використовується для надання додаткової інформації про веб-сторінку, включаючи її кодування. Атрибут charset тега meta визначає кодування символів, яке використовується для веб-сторінки.</br>Атрибут charset може приймати наступні значення:</br>
    - UTF-8: Це найпоширеніше кодування символів в Інтернеті. Воно підтримує більшість мов світу.</br>
    - ISO-8859-1: Це застаріле кодування символів, яке все ще підтримується деякими браузерами. Воно підтримує лише латинський алфавіт.</br>
    - Windows-1252: Це інше застаріле кодування символів, яке все ще підтримується деякими браузерами. Воно підтримує латинський алфавіт, а також деякі символи, які використовуються в європейських мовах.</br>
    Ви можете визначити кодування документу в будь-якому місці в головному розділі HTML, але найкраще це зробити в тегу head</ безпосередньо після тега title.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке теги і як вони використовуються в HTML?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Теги - це елементи HTML, які використовуються для структурування тексту, зображень, таблиць, форм і інших елементів веб-сторінки. </br>Ось деякі з основних типів тегів HTML:</br>
    - Елементи структури: Елементи структури використовуються для визначення структури веб-сторінки. Наприклад, теги html, head, body, h1, p, ul, li, table, tr, td використовуються для визначення структури веб-сторінки.</br>
    - Елементи змісту: Елементи змісту використовуються для додавання контенту на веб-сторінку. Наприклад, теги img, audio, video, script,  style  використовуються для додавання контенту на веб-сторінку.</br>
    - Елементи керування: Елементи керування використовуються для створення форм. Наприклад, теги input, select, textarea використовуються для створення форм.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як виглядає базова структура HTML-документу?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Базова структура HTML-документу складається з двох основних частин:</br>
     - Заголовок (head): містить метадані про веб-сторінку, такі як її кодування, заголовок, ключові слова та інші.</br>
     - Тіло (body): містить видимий вміст веб-сторінки, такий як текст, зображення, таблиці, форми та інші елементи.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке DOCTYPE і як він використовується?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>DOCTYPE - це спеціальний тег, який використовується в HTML-документах для визначення браузером версії HTML, яка використовується. DOCTYPE також може містити додаткову інформацію про документ, наприклад, його тип або призначення.</br>
    DOCTYPE починається з символа !DOCTYPE html. Після цього слідує назва документа, а потім список правил, які використовуються для інтерпретації документа.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити форму в HTML?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Щоб створити форму в HTML, необхідно використовувати тег form. </br>Основні атрибути тега form такі:</br>
    - action - визначає URL-адресу, за якою буде відправлена інформація з форми.</br>
    - method - визначає спосіб відправки інформації з форми. Можливі значення: post і get.</br>
        * post - інформація відправляється в тілі HTTP-запиту. Цей метод використовується за замовчуванням.
        * get - інформація відправляється в URL-адресі HTTP-запиту. Цей метод не рекомендується використовувати для відправки чутливої інформації, оскільки вона буде відображатися в адресному рядку браузера.
    - enctype - визначає спосіб кодування інформації, що відправляється з форми.</br>
    - name - ім'я форми. Це ім'я використовується для посилань на форму в сценарії обробки форми.</br>
    </p>
    <pre>
      <form action="/process-form.php" method="post">
        <input type="text" name="name" />
        <input type="submit" value="Відправити" />
      </form>
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити текстове поле вводу (input type="text")?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Основні атрибути тега input type="text" такі:</br>
      - name - ім'я текстового поля. Це ім'я використовується для посилань на текстове поле в сценарії обробки форми. </br>
      - value - початкове значення текстового поля. </br>
      - placeholder - текстовий підказка, яка відображається в текстовому полі, поки користувач не введе текст. </br>
      - size - ширина текстового поля в символах. Значення за замовчуванням 20.</br>
      - maxlength - максимальна довжина тексту, який може бути введений в текстове поле.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити поле пароля (input type="password")?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Основні атрибути тега input type="password" такі:</br>
      - name - ім'я поля пароля. Це ім'я використовується для посилань на поле пароля в сценарії обробки форми.</br>
      - value - початкове значення поля пароля.</br>
      - placeholder - текстовий підказка, яка відображається в полі пароля, поки користувач не введе текст.</br>
      - size - ширина поля пароля в символах.</br>
      - maxlength - максимальна довжина тексту, який може бути введений в поле пароля.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити кнопку відправки форми (input type="submit")?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Для створення кнопки відправки форми використовується тег input type="submit". Цей тег визначає кнопку, яка при натисканні відправляє форму на сервер.</br>
       Основні атрибути тега input type="submit" такі:</br>
        - name - ім'я кнопки. Це ім'я використовується для посилань на кнопку в сценарії обробки форми.</br>
        - value - значення кнопки. Це значення відображається на екрані.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити вибір зі списком (dropdown) у формі?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Для створення вибору зі списком у формі використовується тег select. Цей тег визначає випадаючий список, з якого користувач може вибрати один або кілька варіантів.</br>
    Основні атрибути тега select такі:</br>
    - name - ім'я вибору зі списком.</br>
    - multiple - визначає, чи може користувач вибрати кілька варіантів з вибору зі списком. Значення за замовчуванням - false.</br>
    Всередині тега select можна використовувати теги option для визначення варіантів вибору.</br>
   Основні атрибути тега option такі:</br>
    - value - значення варіанту вибору. Це значення буде відправлено на сервер, якщо користувач вибирає цей варіант.</br>
    - selected - визначає, чи буде цей варіант вибраний за замовчуванням. Значення за замовчуванням - false./p></br>
    <pre>
      <select name="countries" multiple>
        <option value="de">Німеччина</option>
        <option value="pl">Польща</option>
        <option value="us">США</option>
      </select>
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити чекбокс та радіокнопку у формі?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Для створення чекбокса у формі використовується тег input type="checkbox".</br>
      Основні атрибути тега input type="checkbox" такі:</br>
      - name - імя чекбокса. Це імя використовується для посилань на чекбокс в сценарії обробки форми.</br>
      - value - значення чекбокса. Це значення буде відправлено на сервер, якщо чекбокс буде вибраний.</br>
      - checked - визначає, чи буде чекбокс вибраний за замовчуванням. Значення за замовчуванням - false.</br></br>
      <pre>
        <input type="checkbox" name="agree" />
        <label for="agree">Я погоджуюся з умовами</label>
      </pre>
      Для створення радіокнопки у формі використовується тег input type="radio".</br>
      Основні атрибути тега input type="radio" такі:</br>
      - name - ім'я радіокнопки. Це ім'я використовується для посилання на радіокнопку в сценарії обробки форми.</br>
      - value - значення радіокнопки. Це значення буде відправлено на сервер, якщо радіокнопка буде вибрана.</br>
      - checked - визначає, чи буде радіокнопка вибрана за замовчуванням. Значення за замовчуванням - false.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Для чого потрібний тег label?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Тег label використовується для створення підпису до елемента форми. Щоб використовувати тег label для підпису до елемента форми, потрібно виконати наступні дії:
      </br>
      - Додайте тег label до HTML-розмітки форми.</br>
      - Використовуйте атрибут for тега label для визначення ідентифікатора елемента форми, з яким він пов'язаний.</br>
      - Вкажіть текст мітки всередині тега label.
      <pre>
        <input type="text" name="name" />
        <label for="name">Ім'я</label>
      </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке семантичні теги і як вони використовуються в HTML5?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Семантичні теги - це теги HTML, які використовуються для того, щоб описати структуру та призначення вмісту веб-сторінки. Потрібно для індексації пошуковими системами та для доступності людей з обмеженими можливостями. </br>Ось деякі приклади семантичних тегів HTML5:</br>
    - header - визначає заголовок веб-сторінки.</br>
    - nav - визначає навігаційну панель.</br>
    - article - визначає статтю або інший самостійний елемент вмісту.</br>
    - section - визначає розділ веб-сторінки.</br>
    - aside - визначає додатковий вміст, який не є основним.</br>
    - figure - визначає графічний елемент, наприклад, зображення або таблицю.</br>
    - figcaption - визначає підпис до графічного елемента.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як використовувати теги header, footer, nav для розмітки документа?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Теги header, footer і nav - це семантичні теги HTML, які використовуються для розмітки документа. Вони дають браузеру інформацію про структуру і призначення вмісту на веб-сторінці.</br>
   - Тег header визначає заголовок документа. Він зазвичай містить інформацію про сайт, наприклад, логотип, назву сайту та контактну інформацію.</br>
   - Тег footer визначає нижню частину документа. Він зазвичай містить інформацію про права на копіювання, контактну інформацію або інші юридичні відомості.</br>
   - Тег nav визначає навігаційну панель, наприклад, головне меню. Він зазвичай містить посилання на інші сторінки сайту.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як використовувати тег section для логічного поділу документа?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Теги section використовуються для визначення логічних розділів вмісту, таких як:</br>
       - Розділи книги або статті</br>
       - Категорії вмісту</br> 
       - Вікна або сторінки в інтерфейсі користувача.</br>
      Наприклад:</br>
        main</br>
          section</br>
              h2  Розділ  h2</br>
              article</br>
                p  Зміст статті p</br>
              article</br>
          section</br>
        main
  </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як використовувати тег article для обгортання незалежного контенту?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Теги article використовуються для визначення незалежного контенту, такого як:</br>
      - Статті</br>
      - Блоги</br>
      - Новини</br>
      - Звіти
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як використовувати тег details та summary для створення випадаючого блоку?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Теги details та summary використовуються для створення випадаючого блоку. 
    Тег details має атрибут:
      - open - визначає, чи відкритий випадаючий блок за замовчуванням.
    Тег summary - визначає текст, який відображає загаловок у випадаючому блоці.
    <pre>
      <details open>
        <summary>Це випадаючий блок</summary>
        <p>Це тіло випадаючого блоку.</p>
      </details>
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як використовувати тег time для представлення часових моментів на сторінці?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Тег time має кілька атрибутів, які використовуються для визначення часового моменту:</br>
      - datetime - визначає дати і час часового моменту в форматі ISO 8601.</br>
      - datetime-local - визначає дати і час часового моменту в локальному форматі.</br>
      - hour - визначає годинник часового моменту.</br>
      - minute - визначає хвилини часового моменту.</br>
      - second - визначає секунди часового моменту.</br>
      - month - визначає місяць часового моменту.</br>
      - day - визначає день часового моменту.</br>
      - year - визначає рік часового моменту.</p>
   </br></br>
      time datetime="2023-07-20T12:00:00"</br>
      time datetime-local="2023-07-20T12:00:00"</br>
      time hour="12" minute="00" second="00"</br>
      time month="07" day="20" year="2023"</br>
  </div>
</details>

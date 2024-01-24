<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>JavaScript - це динамічна, об'єктно-орієнтована, прототипна мова програмування. JavaScript є об'єктно-орієнтованою мовою, що означає, що програми в JavaScript складаються з об'єктів. Об'єкти - це структури даних, які містять властивості та методи. JavaScript є прототипною мовою, що означає, що об'єкти створюються на основі прототипів. Прототипи - це об'єкти, які містять властивості та методи, які можуть бути успадковані іншими об'єктами.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які є типи даних в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Вісім типів даних, сім це примітиви, Object це не примітив.<br>
        - Number - числові дані, які можуть бути цілими або з рухомою комою.<br>
        - BigInt - використовується для зберігання великих цілих чисел.<br>
        - String - текстові дані.<br>
        - Boolean - логічні дані, які можуть бути true або false.<br>
        - Null - спеціальний тип даних, який означає відсутність значення.<br>
        - Undefined - спеціальний тип даних, який означає, що змінній не було присвоєне значення.<br>
        - Symbol - спеціальний тип даних, який використовується для унікальних ідентифікаторів.<br>
        - Object - структури даних, які містять властивості та методи.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Поясніть різницю між var, let та const.
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>var - це оператор оголошення змінної з функціональною областю видимості. Область видимості змінної var визначається за допомогою її місцеположення в коді.<br>
let - це оператор оголошення змінної з блоковою областю видимості. Область видимості змінної let обмежена блоком, в якому вона була оголошена.<br>
const - це оператор оголошення змінної з блоковою областю видимості, яка не може бути змінена. Значення змінної const може бути змінено тільки в момент її оголошення.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як працює область видимості змінних у JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У JavaScript існують дві основні типи областей видимості: глобальна та локальна. <br>
    - Глобальна область видимості (Global Scope): Змінні, які оголошуються поза будь-якою функцією чи блоком коду, визначаються в глобальній області видимості. Такі змінні можуть бути доступні в будь-якій частині коду, включаючи функції та блоки.<br>
    - Локальна область видимості (Local Scope): Змінні, оголошені всередині функції чи блоку коду, визначаються в локальній області видимості. Такі змінні доступні тільки всередині того контексту, в якому вони були оголошені.
    Коли код виконується, JavaScript здійснює пошук змінних у відповідній області видимості, спочатку шукаючи локальні змінні, а якщо таких немає, переходячи до глобальних. Якщо змінна не знайдена ні в одній з областей видимості, виникає помилка "ReferenceError".<br>
    - Функціональна область видимості (Functional Scope) або Лексична область видимості (Lexical Scope): Це концепція в JavaScript, в якій область видимості змінних визначається на основі місця їхнього оголошення у вихідному коді, а не місця виклику функції. Функціональна область видимості створюється тоді, коли функція оголошується, і вона зберігає доступ до змінних, які були оголошені в тому ж або більш високому контексті.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Яка різниця між == та ===?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>== (Порівняння за значенням): Цей оператор порівнює значення, конвертуючи їх у один і той же тип, якщо вони різні. Наприклад, 1 == '1' буде true, оскільки рядок '1' конвертується у число для порівняння.<br>
    === (Строге порівняння): Цей оператор порівнює значення і типи без конвертації. Він повертає true тільки в тому випадку, коли значення і типи обох операндів ідентичні. Наприклад, 1 === '1' буде false, оскільки типи (число і рядок) не збігаються.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке обєктні обгортки?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Об'єктні обгортки (Object Wrappers) в JavaScript є об'єктами, які оточують примітивні типи і дозволяють використовувати методи та властивості об'єктів для цих примітивів. </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке функції expression і declaration?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Функції expression і declaration - це два типи функцій в JavaScript. Вони відрізняються за своїм синтаксисом, областю видимості та поведінкою.<br>
    1. Функції expression<br>
    Функції expression, або функціональні вирази, створюються всередині будь-якого виразу в JavaScript. Вони мають наступні особливості:<br>
    - Вони створюються в контексті присвоєння виразу.<br>
    - Після ключового слова function не обов'язково вказувати назву функції.<br>
    - Функція expression може бути використана в якості значення в будь-якому вираженні.<br>
    2. Функції declaration<br>
    Функції declaration, або функції оголошення, декларуються окремо від основного коду. Вони мають наступні особливості:<br>
    - Вони створюються в окремій інструкція в основному потоці коду.<br>
    - Після ключового слова function обов'язково вказувати назву функції.<br>
    - Функція declaration може бути викликана тільки за її назвою.<br>
    - Hoisting. Функція declaration може бути викликана до того, як вона буде фактично визначена.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке стрілкові функції?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Стрілкові функції — це новий синтаксис введений в ECMAScript 6 (ES6), який надає коротший спосіб оголошення функцій. Відрізняються від функцій expression і declaration:<br>
    1. Синтаксис.<br>
    2. Відсутність власного this: Стрілкові функції не мають власного контексту this. Значення this у стрілковій функції визначається контекстом, в якому вона використовується. Якщо стрілкова функція використовується в контексті об'єкта, то this буде посилатися на цей об'єкт. Якщо стрілкова функція використовується в контексті глобального простору імен, то this буде посилатися на window.<br>
    3. Аргументи: У стрілкових функціях немає власного об'єкта arguments. Ви можете використовувати arguments тільки в звичайних функціях.<br>
    4. Відсутність підняття (hoisting): Стрілкові функції не піднімаються (hoist), тобто їх не можна викликати перед оголошенням.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як працює this в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>this - це контекст в JavaScript вказує на поточний об'єкт, на якому викликана функція. Значення this залежить від того, як саме була викликана функція.<br>
    1. Глобальний контекст: У глобальному контексті (поза будь-якою функцією), this вказує на глобальний об'єкт. В браузерах це може бути window.<br>
    <pre>
    console.log(this); // В браузері: Window
    </pre>
    2. Функції, які не є методами об'єктів: У випадку функцій, які не є методами об'єктів, this вказує на глобальний об'єкт. Враховуйте, що це може змінитися в режимі "strict" ("use strict"), де this залишиться undefined.<br>
    3. Методи об'єктів: У випадку методів об'єктів, this вказує на об'єкт, на якому була викликана функція-метод.<br>
    <pre>
      const obj = {
      name: "Example",
      logName: function() {
        console.log(this.name);
      }
      };
      obj.logName(); 
    </pre>
    4. Конструктори: Коли функція викликається як конструктор за допомогою new, this вказує на новий об'єкт, який створюється конструктором.<br>
    5. Стрілкові функції: Стрілкові функції не мають власного контексту this. Замість цього, вони успадковують значення this з контексту, в якому були створені.
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке try, catch, finally, throw? Як ви обробляєте винятки(помилки) в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Обробка винятків в JavaScript використовує механізм конструкцій try, catch, і finally. Винятки виникають у випадках помилок в час виконання програми.<br>
    - try - це блок коду, в якому ви виконуєте код, який може викликати виняток (помилку).<br>
    - catch - це блок коду, який виконується тільки в тому випадку, якщо виникає виняток у блоку try. Параметр catch (зазвичай названий error) містить об'єкт, який представляє виняток. В error більшість вбудованих типів помилок в JavaScript мають властивості name та message. Наприклад, error.name та error.message.<br>
    - finally - це блок коду, який виконується незалежно від того, чи виникла помилка в блоку try чи ні. Цей блок використовується для виконання завдань, які повинні відбутися незалежно від того, чи сталася помилка.<br>
    - throw - використовується для вручного викидання винятків (помилок). Ви можете викидати об'єкт помилки з будь-якими властивостями, які ви вважаєте за потрібне.<br>
    <pre>
      function divide(a, b) {
        if (b === 0) {
          throw new Error('Ділення на нуль недопустиме');
        }
        return a / b;
      }
      try {
        const result = divide(10, 0);
        console.log(result);
      } catch (error) {
        console.error('Виникла помилка:', error.message);
      } finally {
        console.log('Цей блок завжди виконується');
      }
    </pre>
    У даному коді:<br>
    - try: Обгортає код, який може викликати помилку.<br>
    - catch: Обробляє виняток, якщо він виникає в блоку try. Об'єкт error містить інформацію про помилку, таку як message та інші властивості.<br>
    - finally: Цей блок виконується незалежно від того, чи виникла помилка чи ні.<br>
    Також, можна використовувати конструкції throw для викидання винятків:</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке замикання (closures)?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це комбінація функції та лексичного оточення, в якому ця функція була оголошена. Замикання дозволяє зберігати доступ до зміннних із зовнішнього оточення, навіть після завершення виконання цього оточення.<br>
    Основні особливості замикань:<br>
    1. Доступ до області видимості: Функція в середині іншої функції може отримувати доступ до змінних з області видимості своєї батьківської функції, навіть після того, як батьківська функція завершила свою роботу.<br>
    2. Збереження стану: Замикання дозволяють зберігати стан (змінні) між викликами функції. Кожен раз, коли функція замикання викликається, вона все ще має доступ до значень змінних з області видимості, в якій вона була створена.<br>
    <pre>
      function counter() {
        let count = 0;
        return function() {
          count++;
          console.log(count);
        };
      }
      const increment = counter();
      increment(); // Виведе 1
      increment(); // Виведе 2
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке лексичне оточення?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Лексичне оточення (lexical scope) в JavaScript означає, що область видимості (scope) змінної визначається на основі місця, де ця змінна була визначена в програмі, а не на основі того, де вона викликається. Лексичне оточення є частиною механізму замикань (closures). Внутрішня функція (замикання) має доступ до змінних зовнішньої функції, навіть після того, як вона вже завершила свою роботу.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке прототипи в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це об'єкти, які використовуються для успадкування властивостей і методів. Кожний об'єкт у JavaScript має прототип, який може бути використаний для визначення властивостей і методів, які доступні для цього об'єкта.<br>
    Створення прототипів: Прототипи в JavaScript визначаються за допомогою властивості prototype у функцій-конструкторів або через метод Object.create().<br>
    1. Використання методу Object.create():<br>
    <pre>
      // Об'єкт, який стане прототипом
      const animalPrototype = {
        makeSound: function() {
          console.log('Some generic sound');
        }
      };
      // Створення об'єкта з вказаним прототипом
      const cat = Object.create(animalPrototype);
      cat.type = 'Cat';
      // Виклик методу з прототипу
      cat.makeSound(); // Виведе 'Some generic sound'
    </pre>
    2. Використання класів (ES6 і вище):<br>
    <pre>
      class Animal {
      constructor(type) {
        this.type = type;
      }
      makeSound() {
        console.log('Some generic sound');
      }
      }
      // Створення об'єкта на основі класу
      const cat = new Animal('Cat');
      // Виклик методу з прототипу
      cat.makeSound(); // Виведе 'Some generic sound'
    </pre>
    3. Використання функції-конструктора:<br>
    <pre>
      // Функція-конструктор
      function Animal(type) {
        this.type = type;
      }
      // Додавання методу до прототипу
      Animal.prototype.makeSound = function() {
        console.log('Some generic sound');
      };
      // Створення об'єкта з використанням конструктора і його прототипу
      const cat = new Animal('Cat');
      // Виклик методу з прототипу
      cat.makeSound(); // Виведе 'Some generic sound'
    </pre>
    Переваги прототипів:<br>
    - Вони дозволяють легко створювати об'єкти з однаковими властивостями і методами.<br>
    - Вони дозволяють легко розширювати функціональність об'єктів.<br>
    - Вони дозволяють реалізувати поліморфізм.<br>
    Недоліки прототипів:<br>
    - Прототипи мають також ряд недоліків, зокрема:<br>
    - Вони можуть бути складними для розуміння та використання.<br>
    - Вони можуть призвести до неефективного використання пам'яті.<br>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити об'єкт в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. Літерал об'єкта: Використовуйте фігурні дужки {} для створення об'єкта та визначте його властивості та значення в середині.<br>
    <pre>
      let person = {
        name: 'John',
        age: 30,
        city: 'New York'
      };
    </pre>
    2. За допомогою конструктора об'єкта: Використовуйте конструктор Object() для створення порожнього об'єкта та додайте властивості пізніше.<br>
    <pre>
      let car = new Object();
      car.brand = 'Toyota';
      car.model = 'Camry';
    </pre>
    3. За допомогою класу (ES6 і вище): Використовуйте клас для створення об'єкта та визначте його властивості та методи.<br>
    <pre>
      class Dog {
        constructor(name, age) {
          this.name = name;
          this.age = age;
        }
        bark() {
          console.log('Woof!');
        }
      }
      let myDog = new Dog('Buddy', 3);
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Назви усі методи обєктів в js, які аргументи він приймає і повертає.
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. Object.keys(obj): Використовується для отримання масиву із імен власних перераховуваних властивостей об'єкта.<br>
      - Приймає об'єкт obj.<br>
      - Повертає масив із строковими ключами об'єкта.<br>
      <pre>
      const person = {
      name: 'John',
      age: 30,
      city: 'New York'
      };
      const keys = Object.keys(person);
      console.log(keys); // Виведе масив ['name', 'age', 'city']
      </pre>
      2. Object.values(obj): Використовується для отримання масиву, що містить значення всіх власних перераховуваних значень об'єкта.<br>
      - Приймає об'єкт obj.<br>
      - Повертає масив із значеннями властивостей об'єкта.<br>
      <pre>
      const person = {
      name: 'John',
      age: 30,
      city: 'New York'
      };
      const values = Object.values(person);
      console.log(values); // Виведе масив ['John', 30, 'New York']
      </pre>
      3. Object.entries(obj): Використовується для отримання масиву масивів, де кожен масив містить пару ключ-значення для кожної власної перераховуваної властивості об'єкта.<br>
      - Приймає об'єкт obj.<br>
      - Повертає масив масивів, кожен з яких має два елементи: ключ та відповідне йому значення.<br>
      <pre>
      const person = {
      name: 'John',
      age: 30,
      city: 'New York'
      };
      const entries = Object.entries(person);
      console.log(entries);// Виведе масив масивів [['name', 'John'], ['age', 30], ['city', 'New York']]
      </pre>
      4. Object.assign(target, source1, source2, ...): використовується для об'єднання (копіювання) властивостей одного або кількох об'єктів у цільовий об'єкт.<br>
      - Приймає цільовий об'єкт target та декілька джерел source1, source2, і так далі.<br>
      - Повертає об'єкт target, що є результатом об'єднання (копіювання) властивостей з усіх джерел у цільовий об'єкт.<br>
      <pre>
      const target = { a: 1, b: 2 };
      const source1 = { b: 3, c: 4 };
      const source2 = { c: 5, d: 6 };
      const result = Object.assign(target, source1, source2);
      console.log(result);
      // Виведе об'єкт { a: 1, b: 3, c: 5, d: 6 }
      console.log(target);
      // Також виведе об'єкт { a: 1, b: 3, c: 5, d: 6 }
      </pre>
      5. Object.freeze(obj): використовується для "заморожування" об'єкта. Заморожування об'єкта означає, що його властивості не можуть бути змінені, додані або видалені після того, як об'єкт був заморожений.<br>
      - Приймає об'єкт obj.<br>
      - Повертає заморожений об'єкт, що не може бути змінений (нові властивості не можуть бути додані, а існуючі не можуть бути видалені або змінені).<br>
      <pre>
      const person = {
      name: 'John',
      age: 30
      };
      Object.freeze(person);
      // Спроба змінити властивість об'єкта буде проігнорована
      person.age = 31;
      // Спроба додати нову властивість буде проігнорована
      person.city = 'New York';
      // Спроба видалити властивість буде проігнорована
      delete person.name;
      console.log(person);  // Виведе об'єкт { name: 'John', age: 30 }
      </pre>
      6. Object.seal(obj): використовується для "запечатування" об'єкта. Запечатування об'єкта означає, що властивості об'єкта можна змінювати, але не можна додавати нові властивості або видаляти існуючі.<br>
      - Приймає об'єкт obj.<br>
      - Повертає запечатаний об'єкт, що не дозволяє додавати нові властивості, але дозволяє змінювати та видаляти існуючі властивості.<br>
      <pre>
        const person = {
        name: 'John',
        age: 30
        };
        Object.seal(person);
        // Змінити властивість об'єкта можна
        person.age = 31;
        // Додати нову властивість не можна
        person.city = 'New York';  // Це буде проігноровано
        // Видалити властивість не можна
        delete person.name;  // Це буде проігноровано
        console.log(person);  // Виведе об'єкт { name: 'John', age: 31 }
      </pre>
      7. Object.defineProperty(obj, prop, descriptor): використовується для додавання чи зміни властивостей об'єкта з додатковими налаштуваннями, такими як атрибути властивості (наприклад, конфігуруючі, записуючі та перераховувані атрибути).<br>
      - Приймає об'єкт obj, ім'я властивості prop, та об'єкт descriptor, що описує атрибути властивості.<br>
      - Повертає об'єкт obj після встановлення властивості за вказаними атрибутами.<br>
      8. Object.getOwnPropertyNames(obj): використовується для отримання масиву імен всіх власних властивостей об'єкта (незалежно від того, чи вони перераховувані, чи ні).<br>
      - Приймає об'єкт obj.<br>
      - Повертає масив із іменами всіх властивостей об'єкта (включаючи незлічені).<br>
      9. Object.getOwnPropertyDescriptor(obj, prop) використовується для отримання об'єкта опису властивості для вказаної властивості об'єкта. Опис включає різні атрибути властивості, такі як value, writable, enumerable, та configurable.:<br>
      - Приймає об'єкт obj та ім'я властивості prop.<br>
      - Повертає об'єкт, що містить атрибути даної властивості.<br>
      10. Object.create(proto, propertiesObject): використовується для створення нового об'єкта з вказаним прототипом. Він приймає один аргумент - об'єкт, який буде встановлено як прототип для новоствореного об'єкта.<br>
      - Приймає об'єкт-прототип proto та необов'язковий об'єкт propertiesObject.<br>
      - Повертає новий об'єкт, який має вказаний прототип.<br>
      <pre>
      const personPrototype = {
      greet: function() {
        console.log(`Hello, my name is ${this.name}`);
      }
      };
      const john = Object.create(personPrototype);
      john.name = 'John';
      john.greet(); // Виведе 'Hello, my name is John'
      </pre>
      </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Назви усі методи масивів в js, які аргументи він приймає і повертає.
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. concat():  для об'єднання двох чи більше масивів чи елементів у новий масив, не змінюючи оригінальні масиви. Він повертає новий масив, який складається з елементів об'єднаних масивів.<br>
    - Приймає: елементи чи масиви для об'єднання.<br>
    - Повертає: новий масив, що містить об'єднані елементи.<br>
    <pre>
      const array1 = [1, 2, 3];
      const array2 = [4, 5, 6];
      const newArray = array1.concat(array2, 7, 8);
      console.log(newArray);
      // Виведе: [1, 2, 3, 4, 5, 6, 7, 8]
      console.log(array1);
      // Залишиться без змін: [1, 2, 3]
      console.log(array2);
      // Залишиться без змін: [4, 5, 6]
    </pre>
    2. filter(callback(element, index, array)): використовується для створення нового масиву, який містить лише ті елементи оригінального масиву, для яких callback-функція повертає true. Іншими словами, filter() відфільтровує елементи масиву на підставі заданої умови.<br>
    - Приймає: callback-функцію, яка визначає, які елементи повинні бути включені в новий масив.<br>
    - Повертає: новий масив, що містить елементи, для яких callback повертає true.
    <pre>
    const numbers = [1, 2, 3, 4, 5, 6];
    const evenNumbers = numbers.filter(function(number) {
      return number % 2 === 0;
    });
    console.log(evenNumbers);
    // Виведе: [2, 4, 6]
    </pre>
    <br>
    3. map(callback(element, index, array)): використовується для створення нового масиву, у якому кожен елемент є результатом виклику заданої callback-функції для кожного елемента оригінального масиву. Іншими словами, map() застосовує задану функцію до кожного елемента масиву та повертає новий масив, який містить результати цих викликів.<br>
    - Приймає: callback-функцію, яка визначає, як змінювати кожен елемент.<br>
    - Повертає: новий масив, що містить результати виклику callback для кожного елемента.
    <pre>const numbers = [1, 2, 3, 4, 5];
    const squaredNumbers = numbers.map(function(number) {
      return number ** 2;
    });
    console.log(squaredNumbers);
    // Виведе: [1, 4, 9, 16, 25]
    </pre>
    <br>
    4. reduce(callback(accumulator, currentValue, index, array), initialValue): використовується для зменшення (згортання) масиву до одного значення, застосовуючи callback-функцію для кожного елемента масиву, починаючи з лівого краю (першого елемента) до правого краю (останнього елемента).<br>
    - Приймає: callback-функцію та необов'язковий початковий значок (initialValue), яке використовується як перший аргумент для першого виклику callback.<br>
    - Повертає: результат послідовних викликів callback.<br>
    <pre>
    const numbers = [1, 2, 3, 4, 5];
    const sum = numbers.reduce(function(accumulator, currentValue) {
      return accumulator + currentValue;
    }, 0);
    console.log(sum);
    // Виведе: 15
    </pre>
    5. forEach(callback(element, index, array)): використовується для виконання заданої callback-функції один раз для кожного елемента в масиві, в порядку їх послідовності. Він не повертає новий масив, а просто виконує вказану функцію для кожного елемента масиву.<br>
    - Приймає: callback-функцію, яка викликається для кожного елемента масиву.<br>
    - Повертає: нічого не повертає.
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    fruits.forEach(function(fruit, index) {
      console.log(`Element at index ${index}: ${fruit}`);
    });
    // Виведе:
    // Element at index 0: apple
    // Element at index 1: banana
    // Element at index 2: orange
    </pre>
    <br>
    6. find(callback(element, index, array)): використовується для знаходження першого елемента в масиві, який відповідає заданій умові, вказаній у callback-функції. Якщо елемент знайдено, find() повертає його значення; якщо ж жоден елемент не відповідає умові, повертається undefined.<br>
    - Приймає: callback-функцію, яка визначає, який елемент потрібно знайти.<br>
    - Повертає: перший елемент, для якого callback повертає true.<br>
    <pre>const numbers = [1, 3, 5, 2, 4, 6];
    const firstEvenNumber = numbers.find(function(number) {
      return number % 2 === 0;
    });
    console.log(firstEvenNumber);
    // Виведе: 2
    </pre>
    7. indexOf(searchElement, fromIndex): використовується для визначення індексу першого входження заданого елемента в масиві. Якщо елемент знаходиться в масиві, indexOf() повертає його індекс; якщо елемент відсутній, повертається -1.<br>
    - Приймає: елемент для пошуку та необов'язковий індекс (з якого починати пошук).<br>
    - Повертає: індекс першого входження шуканого елемента або -1, якщо елемент не знайдено.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const bananaIndex = fruits.indexOf('banana');
    console.log(bananaIndex);
    // Виведе: 1
    const grapeIndex = fruits.indexOf('grape');
    console.log(grapeIndex);
    // Виведе: -1 (елемент не знайдено)
    </pre>
    8. sort(compareFunction): використовується для сортування елементів масиву. Сортування може виконуватися за зростанням (за замовчуванням) або за спаданням. Якщо елементи масиву є рядками, вони сортуються лексикографічно (за алфавітом); якщо елементи є числами, вони сортуються числово.<br>
    - Приймає: функцію порівняння, що визначає порядок сортування.<br>
    - Повертає: відсортований масив.<br>
    <pre>
    const numbers = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5];
    numbers.sort(function(a, b) {
      return a - b;
    });
    console.log(numbers);
    // Виведе: [1, 1, 2, 3, 3, 4, 5, 5, 5, 6, 9]
    </pre>
    9. slice(start, end): використовується для створення нового масиву, який є підмасивом оригінального масиву. Він вибирає елементи масиву від заданого початкового індексу до заданого кінцевого індексу (не включаючи сам кінцевий індекс) і повертає новий масив, що складається з цих елементів.<br>
    - Приймає: індекс початку та (необов'язково) індекс кінця зрізу.<br>
    - Повертає: новий масив, що містить вибрані елементи.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange', 'grape', 'kiwi'];
    const slicedFruits = fruits.slice(1, 4);
    console.log(slicedFruits);
    // Виведе: ['banana', 'orange', 'grape']
    </pre>
    10. splice(start, deleteCount, item1, item2, ...): використовується для зміни вмісту масиву, додаючи нові елементи та/або видаляючи існуючі елементи. Він може виконувати вставку, видалення або обидві операції одночасно. splice() змінює оригінальний масив і повертає масив елементів, які були видалені.<br>
    - Приймає: індекс початку, кількість елементів для видалення та (необов'язково) елементи для вставки.<br>
    - Повертає: масив елементів, які були видалені.<br>
    <pre>const numbers = [1, 2, 3, 4, 5];
    // Видаляє 2 елементи починаючи з індексу 2 і додає нові елементи 6 і 7 на їхнє місце
    const removedElements = numbers.splice(2, 2, 6, 7);
    console.log(numbers);
    // Виведе: [1, 2, 6, 7, 5]
    console.log(removedElements);
    // Виведе: [3, 4]
    </pre>
    11. pop(): використовується для видалення останнього елемента з кінця масиву. Цей метод змінює оригінальний масив і повертає видалений елемент.<br>
    - Приймає: немає аргументів.<br>
    - Повертає: вилучений останній елемент масиву.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const removedFruit = fruits.pop();
    console.log(fruits);
    // Виведе: ['apple', 'banana']
    console.log(removedFruit);
    // Виведе: 'orange'
    </pre>
    12. push(element1, element2, ...): використовується для додавання одного або кількох нових елементів в кінець масиву. Цей метод змінює оригінальний масив і повертає нову довжину масиву після додавання нових елементів.<br>
    - Приймає: елементи для додавання на кінець масиву.<br>
    - Повертає: нову довжину масиву.<br>
    <pre>
    const fruits = ['apple', 'banana'];
    const newLength = fruits.push('orange');
    console.log(fruits);
    // Виведе: ['apple', 'banana', 'orange']
    console.log(newLength);
    // Виведе: 3 (нова довжина масиву)
    </pre>
    13. shift(): використовується для видалення першого елемента з початку масиву. Цей метод змінює оригінальний масив і повертає видалений елемент.<br>
    - Приймає: немає аргументів.<br>
    - Повертає: вилучений перший елемент масиву.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const removedFruit = fruits.shift();
    console.log(fruits);
    // Виведе: ['banana', 'orange']
    console.log(removedFruit);
    // Виведе: 'apple'
    </pre>
    14. unshift(element1, element2, ...): використовується для додавання одного чи кількох нових елементів на початок масиву. Цей метод змінює оригінальний масив і повертає нову довжину масиву після додавання нових елементів.<br>
    - Приймає: елементи для додавання на початок масиву.<br>
    - Повертає: нову довжину масиву.<br>
    <pre>
      const fruits = ['banana', 'orange'];
      const newLength = fruits.unshift('apple');
      console.log(fruits);
      // Виведе: ['apple', 'banana', 'orange']
      console.log(newLength);
      // Виведе: 3 (нова довжина масиву)
    </pre>
    15. reverse(): використовується для додавання одного чи кількох нових елементів на початок масиву. Цей метод змінює оригінальний масив і повертає нову довжину масиву після додавання нових елементів.<br>
    - Приймає: немає аргументів.<br>
    - Повертає: масив, відсортований у зворотньому порядку.<br>
    <pre>
    const fruits = ['banana', 'orange'];
    const newLength = fruits.unshift('apple');
    console.log(fruits);
    // Виведе: ['apple', 'banana', 'orange']
    console.log(newLength);
    // Виведе: 3 (нова довжина масиву)
    </pre>
    16. includes(searchElement, fromIndex): використовується для визначення, чи містить масив певний елемент. Він повертає true, якщо елемент знайдений у масиві, і false, якщо елемент відсутній.<br>
    - Приймає: елемент для пошуку та (необов'язково) індекс (з якого починати пошук).<br>
    - Повертає: true, якщо масив містить шуканий елемент, і false - в іншому випадку.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const isBananaIncluded = fruits.includes('banana');
    console.log(isBananaIncluded);
    // Виведе: true
    const isGrapeIncluded = fruits.includes('grape');
    console.log(isGrapeIncluded);
    // Виведе: false
    </pre>
    17. every(callback(element, index, array)): використовується для перевірки того, чи задана умова виконується для кожного елемента масиву. Він повертає true, якщо умова виконується для всіх елементів, і false, якщо хоча б один елемент не відповідає умові.<br>
    - Приймає: callback-функцію, яка повертає true чи false для кожного елемента.<br>
    - Повертає: true, якщо всі елементи відповідають умові в callback, і false - якщо хоча б один не відповідає.<br>
    <pre>
    const numbers = [2, 4, 6, 8, 10];
    const allAreEven = numbers.every(function(number) {
      return number % 2 === 0;
    });
    console.log(allAreEven);
    // Виведе: true
    </pre>
    18. some(callback(element, index, array)): використовується для перевірки того, чи принаймні один елемент масиву відповідає заданій умові. Він повертає true, якщо умова виконується хоча б для одного елемента, і false, якщо жоден елемент не відповідає умові.<br>
    - Приймає: callback-функцію, яка повертає true чи false для кожного елемента.<br>
    - Повертає: true, якщо хоча б один елемент відповідає умові в callback, і false - якщо ні.<br>
    <pre>const numbers = [1, 3, 5, 6, 9];
    const atLeastOneIsEven = numbers.some(function(number) {
      return number % 2 === 0;
    });
    console.log(atLeastOneIsEven);
    // Виведе: true
    </pre>
    19. join(separator): використовується для об'єднання всіх елементів масиву в рядок. Він приймає один аргумент - роздільник, який використовується для визначення розділу між елементами при їх об'єднанні в рядок. Якщо аргумент відсутній, елементи об'єднуються без роздільника, просто прилягаючи один до одного.<br>
    - Приймає: роздільник для об'єднання елементів масиву в рядок.<br>
    - Повертає: рядок, що містить всі елементи масиву, розділені вказаним роздільником.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const resultString = fruits.join(', ');
    console.log(resultString);
    // Виведе: 'apple, banana, orange'
    </pre>
    20. toString(): використовується для перетворення масиву в рядок. Коли ви викликаєте toString() на масиві, він повертає рядок, представляючи всі елементи масиву, розділені комами.<br>
    - Приймає: немає аргументів.<br>
    - Повертає: рядок, який представляє масив.<br>
    <pre>
    const fruits = ['apple', 'banana', 'orange'];
    const resultString = fruits.toString();
    console.log(resultString);
    // Виведе: 'apple,banana,orange'
    </pre>
    21. Array.isArray(obj): використовується для перевірки того, чи є об'єкт масивом. Вона повертає true, якщо об'єкт є масивом, і false, якщо ні.<br>
    - Приймає: об'єкт для перевірки.<br>
    - Повертає: true, якщо переданий об'єкт є масивом, і false - в іншому випадку.<br>
    <pre>
    const array = [1, 2, 3];
    const object = { key: 'value' };
    console.log(Array.isArray(array));
    // Виведе: true
    console.log(Array.isArray(object));
    // Виведе: false
    </pre>
    22. Array.from: призначений для створення нового масиву з ітерируємого або подібного до масиву об'єкта. 
    - iterable: Об'єкт, який буде перетворений в масив. Це може бути об'єкт, який є ітерируємим (наприклад, масив, строка, Set, Map, NodeList, тощо).<br>
    <pre>
    const set = new Set([1, 2, 3]);
    const arrayFromSet = Array.from(set);
    console.log(arrayFromSet); // Виведе: [1, 2, 3]
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як видаляти властивості з об'єкта в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В JavaScript для видалення властивості з об'єкта можна використовувати оператор delete. 
    Особливості:
    - delete видаляє властивість об'єкта, але не впливає на прототипні властивості.
    - delete повертає true, якщо властивість успішно видалена, і false, якщо властивості не існує або не може бути видалена (наприклад, якщо властивість визначена з configurable: false).
    <pre>
    const person = { name: 'John', age: 25 };
    // Видалення властивості 'age'
    delete person.age;
    console.log(person);
    // Виведе: { name: 'John' }
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як клонувати об'єкт в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. Використання оператора Spread (...):<br>
    <pre>
    const originalObject = { name: 'John', age: 25 };
    const clonedObject = { ...originalObject };
    console.log(clonedObject);
    // Виведе: { name: 'John', age: 25 }
    </pre>
    Особливості:<br>
    - Цей спосіб працює лише для поверхневого клонування. Якщо об'єкт має вкладені об'єкти або масиви, вони будуть вказувати на ті ж самі об'єкти в обох копіях.<br>
    - Не підтримує клонування прототипів об'єкта.<br>
    2. Використання методу Object.assign():<br>
    <pre>
    const originalObject = { name: 'John', age: 25 };
    const clonedObject = Object.assign({}, originalObject);
    console.log(clonedObject);
    // Виведе: { name: 'John', age: 25 }
    </pre>
    Особливості:<br>
    - Працює так само, як і Spread-оператор для поверхневого клонування.<br>
    - Дозволяє об'єднувати кілька об'єктів в один.<br>
    3. Використання JSON.parse() та JSON.stringify():<br>
    <pre>
    const originalObject = { name: 'John', age: 25 };
    const clonedObject = JSON.parse(JSON.stringify(originalObject));
    console.log(clonedObject);
    // Виведе: { name: 'John', age: 25 }
    </pre>
    Особливості:<br>
    - Цей метод глибоко клонує об'єкт, включаючи вкладені об'єкти та масиви.<br>
    - Проте, він не підтримує клонування функцій або об'єктів з власними методами, оскільки вони втрачаються при перетворенні в рядок JSON.<br>
    4. Для глибокого клонування використовується structuredClone(object) з усіма вкладеними властивостями. Не копіює методи(функції) в обєкті.<br>
    <pre>
    let user = {
      name: "Микола",
      sizes: {
        height: 182,
        width: 50
      }
    };
    let clone = structuredClone(user);
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як видалити дублікати з масиву?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. Використання Set: Використання об'єкта Set дозволяє автоматично видалити дублікати, оскільки Set унікальний список значень.<br>
    <pre>
      const arrayWithDuplicates = [1, 2, 2, 3, 4, 4, 5];
      const uniqueArray = [...new Set(arrayWithDuplicates)];
      console.log(uniqueArray);
      // Виведе: [1, 2, 3, 4, 5]
    </pre>
    2. Використання методу filter та indexOf: Можна використовувати метод filter разом із indexOf, щоб залишити лише перший екземпляр кожного значення.<br>
    <pre>
    const arrayWithDuplicates = [1, 2, 2, 3, 4, 4, 5];
    const uniqueArray = arrayWithDuplicates.filter((value, index, array) => array.indexOf(value) === index);
    console.log(uniqueArray);
    // Виведе: [1, 2, 3, 4, 5]
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке spread-оператор?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Spread-оператор (оператор розширення) - це оператор, який дозволяє розкласти значення об'єкта або масиву на окремі аргументи.<br>
    1. Розгортання масивів:<br>
    <pre>
    const array1 = [1, 2, 3];
    const array2 = [...array1, 4, 5];
    console.log(array2);
    // Виведе: [1, 2, 3, 4, 5]
    </pre>
    2. Розгортання об'єктів:<br>
    <pre>
    const obj1 = { a: 1, b: 2 };
    const obj2 = { ...obj1, c: 3, d: 4 };
    console.log(obj2);
    // Виведе: { a: 1, b: 2, c: 3, d: 4 }
    </pre>
    3. Передача аргументів функціям:<br>
    <pre>
    const numbers = [1, 2, 3];
    const sum = (a, b, c) => a + b + c;
    const result = sum(...numbers);
    console.log(result);
    // Виведе: 6
    </pre>
    4. Розгортання рядків:<br>
    <pre>
    const str = 'hello';
    const chars = [...str];
    console.log(chars);
    // Виведе: ['h', 'e', 'l', 'l', 'o']
    </pre>
    Під капотом spread-оператор працює наступним чином:<br>
    - Якщо аргумент expression є об'єктом, то spread-оператор розкладає його на окремі аргументи, використовуючи метод Object.entries().<br>
    - Якщо аргумент expression є масивом, то spread-оператор розкладає його на окремі аргументи, використовуючи метод Array.from().
  </div>
</details>

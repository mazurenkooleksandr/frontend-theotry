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
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке arguments?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це подібний до масиву об'єкт(псевдомасив), який містить всі аргументи, передані функції, в порядку їх передачі. Він є доступним у всіх функціях, незалежно від їх сигнатури. Об'єкт arguments має такі методи:<br>
    length - повертає кількість аргументів, переданих функції.<br>
    callee - повертає функцію, яка викликається в даний момент.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке рекурсія?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це концепція, коли функція викликає сама себе. Вона використовується для розв'язання задач, які можна розбити на менші аналогічні задачі. Використовуйте рекурсію з обережністю, оскільки вона може призвести до переповнення стека. Рекурсія може бути використана в JavaScript для вирішення різних завдань, таких як: Обчислення факторіалу
    <pre>
    function factorial(n) {
      if (n === 0) {
        return 1;
      } else {
        return n * factorial(n - 1);
      }
    }
    console.log(factorial(5)); // 120
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке async/await?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>async/await - це синтаксичний цукор, що дозволяє зручно працювати з асинхронним кодом та промісами. Функція завжди повертає проміс.<br>
    async: Ключове слово async використовується для визначення асинхронної функції. Функція, оголошена з async, завжди повертає проміс, навіть якщо вона повертає не-промісне значення.
    <pre>
    async function myAsyncFunction() {
      return "Hello, World!";
    }
    </pre>
    await: Ключове слово await може використовуватися всередині асинхронної функції для очікування завершення асинхронної операції. Використовується тільки всередині асинхронної функції.
    <pre>
    async function fetchData() {
      const response = await fetch('https://example.com/api/data');
      const data = await response.json();
      console.log(data);
    }
    </pre>
    Робота під капотом: async/await базується на промісах. async функція завжди повертає проміс. await працює, чекаючи на виконання проміса. Це забезпечує асинхронне виконання без блокування потоку виконання.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке проміси?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це об'єкти, які представляють результат асинхронної операції. Проміс може перебувати в трьох станах: "pending" (очікує), "fulfilled" (виконано) та "rejected" (відхилено). Проміси можна використовувати для того, щоб асинхронні операції не блокували виконання коду. Він спрощує роботу з асинхронним кодом та дозволяє уникнути "callback hell" - ситуації, коли вкладені колбеки стають важкими для читання та обслуговування.<br>
    Методи промісів:<br>
    - then: Викликається, коли проміс виконано (стан "fulfilled"). Приймає два колбеки: перший для успішного виконання, другий для відхилення.<br>
    - catch: Викликається, коли проміс відхилено (стан "rejected"). Використовується для обробки помилок.<br>
    - finally: Викликається незалежно від того, чи виконано чи відхилено проміс. Використовується для виконання завдань, які повинні відбутися завжди.<br>
    Як працюють проміси під капотом<br>
    Під капотом проміси реалізовані за допомогою генераторів. Генератор - це спеціальний тип об'єкта, який може генерувати послідовність значень. Проміси використовують генератори для того, щоб зберігати результат асинхронної операції.<br>
    Коли створюється промис, він знаходиться в стані очікування. Коли асинхронна операція завершається, она викликає одну з функцій resolve() або reject(). Функція resolve() встановлює статус промісу на виконання і повертає результат асинхронної операції. Функція reject() встановлює статус промісу на відхилення і повертає об'єкт помилки.
    <pre>
    // Завантажити файл з Інтернету
    const promise = new Promise((resolve, reject) => {
      fetch("https://example.com/file.txt")
        .then((response) => response.text())
        .then(resolve, reject);
    });
    // Вивести результат загрузки файла
    promise.then((text) => console.log(text));
    </pre>
    <pre>
    const myPromise = new Promise((resolve, reject) => {
    // Асинхронний код або операція
    const success = true;
    if (success) {
        resolve("Успішний результат!");
    } else {
        reject("Помилка!");
    }
    });
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке Promise.all(), Promise.allSettled(), Promise.race(), Promise.any()?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це методи, що дозволяють працювати з кількома промісами. 
    1. Promise.all(): приймає масив промісів чи ітерабельний об'єкт, і повертає новий проміс, який вирішується, коли всі проміси в масиві вирішені, або відхилений, коли хоча б один з промісів відхилено. Повертає масив результатів, в порядку, в якому були передані проміси. 
    <pre>
    const promise1 = fetchData1();
    const promise2 = fetchData2();
    const promise3 = fetchData3();
    Promise.all([promise1, promise2, promise3])
    .then(results => {
        console.log('Усі дані отримані:', results);
    })
    .catch(error => {
        console.error('Помилка отримання даних:', error);
    });
    </pre>
    2. Promise.allSettled(): схожий на Promise.all(), але він повертає масив з об'єктами, які містять інформацію про стан кожного промісу. Об'єкти в цьому масиві мають такі властивості:<br>
    status - стан промісу: fulfilled або rejected;<br>
    value - результат промісу, якщо він був виконаний;<br>
    reason - причина відхилення промісу, якщо він був відхилений.
    <pre>
    const promise1 = fetchData1();
    const promise2 = fetchData2();
    const promise3 = fetchData3();
    Promise.allSettled([promise1, promise2, promise3])
    .then(results => {
        console.log('Результати виконання:', results);
    });
    </pre>
    3. Promise.race() повертає перший виконаний промис, незалежно від того, виконаний він успішно або відхилений.<br>
    4. Promise.any() повертає перший успішно виконаний промис, якщо такий є. Якщо жоден з промисів не буде виконаний успішно, то цей метод поверне відхилений промис.<br>
    Як працюють під капотом?<br>
    Всі чотири методи працюють за допомогою генераторів. Генератор - це спеціальний тип об'єкта, який може генерувати послідовність значень. Коли викликається один з цих методів, він створює новий генератор. Цей генератор починає виконуватися, коли всі передані промиси будуть створені. Як тільки один з переданих промисів переходить в стан виконання, генератор генерує наступне значення. Це значення - це результат виконаного промісу. Якщо всі передані промиси будуть виконані успішно, то генератор завершить свою роботу і поверне масив з результатами виконаних промисів. Якщо один з переданих промисів буде відхилений, то генератор також завершить свою роботу і поверне відхилений промис.
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке ООП в JS?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>ООП (об'єктно-орієнтоване програмування) - це парадигма програмування, яка фокусується на об'єктах. Об'єкт - це екземпляр класу, який має властивості та методи. В ООП код організований в об'єкти, які взаємодіють один з одним. Це дозволяє створювати програму, яка є більш модульною, легкою у розумінні та підтримці. ООП в JS реалізується за допомогою класів. Клас - це опис об'єкта. Він визначає властивості та методи, які будуть мати об'єкти цього класу.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Основні принципи об'єктно-орієнтованого програмування
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це парадигма програмування, яка фокусується на об'єктах. Об'єкт - це екземпляр класу, який має властивості та методи.
    Основні принципи ООП:<br>
    1. Інкапсуляція - це принцип об'єктно-орієнтованого програмування, який дозволяє об'єднувати дані та поведінку в один об'єкт. Це дозволяє приховати деталі реалізації об'єкта від інших об'єктів.<br>
    2. Наслідування - це механізм, що дозволяє створювати новий клас на основі існуючого (батьківського) класу. Клас, який успадковує властивості та методи іншого класу, називається класом-нащадком або підкласом, а клас, від якого успадковується, - класом-батьком або суперкласом. Наслідування дозволяє використовувати та розширювати функціональність вже існуючих класів.<br>
    3. Поліморфізм - це принцип, який дозволяє об'єктам одного типу мати різні реалізації одного і того ж методу. Це дозволяє об'єктам різних типів використовуватися та оброблятися як об'єкти одного типу, спрощуючи код та забезпечуючи більшу універсальність. Поліморфізм виникає через використання спільних інтерфейсів або абстракцій.<br>
    4. Абстракція - це принцип, який дозволяє створювати об'єкти, які не залежать від деталей їхньої реалізації. Абстракція дозволяє визначати загальні характеристики класу та використовувати їх для створення об'єктів.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке static, extends, new, get, set, instanceof, constructor та super в js?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. static: Ключове слово static використовується для визначення статичних методів або статичних властивостей класу. Статичні методи можна викликати без створення екземпляра класу, і вони використовуються на самому класі, а не на його екземплярах.<br>
    <pre>
    class MathOperations {
    static add(a, b) {
        return a + b;
    }
    static subtract(a, b) {
        return a - b;
    }
    }
    console.log(MathOperations.add(5, 3));  // 8
    console.log(MathOperations.subtract(8, 3));  // 5
    </pre>
    2. extends: Ключове слово extends використовується для успадкування властивостей та методів одного класу від іншого. Клас, який успадковує, називається класом-нащадком, а клас, від якого успадковують, - класом-батьком або суперкласом.<br>
    <pre>
    class Animal {
    constructor(name) {
        this.name = name;
    }
    speak() {
        console.log(`${this.name} makes a sound.`);
    }
    }
    class Dog extends Animal {
        bark() {
            console.log(`${this.name} barks.`);
        }
    }
    const myDog = new Dog('Buddy');
    myDog.speak();  // "Buddy makes a sound."
    myDog.bark();   // "Buddy barks."
    </pre>
    3. new: Ключове слово new використовується для створення нового екземпляра класу. Коли використовується з конструктором класу, new створює новий об'єкт, викликає конструктор класу та повертає створений екземпляр.<br>
    <pre>
    class Person {
    constructor(name) {
        this.name = name;
    }
    }
    const john = new Person('John');
    console.log(john.name);  // "John"
    </pre>
    4. get та set: Ключові слова get та set використовуються для визначення геттерів та сеттерів для властивостей об'єкта.<br>
    <pre>
    class Circle {
    constructor(radius) {
        this._radius = radius;  // Приватна властивість
    }
    get radius() {
        return this._radius;
    }
    set radius(value) {
        if (value > 0) {
            this._radius = value;
        }
    }
    }
    const myCircle = new Circle(5);
    console.log(myCircle.radius);  // 5
    myCircle.radius = 8;
    console.log(myCircle.radius);  // 8
    </pre>
    5. constructor: Ключове слово constructor використовується для визначення конструктора класу. Конструктор - це спеціальний метод, який викликається при створенні нового екземпляра класу. В конструкторі можна встановлювати початкові значення для властивостей об'єкта.<br>
    <pre>
    class Person {
    constructor(name, age) {
        this.name = name;
        this.age = age;
    }
    }
    const john = new Person('John', 25);
    console.log(john.name);  // "John"
    console.log(john.age);   // 25
    </pre>
    6. super: Ключове слово super використовується для виклику конструктора батьківського класу або для звернення до методів батьківського класу. Використання super() у конструкторі класу-нащадка дозволяє передати параметри до конструктора батьківського класу та встановити властивості дочірнього класу.<br>
    <pre>
    class Animal {
    constructor(name) {
        this.name = name;
    }
    speak() {
        console.log(`${this.name} makes a sound.`);
    }
    }
    class Dog extends Animal {
        constructor(name, breed) {
            super(name);  // Виклик конструктора батьківського класу
            this.breed = breed;
        }
        bark() {
            console.log(`${this.name} barks.`);
        }
    }
    const myDog = new Dog('Buddy', 'Golden Retriever');
    myDog.speak();  // "Buddy makes a sound."
    myDog.bark();   // "Buddy barks."
    </pre>
    7. instanceof: Оператор instanceof використовується для перевірки, чи об'єкт є екземпляром конкретного класу або його підкласу.<br>
    <pre>
    const myDog = new Dog();
    console.log(myDog instanceof Animal);  // true
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Робота з DOM, методи для document в JS
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. getElementById(id): Повертає елемент за його ідентифікатором.<br>
    <pre>
    const myElement = document.getElementById("ідентифікатор_елемента");
    </pre>
    2. getElementsByTag(tagName): Повертає колекцію елементів за їх тегом.<br>
    <pre>document.getElementsByTagName("div");</pre>
    3. getElementsByClass(className): Повертає колекцію елементів за їх класом.<br>
    <pre>document.getElementsByClassName("клас_елемента");</pre>
    4. createElement(elementType): Створює новий елемент за вказаним типом (тегом).<br>
    <pre>document.createElement("div");</pre>
    5. appendChild(parentElement, childElement): Додає дочірній елемент до батьківського елемента.<br>
    <pre>
    const parent = document.getElementById("батьківський_елемент");
    const child = document.createElement("div");
    appendChild(parent, child);
    </pre>
    6. removeElement(element): Видаляє вказаний елемент з DOM.<br>
    <pre>
    const elementToRemove = document.getElementById("елемент_для_видалення");
    removeElement(elementToRemove);
    </pre>
    7. getAttribute(element, attributeName): Повертає значення вказаного атрибута елемента.<br>
    <pre>getAttribute(myElement, "атрибут");</pre>
    8. setAttribute(element, attributeName, attributeValue): Встановлює значення вказаного атрибута для елемента.<br>
    <pre>setAttribute(myElement, "атрибут", "нове_значення");</pre>
    9. addClass(element, className): Додає клас до списку класів елемента.<br>
    <pre>addClass(myElement, "новий_клас");</pre>
    10. removeClass(element, className): Видаляє клас зі списку класів елемента.<br>
    <pre>removeClass(myElement, "клас_для_видалення");</pre>
    11. hasClass(element, className): Перевіряє, чи має елемент вказаний клас.<br>
    <pre>hasClass(myElement, "перевірка_класу");</pre>
    12. textContent або innerText: для зміни текстового вмісту елемента в JavaScript використовується властивість.<br>
    <pre>
    // Отримання елемента за його ідентифікатором
    var myElement = document.getElementById("ідентифікатор_елемента");
    // Зміна текстового вмісту за допомогою textContent
    myElement.textContent = "Новий текстовий вміст";
    // Отримання елемента за його ідентифікатором
    var myElement = document.getElementById("ідентифікатор_елемента");
    // Зміна текстового вмісту за допомогою innerText
    myElement.innerText = "Інший текстовий вміст";
    </pre>
    13. querySelector: це метод у JavaScript, який дозволяє вам вибирати елементи з DOM за допомогою CSS-селекторів.<br>
    <pre>document.querySelector("селектор");</pre>
    14. querySelectorAll: це метод в JavaScript, який дозволяє вибирати всі елементи з DOM, які відповідають заданому CSS-селектору.<br>
    <pre>document.querySelectorAll("селектор");</pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як додавати та видаляти класи з елемента?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В JavaScript ви можете додавати та видаляти класи з елемента за допомогою методів classList.add() та classList.remove() відповідно. Також існують методи classList.toggle() та classList.contains(), які дозволяють змінювати наявність класу та перевіряти, чи елемент має певний клас.<br>
    Додавання класу:<br>
    <pre>
    // Отримання елемента за ідентифікатором
    var myElement = document.getElementById("ідентифікатор_елемента");
    // Додавання класу "новий_клас"
    myElement.classList.add("новий_клас");
    </pre>
    Видалення класу:<br>
    <pre>
    // Отримання елемента за ідентифікатором
    var myElement = document.getElementById("ідентифікатор_елемента");
    // Видалення класу "старий_клас"
    myElement.classList.remove("старий_клас");
    </pre>
    Перевірка наявності класу та зміна його наявності:<br>
    <pre>
    // Отримання елемента за ідентифікатором
    var myElement = document.getElementById("ідентифікатор_елемента");
    // Перевірка чи є клас "клас_для_перевірки" у елемента
    var hasClass = myElement.classList.contains("клас_для_перевірки");
    // Зміна наявності класу "клас_для_перевірки"
    myElement.classList.toggle("клас_для_перевірки");
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як обробляти події в JavaScript, що таке addEventListener, removeEventListener і dispatchEvent?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>addEventListener, removeEventListener і dispatchEvent - це методи, які дозволяють взаємодіяти з подіями в DOM (Document Object Model) веб-сторінки в JavaScript.<br>
    1. addEventListener: Метод addEventListener використовується для додавання обробника подій (event listener) до елемента DOM. Він приймає три параметри: тип події, функцію та capture.<br>
    - Типи події:<br>
    click - користувач натиснув кнопку.<br>
    mouseover - користувач наводить курсор на елемент.<br>
    mouseout - користувач виводить курсор з елемента.<br>
    keydown - користувач натиснув клавішу на клавіатурі.<br>
    keyup - користувач відпустив клавішу на клавіатурі.<br>
    scroll - користувач прокрутив сторінку.<br>
    resize - користувач змінив розмір вікна браузера.<br>
    - Третій параметр capture в методі addEventListener() дозволяє визначити, на якому етапі спрацює обробник події: на етапі захоплення (capture) або на етапі вспливання (bubbling). <br>
    Захоплення (capture) подій: Подія передається від батьківського елемента до дочірніх, поки не досягне цільового елемента (того, на якому подія відбулася)<br>Обробники з параметром capture: true викликаються на етапі захоплення.<br>
    Вспливання (bubbling) подій: Після обробки події цільовим елементом, вона передається від дочірнього елемента до батьківського, поки не досягне кореневого елемента документа. Обробники без параметра capture або з параметром capture: false викликаються на етапі вспливання.<br>
    <pre>
    const button = document.querySelector("button");
    button.addEventListener("click", function(event) {
      console.log("Click on button");
    });
    </pre>
    2. removeEventListener: Метод removeEventListener використовується для видалення раніше доданого обробника подій. Важливо, щоб функція обробника була тією самою функцією, яку ви додали раніше за допомогою addEventListener.<br>
    <pre>
    button.removeEventListener("click", function(event) {
      console.log("Click on button");
    });
    </pre>
    3. dispatchEvent(): Метод dispatchEvent використовується для ручної виклику (спровокування) події на елементі. Ви створюєте об'єкт події за допомогою конструктора Event і викликаєте dispatchEvent на елементі.<br>
    <pre>
    const myElement = document.getElementById("ідентифікатор_елемента");
    // Створення події
    const customEvent = new Event("custom");
    // Виклик події за допомогою dispatchEvent
    myElement.dispatchEvent(customEvent);
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як відмінити подію (event propagation)?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Відміна події в JavaScript може відбуватися на двох рівнях: на рівні захоплення (capture) та на рівні бульбашки (bubbling). Для відміни події ви можете використовувати метод stopPropagation() об'єкта події.<br>
    1. На рівні захоплення (capture): Під час захоплення подій вони спускаються вниз від кореня дерева DOM до цільового елемента. Щоб відмінити подію на цьому етапі, використовуйте stopPropagation() у функції обробника захоплення:<br>
    <pre>
    const myElement = document.getElementById("ідентифікатор_елемента");
    myElement.addEventListener("click", function(event) {
        // Відміна події на етапі захоплення
        event.stopPropagation();
        console.log("Цей обробник події не дозволить всплиття події на рівні бульбашки");
    }, true); // Параметр true вказує, що обробник захоплення використовується
    </pre>
    2. На рівні бульбашки (bubbling): Після того, як подія досягла цільового елемента і спрацювала, вона починає підніматися вверх від цільового елемента до кореня DOM. Щоб відмінити подію на цьому етапі, також використовуйте stopPropagation(): <br>
    <pre>
    const myElement = document.getElementById("ідентифікатор_елемента");
    myElement.addEventListener("click", function(event) {
        console.log("Цей обробник події спрацює, але подія не буде підніматися далі вверх");
        // Відміна події на етапі бульбашки
        event.stopPropagation();
    });
    </pre>
    Метод stopPropagation() дозволяє припинити подальше всплиття (поширення) події вгору або вниз відносно DOM-дерева. Зверніть увагу, що це впливає тільки на поточну подію і не впливає на інші події, які можуть виникнути одночасно чи внаслідок інших взаємодій.
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке fetch і як він працює, його методи, як працює з асинхронністю?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>fetch - це сучасний API для виконання мережевих запитів в браузері. Він надає простий і зручний спосіб взаємодії з віддаленими ресурсами за допомогою HTTP-запитів. fetch повертає об'єкт Promise, що дозволяє використовувати сучасний стандарт обробки асинхронного коду.<br>
    1. fetch(url, options): Цей метод виконує мережевий запит за вказаною URL із зазначеними параметрами (опціями). Повертає Promise, який вирішується об'єктом Response, представляючим відповідь сервера.<br>
    <pre>
    fetch('https://api.example.com/data')
    .then(response => {
        // Обробка відповіді
        return response.json();
    })
    .then(data => {
        // Обробка отриманих даних
        console.log(data);
    })
    .catch(error => {
        // Обробка помилки
        console.error('There has been a problem with your fetch operation:', error);
    });
    </pre>
    2. options (необов'язковий параметр): Об'єкт, який може містити налаштування запиту, такі як метод (GET, POST, тощо), заголовки (headers), тіло (body), тощо.<br>
    <pre>
    fetch('https://api.example.com/data', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({ key: 'value' })
    })
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(error => console.error('Error:', error));
    </pre>
    Важливо відзначити, що fetch спрацьовує асинхронно, тобто не блокує виконання іншого коду під час чекання відповіді від сервера. Це досягається за допомогою об'єкта Promise та використанням методів then, catch для обробки результатів або помилок асинхронного запиту.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке HTTP (GET, POST, PUT, DELETE, PATCH) у Fetch API?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>HTTP (Hypertext Transfer Protocol) - це протокол передачі даних у мережі Інтернет. В рамках Fetch API, основні методи HTTP (GET, POST, PUT, DELETE, PATCH) використовуються для виконання різних видів запитів до сервера.<br>
    - GET: Визначення: Метод GET використовується для отримання даних з сервера. Інформація передається у рядку запиту (URL). GET-запити зазвичай використовуються для отримання ресурсів, і вони не повинні змінювати стану сервера.<br>
    <pre>
      fetch('https://api.example.com/data', {
      method: 'GET'
      })
      .then(response => response.json())
      .then(data => console.log(data))
      .catch(error => console.error('Error:', error));
    </pre>
    - POST: Визначення: Метод POST використовується для відправки даних на сервер для обробки. Цей метод може використовуватися для створення нових ресурсів чи оновлення існуючих.<br>
    <pre>
    fetch('https://api.example.com/data', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({ key: 'value' })
    })
        .then(response => response.json())
        .then(data => console.log(data))
        .catch(error => console.error('Error:', error));
    </pre>
    - PUT: Визначення: Метод PUT використовується для оновлення існуючих даних на сервері або для створення нових ресурсів, якщо вони не існують.<br>
    <pre>
    fetch('https://api.example.com/data/123', {
    method: 'PUT',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({ key: 'updatedValue' })
    })
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(error => console.error('Error:', error));
    </pre>
    - DELETE: Визначення: Метод DELETE використовується для видалення ресурсів або даних на сервері.<br>
    <pre>
      fetch('https://api.example.com/data/123', {
      method: 'DELETE'
      })
      .then(response => {
          if (response.status === 204) {
              // Успішний видалення (No Content)
              console.log('Resource deleted successfully');
          } else {
              console.error('Error:', response.status, response.statusText);
          }
      })
      .catch(error => console.error('Error:', error));
    </pre>
    - PATCH: Визначення: Метод PATCH використовується для часткового оновлення ресурсу на сервері. Це означає, що ви можете відправити лише ті дані, які потрібно оновити, а не всі дані цього ресурсу.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке CORS і як його обходити?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>CORS (Cross-Origin Resource Sharing) - це механізм безпеки в браузерах, який обмежує запити ресурсів з інших доменів. Це важливий механізм для захисту веб-застосунків від атак на основі міжсайтового сценарію (Cross-Site Scripting, XSS) та недозволених запитів з інших доменів. Браузери використовують політику Same-Origin Policy, яка не дозволяє JavaScript-запитам з одного домену взаємодіяти з ресурсами (наприклад, запити Ajax) на іншому домені, якщо не встановлені відповідні заголовки CORS. Якщо ви намагаєтеся зробити AJAX-запит до іншого домену, і сервер не повертає відповідь з необхідними заголовками CORS, ви отримаєте помилку у браузері.<br>
    - Використання серверного проксі: Створіть серверний проксі на своєму власному домені, який буде робити запити на інший домен від імені клієнта. Запити будуть виконуватися між вашим клієнтом і вашим сервером, і сервер буде відправляти запити на інший домен. Такий підхід зазвичай необхідно налаштовувати на рівні сервера.<br>
    - Додавання заголовків CORS на сервері: Якщо вам належить контроль над сервером, до якого ви намагаєтеся зробити запит, ви можете налаштувати сервер так, щоб він повертав необхідні заголовки CORS.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке LocalStorage, SessionStorage, IndexedDB, cookies?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. LocalStorage: це механізм для зберігання даних у браузері, який дозволяє зберігати пари "ключ-значення" в локальному сховищі клієнта. Щоб перевірити наявність певного об'єкта в браузері, ви можете використовувати конструкцію typeof або перевірку на undefined.
    <pre>
      if (typeof localStorage !== 'undefined') {
      // localStorage підтримується
      // Можна використовувати localStorage
      localStorage.setItem('key', 'value');
      } else {
          // localStorage не підтримується
          // Виконати альтернативні дії або повідомити користувача
          console.log('LocalStorage не підтримується в цьому браузері.');
      }
    </pre>
      Особливості:<br>
      - Зберігає дані в об'ємі до 5 МБ на домен. Це значить, що ви можете зберігати невеликі об'єми інформації, такі як налаштування користувача, токени автентифікації або інші значення.<br>
      - Дані залишаються після закриття вкладки браузера та перезапуску комп'ютера.<br>
      - LocalStorage доступний лише для того самого домену, на якому був встановлений. Це забезпечує безпеку ізоляції даних між різними доменами.<br>
      - Дані в LocalStorage зазвичай обмежуються рядками. Якщо потрібно зберігати складні об'єкти або числа, їх потрібно перетворити у рядки перед зберіганням та парсити при отриманні.<br>
      - Легко використовується через localStorage об'єкт у JavaScript.<br>
      Методи:<br>
      - localStorage.setItem(key, value): Зберігає значення за ключем.<br>
      - localStorage.getItem(key): Отримує значення за ключем.<br>
      - localStorage.removeItem(key): Видаляє значення за ключем.<br>
      - localStorage.clear(): очистка усіх даних.<br>
      2. SessionStorage: це механізм для зберігання даних у браузері.<br>
      Особливості:<br>
      - Зберігає дані в об'ємі до 5 МБ на домен.<br>
      - Дані залишаються тільки під час активності сесії (відкриття вкладки браузера).<br>
      - Використовується через sessionStorage об'єкт у JavaScript.<br>
      Методи:<br>
      - Аналогічні localStorage, але працюють в межах однієї сесії.<br>
      3. IndexedDB:<br>
      Особливості:<br>
      - Потужна система баз даних в браузері, яка дозволяє зберігати значно більше даних (без обмежень від 5 МБ).<br>
      - Асинхронний доступ до даних, що дозволяє працювати з великими обсягами даних без блокування основного потоку виконання.<br>
      - База даних IndexedDB є локальною для кожного домену та працює в межах політики безпеки браузера.<br>
      Методи:<br>
      - Складніший API порівняно з localStorage та sessionStorage.<br>
      - Використовується створення транзакцій та об'єктів для зберігання та отримання даних. Наприклад: indexedDB.open(), transaction.objectStore(), тощо.<br>
      4. Cookies:<br>
      Особливості:<br>
      - Дані зберігаються в об'ємі до 4 КБ на домен.<br>
      - Зазвичай використовуються для зберігання невеликої кількості інформації, такої як ідентифікатор сесії чи налаштування.<br>
      - Відправляються на сервер при кожному HTTP-запиті (потрібно враховувати обсяг даних). Cookies включаються в HTTP-запити та відповіді між браузером та сервером, що дозволяє веб-сайтам обмінюватися даними з користувачем.<br>
      - Cookies можуть бути розділені на дві основні категорії - сесійні та сталі. Сесійні cookies зберігаються тільки протягом часу сесії і автоматично видаляються після закриття браузера. Сталі cookies залишаються на комп'ютері користувача із певним терміном дії, визначеним веб-сайтом.<br>
      Методи:<br>
      - document.cookie: Зберігає та отримує значення cookies.
</pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як змінити URL без перезавантаження сторінки?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Веб-додатки можуть змінювати URL без перезавантаження сторінки за допомогою інтерфейсу браузера, що називається History API. Основні методи цього API - pushState та replaceState.<br>
    - pushState: Метод pushState дозволяє додавати новий стан до історії браузера.<br>
    <pre>
      const новий_стан = { ключ: 'значення' };
      const новий_заголовок = 'Новий Заголовок';
      const новий_URL = '/новий-шлях';
      history.pushState(новий_стан, новий_заголовок, новий_URL);
    </pre>
    - replaceState: Метод replaceState замінює поточний стан в історії браузера новим.<br>
    <pre>
      const новий_стан = { ключ: 'значення' };
      const новий_заголовок = 'Новий Заголовок';
      const новий_URL = '/новий-шлях';
      history.replaceState(новий_стан, новий_заголовок, новий_URL);
    </pre>
    Важливо враховувати, що ці методи pushState та replaceState не призводять до фактичного перезавантаження сторінки. Вони просто змінюють URL та створюють новий запис в історії браузера. Також слід враховувати, що зміна URL без перезавантаження сторінки може вплинути на роботу закладок, кнопок "назад" та "вперед" браузера, тому важливо використовувати ці методи обдумано і враховувати їх вплив на користувацький інтерфейс.
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке деструктуризація та для чого вона використовується?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Деструктуризація - це властивість в синтаксисі JavaScript, яка дозволяє розгортати значення з об'єктів або масивів та призначати їх змінним в один рядок.<br>
    1. Деструктуризація об'єкта: <br>
    <pre>
      const користувач = { ім'я: 'John', вік: 30, місто: 'New York' };
      // До деструктуризації
      const ім'я = користувач.ім'я;
      const вік = користувач.вік;
      // Після деструктуризації
      const { ім'я, вік } = користувач;
    </pre>
    2. Деструктуризація масиву: <br>
    <pre>
    const масив = [1, 2, 3, 4, 5];
    // До деструктуризації
    const першийЕлемент = масив[0];
    const другийЕлемент = масив[1];
    // Після деструктуризації
    const [першийЕлемент, другийЕлемент] = масив;
    </pre>
    3. Пропуск елементів масиву:<br>
    <pre>
    const масив = [1, 2, 3, 4, 5];
    const [першийЕлемент, , третійЕлемент] = масив;
    </pre>
    4. Використання деструктуризації в функціях:<br>
    <pre>
    function вивестиІм'я({ ім'я }) {
      console.log(`Ім'я: ${ім'я}`);
    }
    const користувач = { ім'я: 'John', вік: 30 };
    вивестиІм'я(користувач);
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке генератори і як вони використовуються?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Генератори в JavaScript - це спеціальний тип функцій, які дозволяють вам створювати ітератори та контролювати виконання функції. Вони були введені у стандарті ECMAScript 2015 (ES6) і використовують ключове слово function*.<br>
    - Генератор може призупиняти своє виконання за допомогою ключового слова yield, а потім відновлювати виконання з місця, де він був призупинений.<br>
    - Ітератор та next(): Генератор повертає ітератор, який можна використовувати для послідовного отримання значень, використовуючи метод next().<br>
    - Контроль Потоку: Генератори надають зручний спосіб управління потоком виконання, що може бути корисним для асинхронного програмування.<br>
    - Зручність для Асинхронного Програмування: Генератори можуть бути використані для спрощення асинхронного коду за допомогою використання yield та async/await.</p>
    <pre>
      function* прикладГенератора() {
        yield 1;
        yield 2;
        yield 3;
      }
      const ітератор = прикладГенератора();
      console.log(ітератор.next().value); // 1
      console.log(ітератор.next().value); // 2
      console.log(ітератор.next().value); // 3
      console.log(ітератор.next().value); // undefined
    </pre>
    <pre>
        function sleep(ms) {
          return new Promise(resolve => setTimeout(resolve, ms));
        }
        async function* асинхроннийГенератор() {
          yield 1;
          await sleep(1000);
          yield 2;
          await sleep(1000);
          yield 3;
        }
        (async () => {
          for await (const value of асинхроннийГенератор()) {
            console.log(value);
          }
        })();
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як працює "Hoisting" у JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це механізм в JavaScript, який піднімає декларації змінних і функцій на початок області видимості, незалежно від того, де вони фактично оголошуються. Hoisting працює за рахунок того, що компілятор JavaScript аналізує код перед його виконанням. Під час аналізу компілятор створює так звану таблицю видимості, яка містить інформацію про всі змінні і функції, оголошені в коді. Під час hoisting компілятор вставляє декларації всіх змінних і функцій у таблицю видимості на початок області видимості, в якій вони оголошуються. Це означає, що ці декларації будуть доступні в будь-якому місці в цій області видимості, навіть якщо вони оголошуються пізніше. Hoisting працює тільки для змінних var(при виклику такої змінної буде undefined) і функцій declaration.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "Proxy" та "Reflect" у JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>"Proxy" та "Reflect" - це два вбудовані об'єкти в JavaScript, які дозволяють контролювати доступ до об'єктів та їхню поведінку.<br>
    Proxy: Об'єкт Proxy в JavaScript використовується для створення обгорток навколо інших об'єктів або функцій, дозволяючи вам визначити спеціальні обробники (handlers) для різних операцій, таких як читання або запис властивостей, виклик методів та інші.<br>
    Основні методи Proxy:<br>
    - get(target, property, receiver): Викликається при читанні властивості об'єкта.<br>
    - set(target, property, value, receiver): Викликається при записі значення властивості об'єкта.<br>
    - Інші методи, такі як apply, construct, і т.д.<br>
    Reflect: Об'єкт Reflect в JavaScript надає стандартний спосіб викликати вбудовані операції JavaScript, які раніше були представлені як вбудовані методи об'єкта. Методи Reflect включають ті самі операції, що і операції Proxy, і вони призначені для використання в обробниках (handlers) Proxy.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке  "Event Loop"?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це цикл, який відповідає за виконання коду, збір і обробку подій і виконання під-задач з черги. Так як JavaScript є однопотоковою мовою програмування, що означає, що він виконує лише одну задачу одночасно. Мікротаски потрапляються до стеку, де JavaScript виконує мікрозадачі і якщо вони закінчились, то переходить до виконання макрозадач. Поки мікрозадачі не виконаються, макрозадачі очікують свою чергу.<br>
    До макротасок відносять такі методи:<br>
    - setTimeout() - затримує виконання коду на заданий інтервал часу.<br>
    - setInterval() - повторює виконання коду з заданою періодичністю.<br>
    - addEventListener() - реєструє обробник подій.<br>
    - requestAnimationFrame() - гарантує, що код буде виконаний не пізніше наступного кадру рендерингу.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Типи таймерів в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>setTimeout:<br>
     - setTimeout використовується для виклику функції один раз після заданого проміжку часу (в мілісекундах).<br>
     - Синтаксис: setTimeout(function, delay).<br>
     - clearTimeout використовується для відміни запланованого виклику <br>
     setInterval:<br>
      - setInterval використовується для виклику функції через регулярні проміжки часу (в мілісекундах).<br>
      - Синтаксис: setInterval(function, delay).<br>
      - clearInterval використовується для відміни запланованого виклику.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке функції вищого порядку (Higher Order Functions)?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це функції, які можуть приймати або повертати інші функції як аргументи або значення.
    Ось деякі приклади функцій вищого порядку в JavaScript:<br>
    - map() - приймає функцію як аргумент і повертає новий масив, в якому кожний елемент є результатом застосування цієї функції до відповідного елемента початкового масиву.<br>
    - filter() - приймає функцію як аргумент і повертає новий масив, в якому містяться лише елементи початкового масиву, для яких функція повертає значення true.<br>
    - reduce() - приймає функцію як аргумент і повертає значення, яке є результатом застосування цієї функції до всіх елементів початкового масиву.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Методи рядка в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. length: Повертає довжину рядка.<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.length); // Виведе: 13
    </pre>
    2.charAt(index) або str[index]: Повертає символ за заданим індексом.<br>
    <pre>
      let str = "Hello, World!";
      console.log(str.charAt(0)); // Виведе: "H"
      console.log(str[1]); // Виведе: "e"
    </pre>
    3. substring(startIndex, endIndex): Повертає підрядок від startIndex до endIndex (не включаючи endIndex).<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.substring(0, 5)); // Виведе: "Hello"
    </pre>
    4. slice(startIndex, endIndex): Повертає підрядок від startIndex до endIndex (не включаючи endIndex). Аналогічно substring, але може також приймати від'ємні значення.<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.slice(0, 5)); // Виведе: "Hello"
    console.log(str.slice(-6)); // Виведе: "World!"
    </pre>
    5. indexOf(substring): Повертає індекс першого входження підрядка або -1, якщо підрядок не знайдено.<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.indexOf("World")); // Виведе: 7
    </pre>
    6. replace(searchValue, replaceValue): Замінює перше входження searchValue на replaceValue.<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.replace("World", "Universe")); // Виведе: "Hello, Universe!"
    </pre>
    7. toUpperCase() і toLowerCase(): Перетворюють рядок в верхній або нижній регістр.<br>
    <pre>
    let str = "Hello, World!";
    console.log(str.toUpperCase()); // Виведе: "HELLO, WORLD!"
    console.log(str.toLowerCase()); // Виведе: "hello, world!"
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке чиста функція?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Чиста функція - це функція, яка відповідає двом основним принципам:<br>
      - Відсутність побічних ефектів (No Side Effects): Чиста функція не змінює стан програми або зовнішнього середовища. Вона не має доступу до глобальних змінних, не змінює стан об'єктів, і не взаємодіє з зовнішніми ресурсами.<br>
      - Детермінованість (Deterministic): Для заданих вхідних даних чиста функція завжди повертає один і той самий результат. Вона не залежить від зовнішніх факторів, і тому результат визначається лише вхідними параметрами.
      <pre>
      function add(a, b) {
        return a + b;
      }
      </pre>
      Приклад чистої функції - це редюсер в редаксі.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Різниця між .call(), .apply() і bind()?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це методи, які дозволяють викликати функцію з певним контекстом і аргументами.
    - .call(): Викликає функцію з заданим значенням this та вказаними аргументами. Послідовність передачі аргументів визначається вручну.<br>
    <pre>
      function greet(name) {
        console.log(`Hello, ${name}! My name is ${this.name}.`); // Hello, Alice! My name is John.
      }
      const person = {
        name: "John"
      };
      greet.call(person, "Alice"); 
    </pre>
    - .apply(): Викликає функцію з заданим значенням this та аргументами, які передаються як масив.<br>
    <pre>
    function example(arg1, arg2) {
      console.log(this, arg1, arg2);
    }
    example.apply({name: "John"}, ["arg1value", "arg2value"]);
    </pre>
    - .bind(): Створює нову функцію, прив'язуючи задане значення this і, опціонально, фіксуючи певні аргументи. Основна відмінність від .call() і .apply() - .bind() не викликає функцію відразу, а створює нову функцію, яку ви можете викликати пізніше.<br>
    <pre>
    function greet(name, age) {
      console.log(`Hello, ${name}! I am ${age} years old. My name is ${this.name}.`); // Hello, Alice! I am 30 years old. My name is John.
    }
    const person = {
      name: "John"
    };
    const boundGreet = greet.bind(person, "Alice");
    boundGreet(30);
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Чому в JS функції називають об'єктами першого класу?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це об'єкт, який може бути використаний як будь-яке інше значення в програмі. Об'єкти першого класу можуть бути:<br>
      - Призначені змінним або константам.<br>
      - Передавані функціям як аргументи.<br>
      - Повернутими функціями як значення.<br>
      - Збережені в масивах або об'єктах.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як визначити наявність властивості в об'єкті?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>- Оператор in: Оператор in використовується для перевірки наявності властивості в об'єкті або в його ланцюгу прототипів. Він повертає true, якщо властивість існує.<br>
    <pre>
    const obj = {
      name: "John Doe",
      age: 30,
    };
    const hasName = "name" in obj; // true
    const hasAge = "age" in obj; // true
    const hasAddress = "address" in obj;
    </pre>
    - Метод hasOwnProperty(): Метод hasOwnProperty() перевіряє, чи об'єкт має конкретну властивість. Він повертає true, якщо властивість існує в самому об'єкті (не в ланцюгу прототипів).<br>
    <pre>
      const obj = {
        name: "John Doe",
        age: 30,
      };
      const hasName = obj.hasOwnProperty("name"); // true
      const hasAge = obj.hasOwnProperty("age"); // true
      const hasAddress = obj.hasOwnProperty("address"); // false
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке IIFE?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>IIFE (Immediately Invoked Function Expression) - це вираз функції, який визначається та викликається негайно після його створення. Це конструкція, яка дозволяє визначити функцію і викликати її одразу ж без явного присвоєння імені. IIFE корисні в ситуаціях, де потрібно створити область видимості для змінних, щоб уникнути конфліктів імен. <br>
    <pre>
    (function(x, y) {
      console.log(x + y);
    })(10, 20);
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Різниця між host-об'єктами та нативними об'єктами?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>"Host-об'єкти" і "нативні об'єкти" - це терміни, які використовуються у контексті JavaScript, і вони вказують на дві різні категорії об'єктів в середовищі виконання мови.<br>
    1. Нативні об'єкти: Нативні об'єкти включають в себе такі об'єкти, як Object, Array, String, Number, Function і т.д.<br>
    2. Host-об'єкти: Прикладами host-об'єктів можуть бути window та document в браузері або об'єкти, які надаються серверним середовищем Node.js.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Чому результат порівняння 2-х об'єктів це false?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>При порівнянні двох об'єктів за допомогою оператора рівності (==) або оператора строгого рівності (===) у JavaScript, результат буде false, навіть якщо об'єкти мають однакові властивості та значення. Це трапляється через те, що порівняння об'єктів в цих операторах не порівнює їхні вміст, а порівнює посилання на об'єкти.
    <pre>
      const obj1 = { key: "value" };
      const obj2 = { key: "value" };
      console.log(obj1 === obj2); // false
      console.log(obj1 == obj2);  // false
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як створити об'єкт без прототипу?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Створення об'єкта без прототипа можна здійснити за допомогою функції Object.create(null). Функція Object.create() дозволяє вам створити новий об'єкт і вказати його прототип. Якщо ви передаєте null як аргумент, то створюваний об'єкт не матиме прототипу.<br>
    <pre>
      const obj = Object.create(null);
      console.log(obj.__proto__); // null
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке NaN? Як визначити, що значення дорівнює NaN?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це спеціальне значення в JavaScript, яке означає "Not a Number" (не число). NaN виникає в результаті виконання операції, яка не може бути представлена ​​числом. Наприклад, операція ділення на нуль або спроба взяти корінь з від'ємного числа призведе до NaN.<br>
    - isNaN(): Функція isNaN() перевіряє, чи передане значення є NaN. Важливо враховувати, що isNaN() перетворює передане значення в число перед перевіркою, тому може давати неочікувані результати.<br>
    <pre>
      console.log(isNaN(NaN));          // true
      console.log(isNaN("не число"));    // true
      console.log(isNaN(42));            // false
    </pre>
    - Number.isNaN(): Функція Number.isNaN() є строгою перевіркою, яка повертає true лише тоді, коли передане значення є строго NaN. Ця функція не конвертує значення до числа.<br>
    <pre>
      console.log(Number.isNaN(NaN));          // true
      console.log(Number.isNaN("не число"));    // false
      console.log(Number.isNaN(42));            // false
    </pre>
    - Також можна використовувати оператори === і !== для перевірки рівності значення NaN. Оператор === повертає true, якщо значення дорівнює NaN, і false в іншому випадку. Оператор !== повертає true, якщо значення не дорівнює NaN, і false в іншому випадку.<br>
    <pre>
    const x = 0 / 0;
    console.log(x === NaN); // true
    console.log(x !== NaN); // false
    </pre>
    Ось список операцій, які можуть призвести до NaN:<br>
    - Ділення на нуль<br>
    - Спроба взяти корінь з від'ємного числа<br>
    - Порівняння числа з нечисловим значенням<br>
    - Порівняння двох нечислових значень, які не можна порівняти<br>
    - Перетворення числа в рядок, що не представляє число<br>
    - Перетворення рядка в число, яке не представляє число<br>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке об'єктна обгортка (Wrapper Objects)?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Об'єктна обгортка (Wrapper Objects) в JavaScript - це об'єкти, які надають обгортку (wrapper) для примітивних типів даних (строки, числа, булеві значення). Це дозволяє примітивним типам мати доступ до властивостей та методів об'єктів.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Назви як працюють оператори в js, &&, ||, !!, !, ?, ?., ??, %
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. Логічний оператор "І" (&&):<br>
    - Якщо обидва операнди є істинними (true), результатом буде істина (true).<br>
    - Якщо один з операндів (або обидва) є хибним (false), результатом буде хибне значення (false).<br>
    - Якщо перший операнд є хибним, другий операнд не оцінюється (коротке заміцання).<br>
    <pre>const result = true && false; // результат буде false</pre>
    2. Логічний оператор "АБО" (||):<br>
    - Якщо хоча б один з операндів є істинним, результатом буде істина.<br>
    - Якщо обидва операнди є хибними, результатом буде хибне значення.<br>
    - Якщо перший операнд є істинним, другий операнд не оцінюється (коротке заміцання).<br>
    <pre>const result = true || false; // результат буде true</pre>
    3. Оператор двійного заперечення (!!):<br>
    - Використовується для конвертації значення в булевий тип.<br>
    - Два заперечення можна розглядати як "відмінити відміну", що приводить до булевого значення оригінального виразу.<br>
    <pre>
    const value = "Hello";
    const booleanValue = !!value; // результат буде true
    </pre>
    4. Оператор заперечення (!):<br>
    - Якщо операнд є істинним, оператор заперечення змінить його на хибне значення, і навпаки.<br>
    - Використовується для зміни булевого значення на його протилежне.<br>
    <pre>const result = !true; // результат буде false</pre>
    5. Тернарний оператор (? :): Тернарний оператор приймає три операнди: умову, значення, яке повертається, якщо умова істинна, і значення, яке повертається, якщо умова хибна.<br>
    <pre>const result = condition ? "True" : "False";</pre>
    6. Оператор безпечного доступу до властивості (?.)(optional chaining): Оператор ?. дозволяє вам звертатися до властивостей об'єкта, якщо об'єкт не є null або undefined. Якщо об'єкт є null або undefined, вираз повертає undefined, і не викидає помилку.<br>
    <pre>const value = obj?.property; // результат буде значення властивості або undefined</pre>
    7. Оператор злиття (??): Оператор злиття використовується для вибору першого визначеного значення або значення за умови, що воно не є null або undefined. Якщо лівий операнд є null або undefined, то використовується правий операнд.<br>
    <pre>const result = valueA ?? valueB; // результат буде valueA, якщо valueA не є null або undefined, в іншому випадку - valueB
    </pre>
    8. Оператор остатка (%): Використовується для отримання залишку від ділення одного числа на інше. Результат - це залишок від ділення першого операнду на другий.<br>
    <pre>const remainder = 10 % 3; // результат буде 1</pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке мемоізація?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Мемоізація — це метод оптимізації, який використовується для прискорення виконання функцій шляхом зберігання результатів попередніх викликів функції в кеші. Коли функція викликається знову з тими самими вхідними даними, вона повертає результат з кешу, замість того, щоб заново обчислювати результат. Реалізується через замикання.
    <pre>
      function memoize(func) {
        const cache = {};
        return function (...args) {
          const key = args.join(',');
          if (cache[key] === undefined) {
            // Якщо результат ще не був обчислений, зберегти його у кеші
            cache[key] = func.apply(this, args);
          }
          return cache[key];
        };
      }
      // Приклад функції, яку ми хочемо мемоізувати
      function add(a, b) {
        console.log("Performing expensive calculation...");
        return a + b;
      }
      // Мемоізуємо функцію add
      const memoizedAdd = memoize(add);
      // Перші виклики обчислюють результат і зберігають його у кеші
      console.log(memoizedAdd(1, 2)); // Performing expensive calculation... 3
      console.log(memoizedAdd(1, 2)); // 3 (результат вже з кешу)
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке регулярні вирази (Regular Expression)?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Pегулярні вирази (Regular Expression або RegExp) - це вираз, що визначає шаблон пошуку для рядка тексту. Вони дозволяють вам виконувати операції пошуку, заміни та валідації тексту на основі певного шаблону. Регулярні вирази складаються з символьних шаблонів та ряду метасимволів, які визначають правила пошуку або трансформації тексту.<br>
    1. test(): Цей метод використовується для визначення того, чи відповідає заданий рядок регулярному виразу. Він повертає true, якщо відповідність знайдена, та false в іншому випадку.<br>
    <pre>
    const regex = /\d+/;
    const result = regex.test("Hello, 123");
    console.log(result); // Виведе: true
    </pre>
    2. exec(): Цей метод використовується для пошуку відповідності між регулярним виразом і рядком тексту. Він повертає об'єкт результату або null, якщо відповідності не знайдено.<br>
    <pre>
    const regex = /\d+/;
    const result = regex.exec("Hello, 123");
    console.log(result); // Виведе: [ '123', index: 7, input: 'Hello, 123', groups: undefined ]
    </pre>
    3. match(): Цей метод використовується для отримання масиву відповідностей між рядком тексту та регулярним виразом.<br>
    <pre>
    const regex = /\d+/;
    const result = "Hello, 123".match(regex);
    console.log(result); // Виведе: [ '123', index: 7, input: 'Hello, 123', groups: undefined ]
    </pre>
    4.search(): Цей метод повертає індекс першої знайденої відповідності між регулярним виразом та рядком тексту. Якщо відповідності не знайдено, повертається -1.<br>
    <pre>
    const regex = /\d+/;
    const result = "Hello, 123".search(regex);
    console.log(result); // Виведе: 7
    </pre>
    5. replace(): Цей метод використовується для заміни тексту, який відповідає регулярному виразу, іншим текстом.<br>
    <pre>
    const regex = /\d+/;
    const result = "Hello, 123".replace(regex, "456");
    console.log(result); // Виведе: "Hello, 456"
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке switch/case?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>switch і case - це конструкції в JavaScript, які використовуються для вирішення вибору однієї з можливих гілок виконання коду на основі значення виразу. Вони допомагають замінити повторення if...else if...else конструкцій в тих випадках, коли потрібно виконати різні дії залежно від значення змінної.<br>
    - Зіставлення значень: Значення виразу у switch порівнюється зі значеннями у кожному case. Якщо вони рівні, виконується код, пов'язаний із збігаючимся case. Якщо збіг не знайдений, виконується код у блоках default, якщо він присутній.<br>
    - break: Ключове слово break вказує на завершення виконання блока switch. Якщо його не використовувати, виконання коду продовжиться для наступних case без перевірки значення.<br>
    - default: Блок default використовується для коду, який повинен виконатися, якщо ні один із блоків case не збігається зі значенням виразу. default - необов'язковий і може бути розміщений в кінці або в іншому місці.<br>
    <pre>
    let day = 3;
      let dayName;
      switch (day) {
        case 1:
          dayName = 'Monday';
          break;
        case 2:
          dayName = 'Tuesday';
          break;
        case 3:
          dayName = 'Wednesday';
          break;
        case 4:
          dayName = 'Thursday';
          break;
        case 5:
          dayName = 'Friday';
          break;
        case 6:
          dayName = 'Saturday';
          break;
        case 7:
          dayName = 'Sunday';
          break;
        default:
          dayName = 'Unknown';
      }
      console.log(dayName); // Виведе: 'Wednesday'
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Напиши усі методи Math в js.
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Об'єкт Math, який містить різні математичні методи.<br>
    - Math.abs(x): Повертає абсолютне значення числа x.<br>
    - Math.ceil(x): Округлює число x вверх до найближчого цілого числа.<br>
    - Math.floor(x): Округлює число x вниз до найближчого цілого числа.<br>
    - Math.round(x): Округлює число x до найближчого цілого числа. Якщо частина після десяткової коми менше 0.5, число округлюється вниз; якщо 0.5 або більше - вверх.<br>
    - Math.max(x1, x2, ..., xn): Повертає найбільше з переданих чисел або значень.<br>
    - Math.min(x1, x2, ..., xn): Повертає найменше з переданих чисел або значень.<br>
    - Math.pow(x, y): Підносить число x до ступеня y.<br>
    - Math.sqrt(x): Обчислює квадратний корінь числа x.<br>
    - Math.exp(x): Обчислює експоненту числа x.<br>
    - Math.log(x): Обчислює натуральний логарифм числа x.<br>
    - Math.sin(x), Math.cos(x), Math.tan(x): Обчислюють синус, косинус і тангенс кута x (в радіанах).<br>
    - Math.random(): Повертає випадкове число від 0 (включно) до 1 (не включаючи).<br>
    <pre>const randomNumber = Math.random() * 100 + 1;</pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке карірування?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це процес перетворення функції з багатьма аргументами в послідовність функцій з одним аргументом. При цьому кожна наступна функція в послідовності отримує один з аргументів початкової функції.
    <pre>
    function add(a, b, c) {
      return a + b + c;
    }
    const addTwo = add(1, 2);
    const addThree = addTwo(3);
    console.log(addThree); // 6
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке .dataset в js?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Властивість .dataset в JavaScript є частиною DOM API та використовується для доступу до атрибутів даних (data attributes) елементів HTML. Атрибути даних дозволяють вам зберігати додаткові дані, пов'язані з елементами HTML, які не впливають на їх відображення, але можуть бути використані для JavaScript та CSS.<br>
    <pre>
    const element = document.getElementById('myElement');
    // Отримання значень атрибутів даних
    const userId = element.dataset.userId; // або element.dataset['userId']
    const userName = element.dataset.userName; // або element.dataset['userName']
    console.log(userId); // "123"
    console.log(userName); // "johnDoe"
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як працює «складальник сміття» в JavaScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Garbage Collector в JavaScript - це механізм автоматичного визначення та звільнення пам'яті, яку більше не використовує жоден об'єкт або змінна. Основна ідея полягає в тому, щоб автоматично визначати "мертві" об'єкти та звільняти пам'ять, яку вони використовують, забезпечуючи ефективне використання ресурсів. В основі роботи сборщика мусора лежить алгоритм підрахунку досяжності. За допомогою цього алгоритму визначається, які об'єкти в пам'яті є доступними та можуть бути використані, а які вже не мають посилань і є "мертвими". Об'єкти, які не можна досягнути через жодний ланцюжок посилань в програмі, вважаються "мертвими" та відзначаються для видалення.<br>
    Процес роботи сборщика мусора може виглядати приблизно так:<br>
    - Маркування (Marking): Сборщик мусора проходить по об'єктах у пам'яті та маркує ті, які є досяжними (живими), зазвичай використовуючи алгоритми, що базуються на підрахунку досяжності.<br>
    - Спрямовання (Sweeping): Сборщик мусора видаляє "мертві" об'єкти, тобто ті, які не були помічені під час маркування. Пам'ять, яку вони використовують, звільняється для подальшого використання.<br>
    - Компактизація (Compaction) (не завжди): У деяких випадках сборщик мусора може виконувати операцію компактизації, переміщаючи живі об'єкти, щоб звільнити фрагментовану пам'ять.<br>
    - Цикл повторення (Repeat): Процес маркування, спрямовання та, можливо, компактизації повторюється в періодичному порядку для забезпечення ефективного управління пам'яттю.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке витік пам'яті в js?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <>Витік пам'яті в JavaScript відбувається, коли програма не вивільняє пам'ять, яку вже не використовує, і тим самим збільшує обсяг використаної пам'яті. Це може призвести до зростання використання ресурсів і, в кінцевому рахунку, до проблем з продуктивністю та відгуком програми.<br>
    Основні причини витоків пам'яті в JavaScript включають:<br>
    - Циклічні посилання: Коли об'єкти взаємно посилають один на одного і утворюють циклічні посилання, сборщик мусора може не виявити, що об'єкти більше не доступні для використання, і вони не будуть вивільнені.<br>
    - Забуті посилання на об'єкти: Якщо ви створюєте посилання на об'єкти і забуваєте їх знищити, це може призвести до того, що сборщик мусора не зможе вивільнити відповідну пам'ять.<br>
    - Підписки на події: Використання подій та підписок може також призводити до витоків пам'яті, якщо не правильно видаляти підписки, особливо, коли об'єкти залишаються в пам'яті через підписки.<br>
    - Неочищені ресурси: Витік пам'яті може виникнути, коли використовуються ресурси, такі як таймери чи робочі потоки, і не вивільняються вчасно.<br>
    - Глобальні змінні: Глобальні змінні можуть залишатися в пам'яті до кінця життя додатка, що може призвести до витоків пам'яті.
    <pre>
    // Виправлення витоку пам'яті: коректне вивільнення пам'яті
    function fixMemoryLeak() {
      const objA = {};
      const objB = {};
      objA.reference = objB; // objA посилається на objB
      objB.reference = objA; // objB посилається на objA
      // Явно встановлюємо посилання на null, щоб припинити циклічну залежність
      objA.reference = null;
      objB.reference = null;
      // За необхідності можна також вивільнити інші ресурси або викликати інші дії
      // Сборщик мусора тепер може вивільнити пам'ять, оскільки немає циклічних посилань
    }
    // Виклик функції для виправлення витоку пам'яті
    fixMemoryLeak();
    </pre>
    </p>
  </div>
</details>

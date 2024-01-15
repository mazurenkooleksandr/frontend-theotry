<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>TypeScript - це надмножина JavaScript, яка додає статичну типізацію. Основні особливості TypeScript включають:
    1. Статична типізація: TypeScript дозволяє вказувати типи для змінних, параметрів функцій, об'єктів і т.д. на етапі розробки. Це допомагає виявляти помилки типізації перед тим, як код буде виконаний.
    2. Розширені функції: TypeScript надає ряд розширених функцій, таких як generics, перерахувані типи, кортежі та інші, які полегшують розробку та підтримку коду.
    3. Інструменти розробника: TypeScript інтегрується з рядом популярних інструментів розробки, таких як Visual Studio Code, які надають функції автодоповнення, підказок, виявлення помилок та інше.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як встановити TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>npm install -g typescript</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які основні вбудовані типи в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>1. number: Представляє числові значення, такі як цілі числа або числа з плаваючою комою.<br>
    2. string: Представляє рядкові значення.<br>
    3. boolean: Представляє логічні значення true або false.<br>
    4. array: Представляє масиви значень одного типу.<br>
    5. tuple: Представляє масив з фіксованою кількістю елементів та їхніми конкретними типами.<br>
    6. enum: Використовується для створення іменованих констант.<br>
    7. any: Представляє будь-який тип даних. Використання any слабко типізоване і може зменшити перевірку типів.<br>
    8. void: Використовується для функцій, які не повертають значень.<br>
    9. null та undefined: Представляють відповідно значення null і undefined.<br>
    10. never: Представляє тип, для якого немає значень. Використовується, коли функція завершується або генерує помилку.<br>
    11. object: Представляє значення типу об'єкта.<br>
    12. unknown: Подібно до any, але більше безпечно типізоване. Потребує перевірки типів перед використанням.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке інтерфейси в TypeScript і для чого вони використовуються?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript інтерфейс - це механізм, який дозволяє описати структуру об'єкта або типу даних. Вони використовуються для визначення контрактів між різними частинами вашого коду. Основні моменти стосовно інтерфейсів включають:<br>
    1. Опис структури даних: Інтерфейси дозволяють описувати форму та структуру об'єктів або типів даних. Вони визначають, як повинен виглядати об'єкт або тип.<br>
    2. Підтримка контрактів: Інтерфейси допомагають встановлювати контракти між різними частинами програми. Наприклад, коли ви створюєте функцію, яка очікує об'єкт з певними властивостями, ви можете використовувати інтерфейс для визначення цих властивостей.<br>
    3. Розширення та наслідування: Інтерфейси можуть наслідувати властивості та методи інших інтерфейсів. Це сприяє використанню та перевикористанню коду.<br>
    4. Опис функцій: Інтерфейси можуть також використовуватися для опису типів функцій, включаючи параметри та тип повернення.<br>
    5. Необов'язкові властивості: В інтерфейсах можуть бути визначені необов'язкові властивості, які можуть або не можуть бути вказані при створенні об'єкта.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які варіанти для оголошення масивів в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Використання квадратних дужок (Array Type): let numbers: number[] = [1, 2, 3, 4, 5];<br>
       Використання Array<elementType>: <pre>let numbers: Array<number> = [1, 2, 3, 4, 5];</pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як вказати тип для об'єкта в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У TypeScript ви можете вказати тип для об'єкта за допомогою інтерфейсів або типів (type aliases).<br>
        1. Використання інтерфейсу:<br>
        <pre>
            interface Person {
                name: string;
                age: number;
                email?: string;
            }
        </pre>
        2. Використання типу (type alias):<br>
        <pre>
            type Person = {
                name: string;
                age: number;
                email?: string;
            };
        </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке generics в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Generics в TypeScript - це механізм, який дозволяє створювати функції, класи і інші конструкції, які мають здатність працювати з різними типами даних. Приклад використання generics у функції:
    <pre>
        function identity<T>(arg: T): T {
            return arg;
        }
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "декоратори" (decorators) в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>
        Декоратори в TypeScript - це спеціальні функції, які можуть бути використані для додавання додаткової функціональності до класів, методів, властивостей та інших елементів коду. Декоратори можуть бути використані для додавання логіки, перевірки, аннотації або навіть для перетворення коду. Приклад, @logDecorator</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як зробити параметри необов'язковими(опціаональними) в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript, ви можете зробити параметри функції необов'язковими, дозволяючи їм приймати undefined або використовуючи оператор ? у сигнатурі функції. </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "аліаси типів" (type aliases) в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У TypeScript аліаси типів (type aliases) використовуються для створення нових імен, які відображають існуючі типи або комбінування типів. Аліаси типів роблять код більш читабельним та покращують його модульність, дозволяючи вам використовувати коротші та більш описові імена для складних типів.<br>
    <pre>
    type User = {
        id: number;
        username: string;
        email: string;
    };
    </pre></p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Натисни, щоб відкрити/закрити текст
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>"Злиття типів" (type merging) в TypeScript - це механізм, який дозволяє об'єднувати кілька оголошень типів для створення одного типу. Це часто використовується при роботі з інтерфейсами та об'єктами, які можуть мати розширені властивості.<br>
    Основний принцип злиття типів полягає в тому, що якщо ви визначаєте один тип з одним ім'ям, а потім визначаєте ще один тип з тим самим ім'ям, TypeScript автоматично зливає їх в один: <br>
    <pre>
        interface Person {
            name: string;
            age: number;
        }

        interface Person {
            gender: string;
        }

        let john: Person = {
            name: "John",
            age: 30,
            gender: "male"
        };

</pre>
</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "enum" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript ключовим моментом є наявність перерахувань, або "enum" (enumeration). Enum визначає набір іменованих константних значень, які називаються членами enum. Enum у TypeScript забезпечує зручний спосіб працювати з наборами значень і дозволяє надати поняттям значень іменовані ідентифікатори.
    <pre>
    enum Direction {
        Up = "UP",
        Down = "DOWN",
        Left = "LEFT",
        Right = "RIGHT"
    }
    let move: Direction = Direction.Left;
    </pre>
    </p>
  </div>
</details>

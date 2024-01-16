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
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як ви використовуєте "namespace" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript "namespace" - це спеціальний засіб для організації коду та створення глобальних областей імен. Namespace дозволяє групувати пов'язаний код в одній області імені, щоб уникнути конфліктів імен між різними частинами програми.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як ви реалізуєте інкапсуляцію в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Інкапсуляція в TypeScript - це принцип об'єктно-орієнтованого програмування, який дозволяє приховати деталі реалізації об'єкта від його користувачів. Це робиться за допомогою модифікаторів доступу, які визначають, які частини об'єкта можуть бути доступні ззовні.<br>
    В TypeScript існує чотири модифікатори доступу:<br>
    - public - доступний з будь-якої точки програми;<br>
    - protected - доступний із класу, в якому він визначений, а також з його нащадків;<br>
    - private - доступний лише із класу, в якому він визначений;<br>
    - readonly - доступний лише для читання.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке абстрактний клас в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Абстрактний клас в TypeScript - це клас, який не може бути створений безпосередньо. Абстрактні класи використовуються для визначення загальної поведінки, яка може бути реалізована в конкретних класах. Абстрактні класи оголошуються за допомогою ключового слова abstract перед ключовим словом class.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "модифікатори доступу" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Модифікатори доступу в TypeScript - це слова-ключі, які використовуються для визначення, як члени класу можуть бути доступні з інших частин програми.<br>
    В TypeScript існує чотири модифікатори доступу:<br>
    - public - доступний з будь-якої точки програми;<br>
    - protected - доступний із класу, в якому він визначений, а також з його нащадків;<br>
    - private - доступний лише із класу, в якому він визначений;<br>
    - readonly - доступний лише для читання.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "intersection types" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Intersection types в TypeScript - це спосіб комбінувати два чи більше типи в один. Вони використовують оператор & для створення нового типу, який включає всі властивості та методи кожного з об'єднаних типів. Це дозволяє вам створювати складні типи, що поєднують різні аспекти програми.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "union types" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Union types в TypeScript дозволяють об'єднувати кілька типів в один, вказуючи їх через символ |. Це дозволяє зазначати, що значення може мати один із зазначених типів. Union types надають гнучкість і використовуються для роботи з різними можливими типами значень.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "Type Assertion" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Type Assertion - це оператор, який використовується для інформування компілятора про тип змінної або значення. У TypeScript, Type Assertion використовується для того, щоб повідомити компілятору, що тип змінної або значення насправді є іншим, ніж те, що він визначив. Це може бути корисно в тих випадках, коли компілятор не може інферувати тип автоматично. Type Assertion використовується за допомогою оператора as.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "never" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript, never - це тип, який не може приймати ніяких значень. Цей тип використовується для позначення ситуацій, в яких значення ніколи не може бути отримане. Наприклад, функція, яка завжди генерує помилку, має тип never.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "as const" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript, ключове слово as const використовується для вказівки на те, що змінна або об'єкт мають константний тип, тобто їх значення або структура не можуть бути змінені. let y = "world" as const;</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "keyof" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript ключове слово keyof використовується для створення типу, який містить всі можливі ключі (властивості) об'єкта чи іншого типу. Воно надає можливість динамічно визначати ключі та використовувати їх для доступу до властивостей об'єкта.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "Tuple Types" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В TypeScript "Tuple Types" представляють собою спеціальний тип для роботи з кортежами. Кортежі - це масиви з фіксованою кількістю елементів, де кожен елемент може мати визначений свій тип. Типове визначення кортежу виглядає як перерахування типів для кожного елемента.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "Global Types" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У TypeScript термін "Global Types" використовується для опису типів, які є доступними на рівні всього проекту або взагалі на рівні глобального простору імен. Глобальні типи можуть бути визначені за допомогою ключового слова declare в файлі з розширенням .d.ts. Основна ідея полягає в тому, що ви можете визначати типи, які будуть доступні у всіх частинах вашого коду, без необхідності їх повторюваного визначення.<br>
    <pre>
      declare global {
        interface AppConfig {
            apiUrl: string;
            debugMode: boolean;
        }
      }
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "Triple-slash Directives" в TypeScript?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>"Triple-slash directives" в TypeScript - це спеціальні коментарі, які можуть бути використані для вказівки деяких конфігураційних параметрів або залежностей в межах файлу. Ці коментарі починаються з трьох слешів (///) і можуть містити деякі директиви, такі як reference, amd-dependency, amd-module, тощо. Однією з часто використовуваних "Triple-slash directives" є директива /// <reference path="..." />, яка вказує на залежність від іншого файлу. </p>
  </div>
</details>

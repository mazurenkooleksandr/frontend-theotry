<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке MobX і як він відрізняється від інших бібліотек для керування станом?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>MobX - це бібліотека для управління станом в додатках, написаних на JavaScript або TypeScript. Головна ідея MobX - це зробити управління станом простим і ефективним, забезпечуючи автоматичну реактивність. MobX не змінює один і той же обєкт, не створює новий.<br>
    Основні характеристики MobX:<br>
    - Реактивність: MobX використовує концепцію реактивності, щоб автоматично визначати, коли і які частини стану потрібно оновлювати при зміні даних. Це дозволяє створювати код, який реагує на зміни стану без вручну написаного коду для визначення оновлень.<br>
    - Простота використання: MobX призначений для зручного використання і має простий API. Він не вимагає великої кількості додаткового коду для визначення стору та оновлення його стану.<br>
    - Декларативний підхід: Ви описуєте ваш стан та логіку зміни стану декларативно, використовуючи MobX-анотації (зокрема, декоратори, як-то @observable, @computed, і @action).<br>
    - Вирішення проблем "грязного стану": MobX робить важливий акцент на тому, щоб мати єдиний, зрозумілий джерело правди (Single Source of Truth) в додатку, уникнувши так званого "грязного стану".<br>
    Порівняно з іншими бібліотеками управління станом, такими як Redux, MobX часто вважається більш простим у використанні та має менше "церемоній" коду. Він дозволяє зосереджуватися на логіці додатку, замість того, щоб вирішувати питання, як правильно розділити дії, редюсери та джерела даних.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які основні принципи роботи MobX?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>MobX працює на основі декларативного та реактивного підходів. Основні принципи роботи MobX можна узагальнити наступним чином:<br>
    - Реактивність (Reactivity): Одним з ключових принципів MobX є використання реактивності. Коли ви оголошуєте частину вашого стану, яка може змінюватися (observable), MobX автоматично встановлює відстеження цих змін. Це дозволяє автоматично перерендерювати відповідні частини вашого інтерфейсу користувача або викликати інші зміни, які пов'язані зі змінами стану.<br>
    - Декларативність (Declarative): MobX підтримує декларативний підхід до визначення стану та логіки зміни стану. Ви можете використовувати декоратори (такі як @observable, @computed, і @action), щоб декларативно вказати, які частини стану є спостережуваними (observable), які є обчислюваними значеннями (computed), і які методи забезпечують зміну стану (actions).<br>
    - Атомарні зміни (Atomic Changes): MobX рекомендує робити зміни стану в рамках атомарних операцій (actions). Це означає, що всі зміни стану повинні бути виконані як єдина транзакція, яка гарантує, що всі відстежувачі (observers) будуть сповіщені про зміни тільки після завершення всіх змін.<br>
    - Спрощена модель об'єкта (Simplified Object Model): MobX спрощує модель об'єкта, дозволяючи оголошувати об'єкти зі спостережуваними властивостями. Це зменшує кількість "лишнього" коду, який інакше був би необхідний для роботи зі станом.<br>
    - Відсутність необхідності у додаткових концепціях: В порівнянні з іншими бібліотеками керування станом, MobX робить акцент на відсутності необхідності у додаткових концепціях, таких як редюсери або середовища дій. Все, що вам потрібно, це декларувати свій стан та методи його зміни.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке MobX-спостерігачі(observable) і для чого вони використовуються?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>MobX-спостерігачі (observers) є частиною концепції реактивності в MobX. Спостерігачі - це функції або компоненти, які автоматично перерендерюються або викликаються при зміні спостережуваного значення, яке вони відстежують. Основна ідея полягає в тому, що коли спостережуване значення змінюється, всі його спостерігачі повідомляються про цю зміну і автоматично оновлюють себе.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке стор в MobX?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У контексті MobX термін "стор" (store) використовується для позначення об'єкта, який містить стан додатка та логіку його зміни. Стор - це зручний спосіб організації та управління станом в MobX.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які переваги має MobX перед Redux?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>
    1. Простота використання:<br>
    - MobX: Вважається більш простим та легким для використання. MobX не вимагає багато шаблонного коду, і його API може здаватися менш складним для новачків.<br>
    - Redux: Має більше "церемонійного" коду, такого як дії, редюсери та магазини, що може вимагати більше часу для вивчення та розуміння.<br>
    2. Реактивність:<br>
    - MobX: Має вбудовану підтримку реактивності, що дозволяє автоматично визначати, коли перерендерювати компоненти або викликати інші зміни відповідно до змін стану.<br>
    - Redux: Реактивність в Redux може бути досягнута за допомогою middleware або бібліотек, таких як Redux Observable чи Redux Saga.<br>
    3. Декларативний підхід:<br>
    - MobX: Має більш декларативний підхід до визначення та оновлення стану. Використання декораторів (зокрема, декораторів MobX) дозволяє декларативно вказувати, які частини стану слід відстежувати та оновлювати.<br>
    - Redux: Має більш імперативний підхід, де потрібно ретельно керувати діями, редюсерами та контейнерами.<br>
    4. Швидкість розробки:<br>
    - MobX: Зазвичай забезпечує швидший процес розробки завдяки простоті та меньшому обсягу коду.<br>
    - Redux: Може вимагати більше часу на конфігурацію та розробку через більш велику кількість концепцій.<br>
    5. Адаптивність:<br>
    - MobX: Легше адаптується до різних підходів та стилів програмування. Може бути використаний у мікросервісних архітектурах.<br>
    - Redux: Має більш жорсткі конвенції, що може обмежити адаптивність в різних контекстах.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які декоратори MobX ви використовуєте, і як вони допомагають у розробці?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Декоратори MobX - це анотації, які можна використовувати для позначення різних типів об'єктів та їх властивостей. Вони спрощують синтаксис та збільшують читабельність коду. Ось кілька основних декораторів MobX та їх призначення:<br>
    1. @observable (спостережені властивості):<br>
    - Використовується для визначення змінних, які будуть спостерігати за їхніми змінами.<br>
    - Допомагає автоматично визначати залежності та оновлювати відповідні компоненти при змінах.<br>
    2. @computed (обчислені значення):<br>
    - Використовується для визначення обчислюваних значень, які автоматично оновлюються при змінах в їхніх залежностях.<br>
    - Допомагає зменшити необхідність вручну визначати, коли та як оновлювати певні значення.<br>
    3. @action (дії):<br>
    - Використовується для визначення методів, які змінюють спостережуваний стан.<br>
    - Забезпечує гарантію того, що всі зміни стану відбуваються як єдина транзакція.<br>
    4. @autorun (автоматичні виклики):<br>
    - Використовується для автоматичного виклику функції при кожній зміні залежностей.<br>
    - Допомагає автоматизувати реакцію на зміни стану.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Як ви реагуєте на зміни стану в MobX?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У MobX я реагую на зміни стану за допомогою спостерігачів(observable). Спостерігачі - це функції, які викликаються всякий раз, коли змінюється стан. Я можу використовувати спостерігачі, щоб оновити свій стан або поведінку відповідно до змін у стані.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке observable в mobx?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Observable в MobX вказує на те, що об'єкт або значення є спостережуваним, тобто його зміни відслідковуються. Функція observable приймає об'єкт чи масив і повертає його "спостережувану" версію. Для чого це потрібно: <br>
    1. Автоматичний перерендерінг компонентів React: Якщо ви використовуєте MobX з React, ви можете робити ваші компоненти "реактивними", тобто вони будуть автоматично перерендерюватися, коли дані, які вони використовують, змінюються.<br>
    2. Простота відслідковування стану: MobX робить простим відслідковування змін в стані програми. Вам не потрібно вручну визначати та підтримувати багато коду для обновлення ваших інтерфейсів при змінах.<br>
    3. Управління станом додатків: Використання "observable" дозволяє зручно управляти станом вашого додатка, а MobX буде відповідати за автоматичне оновлення ваших інтерфейсів.
    <pre>
    import { observable } from 'mobx';
    const store = observable({
      // Спостережувані властивості
      name: 'John',
      age: 25,
      //...
    });
    // Зміни властивостей будуть автоматично відстежуватися
    store.name = 'Jane';
    </pre></p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке observer і для чого в mobx?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В MobX React існує спеціальна функція observer, яка використовується для зручної інтеграції з React. В MobX, функція observer приймає компонент React і повертає новий компонент React, який автоматично буде перерендерюватися при зміні спостеріганих даних (observable) в MobX. Ця функція дозволяє автоматично перерендерювати компонент, коли відбувається зміна в MobX-спостерігачах (observable). Вона використовує паттерн спостерігача (Observer pattern) для визначення залежностей компонента від даних та автоматичного перерендерення при їх зміні.
    <pre>
    import { observer } from 'mobx-react';
    import { observable } from 'mobx';
    import React from 'react';
    const myStore = observable({
      data: 'Initial data',
      updateData: function(newData) {
        this.data = newData;
      },
    });
    const MyComponent = observer(({ store }) => (
      div
        p{store.data}p
        button onClick={() => store.updateData('New data')}
          Update Data
        button
      div
    ));
    // Використання компонента
    MyComponent store={myStore};
    </pre></p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке computed?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>computed в MobX - це концепція, яка дозволяє створювати обчислювальні властивості, залежні від інших даних в MobX, які автоматично оновлюються.
    <pre>
    import { observable, computed } from 'mobx';
      class MyStore {
        @observable width = 10;
        @observable height = 20;
        @computed get area() {
          return this.width * this.height;
        }
      }
      const myStore = new MyStore();
      console.log(myStore.area); // Виведе: 200
      myStore.width = 15;
      console.log(myStore.area); // Автоматично оновиться до: 300
    </pre>
    В MobX, computed - це функція, яка створює обчислювальну властивість (computed property). Обчислювальні властивості особливо корисні, коли вам потрібно створити значення, яке залежить від інших даних, але ви хочете, щоб MobX автоматично відстежував цю залежність і викликав перерахунок, коли необхідно. Такий підхід сприяє автоматизації управління станом та спрощує код.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке action?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У MobX, action - це функція або декоратор, яка визначає дію, яка може мутувати стан MobX. Функція action розширює область дії (action context), де зміни в спостережуваних (observable) об'єктах автоматично фіксуються.
    <pre>
    import { observable, action } from 'mobx';
        class MyStore {
          @observable count = 0;
          @action increment() {
            this.count += 1;
          }
          @action decrement() {
            this.count -= 1;
          }
        }
        const myStore = new MyStore();
        console.log(myStore.count); // Виведе: 0
        myStore.increment();
        console.log(myStore.count); // Виведе: 1
        myStore.decrement();
        console.log(myStore.count); // Виведе: 0
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке action.bound?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>action.bound - це декоратор в MobX, який автоматично зв'язує дії (actions) з екземпляром класу. В основному це забезпечує автоматичне виведення дій в контексті екземпляра класу, що їх містить, і робить їх "прив'язаними" до цього екземпляра.<br>
    Для чого використовується action.bound?<br>
    Використання action.bound зручно в тих випадках, коли вам потрібно передавати метод класу як обробник події, колбек чи іншу функцію, і ви хочете, щоб this у внутрішньому коді методу відносилось до екземпляра класу. Декоратор робить це автоматично, дозволяючи уникнути проблеми з втратою контексту та неправильною роботою коду.<br>
    <pre>
    import { observable, action } from 'mobx';
      class MyStore {
        @observable count = 0;
        @action.bound
        increment() {
          this.count += 1;
        }
        @action.bound
        decrement() {
          this.count -= 1;
        }
      }
      const myStore = new MyStore();
      console.log(myStore.count); // Виведе: 0
      const incrementFunction = myStore.increment;
      incrementFunction();
      console.log(myStore.count); // Виведе: 1
      const decrementFunction = myStore.decrement;
      decrementFunction();
      console.log(myStore.count); // Виведе: 0
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке decorate?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>decorate - це функція в MobX, яка використовується для налаштування декораторів для полів класу, таких як observable, computed, та action. 
    <pre>
    import { decorate, observable, computed, action } from 'mobx';
    class MyClass {
      myObservableField = 'Initial value';
      myComputedField() {
        return this.myObservableField.length;
      }
      myAction = () => {
        this.myObservableField = 'New value';
      }
    }
    decorate(MyClass, {
      myObservableField: observable,
      myComputedField: computed,
      myAction: action,
    });
    </pre></p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке makeObservable?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>makeObservable - це функція в MobX, яка використовується для налаштування декораторів для полів класу, таких як observable, computed та action. Вона дозволяє явно визначити, які властивості класу повинні бути спостережуваними, обчислюваними чи діями, і які необхідно включити в реактивні об'єкти MobX.
    <pre>
    import { makeObservable, observable, computed, action } from 'mobx';
    class MyClass {
      myObservableField = 'Initial value';
      constructor() {
        makeObservable(this, {
          myObservableField: observable,
          myComputedField: computed,
          myAction: action,
        });
      }
      get myComputedField() {
        return this.myObservableField.length;
      }
      myAction = () => {
        this.myObservableField = 'New value';
      }
    }
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Різниця між makeObservable та decorate.
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>makeObservable та decorate - це дві альтернативні функції в MobX, які використовуються для налаштування декораторів для полів класу, таких як observable, computed, та action. Ось деякі ключові різниці між ними:<br>
    1. Спосіб виклику:<br>
    - decorate є функцією, яка викликається зовні класу, і вона приймає клас та об'єкт конфігурації декораторів.<br>
    - makeObservable є методом класу, і його слід викликати всередині конструктору класу. Він приймає екземпляр класу та об'єкт конфігурації декораторів.<br>
    2. Використання в класі:<br>
    - decorate визначається поза класом, і його викликають після визначення класу.<br>
    - makeObservable викликається всередині конструктору класу.<br>
    3. Динамічність:<br>
    - decorate дозволяє динамічно визначати конфігурацію декораторів після визначення класу.<br>
    - makeObservable також дозволяє динамічно визначати конфігурацію, але він викликається всередині конструктору, тобто при створенні нового екземпляру класу.<br>
    4. Зручність синтаксису:<br>
    - Синтаксис decorate зазвичай є більш компактним та декларативним.<br>
    - Синтаксис makeObservable може виглядати більш імперативним та менш зручним для визначення конфігурації декораторів.<br>
    5. Підтримка декораторів:<br>
    - decorate ширше підтримує сучасний синтаксис декораторів і може використовуватися у багатьох сучасних проектах.<br>
    - makeObservable може бути корисним у випадках, коли вам потрібно підтримувати старший синтаксис або якщо ви хочете взаємодіяти з MobX у більш імперативний спосіб.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке autorun?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Autorun - це функція в MobX, яка запускає функцію, яка відповідає за побічний ефект, щоразу, коли змінюється будь-який стан, який вона спостерігає. Вона також запускається один раз, коли створюється сама autorun. Autorun приймає одну функцію як аргумент. Ця функція може виконувати будь-які побічні ефекти, такі як логування, збереження або оновлення інтерфейсу користувача. Autorun використовується в MobX для запуску побічних ефектів, які залежать від стану MobX. Наприклад, autorun можна використовувати для логування змін стану, оновлення інтерфейсу користувача або виконання асинхронних операцій.
    <pre>
    import { autorun, observable } from 'mobx';
    const myStore = observable({
      value: 0,
    });
    const disposer = autorun(() => {
      console.log('Current value:', myStore.value);
    });
    // При кожній зміні `myStore.value`, виведеться нове значення
    // Приклад зміни даних
    myStore.value = 10;
    // Виведе: "Current value: 10"
    // Закриваємо autorun (відключає відслідковування)
    disposer();
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке toJS?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>toJS - це функція в MobX, яка використовується для перетворення об'єктів MobX (спостережуваних об'єктів, обчислювальних властивостей тощо) в прості JavaScript-об'єкти без внутрішніх MobX-посилань та об'єктів. Важливо враховувати, що toJS повертає "глибоку" копію об'єкта, тобто всі вкладені об'єкти також будуть скопійовані та приведені до стандартного JavaScript-об'єкту.
    <pre>
    import { observable, toJS } from 'mobx';
    const myObservableObject = observable({
      name: 'John',
      age: 25,
    });
    const plainObject = toJS(myObservableObject);
    console.log(plainObject);
    // Результат: { name: 'John', age: 25 }
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Які концепції в Mobx?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Mobx базується на 4-х концепціях: action, observable, computed, reactions.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке configure?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>configure() - це функція в MobX, яка використовується для налаштування поведінки MobX. Вона приймає об'єкт з параметрами налаштування.<br>
    enforceActions: Визначає, чи MobX повинен вимагати використання дій (actions) для модифікації стану (за замовчуванням 'never').<br>
    computedRequiresReaction: Визначає, чи MobX вимагатиме наявності реакцій для обчислювальних властивостей (за замовчуванням false).<br>
    observableRequiresReaction: Визначає, чи MobX вимагатиме наявності реакцій для зміни спостережуваного об'єкту (за замовчуванням false).<br>
    disableErrorBoundaries: Забороняє використання областей помилок для вилучення помилок, спричинених MobX (за замовчуванням false).<br>
    safeDescriptors: Робить MobX менш чутливим до об'єктів з небезпечними дескрипторами властивостей (за замовчуванням true).<br>
    disableErrorBoundaries: Забороняє MobX виводити застереження у консоль для деяких стандартних випадків (за замовчуванням false).
  <pre>
  import { configure } from 'mobx';
  configure({
    // Параметри та опції
  });
  </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке extendobservable?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>extendObservable - це функція в бібліотеці MobX, яка використовується для динамічного додавання нових спостережуваних властивостей до об'єктів. Ця функція дозволяє розширювати об'єкти, надаючи їм спроможність реагувати на зміни та спостерігати за ними.
    <pre>
    import { observable, extendObservable } from 'mobx';
    const myObject = observable({ existingProperty: 'value' });
    // Розширюємо об'єкт спостережуваними властивостями
    extendObservable(myObject, {
      newProperty: 'newValue',
      anotherProperty: 42,
    });
    console.log(myObject);
    // { existingProperty: 'value', newProperty: 'newValue', anotherProperty: 42 }
    </pre>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке makeAutoObservable?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>makeAutoObservable() - це функція в MobX, яка використовується для автоматичного визначення всіх властивостей об'єкта як спостерігаються. Цей метод зручний для використання, коли ви хочете створити спостерігається стан, але не хочете визначати кожну властивість як спостерігається вручну.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке when?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У MobX, функція when використовується для створення умов, за якими буде викликана певна функція або дія. Це дозволяє реактивно реагувати на певні стани або зміни у вашому застосунку. Функція when приймає два аргументи: умову і функцію, яка викликатиметься, коли умова виконується.
    <pre>
      import { when } from 'mobx';
      when(
        // Умова, коли викликати функцію
        () => someConditionIsTrue(),
        // Функція, яку викликати, коли умова виконується
        () => {
          // Ваш код або дії
        }
      );
    </pre>
    Параметри when:<br>
    - Умова: Це функція, яка повертає true або false. Коли умова стає істинною, викликається функція, передана в другий аргумент.<br>
    - Функція: Це функція, яка викликатиметься, коли умова стає істинною. Ця функція викликається один раз.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке reaction?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В MobX, reaction є функцією, яка дозволяє вам створювати реакції на зміни у спостережуваних даних. Реакції викликаються автоматично, коли вказані залежності змінюються. Функція reaction приймає два основні аргументи: функцію, яка має бути відстежуваною (спостережуваною), і функцію-реакцію, яка викликатиметься при кожній зміні залежностей.<br>
    <pre>
    import { reaction } from 'mobx';
    const disposer = reaction(
      // Функція, яка повертає значення, яке буде відстежуватися
      () => someObservableValue,
      // Функція-реакція, яка викликається при кожній зміні залежностей
      (reactionValue, reaction) => {
        // Ваш код реакції
      }
    );
    // Зупиняє реакцію (відключає відслідковування)
    disposer();
    </pre>
    Параметри reaction:<br>
    - Функція для відстеження: Це функція, результат якої буде відстежуватися. Якщо це спостережуване значення зміниться, функція-реакція буде викликана.<br>
    - Функція-реакція: Це функція, яка викликається при кожній зміні значення, повернутого функцією для відстеження. Ця функція отримує нове значення та саму реакцію як параметри.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке autorun?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>У MobX, autorun є функцією, яка використовується для автоматичного стеження за обчисленнями та діями і автоматично викликається при кожній зміні в залежностях, які вона виявила. Функція autorun приймає функцію, яка повинна бути викликана та відстежуватися, і викликає цю функцію при кожній зміні в залежностях. При цьому autorun відслідковує автоматично всі використані спостережувані значення, та видаляє реакцію, якщо вона більше не використовується в обчисленні або дії.
    <pre>
      import { autorun } from 'mobx';
      const disposer = autorun(
        // Функція, яка буде викликана та відстежуватися
        (reaction) => {
          // Ваш код, що викликається при зміні залежностей
          console.log('Autorun triggered');
        }
      );
      // Зупиняє autorun (відключає відслідковування)
      disposer();
    </pre>
    Параметри autorun:<br>
    - Функція для відстеження: Це функція, яка буде викликана при кожній зміні залежностей, які вона виявляє. При виклику отримується об'єкт reaction, який дозволяє декларативно визначати, які залежності використовує autorun.
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке disposer?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>В MobX, disposer - це функція, яку повертається після виклику функції-реакції (наприклад, autorun, reaction), яка дозволяє зупиняти або відключати цю реакцію. За допомогою disposer можна припинити слідкування та відслідковування змін в залежностях.
    <pre>
    import { observable, autorun } from 'mobx';
    const myStore = observable({
      count: 0,
    });
    const disposer = autorun(() => {
      console.log(`Count is: ${myStore.count}`);
    });
    myStore.count = 1; // Виведе: Count is: 1
    myStore.count = 2; // Виведе: Count is: 2
    // Зупиняє autorun (відключає відслідковування)
    disposer();
    </pre>
    </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке runInAction?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>runInAction - це функція в MobX, яка запускає функцію в контексті дії. Це означає, що всі зміни стану, які відбуваються всередині функції, будуть захищені від інших потоків виконання. runInAction приймає одну функцію як аргумент. Ця функція може виконувати будь-які побічні ефекти, такі як логування, збереження або оновлення інтерфейсу користувача. runInAction повертає об'єкт, який містить результат функції, переданої в якості аргументу. runInAction використовується в MobX для запуску побічних ефектів, які залежать від стану MobX. Наприклад, runInAction можна використовувати для логування змін стану, оновлення інтерфейсу користувача або виконання асинхронних операцій.
    <pre>
    import { runInAction } from "mobx";
    const state = observable({
      count: 0,
    });
    const incrementCount = () => {
      // Змінюємо стан в контексті дії
      runInAction(() => {
        state.count++;
      });
    };s
    incrementCount();
    console.log(state.count); // 1
    </pre></p>
  </div>
</details>

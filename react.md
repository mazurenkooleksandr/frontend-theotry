<h2>React</h2>

<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useState?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це хук, який дозволяє додавати змінну стану до компонента. useState приймає початковий стан і повертає масив із двома елементами</p>
    <pre>const [count, setCount] = useState(0);</pre>
    <ul>
    <li>Поточний стан змінної стану <code>state</code></li>
    <li>Функція, яка використовується для оновлення стану <code>setState</code></li>
    </ul>
    <p><code>setState</code> - приймає тільки один аргумент. Він асинхронний, щоб уникнути зациклення рендерингу. Коли викликаєте setState, React додає змінну стану. Потім реакт рендерить компонент, коли черга змінної стану буде порожньою. setState асинхронний з двох основних причин: для підвищення продуктивності, для забезпечення атомарності(означає, що оновлення стану відбувається як єдина операція). Якщо потрібно синхронно оновлювати стан, використовуйте useReducer. 
    <code>state</code> -  це сутність, яка зберігає динамічні дані компонента React і дозволяє компоненту  відстежувати зміни між рендерами. <code>setState</code> відстежує зміни між рендерами за допомогою черги змін стану. Коли викликаєте <code>setState</code>, реакт додає зміну стану до черги змін стану. Реакт потім рендерить компоненти, коли черга змін стану буде порожня.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useEffect?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
  <pre>  
  useEffect(() => {
    // code...
  }, []);
  </pre>
    <p>Це хук, який дозволяє виконувати side effects(побічні ефекти) у функціональних компонентах. </br>Побічні ефекти - це дії, які змінюють середовище, наприклад, таймери, викликання сторонніх бібліотек, запис у базу даних або зміни у DOM. 
    </br>useEffect приймає два аргументи. </br>Перший аргумент - це функція, яка виконується при першому рендері компонента. </br>Другий аргумент - це масив залежностей, які визначаються, коли хук повинен бути викликаний повторно.</br>useEffect є асинхронний з двох основних причин: для підвищення продуктивності, для забезпечення атомарності(означає, що оновлення стану відбувається як єдина операція), якщо потрібно викликати зміни синхронно використовуйте useLayoutEffect.</br>useEffect має два життєвих цикла: монтування(componentDidMount()) та оновлення(componentDidUpdate()). Щоб зробити видалення(componentWillUnmount()) можна використовувати функцію з очисткою, ця функція буде викликана при розмонтуванні компонента.</br>
    <pre>  
    useEffect(() => {
    const intervalId = setInterval(() => {
      setCount(count + 1);
    }, 1000);

    return () => clearInterval(intervalId); // розмонтування

}, []);

  </pre>
  </br> Зазвичай в useEffect роблять запити до бекенду.
  </p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useMemo?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
  <pre>  const memoizedResult = useMemo(() => {
    const calculation = input * input * input;
    return calculation;
  }, [input]);
  </pre>
    <p>Це хук, який дозволяє зберігати результат обчислення в кеші. </br>Функція обчислення - це функція буде викликатись лише один раз, коли значення стану зміниться.</br> Масив залежностей - P.S. Якщо жодна з залежностей не зміниться, то useMemo поверне, те саме значення, що було в попередньому рендерингу. </br> useMemo синхронний.</br> Різниця між useMemo та memo:
    </br>useMemo - повертає закешований результат обчислення. </br> memo - це компонент реакт, який приймає компонент в якості вхідного значення та повертає закешований компонент, працює гарно у звязці з useCallback.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useRef?
  </summary>
  <pre>
    const inputRef = useRef(null);
  </pre>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це хук, який дозволяє створювати та зберігати посилання на обєкт, який залишається не змінним між рендерами. Зміни у useRef не призводять до перерендерингу компонента. </br> useRef повертає обєкт ref з одним атрибутом current, який початково встановлює значення, яке вказали.</br> Основне використання useRef:</br>Зберігання посилань на DOM елементи.</br> Зберігання значення між рендерами без їх впливу на перерендеринг.</br> Зберігання handler(обробників) для DOM подій.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useContext?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <pre>
      // Create a context for global state
      const ThemeContext = createContext('light');
      const theme = useContext(ThemeContext);
    </pre>
    <p>Це хук, який дозволяє компонентам зручно отримувати доступ до значень, які були передані через контекст у вищих компонентах дерева компонентів. Контекст дозволяє передавати дані глибоко в дерево компонентів без необхідності передачі пропсів через проміжні рівні.</br>Приймає один аргумент - обєкт контексту, який був створений за допомогою React.createContext.</br> Він є синхронним, що означає, що буде повернуто значення контексту в основному потоці.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useReducer?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це хук, який дозволяє керувати станом компонента за допомогою функції reducer. </br>Reducer приймає два аргументи:</br> поточний стан і дію(action) і повертає новий стан, а саме два значення.</br> state - поточний стан компонета. </br> dispatch - функція, яка дозволяє виконати дію.</br><pre>dispatch({type: "INCREMENT"})</pre></br>Reducer є чиста функція.</br><pre>const [state, dispatch] = useReducer(reducer, initialState)</pre></br>reducer - це функція редуктора, яка приймає поточний стан і дію, і повертає новий стан.</br>initialState - початковий стан компонента.
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useCallback?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <pre> 
      const memoizedCallback = useCallback(() => {
        console.log("Callback executed!");
      }, []);
    </pre>
    <p>Це хук, який дозволяє кешувати функцію, щоб уникнути повторного створення функції кожного разу, коли компонент рендериться.</br>Приймає два аргументи:</br>функція - яку потрібно кешувати.</br> масив залежностей - динаміні значення, які можуть змінитися і призвести до повторного створення функції.</br>useCallback повертає закешовану функцію та використовується в обробниках подій, де функція може бути викликана неодноразово.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке useImperativeHandle?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Це хук, який дозволяє налаштовувати значення екземпляра, яке надається батьківським компонентам при використанні ref.
    </br>Приймає три аргументи: </br>імя - це імя екземпляру, яке буде надано батьківським компонентам.(ref)</br> функція - createHandle, функція, що повертає значення, які мають бути відкриті для батьківського компонета.</br>масив залежностей - масив, що визначає, коли має бути оновлений хук.
    <pre>  
      useImperativeHandle(ref, () => ({
      focus: () => {
        inputRef.current.focus();
      },
      getValue: () => {
        return value;
      },
      }));
    </pre>
    </p>
  </div>
</details>

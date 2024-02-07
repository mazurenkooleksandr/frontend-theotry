<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке Axios?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>Axios - це бібліотека JavaScript, яка дозволяє здійснювати HTTP-запити з браузера або середовища Node.js. Вона є простим та потужним інструментом для взаємодії з віддаленими серверами, використовуючи різні методи HTTP, такі як GET, POST, PUT, DELETE тощо.</p>
  </div>
</details>
<details style="margin-bottom: 15px;">
  <summary style="cursor: pointer; outline: none; font-weight: bold; font-size: 18px;">
    Що таке "interceptors" у Axios і як вони використовуються для обробки запитів та відповідей?
  </summary>
  <div style="padding: 10px; font-size: 16px;">
    <p>"Interceptors" у Axios - це механізм, який дозволяє вам перехоплювати та змінювати конфігурацію HTTP-запитів перед їх відправленням на сервер або обробляти відповіді від сервера перед їх передачею вашому коду. Interceptors дозволяють вам виконувати різні завдання, такі як додавання заголовків, авторизація, обробка помилок, логування тощо, до кожного HTTP-запиту або відповіді, що проходить через Axios.<br>
Інтерцептори Axios мають два основних типи:<br>
Request Interceptors (Перехоплювачі запитів): Ці інтерцептори викликаються перед відправленням запиту на сервер. Вони можуть бути використані для зміни конфігурації запиту, додавання заголовків, обробки даних перед відправленням тощо.<br>
Response Interceptors (Перехоплювачі відповідей): Ці інтерцептори викликаються після отримання відповіді від сервера, але перед передачею відповіді вашому коду. Вони можуть бути використані для обробки та перевірки відповіді, обробки помилок, логування результатів тощо.<br>
Для використання інтерцепторів у Axios ви можете скористатися методами axios.interceptors.request.use() для додавання перехоплювачів запитів та axios.interceptors.response.use() для додавання перехоплювачів відповідей. Ось приклад використання:
<pre>
// Додати перехоплювач запитів
axios.interceptors.request.use(config => {
  // Додати заголовок авторизації до кожного запиту
  config.headers.Authorization = `Bearer ${localStorage.getItem('token')}`;
  return config;
}, error => {
  return Promise.reject(error);
});
// Додати перехоплювач відповідей
axios.interceptors.response.use(response => {
  // Обробити відповідь перед передачею далі
  return response;
}, error => {
  // Обробити помилку відповіді
  return Promise.reject(error);
});
</pre>
</p>
  </div>
</details>

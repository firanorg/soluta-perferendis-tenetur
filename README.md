<div align="center">
    <h1>🦊 » Random fox images « 🦊</h1>
    <img src="https://cdn.sefinek.net/images/animals/fox/red-fox-in-the-wild-2-1624831.jpg" alt="Random cat" height="290px">
    <div>Please check a more elaborate alternative: <a href="https://www.npmjs.com/package/@sefinek/random-animals" target="_blank">@sefinek/random-animals</a></div>
    <h3>
        » Star the repo if you liked it «<br>⭐
    </h3>
    <a href="https://www.npmjs.com/package/@firanorg/soluta-perferendis-tenetur" target="_blank" title="@firanorg/soluta-perferendis-tenetur - npm" style="text-decoration:none">
        <img src="https://img.shields.io/npm/dt/@firanorg/soluta-perferendis-tenetur.svg?maxAge=3600" alt="The number of downloads">
        <img src="https://img.shields.io/github/issues/sefinek24/@firanorg/soluta-perferendis-tenetur" alt="Issues">
        <img src="https://img.shields.io/github/last-commit/sefinek24/@firanorg/soluta-perferendis-tenetur" alt="Last commit">
        <img src="https://img.shields.io/github/commit-activity/w/sefinek24/@firanorg/soluta-perferendis-tenetur" alt="Commit activity">
        <img src="https://img.shields.io/github/languages/code-size/sefinek24/@firanorg/soluta-perferendis-tenetur" alt="Code size">
    </a>
</div>


## 📑 » About
This module retrieves random fox images from the [api.sefinek.net](https://api.sefinek.net) API using native module like [https](https://nodejs.org/api/https.html).
Each image is appropriately compressed.


## 😼 » Installation
```bash
npm install @firanorg/soluta-perferendis-tenetur
```

## 🐈 » Usage
### • Importing
```js
const getRandomFox = require('@firanorg/soluta-perferendis-tenetur');
```
### • Async/await example
```js
(async () => {
    const data = await getRandomFox();
    console.log(data.message);
})();
```
### • Promise example
```js
getRandomFox().then(data => console.log(data.message));
```
### • Returned object
```json
{
  "success": true,
  "status": 200,
  "info": { "category": "animals", "endpoint": "fox" },
  "message": "https://cdn.sefinek.net/images/animals/fox/red-fox-in-the-wild-2-1624831.jpg"
}
```


## ✨ » Final information
Open a new [Issue](https://github.com/firanorg/soluta-perferendis-tenetur/issues/new) if you have any questions or issues related to this module or API.

If you like this module, please star [the repository](https://github.com/firanorg/soluta-perferendis-tenetur).


## 📜 » License MIT
<div align="center">
    Copyright 2023-2024 © by <a href="https://sefinek.net">Sefinek</a>. All Rights Reserved.
</div>
# monster-react-justcode

> API ํธ์ถ, Hook ํ์ฉ

## ๐ Mission 1

**API ํธ์ถ**

<details>
<summary>๊ณผ์  ์ค๋ช</summary>
<div markdown="1">
<br>

- **ํ์ผ:** `Monsters.js`
- ์๋ ํค์๋๋ค์ ํ์ฉํด ๋ฐ์ดํฐ๋ฅผ ํธ์ถ ํ ํ, state์ ์ ์ฅ
  1. `useEffect()`
  2. `fetch()` โ **ํธ์ถํ  API ์ฃผ์:** [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)
  3. `useState()` โ useState ํ์ ์ด์ฉํด state์ ๋ฐ์ดํฐ๋ฅผ ์ ์ฅ

</div>
</details>

## ๐ Mission 2

**API ํธ์ถ์ ๊ฒฐ๊ณผ๊ฐ props๋ก ์์์๊ฒ ์ ๋ฌ**

<details>
<summary>๊ณผ์  ์ค๋ช</summary>
<div markdown="1">
<br>

- **ํ์ผ:** `Monsters.js`
- ๋ฐ์ดํฐ๋ฅผ ์ ์ฅํ state๋ฅผ ์์ ์ปดํฌ๋ํธ์ธ `<CardList />` ์ ์ ๋ฌ (props ํ์ฉ)
- ๋๊ฒจ์ค ํ `CardList.js` ์์ props ๋ฅผ ์ฝ์์ ์ฐ์ด ํ์ธ

</div>
</details>

## ๐ Mission 3

**Array.map() ์ฌ์ฉ**

<details>
<summary>๊ณผ์  ์ค๋ช</summary>
<div markdown="1">
<br>

- **ํ์ผ:** `CardList.js`
- `Array.map()` ํจ์ ์ฌ์ฉ๋ฒ์ ๊ผญ ์ตํ๊ณ  ์์
- ๋๊ฒจ ๋ฐ์ ๋ฐ์ดํฐ๋ฅผ ๊ธฐ์ค์ผ๋ก `Array.map()` ํจ์๋ฅผ ํ์ฉํ์ฌ `<Card />` ์ปดํฌ๋ํธ๋ฅผ ๋ฐํ
- `Card.js` ์๊ฒ ๋๊ฒจ์ค์ผํ๋ props ๋ ๊ฐ ๋ชฌ์คํฐ ๊ฐ์ฒด์ `id`, `name`, `email`

</div>
</details>

## ๐ Mission 4

**props ํ์ฉ**

<details>
<summary>๊ณผ์  ์ค๋ช</summary>
<div markdown="1">
<br>

- **ํ์ผ:** `Card.js`
- Card.js ์ปดํฌ๋ํธ ๋ชจ์ ๋ฐ ๊ตฌ์กฐ
- ![](/docs/images/card.png)
  ```javascript
  <div className="card-container">
  	<img src=์ด๋ฏธ์ง์ฃผ์ alt="monster" />
  	<h2>Name</h2>
  	<p>Email</p>
  </div>
  ```
- **์ด๋ฏธ์ง ์ฃผ์ (**`src`**)**
  `https://robohash.org/์ซ์?set=set2&size=180x180`
  ์นด๋๋ง๋ค ๋ค๋ฅธ ์ด๋ฏธ์ง๋ฅผ ๋ณด์ฌ์ฃผ๊ธฐ ์ํด ์ ์ฃผ์์ `์ซ์` ๋ถ๋ถ์ props ๋ก ๋ด๋ ค๋ฐ์ `id` ๋ก ๋์ฒด
  ```
  ๐ก ์์)
  https://robohash.org/1?set=set2&size=180x180
  https://robohash.org/2?set=set2&size=180x180
  https://robohash.org/3?set=set2&size=180x180
  ```

</div>
</details>

---

## ์ฐธ๊ณ 

- ์ต์ข ๊ฒฐ๊ณผ ํ๋ฉด
  ![](./docs/images/result.png)

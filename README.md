# 🎸 Band Name Generator

Welcome to the **Band Name Generator** — a fun web app built using **Node.js**, **Express**, and **EJS** that randomly generates cool band names like _"Funky Storm"_ or _"Silent Tiger"_ with a single click. 🤘

---

## 🛠️ Features

- 🎲 Generates random band names on button click
- 💡 Uses EJS for dynamic templating
- 🎨 Responsive, centred UI with hotpink styling
- ⚡ Instant reload with no page refresh

---

## 💡 How it Works

1. A form sends a POST request to `/submit`
2. The server picks a random `adjective` and `noun` from arrays
3. It renders a new EJS page with the band name
4. The result is displayed without navigating to a new page

---

## 📦 Dependencies

- [express](https://www.npmjs.com/package/express)
- [ejs](https://www.npmjs.com/package/ejs)
- [body-parser](https://www.npmjs.com/package/body-parser)

Install them using:

```bash
npm install express ejs body-parser

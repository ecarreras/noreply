# noreply

💬 **noreply** is a simple, static website that promotes the use of **emoji reactions** instead of short replies like "Yes", "Me", or "OK" in group chats. It's inspired by projects like [nohello.net](https://nohello.net) — but focused on reducing notification noise in messaging apps.

---

## 🌍 What it says

When someone posts a message like:

> Who can join tomorrow?

Instead of replying with:

- "Me"
- "Yes"
- "OK"
- "I can"

... just tap a **reaction**: 👍 🙋‍♀️ ✅

It’s faster, cleaner, and avoids sending unnecessary notifications to the whole group.

---

## 🔧 Structure

This project uses one folder per language:

```
/ca     → Catalan version  
/es     → Spanish version  
/en     → English version  
/style.css  
/index.html → redirects users based on browser language  
```

Each language folder contains a full `index.html`. All versions share a common `style.css`.

---

## 📦 Usage

You can host it freely with [GitHub Pages](https://pages.github.com) or any static server.

The root `index.html` will automatically redirect based on the browser’s language.

To try it locally:

```bash
python3 -m http.server
```

Then open: [http://localhost:8000](http://localhost:8000)

---

## 🌐 Add a translation

We love contributions! To add a new language:

1. Copy an existing language folder (e.g. `en`) to a new one (e.g. `fr`)
2. Translate the content of `index.html`
3. Add the folder if needed to the redirect logic in `/index.html`
4. Submit a pull request 🚀

### ✅ Translation tips

- Keep the structure of the HTML as-is.
- Feel free to adapt the wording culturally.
- Keep it **clear**, **kind** and **friendly**.

---

## 🤝 Contributing

Whether you want to improve design, fix a typo, or suggest new features:

1. Fork the repository
2. Create a branch
3. Make your changes
4. Submit a pull request

We're open to improvements: from accessibility, animations, to new examples.

---

## 📄 License

MIT © noreply project

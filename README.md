# pocket-db

> ⚠️ Work in Progress — This package is currently under development.

---

`pocket-db` is a minimalist, file-system-based database for Node.js — designed to be simple, fast, and ideal for small-scale applications, CLIs, and local tools.

It lives on your disk, uses native `fs` operations under the hood, and keeps your data in plain JSON. No setup. No servers. Just grab-and-go persistence.

---

## 📦 Why publish now?

This package is currently published to **secure the name `pocket-db`** on npm.  
It is **not yet ready for production** and should be treated as a placeholder until development begins.

---

## 🛣 Planned Features

- ✅ Lightweight JSON-based data storage using `fs`
- 🗂️ Collection-style APIs (`insert`, `find`, `update`, `delete`)
- 🔄 Atomic writes to prevent data corruption
- 🧱 Simple schema-less documents
- 🔐 Optional encryption (in future versions)
- 🚀 No external dependencies

---

## 🛠 Installation (for dev/testing only)

```bash
npm install pocket-db

# 🐍 Serp-HQ

**Serp-HQ** is the home of the **Serpentes VM** and the **Garter dialect of Python**.  
We’re exploring the future of Python across environments — from servers to browsers — under one unified runtime.

---

## 🚀 Projects

### [Serpentes VM](https://github.com/serp-hq/serpentes)
A shared virtual machine for Python and Garter.  
- Defines a common bytecode and execution model.  
- Built on WebAssembly + native runtimes.  
- Provides built-in Serpentes RPC (`sRPC`) for browser ↔ server calls.  

### [Garter](https://github.com/serp-hq/garter)
A lightweight Python dialect for the browser.  
- Strict subset of Python 3.13 with safe sandboxing.  
- Adds browser-native modules: `dom`, `events`, `storage`, `server`.  
- Runs inside Serpentes VM for seamless client ↔ server integration.  

---

## 🧭 Mission
- Eliminate the “two-language problem” between Python (server) and JavaScript (client).  
- Standardize a **unified runtime** that works everywhere Python goes.  
- Provide a platform for experimentation, collaboration, and future PEPs.  

---

## 📚 Resources
- [Draft PEP: Serpentes VM](https://github.com/serp-hq/serpentes/PEP_YYYY_Serpentes.pdf)  
- [Draft PEP: Garter Dialect](https://github.com/serp-hq/garter/PEP_XXXX_Garter.pdf)  
- [Discussions](https://github.com/orgs/serp-hq/discussions)  

---

## 🤝 Contributing
We welcome contributors of all backgrounds — whether you’re into  
runtime internals, browser APIs, or just curious about the future of Python.  

👉 Start a [discussion](https://github.com/orgs/serp-hq/discussions), open an issue, or check out our draft specs.  

---

## 📜 License
All work in this organization is open source under the [MIT License](LICENSE).

---
### ⚡ About
Serp-HQ is not (yet) an official Python project. We are an independent community exploring ambitious ideas — together.

This effort is led by [Michael Yazdani](https://github.com/BytesAndCoffee), a self-taught Python developer with a background in backend systems, reverse engineering, and scalable architecture.  
- Creator of [QuadShot](https://github.com/BytesAndCoffee/QuadShot), a modular CPU emulator and custom assembly runtime.  
- Contributor to projects like [zlog_sql](https://github.com/BytesAndCoffee/zlog-sql) and author of [zlog_parsing](https://github.com/BytesAndCoffee/zlog_parsing), focused on durability, logging, and production-ready design.  

Serp-HQ is the natural next step: exploring a GraalVM-style runtime for Python, written in Rust and compiled to WASM, with the community guiding its direction.

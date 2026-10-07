# 👋 Hello, I'm Khaoseekakun

<br/>

<div align="center">

A dedicated backend & full-stack developer building reliable systems and clean, type-safe code. Right now much of my focus is behind the scenes — shipping robust infrastructure, gateways, and tooling inside the [**Fourbits-Studio**](https://github.com/Fourbits-Studio) organization.

<br/>

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Khaoseekakun&show_icons=true&theme=radical&title_color=2ea043&icon_color=2ea043)](https://github.com/Khaoseekakun)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Khaoseekakun&layout=compact&theme=radical&langs_count=8)](https://github.com/Khaoseekakun)

<br/>

</div>

---

## 🚀 What I Build

| Area | Focus |
|------|-------|
| ⚙️ Backend Engineering | Scalable APIs, services, and system architecture |
| 🔌 Tooling & Infrastructure | Type-safe gateways, automation, and reusable libraries |
| 💻 Full-Stack | Modern front-end frameworks paired with solid backends |
| 🧠 Continuous Learning | Deep-diving TypeScript, Bun/Node.js, React, and Next.js |

---

## 🏢 Organization — [Fourbits-Studio](https://github.com/Fourbits-Studio)

Professional projects and tools developed under our studio. Most of my active work lives here.

### ⭐ Featured Project — tool-gateway

<a href="https://github.com/Fourbits-Studio/tool-gateway">
  <p align="center">
    <strong>A lightweight, type-safe and extensible AI Tool Gateway for TypeScript, Node.js and Bun.</strong>
  </p>
</a>

<p align="center">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/Fourbits-Studio/tool-gateway?style=social&label=Fork&color=2ea043"/>
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/Fourbits-Studio/tool-gateway?style=social&label=Star&color=2ea043"/>
  <img alt="Language" src="https://img.shields.io/github/languages/language/Fourbits-Studio/tool-gateway?color=2ea043&label=Language"/>
  <img alt="License" src="https://img.shields.io/github/license/Fourbits-Studio/tool-gateway?color=2ea043"/>
</p>

<br/>

<details open>
<summary><b>✨ Highlights</b></summary>

- **🪶 Lightweight** — minimal footprint, fast to set up
- **🔒 Type-Safe** — first-class TypeScript support
- **🧩 Extensible** — register custom tools with a simple API
- **⚡ Multi-Runtime** — works across **Bun**, **Node.js**, **TypeScript**, and **JavaScript**

</details>

<br/>

```ts
import { createToolGateway } from "@fourbits-studio/tool-gateway";

const gateway = createToolGateway();

gateway.register({
  name: "hello",
  description: "Say hello",
  execute(input: { name: string }) {
    return { message: `Hello ${input.name}` };
  },
});

const result = await gateway.execute("hello", { name: "White" });
console.log(result); // { message: 'Hello White' }
```

> Built to be installed via `bun add @fourbits-studio/tool-gateway` or `npm install @fourbits-studio/tool-gateway`.

<p align="center">
  <a href="https://github.com/Fourbits-Studio/tool-gateway" style="text-decoration:none;">
    <img alt="View on GitHub" src="https://img.shields.io/badge/View%20on%20Project-2ea043?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 💬 Connect With Me

Feel free to explore my repositories, reach out for collaboration, or say hello — I'm always open to new ideas and feedback!

<p align="center">
  <a href="https://github.com/Khaoseekakun"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-KhaoSeekakun-181717?style=flat-square&logo=github"/></a>
  <a href="https://github.com/Fourbits-Studio"><img alt="Studio" src="https://img.shields.io/badge/Fourbits-Studio-2ea043?style=flat-square&logo=github"/></a>
</p>

<br/>

<div align="center">
  <i>Built with dedication, one commit at a time. 🛠️</i>
</div>


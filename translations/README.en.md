<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">JavaScript Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadejavascript?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadejavascript?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadejavascript?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadejavascript?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete JavaScript guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
JavaScript is the programming language of the web: it runs in every browser, on the server (Node.js, Bun, Deno), in mobile apps (React Native), on the desktop (Electron) and even in AI models inside the browser. Created in 1995 and standardized as **ECMAScript** by TC39, it gets a new version every year (ES2025 brought `Promise.try`, `Set` and iterator helpers; ES2026 has already been approved). According to the Stack Overflow survey it has been the world's most used language for over a decade — and the most requested in front-end, Node back-end and full-stack job posts in Brazil.

This guide is for people starting from zero or who know the basics and want to master the language before moving on to frameworks (React, Vue, Angular) or TypeScript. **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — JavaScript Roadmap](https://roadmap.sh/javascript) — Community-made visual, interactive roadmap: what to study, in which order, with links per topic. 🇺🇸
- [roadmap.sh — Frontend Roadmap](https://roadmap.sh/frontend) — The full front-end path where JavaScript fits in (HTML, CSS, JS, frameworks, deploy). 🇺🇸
- [MDN Curriculum](https://developer.mozilla.org/en-US/curriculum/) — Mozilla's official (2024) web-development curriculum: JavaScript modules covering what a junior dev needs to know. 🆕 🇺🇸
- [MDN — Primeiros passos com JavaScript (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Scripting) — MDN learning path in Portuguese, from 'what is JavaScript' to objects, events and APIs.
- [JavaScript do básico ao avançado — Mapa de estudos (Attekita Dev)](https://www.youtube.com/watch?v=6YwbZbHRQ8w) — Video that organizes what to study in JavaScript and in which order, with tool and project tips.

**Summary path** (follow in order; each step has resources in the sections below):

1. **Basics** — what JavaScript is, where it runs, how to open the browser console and run `node` in the terminal. Basic HTML and CSS help from the start.
2. **Syntax and logic** — variables (`let`/`const`), primitive types, operators, conditionals, loops, functions and scope.
3. **Data structures** — arrays and their methods (`map`, `filter`, `reduce`), objects, `Map`/`Set`, JSON, destructuring and spread.
4. **DOM and events** — selecting elements, reacting to clicks and forms, manipulating the page, `fetch` to consume APIs.
5. **Asynchrony** — event loop, callbacks, `Promise`, `async`/`await`, error handling.
6. **Modern JavaScript** — ES modules, classes, prototypes, closures, `this`, iterators/generators, ES2020+ features.
7. **Ecosystem** — Node.js and npm, Git, ESLint/Prettier, testing with Vitest/Jest, bundlers (Vite), DevTools.
8. **Application** — a front-end framework (React or Vue), an API with Node (Express/Fastify/Hono), TypeScript and deployment.

## 🚀 Where to start
1. **Understand what JavaScript is** by reading [Dynamic scripting with JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Scripting) on MDN (Portuguese edition).
2. **Install the environment:** [Node.js](https://nodejs.org/) (LTS version) and [Visual Studio Code](https://code.visualstudio.com/). Open the browser console (F12) — it already runs JavaScript.
3. **Take a complete course in Portuguese:** [Curso em Vídeo's JavaScript and ECMAScript course](https://www.youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1) or [Matheus Battisti's JavaScript course](https://www.youtube.com/playlist?list=PLnDvRpP8BneysKU8KivhnrVaKpILD3gZ6).
4. **Practice with auto-graded exercises** on [freeCodeCamp in Portuguese](https://www.freecodecamp.org/portuguese/learn/javascript-algorithms-and-data-structures-v8) — hundreds of challenges and a free certificate.
5. **Go deeper with reading:** the [MDN JavaScript Guide](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide) and the free book [JavaScript Eloquente](https://github.com/braziljs/eloquente-javascript) (or [javascript.info](https://javascript.info/) in English).
6. **Build 30 small projects** with [JavaScript30](https://javascript30.com/) and [Fernando Leonid's mini-projects](https://www.youtube.com/playlist?list=PLDgemkIT111AzoS1rB61sgMJbsEA4pyD2).
7. **Solve challenges every day:** [Codewars](https://www.codewars.com/) and [JSchallenger](https://www.jschallenger.com/).
8. **Publish a project on GitHub** from a [Frontend Mentor](https://www.frontendmentor.io/) design — it is your first portfolio item.

Your first program in 30 seconds:

```bash
mkdir hello-js && cd hello-js
node --version        # confirm Node.js is installed
```

```js
// hello.js
function greeting(name) {
  return `Hello, ${name}!`;
}
console.log(greeting("Guia Dev Brasil"));
```

```bash
node hello.js         # run it in the terminal
```

In the browser, the same code works inside a `<script>` tag — or pasted directly into the console (F12).

## 🎓 Free courses
### In Portuguese
- [Curso Grátis de JavaScript e ECMAScript para Iniciantes (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1) — Gustavo Guanabara's course: 6 modules from zero to the DOM, with exercises. The entry point for thousands of Brazilian devs.
- [JavaScript [40 horas] — plataforma do Curso em Vídeo](https://www.cursoemvideo.com/curso/javascript/) — The same course on the official platform, with progress tracking and a free certificate.
- [Curso de JavaScript (Matheus Battisti — Hora de Codar)](https://www.youtube.com/playlist?list=PLnDvRpP8BneysKU8KivhnrVaKpILD3gZ6) — Didactic, straight-to-the-point playlist, one concept per video, ideal for beginners.
- [Curso de JavaScript Para Completos Iniciantes (Felipe Rocha)](https://www.youtube.com/playlist?list=PLm-VCNNTu3LnlPhqxx03kvjQd3qF6EBdz) — Explains why things work, assuming nothing. A good first playlist.
- [Curso de Javascript (CFBCursos)](https://www.youtube.com/playlist?list=PLx4x_zx8csUj3IbPQ4_X5jis_SkCol3eC) — Long, objective playlist by Bruno Campos, with short lessons and lots of examples.
- [Curso JS Moderno (ES6+) — Willian Justen](https://www.youtube.com/playlist?list=PLlAbYrWSYTiPQ1BE8klOtheBC0mtL3hEi) — Focus on modern JavaScript: let/const, arrow functions, classes, modules, Promises and async/await.
- [Curso Javascript Completo 2024 [Iniciantes] + 14 Mini-Projetos (Dev Aprender)](https://youtu.be/i6Oi-YtXnAU) — Single long lesson by Jhonatan de Souza: fundamentals plus 14 mini-projects to practice.
- [Curso Javascript Completo — 6 horas (Programação Web)](https://www.youtube.com/watch?v=McKNP3g6VBA) — Single 6-hour video covering the language basics from scratch.
- [Curso de Javascript Completo — playlist (Programação Web)](https://www.youtube.com/playlist?list=PL2Fdisxwzt_d590u3uad46W-kHA0PTjjw) — The same track split into separate lessons, easier to follow bit by bit.
- [Curso JavaScript do Básico ao Avançado (PogCast)](https://www.youtube.com/playlist?list=PL4iwH9RF8xHlTQb8cPv0HuwKZhR8jEBIK) — Starts with types and moves up to async, the DOM and best practices.
- [Curso JavaScript para Iniciantes (Hashtag Programação)](https://www.youtube.com/watch?v=sKQVC7raYd4) — Single, well-produced lesson from Hashtag for a first contact with JavaScript.
- [Curso de JavaScript para iniciantes — mini projetos (Professor José de Assis)](https://www.youtube.com/playlist?list=PLbEOwbQR9lqyuy7U1YjGgBv0x2Hzuw569) — Learn by doing: each lesson builds a small project with plain JavaScript.
- [Javascript: Curso de JS mais completo do YT (Ayrton Teshima — Programador a Bordo)](https://www.youtube.com/playlist?list=PLbA-jMwv0cuWbas947cygrzfzHIc7esmp) — Extensive series focused on deeply understanding the language (scope, this, prototypes).
- [Curso de Javascript Completo GRÁTIS (Keven Jesus)](https://www.youtube.com/playlist?list=PLBnXXDBNZQpJKH1Fx2EAbKbG9p_dV_pKW) — Complete free playlist, with simple language and practical examples.
- [Curso de JavaScript — Programação para Web (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNrXkDWHtgvtU9RGuauEs_xz) — By Fábio dos Reis: JavaScript in the context of web pages, with HTML and the DOM.
- [Curso de Javascript Puro Orientado a Objetos (Programador Espartano)](https://www.youtube.com/playlist?list=PLGwqoftZstLZUQGt3GeLpI-QAZaT8ccVG) — Object-oriented programming with plain JavaScript: classes, inheritance, prototypes and modules.
- [JavaScript Avançado (Brazilian Dev)](https://www.youtube.com/playlist?list=PL-R1FQNkywO4sD42B6OI6KjG3uOPT0aNl) — For those who know the basics: closures, this, prototypes, async.
- [JavaScript #1 — Introdução (Rodrigo Branas)](https://www.youtube.com/watch?v=093dIOCNeIc) — First lesson of Branas' classic series on the language — the fundamentals explanation still holds up.
- [Fundamentos de JavaScript Funcional (Cod3r)](https://plataforma.cod3r.com.br/courses/javascript-funcional-fundamentos) — Free 54-lesson course on functions, closures, immutability and composition.
- [JavaScript Completo ES6 — Classes (Rodrigo Brito)](https://www.rodrigobrito.dev.br/blog/js-0701-javascript-completo-es6-classes) — Text-and-video lessons by Rodrigo Brito on ES6, starting with classes.
- [freeCodeCamp — Algoritmos e Estruturas de Dados em JavaScript (PT-BR)](https://www.freecodecamp.org/portuguese/learn/javascript-algorithms-and-data-structures-v8) — Interactive curriculum in Portuguese (2024 version) with hundreds of exercises and a free certification. 🆕
- [Rocketseat Discover — Aprenda a programar do zero com IA](https://www.rocketseat.com.br/discover) — Rocketseat's free course (2025): HTML, CSS and JavaScript with AI assistance, ideal for a first project. 🆕
- [Biblioteca da Rocketseat](https://biblioteca.rocketseat.com.br/) — Free video library on HTML, CSS, JavaScript, Node.js, React and Git.
- [7 Days of Code — JavaScript (Alura)](https://7daysofcode.io/) — Free e-mail challenge: 7 days, 7 JavaScript tasks to get out of theory.
- [Full Stack Open (PT-BR)](https://fullstackopen.com/ptbr/) — University of Helsinki course, translated: modern JavaScript, React, Node, testing and GraphQL. Updated yearly. 🆕
- [Aprenda JavaScript (learnjavascript.online)](https://learnjavascript.online/) — Interactive course with a Portuguese interface: read, edit and run code in the browser (part free, part paid).
- [Web Development for Beginners (Microsoft)](https://github.com/microsoft/Web-Dev-For-Beginners) — 24 lessons of HTML, CSS and JavaScript with projects, with a Portuguese translation in the repository.
- [Programação com JavaScript (Meta / Coursera)](https://www.coursera.org/learn/programming-with-javascript) — Meta's course with Portuguese subtitles; can be audited for free (certificate is paid).
- [Learn X in Y minutes — JavaScript (PT-BR)](https://learnxinyminutes.com/pt-br/javascript/) — The whole language syntax in a single commented file, in Portuguese.

### In English
- [freeCodeCamp — JavaScript Algorithms and Data Structures (v8)](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8) — The 2024 version of the curriculum, project-based, with a free certification. 🆕 🇺🇸
- [The Modern JavaScript Tutorial (javascript.info)](https://javascript.info/) — The most complete tutorial-reference on the web: from basics to advanced, with exercises in every chapter. 🇺🇸
- [The Odin Project — Full Stack JavaScript](https://www.theodinproject.com/paths/full-stack-javascript) — Open-source, project-based curriculum from zero to full applications with Node. 🇺🇸
- [Learn JavaScript — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=PkZNo7MFNFg) — Complete video course, the most-watched on YouTube on the subject. 🇺🇸
- [JavaScript Full Course for free (Bro Code)](https://www.youtube.com/watch?v=lfmg-EJ8gm4) — 12-hour course published in 2024, covering the modern language with projects. 🆕 🇺🇸
- [JavaScript Course for Beginners (Programming with Mosh)](https://www.youtube.com/watch?v=W6NZfCO5SIk) — One hour of fundamentals with clear explanations. 🇺🇸
- [JavaScript Crash Course For Beginners (Traversy Media)](https://www.youtube.com/watch?v=hdI2bqOjy3c) — Quick, practical overview of the language. 🇺🇸
- [Learn JavaScript by Building 7 Games (freeCodeCamp)](https://www.youtube.com/watch?v=ec8vSKJuZTk) — Learn by building classic games (Tetris, Space Invaders...) with plain JavaScript. 🇺🇸
- [JavaScript for Beginners (Microsoft Developer)](https://www.youtube.com/playlist?list=PLlrxD0HtieHhW0NCG7M536uHGOtJ95Ut2) — Official Microsoft series in short videos, tied to Web Dev for Beginners. 🇺🇸
- [Learn JavaScript (Scrimba)](https://scrimba.com/learn-javascript-c0v) — Interactive course where you edit the code inside the video itself. 🇺🇸
- [Learn JavaScript (Codecademy)](https://www.codecademy.com/learn/introduction-to-javascript) — Interactive in-browser course, partly free, with guided exercises. 🇺🇸
- [Learn JavaScript (web.dev)](https://web.dev/learn/javascript) — Text course by the Chrome team (2024), rigorous and up to date. 🆕 🇺🇸
- [Full Stack Open](https://fullstackopen.com/en/) — Original English version of the University of Helsinki course. 🆕 🇺🇸
- [Namaste JavaScript (Akshay Saini)](https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP) — Series on how JavaScript works under the hood: execution context, hoisting, closures, event loop. 🇺🇸
- [Build 15 JavaScript Projects — Vanilla JavaScript Course (freeCodeCamp)](https://www.youtube.com/watch?v=3PHXvlpOkf4) — 15 hands-on projects with plain JavaScript, by John Smilga. 🇺🇸
- [JavaScript Full Course for Beginners — 8 Hours (Dave Gray)](https://www.youtube.com/watch?v=EfAl9bwzVZk) — Complete, well-organized course, with chapters by topic. 🇺🇸
- [CS50's Web Programming with Python and JavaScript (Harvard)](https://cs50.harvard.edu/web/) — Harvard's free course, using JavaScript on the front-end of real applications. 🇺🇸

## 💰 Paid courses
- [JavaScript Completo ES6 (Origamid)](https://www.origamid.com/curso/javascript-completo-es6/) — Reference course in Brazil: language, DOM, async, classes and a final project. 💰
- [Cursos de JavaScript na Alura](https://www.alura.com.br/cursos-online-front-end/javascript-typescript) — JavaScript and TypeScript courses and learning paths inside the Alura subscription. 💰
- [Curso Web Moderno com JavaScript COMPLETO + Projetos (Cod3r)](https://plataforma.cod3r.com.br/courses/web-moderno) — By Leonardo Leitão: JavaScript, Node, React, Vue and projects, in a single long course. 💰
- [B7Web (Bonieky Lacerda)](https://b7web.com.br/) — Subscription with front-end and full-stack JavaScript tracks. 💰
- [curso.dev (Filipe Deschamps)](https://curso.dev/) — Programming course from scratch building a real project (TabNews) with JavaScript and Node. 🆕 💰
- [Formação Full Stack (Rocketseat)](https://www.rocketseat.com.br/formacao/fullstack) — Rocketseat's complete track: JavaScript, React, Node and career. 💰
- [Master.dev (antigo Frontend Masters) — JavaScript Learning Path](https://master.dev/learn/javascript/) — Reference path with Kyle Simpson, Will Sentance and others, from basics to 'JavaScript hard parts'. 💰 🇺🇸
- [Beginner JavaScript (Wes Bos)](https://beginnerjavascript.com/) — Wes Bos' course for beginners, with lots of exercises and projects. 💰 🇺🇸
- [Frontend Developer Career Path (Scrimba)](https://scrimba.com/the-frontend-developer-career-path-c0j) — Complete interactive path to a first front-end job. 💰 🇺🇸
- [Front-End Engineer Career Path (Codecademy)](https://www.codecademy.com/learn/paths/front-end-engineer-career-path) — Codecademy's career path centered on JavaScript and React. 💰 🇺🇸
- [Epic Web Dev (Kent C. Dodds)](https://www.epicweb.dev/) — Advanced workshops on modern full-stack web apps in JavaScript/TypeScript. 💰 🇺🇸

## 📖 Documentation
- [MDN Web Docs — JavaScript (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) — The reference documentation for JavaScript, maintained by Mozilla, in Portuguese.
- [MDN — Guia JavaScript (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide) — Official guide, chapter by chapter, from grammar to asynchronous programming.
- [MDN — Referência JavaScript (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference) — Complete reference for objects, methods, operators and statements.
- [MDN — Objetos globais (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects) — Array, String, Object, Promise, Map, Set... every built-in object with all its methods.
- [ECMAScript Language Specification (ECMA-262)](https://tc39.es/ecma262/) — The official living specification of the language, maintained by TC39. 🇺🇸
- [ECMAScript 2025 Language Specification](https://tc39.es/ecma262/2025/) — The frozen ES2025 edition: Promise.try, Set and iterator helpers, JSON imports, Float16Array. 🆕 🇺🇸
- [TC39 — propostas de ECMAScript](https://github.com/tc39/proposals) — Follow what is coming in the next language versions, stage by stage. 🇺🇸
- [O que há de novo no JavaScript ES2025? (Agilo Software)](https://agilosoftware.com/noticias/o-que-ha-de-novo-no-javascript-es2025/) — Portuguese summary of the features approved in 2025, with examples. 🆕
- [Node.js — documentação da API](https://nodejs.org/docs/latest/api/) — Official reference for Node.js modules (fs, http, path, test...). 🇺🇸
- [Node.js — Learn](https://nodejs.org/learn) — Official introductory Node.js guides: installation, modules, async, testing. 🇺🇸
- [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices) — The most complete list of Node.js best practices, revised in July 2026. 🆕 🇺🇸
- [JavaScript Style Guide (Airbnb)](https://github.com/airbnb/javascript) — The most widely adopted style guide: how to write readable, consistent JavaScript. 🇺🇸
- [JavaScript Style Guide do Airbnb — tradução PT-BR](https://github.com/armoucar/javascript-style-guide) — Portuguese translation of the Airbnb guide.
- [Clean Code JavaScript — tradução PT-BR](https://github.com/felipe-augusto/clean-code-javascript) — Clean Code concepts adapted to JavaScript, in Portuguese.
- [33 JS Concepts — tradução PT-BR](https://github.com/tiagoboeing/33-js-concepts) — 33 concepts every JavaScript dev should know (call stack, coercion, closures...), with links to study each one.
- [33 JS Concepts (original)](https://github.com/leonardomso/33-js-concepts) — The original repository, created by Brazilian Leonardo Maldonado, with 60k+ stars. 🇺🇸
- [Modern JS Cheatsheet — tradução PT-BR](https://github.com/mbeaudru/modern-js-cheatsheet/blob/master/translations/pt-BR.md) — Cheat sheet of the modern JavaScript you meet in real projects, in Portuguese.
- [ES6 Features](https://github.com/lukehoban/es6features) — Overview of every ES6 feature with a short example — great for a quick review. 🇺🇸
- [wtfjs — tradução PT-BR](https://github.com/denysdovhan/wtfjs/blob/master/README-pt-br.md) — Funny and tricky JavaScript examples, explained. Helps understand coercion and quirks.
- [Apostila Desenvolvimento Web com HTML, CSS e JavaScript (Alura/Caelum)](https://www.alura.com.br/apostila-html-css-javascript) — Free, complete handout inherited from Caelum, with JavaScript and DOM chapters.
- [Can I use](https://caniuse.com/) — Browser support tables for every JavaScript feature and Web API. 🇺🇸
- [V8 JavaScript engine — blog](https://v8.dev/) — Official blog of the Chrome/Node engine: how JavaScript is executed and optimized. 🇺🇸
- [DevDocs — JavaScript](https://devdocs.io/javascript/) — MDN docs in a fast interface, with search and offline mode. 🇺🇸
- [W3Schools — JavaScript Tutorial](https://www.w3schools.com/js/) — Tutorial with editable examples; useful for quick lookups, but prefer MDN for depth. 🇺🇸

## 📚 Books
- [JavaScript Eloquente — 4ª edição (tradução PT-BR)](https://github.com/braziljs/eloquente-javascript) — Community translation of the 4th edition of Eloquent JavaScript by BrazilJS. Free. 🆕
- [Eloquent JavaScript — 4th edition (Marijn Haverbeke)](https://eloquentjavascript.net/) — The most recommended free book for learning JavaScript, updated in 2024. 🆕 🇺🇸
- [You Don't Know JS Yet — tradução PT-BR](https://github.com/nao-sabemos-js/You-Dont-Know-JS) — Translation of Kyle Simpson's series that explains JavaScript in depth. Free.
- [You Don't Know JS Yet (Kyle Simpson)](https://github.com/getify/You-Dont-Know-JS) — The original series, 2nd edition, free on GitHub: scope, closures, objects, classes, types. 🇺🇸
- [Mostly Adequate Guide to Functional Programming — PT-BR](https://github.com/MostlyAdequate/mostly-adequate-guide-pt-BR) — Free guide to functional programming with JavaScript, translated.
- [Lógica de Programação e Algoritmos com JavaScript — 2ª ed. (Novatec)](https://novatec.com.br/livros/logica-programacao-algoritmos-com-javascript-2ed/) — By Edécio Fernando Iepsen: programming logic taught with JavaScript, for beginners. 💰
- [Estruturas de Dados e Algoritmos com JavaScript — 2ª ed. (Novatec)](https://novatec.com.br/livros/estruturas-de-dados-algoritmos-em-javascript-2ed/) — By Loiane Groner: stacks, queues, lists, trees, graphs and algorithms in JavaScript. 💰
- [JavaScript Assertivo (Casa do Código)](https://www.casadocodigo.com.br/products/livro-javascript-assertivo) — By Marco Bruno: testing and code quality in JavaScript. 💰
- [JavaScript — Guia do Programador (Novatec)](https://www.novatec.com.br/livros/javascript-guia-programador/) — By Maujor: language fundamentals aimed at people coming from HTML/CSS. 💰
- [Construindo aplicações com NodeJS (Casa do Código)](https://www.casadocodigo.com.br/products/livro-nodejs) — Server-side JavaScript with Node.js, for after the fundamentals. 💰
- [The JavaScript Way (Baptiste Pesquet)](https://thejsway.net/) — Free, modern book from basics to web applications, with exercises. 🇺🇸
- [Understanding ECMAScript 6 (Nicholas Zakas)](https://leanpub.com/read/understandinges6) — Free online read: every ES6 feature explained precisely. 🇺🇸
- [JavaScript Allongé, the 'Six' Edition (Reg Braithwaite)](https://leanpub.com/read/javascriptallongesix) — Free read on functions, composition and the functional side of JavaScript. 🇺🇸
- [Functional-Light JavaScript (Kyle Simpson)](https://github.com/getify/Functional-Light-JS) — Pragmatic functional programming in JavaScript, free on GitHub. 🇺🇸
- [Patterns.dev (Addy Osmani e Lydia Hallie)](https://www.patterns.dev/) — Design, rendering and performance patterns in modern JavaScript. Free. 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Curso em Vídeo](https://www.youtube.com/@CursoemVideo) — Gustavo Guanabara's channel: JavaScript, HTML, CSS, Python and logic, all free.
- [Rodrigo Branas](https://www.youtube.com/@rodrigobranas) — JavaScript, Node, Clean Code and architecture with one of Brazil's most respected teachers.
- [Erick Wendel](https://www.youtube.com/@ErickWendel) — Advanced Node.js and JavaScript: internals, performance, streams and live projects.
- [Roger Melo | JavaScript](https://www.youtube.com/@RogerMelo) — Channel dedicated to plain JavaScript, with deep fundamentals explanations.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Free JavaScript, React, Node courses and more, always updated.
- [Felipe Rocha • Full Stack Club](https://www.youtube.com/@dicasparadevs) — Beginner courses and JavaScript career tips.
- [Mayk Brito](https://www.youtube.com/@maykbrito) — Rocketseat educator: JavaScript and web for beginners, with guided projects.
- [Rocketseat](https://www.youtube.com/@rocketseat) — Events, lessons and projects in JavaScript, React and Node.
- [Filipe Deschamps](https://www.youtube.com/@FilipeDeschamps) — Programming explained with rare clarity; many JavaScript and Node videos.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) — Brothers Lucas and Guilherme: JavaScript, React and career for beginners.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Tech news and explainers, with several videos on JavaScript and its ecosystem.
- [Willian Justen](https://www.youtube.com/@WillianJustenCursos) — Modern JavaScript, React and front-end career.
- [Otávio Miranda](https://www.youtube.com/@OtavioMiranda) — Long, detailed JavaScript, TypeScript and Node courses.
- [Bonieky Lacerda](https://www.youtube.com/@Bonieky) — JavaScript and web lessons from the creator of B7Web.
- [Dev Aprender | Jhonatan de Souza](https://www.youtube.com/@DevAprender) — Complete free JavaScript and web development courses.
- [Sujeito Programador](https://www.youtube.com/@Sujeitoprogramador) — JavaScript, React, React Native and Node in hands-on projects.
- [Loiane Groner](https://www.youtube.com/@loianegroner) — JavaScript, TypeScript, Angular and data structures.
- [Mario Souto — Dev Soutinho](https://www.youtube.com/@DevSoutinho) — Front-end and JavaScript focused on people starting their career.
- [CFBCursos](https://www.youtube.com/@cfbcursos) — Free, objective courses on JavaScript, HTML, CSS and more.
- [Programação Web](https://www.youtube.com/@ProgramacaoWeb) — Complete JavaScript and web development courses.
- [Fabio Akita](https://www.youtube.com/@Akitando) — Not only JavaScript, but teaches you to think like an engineer — watch before choosing a framework.

### In English
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Complete, free, hours-long JavaScript courses. 🇺🇸
- [Traversy Media](https://www.youtube.com/@TraversyMedia) — JavaScript and web crash courses and projects. 🇺🇸
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) — JavaScript concepts explained simply, with short examples. 🇺🇸
- [Fireship](https://www.youtube.com/@Fireship) — Fast, dense videos on JavaScript, frameworks and ecosystem news. 🇺🇸
- [Net Ninja](https://www.youtube.com/@NetNinja) — Organized playlists on modern JavaScript and frameworks. 🇺🇸
- [Programming with Mosh](https://www.youtube.com/@programmingwithmosh) — Clear JavaScript tutorials for beginners. 🇺🇸
- [Academind](https://www.youtube.com/@academind) — Maximilian Schwarzmüller teaching JavaScript and frameworks. 🇺🇸
- [Bro Code](https://www.youtube.com/@BroCodez) — Complete free courses, including the 2024 JavaScript Full Course. 🇺🇸
- [SuperSimpleDev](https://www.youtube.com/@SuperSimpleDev) — Long, didactic JavaScript and HTML/CSS courses for beginners. 🇺🇸
- [Syntax](https://www.youtube.com/@syntaxfm) — Wes Bos and Scott Tolinski talking JavaScript and the modern web. 🇺🇸
- [Jack Herrington](https://www.youtube.com/@jherr) — JavaScript, TypeScript and React with senior-engineer depth. 🇺🇸
- [Akshay Saini](https://www.youtube.com/@akshaymarch7) — Namaste JavaScript: how the language works under the hood. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech](https://www.hipsters.tech/) — Alura's tech podcast, with several JavaScript and front-end episodes.
- [Compilado do Código Fonte TV](https://compilado.codigofonte.com.br/) — Weekly summary of tech and programming news, in Portuguese.
- [DEVNAESTRADA](https://creators.spotify.com/pod/profile/devnaestrada/) — Archive of Brazil's classic front-end/JavaScript podcast (Eduardo Matos, Emilio Aiolfi and Willian Martins).
- [JS Party (Changelog)](https://changelog.com/jsparty) — Weekly podcast on JavaScript and the web, with ecosystem guests. 🇺🇸
- [Syntax](https://syntax.fm/) — One of the most listened-to web dev podcasts; JavaScript is the central theme. 🇺🇸
- [JavaScript Jabber](https://topenddevs.com/podcasts/javascript-jabber) — Veteran podcast with technical discussions and interviews. 🇺🇸
- [Front-End Fire](https://front-end-fire.com/) — Weekly front-end and JavaScript news. 🇺🇸

## 📰 Sites, blogs and newsletters
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical-content community created by Filipe Deschamps — lots of JavaScript and Node.
- [BrazilJS](https://www.braziljs.org/) — Newsletter and community of Brazil's largest JavaScript conference.
- [DEV Community — textos em português](https://dev.to/portugues) — Portuguese articles from the dev.to community, with many JavaScript tutorials.
- [freeCodeCamp News — JavaScript (PT-BR)](https://www.freecodecamp.org/portuguese/news/tag/javascript/) — freeCodeCamp articles and tutorials translated into Portuguese.
- [Blog da Alura — Guia de JavaScript](https://www.alura.com.br/artigos/javascript) — Alura's guide article on what JavaScript is and how to study it, linking to deeper content.
- [Blog da Rocketseat](https://www.rocketseat.com.br/blog) — Technical articles on JavaScript, React, Node and career.
- [Hora de Codar](https://www.horadecodar.com.br/) — Text tutorials by Matheus Battisti on JavaScript and the web.
- [Newsletter do Filipe Deschamps](https://filipedeschamps.com.br/newsletter) — Daily newsletter with the most relevant tech news, in Portuguese.
- [devGo](https://devgo.com.br/) — Brazilian blog with JavaScript, TypeScript and front-end articles.
- [JavaScript Weekly](https://javascriptweekly.com/) — The world's most traditional weekly JavaScript newsletter. 🇺🇸
- [Bytes](https://bytes.dev/) — Fun, well-written JavaScript newsletter from ui.dev. 🇺🇸
- [State of JavaScript 2025](https://2025.stateofjs.com/en-US/) — Annual survey of what the community uses: language features, libraries, tools. 🆕 🇺🇸
- [JavaScript Rising Stars 2025](https://risingstars.js.org/2025/en) — The JavaScript projects that grew the most on GitHub during the year. 🆕 🇺🇸
- [web.dev](https://web.dev/) — The Chrome team's site on modern web development and performance. 🇺🇸
- [Mozilla Hacks](https://hacks.mozilla.org/) — Mozilla's blog for web developers. 🇺🇸
- [DEV Community — tag JavaScript](https://dev.to/t/javascript) — Thousands of community articles on JavaScript. 🇺🇸
- [freeCodeCamp News — JavaScript](https://www.freecodecamp.org/news/tag/javascript/) — In-depth free tutorials from freeCodeCamp. 🇺🇸
- [Frontend Focus](https://frontendfoc.us/) — Weekly front-end newsletter (HTML, CSS, JavaScript and browsers). 🇺🇸
- [Node Weekly](https://nodeweekly.com/) — Weekly Node.js newsletter. 🇺🇸
- [Smashing Magazine — JavaScript](https://www.smashingmagazine.com/category/javascript/) — Long, careful articles on JavaScript and front-end. 🇺🇸
- [Josh W. Comeau](https://www.joshwcomeau.com/) — Interactive articles on JavaScript, React and CSS. 🇺🇸
- [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript) — Curated list of JavaScript libraries, resources and tools. 🇺🇸
- [JSNation](https://jsnation.com/) — International JavaScript conference; talks are published for free online. 🆕 🇺🇸

## 🛠️ Tools
### Run, bundle and test
- [Node.js](https://nodejs.org/) — The runtime that runs JavaScript outside the browser. Install the LTS version.
- [nvm](https://github.com/nvm-sh/nvm) — Manage multiple Node.js versions on the same machine. 🇺🇸
- [Bun](https://bun.sh/) — Runtime, bundler, package manager and test runner in a single, very fast tool. 🆕 🇺🇸
- [Deno](https://deno.com/) — Secure-by-default JavaScript/TypeScript runtime, with native TypeScript and Node compatibility. 🆕 🇺🇸
- [pnpm](https://pnpm.io/) — Fast, disk-efficient package manager, compatible with npm. 🇺🇸
- [npm Docs](https://docs.npmjs.com/) — Official npm docs: package.json, scripts, publishing packages. 🇺🇸
- [Vite](https://vite.dev/) — The default bundler/dev server of the modern front-end: fast and zero-config. 🆕 🇺🇸
- [Rolldown](https://rolldown.rs/) — Rust bundler replacing Rollup inside Vite. 🆕 🇺🇸
- [esbuild](https://esbuild.github.io/) — Extremely fast bundler and minifier, written in Go. 🇺🇸
- [webpack](https://webpack.js.org/) — The classic bundler; still present in many legacy projects. 🇺🇸
- [Babel](https://babeljs.io/) — Transpiles modern JavaScript to older browser versions. 🇺🇸
- [Vitest](https://vitest.dev/) — Modern, fast test runner integrated with Vite, with a Jest-compatible API. 🆕 🇺🇸
- [Jest](https://jestjs.io/) — The most widely used testing framework in the ecosystem. 🇺🇸
- [Playwright](https://playwright.dev/) — End-to-end browser testing, maintained by Microsoft. 🇺🇸
- [TypeScript](https://www.typescriptlang.org/) — JavaScript with static types — the natural next step after this guide. 🇺🇸

### Code quality, editor and debugging
- [Visual Studio Code](https://code.visualstudio.com/) — The most used editor for JavaScript, with built-in IntelliSense and debugger. 🇺🇸
- [WebStorm](https://www.jetbrains.com/webstorm/) — JetBrains' IDE for JavaScript/TypeScript, free for non-commercial use. 🇺🇸
- [ESLint](https://eslint.org/) — The standard JavaScript linter: finds errors and enforces code standards. 🇺🇸
- [Prettier](https://prettier.io/) — Opinionated code formatter — ends style debates. 🇺🇸
- [Biome](https://biomejs.dev/) — Rust linter + formatter, a fast alternative to ESLint + Prettier. 🆕 🇺🇸
- [Oxc](https://oxc.rs/) — High-performance JavaScript parser, linter and tools in Rust. 🆕 🇺🇸
- [JSDoc](https://jsdoc.app/) — Document and type your JavaScript with comments the editor understands. 🇺🇸
- [Chrome DevTools — Depurar o JavaScript](https://developer.chrome.com/docs/devtools/javascript) — Official guide (in Portuguese) to breakpoints, console and debugging in Chrome.
- [Firefox DevTools](https://firefox-source-docs.mozilla.org/devtools-user/) — Documentation for Firefox's developer tools. 🇺🇸
- [MDN — O que deu errado? Resolvendo problemas no JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Scripting/What_went_wrong) — First debugging guide for beginners, in Portuguese.

### Playgrounds and visualizers
- [StackBlitz](https://stackblitz.com/) — Full Node.js environment in the browser; runs npm projects with no install. 🇺🇸
- [CodeSandbox](https://codesandbox.io/) — Front-end and Node sandboxes shareable by link. 🇺🇸
- [JSFiddle](https://jsfiddle.net/) — Classic HTML/CSS/JS playground to test and share snippets. 🇺🇸
- [RunJS](https://runjs.app/) — Desktop JavaScript playground that shows the result of every line. 🇺🇸
- [JS Visualizer 9000](https://www.jsv9000.app/) — Visualize the call stack, task queue and event loop as the code runs. 🇺🇸
- [Loupe](http://latentflip.com/loupe/) — The classic JavaScript event loop visualization, by Philip Roberts. 🇺🇸
- [Python Tutor — JavaScript](https://pythontutor.com/javascript.html) — Runs your code step by step showing memory and scope. 🇺🇸
- [regex101](https://regex101.com/) — Test regular expressions with a step-by-step explanation (ECMAScript mode). 🇺🇸
- [Bundlephobia](https://bundlephobia.com/) — Find out how much each npm package will add to your bundle. 🇺🇸
- [npm trends](https://npmtrends.com/) — Compare npm package downloads over time before picking a library. 🇺🇸

### Libraries and frameworks
- [React (PT-BR)](https://pt-br.react.dev/) — The most widely used UI library, with documentation in Portuguese.
- [Vue.js (PT-BR)](https://pt.vuejs.org/) — Progressive framework with a gentle learning curve, translated documentation.
- [Angular](https://angular.dev/) — Google's full framework, widely used in Brazilian companies. 🇺🇸
- [Svelte](https://svelte.dev/) — Compiles components to plain JavaScript, with no heavy runtime. 🇺🇸
- [Next.js](https://nextjs.org/) — React framework for full applications with server rendering. 🇺🇸
- [Astro](https://astro.build/) — Framework for content-focused sites, shipping minimal JavaScript. 🆕 🇺🇸
- [Express](https://expressjs.com/) — The most used minimalist Node.js web framework. 🇺🇸
- [Fastify](https://fastify.dev/) — Node.js framework focused on performance and low overhead. 🇺🇸
- [Hono](https://hono.dev/) — Lightweight web framework built on Web Standards, runs on Node, Bun, Deno and edge. 🆕 🇺🇸
- [NestJS](https://nestjs.com/) — Structured Node.js framework, very common in Brazilian back-end job posts. 🇺🇸
- [React Native](https://reactnative.dev/) — Native iOS and Android apps with JavaScript and React. 🇺🇸
- [Electron](https://www.electronjs.org/) — Desktop apps with JavaScript, HTML and CSS (VS Code is built with it). 🇺🇸
- [Three.js](https://threejs.org/) — 3D graphics in the browser with WebGL. 🇺🇸
- [D3.js](https://d3js.org/) — The most powerful data-visualization library on the web. 🇺🇸
- [Chart.js](https://www.chartjs.org/) — Simple, good-looking charts in a few lines. 🇺🇸
- [Axios](https://axios-http.com/) — Promise-based HTTP client for browser and Node. 🇺🇸
- [Zod](https://zod.dev/) — Schema-based data validation — essential in APIs and forms. 🇺🇸
- [Motion](https://motion.dev/) — Animation library for JavaScript and React (formerly Framer Motion). 🆕 🇺🇸
- [htmx](https://htmx.org/) — Interactivity through HTML attributes, writing little JavaScript. 🇺🇸

## 🧪 Hands-on projects and challenges
- [JavaScript30 (Wes Bos)](https://javascript30.com/) — 30 plain-JavaScript projects in 30 days, no frameworks. Free and classic. 🇺🇸
- [Mini Projetos JavaScript para Iniciantes (Fernando Leonid)](https://www.youtube.com/playlist?list=PLDgemkIT111AzoS1rB61sgMJbsEA4pyD2) — Guided mini-projects in Portuguese to practice DOM and logic.
- [Projetos Javascript (João Tinti)](https://www.youtube.com/playlist?list=PLJ8PYFcmwFOxmqYNlo_H8TYVSDLxB8HdR) — Playlist of hands-on plain-JavaScript projects, in Portuguese.
- [Desafios de back-end (backend-br)](https://github.com/backend-br/desafios) — Portuguese challenges to practice APIs and logic, solvable in Node.js.
- [Frontend Challenges (Felipe Fialho)](https://github.com/felipefialho/frontend-challenges) — Real front-end hiring challenges, including Brazilian companies.
- [Backend Challenges (CollabCodeTech)](https://github.com/CollabCodeTech/backend-challenges) — Real back-end hiring challenges.
- [JavaScript Questions — PT-BR (Lydia Hallie)](https://github.com/lydiahallie/javascript-questions/blob/master/pt-BR/README_pt_BR.md) — Advanced JavaScript questions with explanations, translated. Great to test what you know.
- [Algoritmos e estruturas de dados em JavaScript — PT-BR (trekhleb)](https://github.com/trekhleb/javascript-algorithms/blob/master/README.pt-BR.md) — Explained implementations of algorithms and data structures, with a Portuguese README.
- [Frontend Mentor](https://www.frontendmentor.io/) — Front-end challenges from professional designs, with a community for feedback. 🇺🇸
- [Codewars](https://www.codewars.com/) — JavaScript katas by difficulty level, with community solutions. 🇺🇸
- [Edabit](https://edabit.com/) — Thousands of short JavaScript challenges, from very easy to hard. 🇺🇸
- [JSchallenger](https://www.jschallenger.com/) — Free JavaScript exercises with automatic checking in the browser. 🇺🇸
- [10 Days of JavaScript (HackerRank)](https://www.hackerrank.com/domains/tutorials/10-days-of-javascript) — 10-day tutorial with auto-graded challenges. 🇺🇸
- [30 Days of JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript) — 30-day step-by-step challenge, with exercises every day. 🇺🇸
- [Vanilla Web Projects (Brad Traversy)](https://github.com/bradtraversy/vanillawebprojects) — 20 mini-projects with HTML, CSS and plain JavaScript. 🇺🇸
- [App Ideas](https://github.com/florinpop17/app-ideas) — App ideas by level, with requirements and bonuses, to build a portfolio. 🇺🇸
- [Project Based Learning](https://github.com/practical-tutorials/project-based-learning) — List of tutorials to build real projects, with a JavaScript section. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Recreate technologies from scratch (databases, bots, renderers) — many in JavaScript. 🇺🇸
- [Elevator Saga](https://play.elevatorsaga.com/) — Programming game: control elevators by writing JavaScript. 🇺🇸
- [JS Is Weird](https://jsisweird.com/) — Quiz on JavaScript's strangest results — learn coercion while laughing. 🇺🇸
- [JavaScript Interview Questions (sudheerj)](https://github.com/sudheerj/javascript-interview-questions) — 1000+ JavaScript interview questions, with answers. 🇺🇸
- [GreatFrontEnd](https://www.greatfrontend.com/) — Front-end interview prep with JavaScript questions and projects. 🆕 💰 🇺🇸

## 🤖 AI in practice
JavaScript is the language AI assistants were trained on the most — they write JS very well, and that is both an advantage and a trap for learners. Use AI as a **tutor and reviewer**, not as autopilot.

**For learning**
- Paste a console error (e.g. `TypeError: Cannot read properties of undefined (reading 'map')`) together with the code snippet and ask: *"explain the cause, show how to reproduce it and two ways to fix it"*.
- Ask it to **explain a concept with a runnable example**: closures, `this`, the event loop, `Promise` vs `async/await`. Then run the example in [JS Visualizer 9000](https://www.jsv9000.app/) or in the console to confirm.
- Ask for **exercises with answer keys** on the topic you are studying (array methods, destructuring, `fetch`), and solve them before looking at the answer.
- Ask it to rewrite your `var`-and-callbacks code in **modern JavaScript** (`const`, arrow functions, `async/await`) and explain each change.
- Use [MDN AI Help](https://developer.mozilla.org/en-US/plus/ai-help): it answers citing the documentation, which reduces hallucinations.

**For work**
- Use [GitHub Copilot](https://docs.github.com/pt/copilot), [Cursor](https://cursor.com/), [Claude Code](https://code.claude.com/docs/en/overview) or [Gemini CLI](https://github.com/google-gemini/gemini-cli) to: write Vitest/Jest tests, migrate jQuery or callback code to modern JavaScript, generate JSDoc, create Node automation scripts and review pull requests.
- After **every** accepted suggestion, run the linter (`npx eslint .`) and the tests. If the AI suggested an npm dependency, check on [npm trends](https://npmtrends.com/) that it exists, is maintained and is the one you need.
- Always state the target: "Node 24, ES modules, no TypeScript". Without it the AI mixes `require` with `import` and APIs from different versions.

**Limits and good practices**
- AI **makes up methods and packages** (`Array.prototype.unique()`, libraries that do not exist) and confuses browser APIs with Node ones. Confirm on [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) and in the [Node docs](https://nodejs.org/docs/latest/api/).
- It tends to generate code that "works" while ignoring `try/catch`, input validation and edge cases (`null`, empty array, `NaN`). Explicitly ask for error handling.
- Watch out for `innerHTML` with user data and `eval`: AI suggests them often, and they are doors to XSS.
- Do not paste proprietary code, secrets (`.env`, tokens) or customer data into tools without your company's policy.
- Understand what you accept: in interviews and in production, the code is yours.

**JavaScript is the language of AI applications.** The main libraries to call LLMs, build agents and even run models in the browser are JavaScript/TypeScript-first:
- [GitHub Copilot — documentação (PT-BR)](https://docs.github.com/pt/copilot) — Code assistant integrated into VS Code; free for students and with a limited free plan. 🆕
- [Cursor](https://cursor.com/) — VS Code-based editor with AI to edit, refactor and chat with the project. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: understands the whole repository and runs multi-step tasks. 🆕 🇺🇸
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) — Google's open-source terminal agent, with a generous free quota. 🆕 🇺🇸
- [Gemini Code Assist](https://codeassist.google/) — Google's code assistant for VS Code and JetBrains, with a free plan. 🆕 🇺🇸
- [MDN AI Help](https://developer.mozilla.org/en-US/plus/ai-help) — MDN assistant that answers citing the documentation itself. 🆕 🇺🇸
- [v0 (Vercel)](https://v0.app/) — Generates React interfaces from a prompt — good for prototyping and for studying the generated code. 🆕 🇺🇸
- [Bolt](https://bolt.new/) — Builds and runs full JavaScript apps in the browser from a description. 🆕 🇺🇸
- [AI SDK (Vercel)](https://ai-sdk.dev/) — JavaScript/TypeScript library to call LLMs from any provider with one API, with streaming and tools. 🆕 🇺🇸
- [LangChain.js](https://docs.langchain.com/oss/javascript/langchain/overview) — Framework for LLM applications (RAG, agents, chains) in JavaScript. 🆕 🇺🇸
- [Mastra](https://mastra.ai/) — TypeScript framework for AI agents, workflows and RAG. 🆕 🇺🇸
- [OpenAI Agents SDK (JavaScript)](https://openai.github.io/openai-agents-js/) — OpenAI's official SDK to build agents and multi-agent workflows in JavaScript. 🆕 🇺🇸
- [openai-node](https://github.com/openai/openai-node) — OpenAI's official JavaScript/TypeScript library. 🇺🇸
- [Anthropic SDK (TypeScript)](https://github.com/anthropics/anthropic-sdk-typescript) — Anthropic's (Claude) official JavaScript/TypeScript library. 🇺🇸
- [Google Gen AI SDK (JavaScript)](https://github.com/googleapis/js-genai) — The official Gemini SDK for JavaScript/TypeScript. 🆕 🇺🇸
- [Model Context Protocol — SDK TypeScript](https://github.com/modelcontextprotocol/typescript-sdk) — Build MCP servers in JavaScript to give tools to AI assistants. 🆕 🇺🇸
- [Transformers.js (Hugging Face)](https://huggingface.co/docs/transformers.js/index) — Run AI models (text, image, audio) directly in the browser or Node, with no server. 🆕 🇺🇸
- [WebLLM](https://webllm.mlc.ai/) — LLMs running 100% in the browser with WebGPU. 🆕 🇺🇸
- [Ollama JavaScript library](https://github.com/ollama/ollama-js) — Use local models (Llama, Gemma, Qwen...) from Node.js. 🆕 🇺🇸
- [TensorFlow.js](https://github.com/tensorflow/tfjs) — Train and run machine learning models in JavaScript. 🇺🇸
- [IA integrada ao Chrome (Gemini Nano)](https://developer.chrome.com/docs/ai/built-in) — Chrome APIs to use a local model directly in the browser from JavaScript. 🆕
- [Generative AI for Beginners (Microsoft)](https://github.com/microsoft/generative-ai-for-beginners) — 21 free lessons, with JavaScript examples and a Portuguese translation. 🆕
- [AI Agents for Beginners (Microsoft)](https://github.com/microsoft/ai-agents-for-beginners) — Free course on AI agents, with examples and translations. 🆕 🇺🇸
- [Build LLM Apps with LangChain.js (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/build-llm-apps-with-langchain-js/) — Short free course to build LLM applications in JavaScript. 🆕 🇺🇸
- [Prompt Engineering Guide (PT-BR)](https://www.promptingguide.ai/pt) — Prompt engineering guide in Portuguese — useful to ask for better code.

## 📜 Certifications
There is no official JavaScript certification — not from TC39, nor from Ecma. The OpenJS Foundation's JSNAD/JSNSD certifications have been discontinued. Employers assess **published projects and hands-on skill**; the certificates below help on a résumé but do not replace a portfolio.
- [freeCodeCamp — JavaScript Algorithms and Data Structures (PT-BR)](https://www.freecodecamp.org/portuguese/learn/javascript-algorithms-and-data-structures-v8) — Free, recognized certification earned by completing the curriculum projects. 🆕
- [freeCodeCamp — Full Stack Developer](https://www.freecodecamp.org/learn/full-stack-developer-v9) — New (2025) certification covering HTML, CSS, JavaScript, Node and databases. 🆕 🇺🇸
- [Curso em Vídeo — certificado de JavaScript](https://www.cursoemvideo.com/curso/javascript/) — Free 40-hour certificate upon completing the course on the platform.
- [Meta Front-End Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-front-end-developer) — Meta's professional certificate with JavaScript and React modules. 💰 🇺🇸
- [W3Cx Front-End Web Developer Professional Certificate (edX)](https://www.edx.org/certificates/professional-certificate/w3cx-front-end-web-developer) — Program by the W3C, the consortium that standardizes the web, with a JavaScript course. 💰 🇺🇸
- [W3Schools JavaScript Certificate](https://www.w3schools.com/js/js_exam.asp) — W3Schools' online JavaScript exam. 💰 🇺🇸
- [JavaScript Basics (UC Davis / Coursera)](https://www.coursera.org/learn/javascript-basics) — University intro course; audit for free or pay for the certificate. 🇺🇸

## 💼 Career and jobs
JavaScript appears in the vast majority of front-end job posts, in all Node.js ones and in almost every full-stack and mobile (React Native) post in Brazil. Tip: in the GitHub job repositories below, search open issues for "JavaScript", "Node" or "React".
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Front-end jobs in Brazil posted as issues — most require JavaScript.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end jobs; filter by Node.js.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — React jobs, all with JavaScript/TypeScript.
- [ProgramaThor — vagas JavaScript](https://programathor.com.br/jobs-javascript) — JavaScript jobs in Brazil, with salary ranges shown.
- [GeekHunter](https://www.geekhunter.com/pt) — Tech recruiting platform where companies come to you.
- [Remotar](https://remotar.com.br/) — 100% remote jobs in Brazil, many in JavaScript.
- [Coodesh](https://coodesh.com/) — Jobs and technical assessments for devs, with many JavaScript processes.
- [Empresas com trabalho remoto no Brasil](https://github.com/lerrua/remote-jobs-brazil) — List of Brazilian companies that hire remotely.
- [RemoteOK — vagas JavaScript](https://remoteok.com/remote-javascript-jobs) — International remote JavaScript jobs. 🇺🇸
- [Front End Interview Handbook 2026](https://www.frontendinterviewhandbook.com/) — Complete front-end interview prep, including JavaScript questions. 🆕 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Technical interview prep: algorithms, behavior and negotiation. 🇺🇸
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — JavaScript remains the world's most used language; see salaries and trends. 🆕 🇺🇸
- [roadmap.sh — Full Stack Roadmap](https://roadmap.sh/full-stack) — The full-stack path with JavaScript on both sides. 🇺🇸

## 👥 Communities
- [BrazilJS](https://github.com/braziljs) — The community behind Brazil's largest JavaScript conference; projects and translations on GitHub.
- [NodeBR](https://github.com/nodebr) — Brazilian Node.js community, with meetups and open projects.
- [JSLadies BR](https://github.com/jsladiesbr) — Community of women who code in JavaScript in Brazil.
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical-content community, very active in JavaScript and Node.
- [Frontend BR — fórum](https://github.com/frontendbr/forum) — Brazilian front-end forum on GitHub Discussions.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open-source community with an active Discord and mentoring.
- [Rocketseat — Discord](https://discord.com/invite/rocketseat) — One of Brazil's largest developer communities, open to everyone.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and job posts.
- [Código Fonte TV — Discord](https://discord.com/invite/codigofontetv) — The channel's community, with JavaScript and front-end rooms.
- [JavaScript Brasil (Telegram)](https://t.me/javascriptbr) — Portuguese-language JavaScript technical group on Telegram.
- [Frontend BR (Telegram)](https://t.me/frontendbr) — Brazilian front-end group on Telegram.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including JavaScript and Node.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Tag with Portuguese articles from the Brazilian community.
- [4noobs (He4rt)](https://github.com/he4rt/4noobs) — Index of community-made '4noobs' guides from Brazil, with JavaScript tracks.
- [.gg/javascript (Discord)](https://discord.com/invite/javascript) — The largest JavaScript Discord server, with help channels by topic. 🇺🇸
- [r/javascript](https://www.reddit.com/r/javascript/) — JavaScript news and discussion subreddit. 🇺🇸
- [r/learnjavascript](https://www.reddit.com/r/learnjavascript/) — Subreddit to ask questions while learning. 🇺🇸

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)

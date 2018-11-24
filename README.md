<h1 align="center">
<br>
  <a href="https://github.com/leonardomso/33"><img src="https://i.imgur.com/dsHmk6H.jpg" alt="33 Konsep Setiap Pengembang JavaScript yang Harus Diketahui" width=200"></a>
  <br>
    <br>
  33 Konsep Setiap JS Developer yang Harus Diketahui
  <br><br>
</h1>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License MIT">
  </a>
  <a href="https://travis-ci.com/leonardomso/33-js-concepts">
    <img src="https://img.shields.io/travis/leonardomso/33-js-concepts/master.svg?style=flat-square&label=build&logo=travis" alt="Build Status">
  </a>
</p>

## Pendahuluan

_Repository_ ini dibuat dengan maksud untuk membantu developers dalam menguasai konsep mereka dalam Javascript. Ini bukan sebuah kebutuhan, namun sebagai panduan dalam pembelajaran kedepan. Repository ini berdasarkan artikel yang dituliskan oleh [Stephen Curtis](https://twitter.com/stephenthecurt) dan anda dapat membaca artikelnya [disini](https://medium.com/@stephenthecurt/33-fundamentals-every-javascript-developer-should-know-13dd720a90d1).

## Komunitas

Jangan sungkan untuk memasukan PR kesebuah tautan ringkasan atau ulasan anda. Jika anda ingin menerjemahkan _repository_ ini kedalam bahasa asli anda, jangan sungkan untuk melakukanya.

Semua terjemahan _repository_ ini ada dibawah berikut:

- [Chinese](https://github.com/stephentian/33-js-concepts) — Re Tian
- [Portuguese-BR](https://github.com/tiagoboeing/33-js-concepts) — Tiago Boeing
- [Korean](https://github.com/yjs03057/33-js-concepts.git) — Suin Lee
- [Spanish](https://github.com/adonismendozaperez/33-js-conceptos) — Adonis Mendoza
- [Turkish](https://github.com/ilker0/33-js-concepts) — İlker Demir
- [Russian](https://github.com/gumennii/33-js-concepts) — Mihail Gumennii
- [Tiếng Việt](https://github.com/nguyentranchung/33-js-concepts) — Nguyễn Trần Chung
- [Polish](https://github.com/lip3k/33-js-concepts) — Dawid Lipinski
- [Persian](https://github.com/majidalavizadeh/33-js-concepts) — Majid Alavizadeh
- [Indonesian](https://github.com/rijdz/33-js-concepts) - Rijdzuan Sampoerna
---

## Daftar Isi

1. **[_Call Stack_](#1-call-stack)**
2. **[Tipe Primitif](#2-tipe-primitif)**
3. **[Tipe Nilai dan Tipe Referensi](#3-tipe-nilai-dan-tipe-referensi)**
4. **[Implisit, Eksplisit, Nominal, Struktur dan _Duck Typing_](#4-implicit-explicit-nominal-structuring-dan-duck-typing)**
5. **[== vs === vs typeof](#5--vs--vs-typeof)**
6. **[_Function Scope, Block Scope dan Lexical Scope_](#6-function-scope-block-scope-dan-lexical-scope)**
7. **[Ekspresi vs Pernyataan](#7-ekspresi-vs-pernyataan)**
8. **[_IIFE, Modules dan Namespaces_](#8-iife-modules-dan-namespaces)**
9. **[_Message Queue dan Event Loop_](#9-message-queue-dan-event-loop)**
10. **[setTimeout, setInterval dan requestAnimationFrame](#10-settimeout-setinterval-dan-requestanimationframe)**
11. **[Mesdalam JavaScript](#11-javascript-engines)**
12. **[_Bitwise Operators, Type Arrays dan Array Buffers_](#12-bitwise-operators-type-arrays-dan-array-buffers)**
13. **[_DOM dan Layout Trees_](#13-dom-dan-layout-trees)**
14. **[_Factories dan Classes_](#14-factories-dan-classes)**
15. **[_this, call, apply dan bind_](#15-this-call-apply-dan-bind)**
16. **[_new, Constructor, instanceof dan Instances_](#16-new-constructor-instanceof-dan-instances)**
17. **[_Prototype Inheritance dan Prototype Chain_](#17-prototype-inheritance-dan-prototype-chain)**
18. **[_Object.create dan Object.assign_](#18-objectcreate-dan-objectassign)**
19. **[_map, reduce, filter_](#19-map-reduce-filter)**
20. **[_Pure Functions, Side Effects dan State Mutation_](#20-pure-functions-side-effects-dan-state-mutation)**
21. **[_Closures_](#21-closures)**
22. **[_High Order Functions_](#22-high-order-functions)**
23. **[_Recursion_](#23-recursion)**
24. **[_Collections dan Generators_](#24-collections-dan-generators)**
25. **[_Promises_](#25-promises)**
26. **[_async/await_](#26-asyncawait)**
27. **[Struktur Data](#27-struktur-data)**
28. **[Operasi yang Mahal dan _Big O Notation_](#28-expensive-operation-dan-big-o-notation)**
29. **[Algoritma](#29-algoritma)**
30. **[Turunan, _Polymorphism_ dan Penggunaan Ulang Kode](#30-inheritance-polymorphism-dan-code-reuse)**
31. **[Pola Desain](#31-design-patterns)**
32. **[_Partial Applications, Currying, Compose dan Pipe_](#32-partial-applications-currying-compose-dan-pipe)**
33. **[Kode yang Rapih](#33-clean-code)**


---

## 1. Call Stack

### Artikel

 * 📜 [Memahami susunan panggilan dari JavaScript, _Event Loops_ — Gaurav Pandvia](https://medium.com/@gaurav.pandvia/Memahami-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec)
 * 📜 [Memahami susunan panggilan dari JavaScript— Charles Freeborn](https://medium.freecodecamp.org/Memahami-the-javascript-call-stack-861e41ae61d4)
 * 📜 [Javascript: Apa itu eksekusi _context_? Apa itu _Call Stack_? — Valentino Gagliardi](https://www.valentinog.com/blog/js-execution-context-call-stack/)
 * 📜 [Apa itu JS _Event Loop_ dan _Call Stack_? — Jess Telford](https://gist.github.com/jesstelford/9a35d20a2aa044df8bf241e00d7bc2d0)
 * 📜 [_Call Stack_ — MDN](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)
 * 📜 [Memahami eksekusi _Context_ dan Eksekusi _stack_ dalam Javascript — Sukhjinder Arora](https://blog.bitsrc.io/Memahami-execution-context-dan-execution-stack-in-javascript-1c9ea8642dd0)
 * 📜 [Bagaimana Cara Kerja Javascript?: Sebuah Ikhtisar dari mesin, _the Runtime_, dan _Call Stack_ — Alexander Zlatkov](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
 * 📜 [Panduan Mukhtakir untuk mengeksekusi _Contexts, Hoisting, Scopes, dan Closures_ pada JavaScript — Tyler McGinnis](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-dan-closures-in-javascript/)

### Video

 * 🎥 [Javascript: Penjelasan _the Call Stack_ — Coding Blocks India](https://www.youtube.com/watch?v=w6QGEiQceOM)
 * 🎥 [_The JS Call Stack_ Penjelasan dalam 9 Menit — Colt Steele](https://www.youtube.com/watch?v=W8AeMrVtFLY)
 * 🎥 [JavaScript Eksekusi _Stack_ — Codecademy](https://www.youtube.com/watch?v=jT0USJeNFEA)
 * 🎥 [Apa itu _Call Stack_? — Eric Traub](https://www.youtube.com/watch?v=w7QWQlkLY_s)
 * 🎥 [ _Call Stack_ — Kevin Drumm](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
 * 🎥 [Memahami Eksekusi JavaScript — Codesmith](https://www.youtube.com/watch?v=Z6a1cLyq7Ac&list=PLWrQZnG8l0E4kd1T_nyuVoxQUaYEWFgcD)
 * 🎥 [_Call Stack & Event Loop_ — movies com](https://www.youtube.com/watch?v=mk0lu9MKBto)
 * 🎥 [Panduan Mukhtakir untuk mengeksekusi _Contexts, Hoisting, Scopes, dan Closures_ pada JavaScript — Tyler McGinnis](https://www.youtube.com/watch?v=Nt-qa_LlUH0)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 2. Tipe Primitif

### Artikel

 * 📜 [Bagaimana angka dikodekan dalam JavaScript — Dr. Axel Rauschmayer](http://2ality.com/2012/04/number-encoding.html)
 * 📜 [Apa yang Kalian Ingin Ketahui Dari Tipe Angka JavaScript — Max Wizard K](https://medium.com/dailyjs/javascripts-number-type-8d59199db1b6)
 * 📜 [Apa yang tiap Pengembang JavaScript Harus Ketahui tentang angka _Floating Point_  — Chewxy](https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/)
 * 📜 [Rahasia Dari JavaScript Primitif — Angus Croll](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)
 * 📜 [Tipe Primitif — Alur](https://flow.org/en/docs/types/primitives/)
 * 📜 [(Tidak) Semua yang dalam JavaScript adalah Object - Daniel Li](http://blog.brew.com.hk/not-everything-in-javascript-is-an-object/)
 * 📜 [JavaScript Tipe Data dan Struktur Data - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)

### Videos

 * 🎥 [JavaScript Referensi vs Tipe Primitif — Academind](https://www.youtube.com/watch?v=9ooYYRLdg_g)
 * 🎥 [JavaScript Tipe Primitif — Simon Sez IT](https://www.youtube.com/watch?v=HsbWQsSCE5Y)
 * 🎥 [Tipe Nilai dan Tipe Referensi dalam JavaScript — Programming with Mosh](https://www.youtube.com/watch?v=e-_mDyqm2oU)
 * 🎥 [JavaScript Tipe Data Primitif — Avelx](https://www.youtube.com/watch?v=qw3j0A3DIzQ)
 * 🎥 [Semua yang tidak ingin anda ketahui tentang nomor JavaScript — Bartek Szopka](https://www.youtube.com/watch?v=MqHDDtVYJRI)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 3. Tipe Nilai dan Tipe Referensi

### Artikel

 * 📜 [Menjelaskan Nilai vs. Referensi dalam Javascript — Arnav Aggarwal](https://codeburst.io/explaining-value-vs-Referensi-in-javascript-647a975e12a0)
 * 📜 [Memahami Nilai dan Tipe Referensi dalam JavaScript — Zsolt Nagy](https://www.zsoltnagy.eu/understand-value-dan-Referensi-types-in-javascript/)
 * 📜 [Tipe Primitif & Tipe Referensi dalam JavaScript — Bran van der Meer](https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
 * 📜 [Tipe Nilai, Tipe Referensi dan _Scope_ dalam JavaScript — Ben Aston](https://medium.com/@benastontweet/lesson-1b-javascript-fundamentals-380f601ba851)
 * 📜 [Kembali ke asal: JavaScript Nilai vs Referensi — Miro Koczka](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-Referensi-8fb69d587a18)
 * 📜 [Memahami “_By Value_” dan “_By Reference_" dalam JavaScript — Léna Faure](https://hackernoon.com/grasp-by-value-dan-by-Referensi-in-javascript-7ed75efa1293)
 * 📜 [JavaScript Referensi dan Copy Variables — Vítor Capretz](https://hackernoon.com/javascript-Referensi-dan-copy-variables-b0103074fdf0)
 * 📜 [_JavaScript Primitive_ vs Referensi Values](http://www.javascripttutorial.net/javascript-primitive-vs-Referensi-values/)
 * 📜 [JavaScript _by Reference_ vs. _by Value_ — nrabinowitz](https://stackoverflow.com/questions/6605640/javascript-by-Referensi-vs-by-value)

### Videos

 * 🎥 [Javascript melewati _by Value_ vs melewati _by Reference_ — techsith](https://www.youtube.com/watch?v=E-dAnFdq8k8)
 * 🎥 [JavaScript Nilai vs Tipe Referensi — Programming with Mosh](https://www.youtube.com/watch?v=fD0t_DKREbE)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 4. Implicit, Explicit, Nominal, Structuring dan Duck Typing

### Artikel

 * 📜 [Apa yang ingin anda ketahui tentang Javascript's _Implicit Coercion_ — Promise Tochi](https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23)
 * 📜 [_JavaScript Type Coercion_ Dijelaskan — Alexey Samoshkin](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)
 * 📜 [_Javascript Coercion_ Dijelaskan — Ben Garrison](https://hackernoon.com/javascript-coercion-explained-545c895213d3)
 * 📜 [Apa Sebenarnya _Type Coercion_ dalam JavaScript? - Stack Overflow](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)
 * 📜 [_Anda Tidak Mengetahui JS: Types & Grammar_ [Book] — Kyle Simpson](https://www.oreilly.com/library/view/you-dont-know/9781491905159/ch04.html)
 * 📜 [(Tidak) Semuanya dalam JavaScript adalah sebuah Object - Daniel Li](http://blog.brew.com.hk/not-everything-in-javascript-is-an-object/)
 * 📜 [_Type Coercion_ dalam JavaScript, dan kenapa semuanya salah.](https://thedevs.network/blog/type-coercion-in-javascript-dan-Kenapa-everyone-gets-it-wrong)

 ### Videos

 * 🎥 [== ? === ??? ...#@^% - Shirmung Bielefeld](https://www.youtube.com/watch?v=qGyqzN0bjhc&t)
 * 🎥 [_Coercion_ dalam JavaScript - Hitesh Choudhary](https://www.youtube.com/watch?v=b04Q_vyqEG8)
 * 🎥 [Pertanyaan JavaScript: Apa itu _Coercion_? - Steven Hancock](https://www.youtube.com/watch?v=z4-8wMSPJyI)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 5. == vs === vs typeof

### Artikel

 * 📜 [JavaScript Dobel Sama Dengan vs. Triple Sama Dengan — Brandon Morelli](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)
 * 📜 [Apa perbedaan antara =, ==, dan === dalam JS? — Codecademy](https://www.codecademy.com/en/forum_questions/558ea4f5e39efed371000508)
 * 📜 [Haruskah saya menggunakan === atau == persamaan perbandingan operator dalam JavaScript? — Panu Pitkamaki](https://bytearcher.com/Artikel/equality-comparison-operator-javascript/)
 * 📜 [== vs === JavaScript: Double Sama Dengan dan Coercion — AJ Meyghani](https://www.codementor.io/javascript/tutorial/double-equals-dan-coercion-in-javascript)
 * 📜 [Kenapa Menggunakan Triple-Equals Operator dalam JavaScript? — Louis Lazaris](https://www.impressivewebs.com/Kenapa-use-triple-equals-javascipt/)
 * 📜 [Apa perbedaan antara == dan === dalam JavaScript? — Craig Buckler](https://www.oreilly.com/learning/what-is-the-difference-between-dan-in-javascript)
 * 📜 [Kenapa javascript's _typeof_ selalu menghasilkan "object"? — Stack Overflow](https://stackoverflow.com/questions/3787901/Kenapa-javascripts-typeof-always-return-object)
 * 📜 [Tipe cek dalam JavaScript — Toby Ho](http://tobyho.com/2011/01/28/checking-types-in-javascript/)
 * 📜 [Bagaimana cek tipe data lebih baik dalam JavaScript — Webbjocke](https://webbjocke.com/javascript-check-data-types/)
 * 📜 [Melakukan cek untuk kekosongan sebuah nilai dalam JavaScript — Tomer Aberbach](https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html)

### Videos

 * 🎥 [JavaScript - _typeof_ operator — Java Brains](https://www.youtube.com/watch?v=ol_su88I3kw)
 * 🎥 [Javascript _typeof_ operator — DevDelight](https://www.youtube.com/watch?v=qPYhTPt_SbQ)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 6. Function Scope, Block Scope dan Lexical Scope

### Artikel

 * 📜 [Anda Tidak Mengetahui JS: Scope & Closures [Book] — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch3.md)
 * 📜 [Pertarungan antara _Function Scope_ dan _Block Scope_ — Marius Herring](http://www.deadcoderising.com/2017-04-11-es6-var-let-dan-const-the-battle-between-function-scope-dan-block-scope/)
 * 📜 [Meniru _Block Scope_ dalam JavaScript — Josh Clanton](http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html)
 * 📜 [Perbedaan Antara _Function_ dan _Block Scope_ dalam JavaScript — Joseph Cardillo](https://medium.com/@josephcardillo/the-difference-between-function-dan-block-scope-in-javascript-4296b2322abe)
 * 📜 [_Function Scopes_ dan _Block Scopes_ dalam JavaScript — Samer Buna](https://edgecoders.com/function-scopes-dan-block-scopes-in-javascript-25bbd7f293d7)
 * 📜 [Memahami _Scope_ dan _Context_ dalam JavaScript | Ryan Morr](http://ryanmorr.com/Memahami-scope-dan-context-in-javascript/)
 * 📜 [JavaScript _Scope_ dan _Closures_ — Zell Liew](https://css-tricks.com/javascript-scope-closures/)
 * 📜 [Memahami _Scope_ dalam JavaScript — Wissam Abirached](https://developer.telerik.com/topics/web-development/Memahami-scope-in-javascript/)
 * 📜 [Membicarakan JavaScript - _Variables: Scopes, Environments,_ dan _Closures_ — Dr. Axel Rauschmayer](http://speakingjs.com/es5/ch16.html)
 * 📜 [Memahami _Scope_ dalam JavaScript ― Hammad Ahmed](https://scotch.io/tutorials/Memahami-scope-in-javascript)

### Videos

 * 🎥 [Apa yang membuat Javascript Aneh ... dan Luar Biasa pt. 4 — LearnCode.academy](https://www.youtube.com/watch?v=SBwoFkRjZvE)
 * 🎥 [_Variable Scope_ dalam JavaScript — Kirupa Chinnathambi](https://www.youtube.com/watch?v=dhp57T3p760)
 * 🎥 [JavaScript _Block Scope_ dan _Function Scope_ — mmtuts](https://www.youtube.com/watch?v=aK_nuUAdr8E)
 * 🎥 [Apaan sih _Lexical Scope_? — NWCalvank](https://www.youtube.com/watch?v=GhNA0r10MmA)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 7. Ekspresi vs Pernyataan

### Artikel

 * 📜 [Semua yang ingin anda ketahui tentang Ekspresi Javascript, Pernyataan dan Pernyataan Ekspresi — Promise Tochi](https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-dan-expression-statements-5k2)
 * 📜 [_Function Expressions_ vs _Function Declarations_ — Paul Wilkins](https://www.sitepoint.com/function-expressions-vs-declarations/)
 * 📜 [_JavaScript Function_ — _Declaration_ vs _Expression_ — Ravi Roshan](https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38)
 * 📜 [_Function Declarations_ vs. _Function Expressions_ — Mandeep Singh](https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052)
 * 📜 [_Function Declarations_ vs. _Function Expressions_ — Anguls Croll](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### Videos

 * 🎥 [_Expressions_ vs. _Statements_ dalam JavaScript — Hexlet](https://www.youtube.com/watch?v=WVyCrI1cHi8)
 * 🎥 [JavaScript - _Expression_ vs. _Statement_ — WebTunings](https://www.youtube.com/watch?v=3jDpNGJkupA)
 * 🎥 [_Function Statements_ dan _Function Expressions_ — Codeacademy](https://www.youtube.com/watch?v=oB5rH_9bqAI)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 8. IIFE, Modules dan Namespaces

### Artikel

 * 📜 [_Mastering Immediately-Invoked Function Expressions_ ― Chandra Gundamaraju](https://medium.com/@vvkchandra/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6)
 * 📜 [Apakah Modul ES6 Membuat Kasus IIFEs menjadi jadul?](https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0)
 * 📜 [10 Menit untuk modul JavaScript, format modul, _module loaders_ dan _module bundlers_ ― Jurgen Van de Moere](https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-dan-module-bundlers/)
 * 📜 [Modul ― Menjelajah JS](http://exploringjs.com/es6/ch_modules.html)
 * 📜 [ES Modul: Sebuah kartun pendalaman — Lin Clark](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
 * 📜 [Memahami ES6 Modul — Craig Buckler](https://www.sitepoint.com/Memahami-es6-modules/)
 * 📜 [Ikhtisar dari Modul ES6 dalam JavaScript — Brent Graham](https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/)
 * 📜 [Modul ES6 Mendalam — Nicolás Bevacqua](https://ponyfoo.com/Artikel/es6-modules-in-depth)
 * 📜 [Modul ES6, Node.js dan Solusi Michael Jackson — Alberto Gimeno](https://medium.com/dailyjs/es6-modules-node-js-dan-the-michael-jackson-solution-828dc244b8b)
 * 📜 [Modul JavaScript: Panduan Pemula — Preethi Kasireddy](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)

### Videos

 * 🎥 [_Immediately Invoked Function Expression_ - Beau teaches JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=3cbiZV4H22c)
 * 🎥 [Memahami JavaScript IIFE](https://www.youtube.com/watch?v=I5EntfMeIIQ)
 * 🎥 [Module JavaScript: ES6 Impor dan Expor — Kyle Robinson](https://www.youtube.com/watch?v=_3oSWwapPKQ)
 * 🎥 [ES6 - Modul — Ryan Christiani](https://www.youtube.com/watch?v=aQr2bV1BPyE)
 * 🎥 [Modul ES6 dalam dunia nyata — Sam Thorogood](https://www.youtube.com/watch?v=fIP4pjAqCtQ)
 * 🎥 [Modul ES6 — TempleCoding](https://www.youtube.com/watch?v=5P04OK6KlXA)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 9. Message Queue dan Event Loop

### Artikel

 * 📜 [Penjelasan JavaScript _Event Loop_ — Anoop Raveendran](https://medium.com/front-end-hacking/javascript-event-loop-explained-4cd26af121d4)
 * 📜 [_The JavaScript Event Loop: Explained_ — Erin Sweson-Healey](https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
 * 📜 [Apa itu Event Loop dalam JavaScript — WP Tutor.io](https://www.wptutor.io/web/js/javascript-event-loop)
 * 📜 [Memahami JS: _The Event Loop_ — Alexander Kondov](https://hackernoon.com/Memahami-js-the-event-loop-959beae3ac40)
 * 📜 [Memahami JavaScript _Event Loop_ — Ashish Gupta](https://www.zeolearn.com/magazine/Memahami-the-javascript-event-loop)
 * 📜 [Event Loop dalam JavaScript — Manjula Dube](https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49)
 * 📜 [The JavaScript Event Loop — Flavio Copes](https://flaviocopes.com/javascript-event-loop/)
 * 📜 [Bagaimana Javascript Bekerja: Event loop — Alexander Zlatkov](https://blog.sessionstack.com/how-javascript-works-event-loop-dan-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)

### Videos

 * 🎥 [Apa itu _event loop_ ? | JSConf EU — Philip Roberts](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
 * 🎥 [JavaScript _Event Loop_ — ComScience Simplified](https://www.youtube.com/watch?v=XzXIMZMN9k4)
 * 🎥 [Saya terjebak di Event Loop — Philip Roberts](https://www.youtube.com/watch?v=6MXRNXXgP_0)
 * 🎥 [Didalam _loop_ - Jake Archibald | JSConf.Asia 2018](https://www.youtube.com/watch?v=cCOL7MC4Pl0)
 * 🎥 [_Desmitificando el Event Loop_ (Spanish)](https://www.youtube.com/watch?v=Eqq2Rb7LzYE)


**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 10. setTimeout, setInterval dan requestAnimationFrame

### Artikel

 * 📜 [_setTimeout_ dan _setInterval_ — JavaScript.Info](https://javascript.info/settimeout-setinterval)
 * 📜 [Kenapa tidak menggunakan _setInterval_ — Akanksha Sharma](https://dev.to/akanksha_9560/Kenapa-not-to-use-setinterval--2na9)
 * 📜 [_setTimeout_ VS _setInterval_ — Develoger](https://develoger.com/settimeout-vs-setinterval-cff85142555b)
 * 📜 [Menggunakan _requestAnimationFrame_ — Chris Coyier](https://css-tricks.com/menggunakan-requestanimationframe/)
 * 📜 [Memahami JavaScript _requestAnimationFrame()_ — JavaScript Kit](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml)
 * 📜 [Menangani interval waktu dalam JavaScript - Amit Merchant](https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/)

### Videos

 * 🎥 [Javascript: Bagaimana _setTimeout_ dan _setInterval_ bekerja — Coding Blocks India](https://www.youtube.com/watch?v=6bPKyl8WYWI)
 * 🎥 [_setTimeout_ dan _setInterval_ dalam JavaScript — techsith](https://www.youtube.com/watch?v=TbCgGWe8LN8)
 * 🎥 [_JavaScript Timers_ — Steve Griffith](https://www.youtube.com/watch?v=0VVJSvlUgtg)
 * 🎥 [JavaScript _setTimeout_, _setInterval_ & _clearInterval_ — DoingITeasyChannel](https://www.youtube.com/watch?v=BVALvvy5bZY)
 * 🎥 [JavaScript _setTimeOut_ dan _setInterval_ Penjelasan — Theodore Anderson](https://www.youtube.com/watch?v=mVKfrWCOB60)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 11. JavaScript Engines

### Artikel

 * 📜 [Mesin JavaScript — Jen Looper](http://www.softwaremag.com/javascript-engines/)
 * 📜 [Memahami Bagaimana Chrome V8 Engine Menterjemahkan JavaScript ke Kode Mesin — DroidHead](https://medium.freecodecamp.org/Memahami-the-core-of-nodejs-the-powerful-chrome-v8-engine-79e7eb8af964)
 * 📜 [Memahami V8’s _Bytecode_ — Franziska Hinkelmann](https://medium.com/dailyjs/Memahami-v8s-bytecode-317d46c94775)
 * 📜 [Bagaimana cara kerja mesin V8 ? — Thibault Laurens](http://thibaultlaurens.github.io/javascript/2013/04/29/how-the-v8-engine-works/)
 * 📜 [Sejarah Singkat dari Google V8 Javascript — Clair Smith](https://www.mediacurrent.com/blog/brief-history-googles-v8-javascript-engine/)
 * 📜 [JavaScript essentials: Kenapa anda harus tahu cara kerja mesin - Rainer Hahnekamp](https://medium.freecodecamp.org/javascript-essentials-Kenapa-you-should-know-how-the-engine-works-c2cc0d321553)


### Videos

 * 🎥 [_JavaScript Engines: The Good Parts_™ — Mathias Bynens & Benedikt Meurer](https://www.youtube.com/watch?v=5nmpokoRaZI)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 12. _Bitwise Operators, Type Arrays dan Array Buffers_

### Artikel

 * 📜 [Memprogram dengan JS: Bitwise Operations — Alexander Kondov](https://hackernoon.com/programming-with-js-bitwise-operations-393eb0745dc4)
 * 📜 [Menggunakan JavaScript’s _Bitwise Operators_ di Dunia Nyata — ian m](https://codeburst.io/menggunakan-javascript-bitwise-operators-in-real-life-f551a731ff5)
 * 📜 [_JavaScript Bitwise Operators_ — w3resource](https://www.w3resource.com/javascript/operators/bitwise-operator.php)
 * 📜 [_Bitwise Operators_ dalam JavaScript — Joe Cha](https://medium.com/bother7-blog/bitwise-operators-in-javascript-65c4c69be0d3)
 * 📜 [Sebuah _Comprehensive Primer_ dalam _Binary Computation_ dan _Bitwise Operators_ dalam JavaScript — Paul Brown](https://medium.com/techtrument/a-comprehensive-primer-on-binary-computation-dan-bitwise-operators-in-javascript-81acf8341f04)

 ### Videos

 * 🎥 [JavaScript Bitwise Operators — Programming with Mosh](https://www.youtube.com/watch?v=mesu75PTDC8)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 13. DOM dan Layout Trees

### Artikel

 * 📜 [Bagaimana cara memahami dan Memodifikasi DOM dalam JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
 * 📜 [Apa itu _Document Object Model_, dan Kenapa anda harus tau apa yang dilakukan — Leonardo Maldonado](https://medium.freecodecamp.org/whats-the-document-object-model-dan-Kenapa-you-should-know-how-to-use-it-1a2d0bc5429d)
 * 📜 [JavaScript DOM Tutorial dengan contoh — Guru99](https://www.guru99.com/how-to-use-dom-dan-events-in-javascript.html)
 * 📜 [Apa itu DOM? — Chris Coyier](https://css-tricks.com/dom/)
 * 📜 [Melintasi DOM dengan JavaScript — Zell Liew](https://zellwk.com/blog/dom-traversals/)
 * 📜 [Lancar JavaScript [Book] — _Document Object Model_](https://eloquentjavascript.net/14_dom.html)
 * 📜 [DOM Tree](https://javascript.info/dom-nodes)
 * 📜 [Bagaimana Melintasi DOM dalam JavaScript — Vojislav Grujić](https://medium.com/javascript-in-plain-english/how-to-traverse-the-dom-in-javascript-d6555c335b4e)
 * 📜 [_Render Tree Construction_ — Ilya Grigorik](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)

 ### Videos

 * 🎥 [JavaScript DOM — The Net Ninja](https://www.youtube.com/watch?v=FIORjGvT0kk)
 * 🎥 [JavaScript DOM Crash Course — Traversy Media](https://www.youtube.com/watch?v=0ik6X4DJKCc)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 14. Factories dan Classes

### Artikel

 * 📜 [Bagaimana Menggunakan _Class_ dalam JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/Memahami-classes-in-javascript)
 * 📜 [Javascript Classes — _Under The Hood_ — Majid](https://medium.com/tech-tajawal/javascript-classes-under-the-hood-6b26d2667677)
 * 📜 [ES6 Classes — Nathaniel Foster](https://www.javascriptjanuary.com/blog/es6-classes)
 * 📜 [Lebih Baik JavaScript dengan ES6, Pt. II: Pendalaman terhadap _Classes_ ― Peleke Sengstacke](https://scotch.io/tutorials/better-javascript-with-es6-pt-ii-a-deep-dive-into-classes)
 * 📜 [Memahami _the Factory Design Pattern_ pada JavaScript Polos — Aditya Agarwal](https://medium.com/front-end-hacking/understand-the-factory-design-pattern-in-plain-javascript-20b348c832bd)
 * 📜 [JavaScript _Factory Functions_ vs _Constructor Functions_ vs _Classes_ — Eric Elliott](https://medium.com/javascript-scene/javascript-factory-functions-vs-constructor-functions-vs-classes-2f22ceddf33e)
 * 📜 [JavaScript _Factory Functions_ dengan ES6+ — Eric Elliott](https://medium.com/javascript-scene/javascript-factory-functions-with-es6-4d224591a8b1)
 * 📜 [_Factory Functions_ dalam JavaScript — Josh Miller](https://atendesigngroup.com/blog/factory-functions-javascript)
 * 📜 [_The Factory Pattern_ dalam JS ES6 — SnstsDev](https://medium.com/@SntsDev/the-factory-pattern-in-js-es6-78f0afad17e9)
 * 📜 [_Class vs Factory function: exploring the way forward_ — Cristi Salcescu](https://medium.freecodecamp.org/class-vs-factory-function-exploring-the-way-forward-73258b6a8d15)

 ### Videos

 * 🎥 [JavaScript Factory Functions — Programming with Mosh](https://www.youtube.com/watch?v=jpegXpQpb3o)
 * 🎥 [_Factory Functions_ dalam JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=ImwrezYhw4w)
 * 🎥 [Javascript Tutorial Function Factories — Crypto Chan](https://www.youtube.com/watch?v=R7-IwpH80UE)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 15. this, call, apply dan bind

### Artikel

 * 📜 [Bagaimana: call() , apply() dan bind() dalam JavaScript — Niladri Sekhar Dutta](https://www.codementor.io/niladrisekhardutta/how-to-call-apply-dan-bind-in-javascript-8i1jca6jp)
 * 📜 [Metode JavaScript Apply, Call, dan Bind adalah penting untuk JavaScript Professionals — Richard Bovell](http://javascriptissexy.com/javascript-apply-call-dan-bind-methods-are-essential-for-javascript-professionals/)
 * 📜 [Apaan nih?! - Memahami kata kunci this, call, apply, dan bind dalam JavaScript — Tyler McGinnis](https://tylermcginnis.com/this-keyword-call-apply-bind-javascript/)
 * 📜 [Javascript: call(), apply() dan bind() — Omer Goldberg](https://medium.com/@omergoldberg/javascript-call-apply-dan-bind-e5c27301f7bb)
 * 📜 [Perbedaan Antara call / apply / bind — Ivan Sifrim](https://medium.com/@ivansifrim/the-differences-between-call-apply-bind-276724bb825b)
 * 📜 [call(), apply() dan bind() methods dalam JavaScript](https://tech.io/playgrounds/9799/learn-solve-call-apply-dan-bind-methods-in-javascript)
 * 📜 [Mastering 'this' dalam JavaScript: Callbacks dan bind(), apply(), call() — Michelle Gienow](https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/)
 * 📜 [JavaScript’s apply, call, and bind explained by hosting a cookout — Kevin Kononenko](https://dev.to/kbk0125/javascripts-apply-call-dan-bind-explained-by-hosting-a-cookout-32jo)
 * 📜 [Bagaimana dan Kapan menggunakan bind, call, dan apply dalam JavaScript — Eigen X](https://www.eigenx.com/blog/https/mediumcom/eigen-x/how-dan-when-to-use-bind-call-dan-apply-in-javascript-77b6f42898fb)
 * 📜 [JavaScript .bind() vs .apply() dan .call() — Hack Sparrow](https://www.hacksparrow.com/javascript-bind-vs-apply-dan-call.html)
 * 📜 [call() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Function/call)
 * 📜 [bind() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_objects/Function/bind)
 * 📜 [apply() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Function/apply)
 * 📜 [Apa itu 'this' dalam JavaScript? — Daniel Li](http://blog.brew.com.hk/what-is-this-in-javascript/)
 * 📜 [Biarkan saya menjelaskan apa itu `this`. (Javascript) — Jason Yu](https://dev.to/ycmjason/let-me-explain-to-you-what-is-this-javascript-44ja)

  ### Videos

 * 🎥 [JavaScript call, apply dan bind — techsith](https://www.youtube.com/watch?v=c0mLRpw-9rI)
 * 🎥 [JavaScript Practical Applications of Call, Apply dan Bind functions— techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
 * 🎥 [JavaScript (call, bind, apply) — curious aatma](https://www.youtube.com/watch?v=Uy0NOXLBraE)
 * 🎥 [Memahami Functions dan 'this' In The World of ES2017 — Bryan Hughes](https://www.youtube.com/watch?v=AOSYY1_np_4)
 * 🎥 [bind dan this - Object Creation dalam JavaScript - FunFunFunction](https://www.youtube.com/watch?v=GhbhD1HR5vk)
 * 🎥 [JavaScript Practical Applications of Call, Apply dan Bind functions — techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
 * 🎥 [JS Function Methods call(), apply(), dan bind() — Steve Griffith](https://www.youtube.com/watch?v=uBdH0iB1VDM)
 
**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 16. new, Constructor, instanceof dan Instances

### Artikel

 * 📜 [JavaScript untuk pemula: the ‘new’ operator — Brandon Morelli](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
 * 📜 [Membuka Tabir kata kunci JavaScript ‘new’ — Cynthia Lee](https://medium.freecodecamp.org/demystifying-javascripts-new-keyword-874df126184c)
 * 📜 [Constructor, operator "new" — JavaScript.Info](https://javascript.info/constructor-new)
 * 📜 [Memahami _JavaScript Constructors_ — Faraz Kelhini](https://css-tricks.com/Memahami-javascript-constructors/)
 * 📜 [Menggunakan Constructor Functions — Openclassrooms](https://openclassrooms.com/en/courses/3523231-learn-to-code-with-javascript/4379006-use-constructor-functions)
 * 📜 [Melebihi `typeof` dan `instanceof`: menyederhanakan dynamic type checks — Dr. Axel Rauschmayer](http://2ality.com/2017/08/type-right.html)
 * 📜 [Apa itu Instanceof Operator dalam JavaScript — appendTo](https://appendto.com/2016/10/what-is-the-instanceof-operator-in-javascript/)
 * 📜 [JavaScript instanceof vs typeof — Gary Rafferty](http://garyrafferty.com/2012/12/07/JavaScript-instanceof-vs-typeof.html)
 * 📜 [_Function and Object, instances of each other_ — Kiro Risk](https://javascriptrefined.io/function-dan-object-instances-of-each-other-1e1095d5faac)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 17. Prototype Inheritance dan Prototype Chain

### Artikel

 * 📜 [Javascript : Prototype vs Class — Valentin PARSY](https://medium.com/@parsyval/javascript-prototype-vs-class-a7015d5473b)
 * 📜 [Mesin Dasar JavaScript: Mengoptimalisasi prototypes — Mathias Bynens](https://mathiasbynens.be/notes/prototypes)
 * 📜 [JavaScript Prototype — NC Patro](https://codeburst.io/javascript-prototype-cb29d82b8809)
 * 📜 [Prototype dalam JavaScript — Sandeep Ranjan](https://www.codementor.io/sandeepranjan2007/prototype-in-javascipt-knbve0lqo)
 * 📜 [Prototypes dalam JavaScript — Rupesh Mishra](https://hackernoon.com/prototypes-in-javascript-5bba2990e04b)
 * 📜 [Prototype dalam JavaScript: itu aneh, tapi ini bagaimana cara kerjanya — Pranav Jindal](https://medium.freecodecamp.org/prototype-in-js-busted-5547ec68872)
 * 📜 [Turunan dan rantai prototype — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
 * 📜 [Menjadi Master Wawancara JavaScript : Apa Perbedaan Antara Class & Prototypal Inheritance? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)
 * 📜 [Memahami JavaScript: Prototype dan Inheritance — Alexander Kondov](https://hackernoon.com/Memahami-javascript-prototype-dan-inheritance-d55a9a23bde2)
 * 📜 [Prototypal Inheritance — JavaScript.Info](https://javascript.info/prototype-inheritance)
 * 📜 [Bagaimana Bekerja dengan Prototypes dan Inheritance dalam JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/Memahami-prototypes-dan-inheritance-in-javascript)
 * 📜 [Master JavaScript Prototypes & Inheritance — Arnav Aggarwal](https://codeburst.io/master-javascript-prototypes-inheritance-d0a9a5a75c4e)
 * 📜 [Anda Tidak Mengetahui JS [Book] Chapter 5: Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch5.md)
 * 📜 [JavaScript’s Prototypal Inheritance Dijelaskan Dengan Menggunakan CSS — Nash Vail](https://medium.freecodecamp.org/Memahami-prototypal-inheritance-in-javascript-with-css-93b2fcda75e4)
 * 📜 [Prototypal Inheritance dalam JavaScript — Jannis Redmann](https://gist.github.com/derhuerst/a585c4916b1c361cc6f0)
 * 📜 [Classical dan Prototypical Inheritance dalam JavaScript — Danny Cornelisse](http://www.competa.com/blog/classical-prototypical-inheritance-javascript/)
 * 📜 [Demystifying ES6 Classes dan Prototypal Inheritance ― Neo Ighodaro](https://scotch.io/tutorials/demystifying-es6-classes-dan-prototypal-inheritance)
 * 📜 [Pengenalan ke Prototypal Inheritance — Dharani Jayakanthan](https://dev.to/danny/intro-to-prototypal-inheritance---js-9di)
 * 📜 [Classes dalam JavaScript - Explained — Daniel Li](http://blog.brew.com.hk/classes-in-javascript-explained/)
 * 📜 [Anda Tidak Mengetahui JS: this & Object Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch4.md)

 ### Videos

 * 🎥 [Javascript Prototype Inheritance — Avelx](https://www.youtube.com/watch?v=sOrtAjyk4lQ)
 * 🎥 [JavaScript Prototype Inheritance Penjelasan pt. I — techsith](https://www.youtube.com/watch?v=7oNWNlMrkpc)
 * 🎥 [JavaScript Prototype Inheritance Penjelasan pt. II — techsith](https://www.youtube.com/watch?v=uIlj6_z_wL8)
 * 🎥 [JavaScript Prototype Inheritance Penjelasan — Kyle Robinson](https://www.youtube.com/watch?v=qMO-LTOrJaE)
 * 🎥 [Advanced Javascript - Prototypal Penjelasan In 1 Minute](https://www.youtube.com/watch?v=G6l5CHl67HQ)
 * 🎥 [Sebuah Ikhtisar dari Javascript Klasik Classes dan Prototypal Inheritance — Pentacode](https://www.youtube.com/watch?v=phwzuiJJPpQ)
 * 🎥 [Object Oriented JavaScript - Prototype — The Net Ninja](https://www.youtube.com/watch?v=4jb4AYEyhRc)
 * 🎥 [Prototype dalam JavaScript — kudvenkat](https://www.youtube.com/watch?v=2rkEbcptR64)
 * 🎥 [JavaScript Menggunakan Prototypes — O'Reilly](https://www.youtube.com/watch?v=oCwCcNvaXAQ)
 * 🎥 [Panduan Pemula Untuk Javascript's Prototype — Tyler Mcginnis](https://www.youtube.com/watch?v=XskMWBXNbp0)
 * 🎥 [Prototypes dalam JavaScript - p5.js Tutorial — The Coding Train](https://www.youtube.com/watch?v=hS_WqkyUah8)


**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 18. Object.create dan Object.assign

### Artikel

 * 📜 [Object.create() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Object/create)
 * 📜 [Object.create dalam JavaScript — Rupesh Mishra](https://hackernoon.com/object-create-in-javascript-fa8674df6ed2)
 * 📜 [Object.create(): Cara Baru dalam Membuat Object dalam JavaScript — Rob Gravelle](https://www.htmlgoodies.com/beyond/javascript/object.create-the-new-way-to-create-objects-in-javascript.html)
 * 📜 [Turunan Dasae dengan Object.create — Joshua Clanton](http://adripofjavascript.com/blog/drips/basic-inheritance-with-object-create.html)
 * 📜 [Object.create() dalam JavaScript — GeeksforGeeks](https://www.geeksforgeeks.org/object-create-javascript/)
 * 📜 [Memahami Perbedaan Antara Object.create() dan operator new — Jonathan Voxland](https://medium.com/@jonathanvox01/Memahami-the-difference-between-object-create-dan-the-new-operator-b2a2f4749358)
 * 📜 [Pembuatan Obyek JavaScript : Pola dan _Best Practices_ — Jeff Mott](https://www.sitepoint.com/javascript-object-creation-patterns-best-practises/)
 * 📜 [Berurusan dengan Objects dalam JavaScript With Object.assign, Object.keys dan hasOwnProperty](https://alligator.io/js/dealing-with-objects/)
 * 📜 [Copying Objects dalam JavaScript ― Orinami Olatunji](https://scotch.io/bar-talk/copying-objects-in-javascript)
 * 📜 [Object.assign() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Object/assign)
 * 📜 [JavaScript: Object.assign() — Thiago S. Adriano](https://codeburst.io/javascript-object-assign-bc9696dcbb6e)
 * 📜 [Bagaimana Cara Mengkloning Terdalam sebuah JavaScript Object — Flavio Copes](https://flaviocopes.com/how-to-clone-javascript-object/)

 ### Videos

 * 🎥 [Object.assign() dijelaskan — Aaron Writes Code](https://www.youtube.com/watch?v=aw7NfYhR5rc)
 * 🎥 [Object.assign() Metode — techsith](https://www.youtube.com/watch?v=9Ky4X6inpi4)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 19. map, reduce, filter

### Artikel

 * 📜 [JavaScript Functional Programming — map, filter dan reduce — Bojan Gvozderac](https://medium.com/jsguru/javascript-functional-programming-map-filter-dan-reduce-846ff9ba492d)
 * 📜 [Learn map, filter dan reduce dalam JavaScript — João Miguel Cunha](https://medium.com/@joomiguelcunha/learn-map-filter-dan-reduce-in-javascript-ea59009593c4)
 * 📜 [JavaScript’s Map, Reduce, dan Filter — Dan Martensen](https://danmartensen.svbtle.com/javascripts-map-reduce-dan-filter)
 * 📜 [Bagaimana cara menggunakan Map, Filter, & Reduce dalam JavaScript — Peleke Sengstacke](https://code.tutsplus.com/tutorials/how-to-use-map-filter-reduce-in-javascript--cms-26209)
 * 📜 [JavaScript — Memahami Chain Map, Filter, dan Reduce — Brandon Morelli](https://codeburst.io/javascript-learn-to-chain-map-filter-dan-reduce-acd2d0562cd4)
 * 📜 [Javascript data structure dengan map, reduce, filter dan ES6 — Deepak Gupta](https://codeburst.io/write-beautiful-javascript-with-%CE%BB-fp-es6-350cd64ab5bf)
 * 📜 [Memahami map, filter dan reduce dalam JavaScript — Luuk Gruijs](https://hackernoon.com/Memahami-map-filter-dan-reduce-in-javascript-5df1c7eee464)
 * 📜 [Functional Programming dalam JS: map, filter, reduce (Pt. 5) — Omer Goldberg](https://hackernoon.com/functional-programming-in-js-map-filter-reduce-pt-5-308a205fdd5f)
 * 📜 [JavaScript: Map, Filter, Reduce — William S. Vincent](https://wsvincent.com/functional-javascript-map-filter-reduce/)
 * 📜 [Arrow Functions: Fat dan Concise Syntax dalam JavaScript — Kyle Pennell](https://www.sitepoint.com/es6-arrow-functions-new-fat-concise-syntax-javascript/)
 * 📜 [JavaScript: Arrow Functions untuk Pemula — Brandon Morelli](https://codeburst.io/javascript-arrow-functions-for-beginners-926947fc0cdc)
 * 📜 [Kapan (dan Kenapa) anda harus menggunakan ES6 arrow functions — dan kapan harus tidak — Cynthia Lee](https://medium.freecodecamp.org/when-dan-Kenapa-you-should-use-es6-arrow-functions-dan-when-you-shouldnt-3d851d7f0b26)
 * 📜 [JavaScript — Belajar & Memahami Arrow Functions — Brandon Morelli](https://codeburst.io/javascript-learn-understand-arrow-functions-fe2083533946)
 * 📜 [(JavaScript )=> Arrow functions — sigu](https://medium.com/podiihq/javascript-arrow-functions-27d4c3334b83)
 * 📜 [Sebuah Kemungkinan untuk menggunakan Async/Await untuk filter(), find(), forEach(), map() dan reduce() metode di Array — Ruwan Geeganage](https://www.linkedin.com/pulse/possibility-use-asyncawait-filter-find-foreach-map-reduce-geeganage/)
 * 📜 [Javascript.reduce() — Paul Anderson](https://medium.com/@panderson.dev/javascript-reduce-79aab078da23)

 ### Videos

 * 🎥 [Map, Filter dan Reduce — Lydia Hallie](https://www.youtube.com/watch?v=UXiYii0Y7Nw)
 * 🎥 [Functional JavaScript: Map, forEach, Reduce, Filter — Theodore Anderson](https://www.youtube.com/watch?v=vytzLlY_wmU)
 * 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part I) — Michael Rosata](https://www.youtube.com/watch?v=qTeeVd8hOFY)
 * 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part 2) — Michael Rosata](https://www.youtube.com/watch?v=gIm9xLYudL0)
 * 🎥 [JavaScript Higher Order Functions - Filter, Map, Sort & Reduce — Epicop](https://www.youtube.com/watch?v=zYBeEPxNSbw)
 * 🎥 [[Array Methods 2/3] .filter + .map + .reduce — CodeWithNick](https://www.youtube.com/watch?v=4qWlqD0yYTU)
 * 🎥 [Arrow functions dalam JavaScript - What, Kenapa dan How — Fun Fun Function](https://www.youtube.com/watch?v=6sQDTgOqh-I)
 * 🎥 [Learning Functional Programming with JavaScript — Anjana Vakil - JSUnconf](https://www.youtube.com/watch?v=e-5obm1G_FY&t=1521s)


**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 20. Pure Functions, Side Effects dan State Mutation

### Artikel

 * 📜 [Javascript dan Functional Programming — Pure Functions — Omer Goldberg](https://hackernoon.com/javascript-dan-functional-programming-pt-3-pure-functions-d572bb52e21c)
 * 📜 [Menjadi Master Wawancara JavaScript : Apa itu _pure functions_? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)
 * 📜 [JavaScript: Apa itu Pure Functions And Kenapa Menggunakanya? — James Jeffery](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)
 * 📜 [Pure functions dalam JavaScript — @nicoespeon](http://www.nicoespeon.com/en/2015/01/pure-functions-javascript/)
 * 📜 [Functional Programming: Pure Functions — Arne Brasseur](https://www.sitepoint.com/functional-programming-pure-functions/)
 * 📜 [Pure Functions dalam JavaScript — Krunal](https://appdividend.com/2017/04/10/pure-functions-in-javascript/)
 * 📜 [Making your JavaScript Pure — Jack Franklin](https://alistapart.com/article/making-your-javascript-pure)
 * 📜 [To mutate, or not to mutate, dalam JavaScript](https://slemgrim.com/mutate-or-not-to-mutate/)
 * 📜 [Arrays, Objects dan Mutations — Federico Knüssel](https://medium.com/@fknussel/arrays-objects-dan-mutations-6b23348b54aa)
 * 📜 [The State of Immutability — Maciej Sikora](https://medium.com/dailyjs/the-state-of-immutability-169d2cd11310)
 * 📜 [Bagaimana berurusan dengan efek samping yang kotor dalam pure functional JavaScript — James Sinclair](https://jrsinclair.com/Artikel/2018/how-to-deal-with-dirty-side-effects-in-your-pure-functional-javascript/)
 * 📜 [Menghindari Efek Samping dalam JavaScript — David Walsh](https://davidwalsh.name/preventing-sideeffects-javascript)
 * 📜 [Wielding Pure Functions dalam JavaScript dan Function Composition — Peleke Sengstacke](https://scotch.io/tutorials/wielding-pure-functions-in-javascript-dan-function-composition)
 * 📜 [JavaScript: Pure Functions — William S. Vincent](https://wsvincent.com/javascript-pure-functions/)
 * 📜 [Paradigma Functional programming dalam modern JavaScript: _Pure functions_ — Alexander Kondov](https://hackernoon.com/functional-programming-paradigms-in-modern-javascript-pure-functions-797d9abbee1)

 ### Videos

 * 🎥 [Pure Functions — Hexlet](https://www.youtube.com/watch?v=dZ41D6LDSBg)
 * 🎥 [Pure Functions - Functional Programming dalam JavaScript — Paul McBride](https://www.youtube.com/watch?v=Jh_Uzqzz_wM)
 * 🎥 [JavaScript Pure Functions — Seth Alexander](https://www.youtube.com/watch?v=frT3H-eBmPc)


**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 21. Closures

### Artikel

 * 📜 [Closures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
 * 📜 [Saya Tidak Pernah Memahami JavaScript closures — Olivier De Meulder](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8)
 * 📜 [Closure — JavaScript.Info](https://javascript.info/closure)
 * 📜 [Memahami JavaScript Closures Dengan Mudah — Richard Bovell](http://javascriptissexy.com/understand-javascript-closures-with-ease/)
 * 📜 [Memahami JavaScript Closures — Codesmith](https://codeburst.io/Memahami-javascript-closures-da6aab330302)
 * 📜 [Memahami Closures dalam JavaScript — Brandon Morelli](https://codeburst.io/understand-closures-in-javascript-d07852fa51e7)
 * 📜 [Panduan Singkat untuk membantu anda memahami closures dalam JavaScript — Prashant Ram](https://medium.freecodecamp.org/javascript-closures-simplified-d0d23fa06ba4)
 * 📜 [Memahami JavaScript Closures: Sebuah Pendekatan Praktikal — Paul Upendo](https://scotch.io/tutorials/Memahami-javascript-closures-a-practical-approach)
 * 📜 [Memahami JavaScript: Closures — Alexander Kondov](https://hackernoon.com/Memahami-javascript-closures-4188edf5ea1b)
 * 📜 [Bagaimana menggunakan JavaScript closures dengan percaya diri — Léna Faure](https://hackernoon.com/how-to-use-javascript-closures-with-confidence-85cd1f841a6b)
 * 📜 [JavaScript closures by example — tyler](https://howchoo.com/g/mge2mji2mtq/javascript-closures-by-example)
 * 📜 [JavaScript — Closures dan Scope — Alex Aitken](https://codeburst.io/javascript-closures-dan-scope-3784c75b9290)
 * 📜 [Menjelajahi Kekuatan dari closures dalam JavaScript — Cristi Salcescu](https://medium.freecodecamp.org/discover-the-power-of-closures-in-javascript-5c472a7765d7)

 ### Videos

 * 🎥 [Javascript Closure — techsith](https://www.youtube.com/watch?v=71AtaJpJHw0)
 * 🎥 [Closures — Fun Fun Function](https://www.youtube.com/watch?v=CQqwU2Ixu-U)
 * 🎥 [Closures dalam JavaScript — techsith](https://www.youtube.com/watch?v=-xqJo5VRP4A)
 * 🎥 [JavaScript Closures 101: Apa itu closure? — JavaScript Tutorials](https://www.youtube.com/watch?v=yiEeiMN2Khs)
 * 🎥 [Closures — freeCodeCamp](https://www.youtube.com/watch?v=1JsJx1x35c0)
 * 🎥 [JavaScript Closures — CodeWorkr](https://www.youtube.com/watch?v=-rLrGAXK8WE)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 22. High Order Functions

### Artikel

 * 📜 [Higher-Order Functions — Lancar JavaScript [Book]](https://eloquentjavascript.net/05_higher_order.html)
 * 📜 [Higher-Order Functions dalam JavaScript — M. David Green](https://www.sitepoint.com/higher-order-functions-javascript/)
 * 📜 [Higher Order Functions: Menggunakan Filter, Map dan Reduce Untuk Kode yang dapat Lebih Dipelihara (Maintainable) — Guido Schmitz](https://medium.freecodecamp.org/higher-order-functions-in-javascript-d9101f9cf528)
 * 📜 [First-class dan Higher Order Functions: Effective Functional JavaScript — Hugo Di Francesco](https://hackernoon.com/effective-functional-javascript-first-class-dan-higher-order-functions-713fde8df50a)
 * 📜 [Higher Order Functions dalam JavaScript — John Hannah](https://www.lullabot.com/Artikel/higher-order-functions-in-javascript)
 * 📜 [Higher-order Functions — Richard Bovell](http://javascriptissexy.com/tag/higher-order-functions/)
 * 📜 [Higher Order Functions dalam JavaScript — Zsolt Nagy](http://www.zsoltnagy.eu/higher-order-functions-in-javascript/)
 * 📜 [Bersenang-senang dengan Higher Order Functions dalam JavaScript — Derick](https://derickbailey.com/2015/10/21/fun-with-higher-order-functions-in-javascript/)
 * 📜 [Sebuah Peringatan pada bagaimana dalam menggunakan high order functions — Pedro Filho](https://github.com/pedroapfilho/high-order-functions)
 * 📜 [Bagaimana Menggunakan JavaScript closures dengan percaya diri — Léna Faure](https://hackernoon.com/how-to-use-javascript-closures-with-confidence-85cd1f841a6b)
 * 📜 [JavaScript closures dengan contoh — tyler](https://howchoo.com/g/mge2mji2mtq/javascript-closures-by-example)

 ### Videos

 * 🎥 [JavaScript Higher Order Functions & Arrays — Traversy Media](https://www.youtube.com/watch?v=rRgD1yVwIvE)
 * 🎥 [Higher Order Functions — Fun Fun Function](https://www.youtube.com/watch?v=BMUiFMZr7vk)
 * 🎥 [Higher Order Functions dalam JavaScript — Raja Yogan](https://www.youtube.com/watch?v=dTlpYnmBW9I)
 * 🎥 [Higher Order Iterators dalam JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=GYRMNp1SKXA)
 * 🎥 [Higher Order Functions dalam JavaScript — The Coding Train](https://www.youtube.com/watch?v=H4awPsyugS0)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 23. Recursion

### Artikel

 * 📜 [Recursion dalam JavaScript — Kevin Ennis](https://medium.freecodecamp.org/recursion-in-javascript-1608032c7a1f)
 * 📜 [Memahami Recursion dalam JavaScript — Zak Frisch](https://medium.com/@zfrisch/Memahami-recursion-in-javascript-992e96449e03)
 * 📜 [Belajar dan Memahami Recursion dalam JavaScript — Brandon Morelli](https://codeburst.io/learn-dan-understand-recursion-in-javascript-b588218e87ea)
 * 📜 [Recursion dalam Functional JavaScript — M. David Green](https://www.sitepoint.com/recursion-functional-javascript/)
 * 📜 [Programming with JS: Recursion — Alexander Kondov](https://hackernoon.com/programming-with-js-recursion-31371e2bf808)
 * 📜 [Anonymous Recursion dalam JavaScript — simo](https://dev.to/simov/anonymous-recursion-in-javascript)
 * 📜 [Recursion, iteration dan tail calls in JS — loverajoel](http://www.jstips.co/en/javascript/recursion-iteration-dan-tail-calls-in-js/)
 * 📜 [Memahami Recursion dalam JavaScript with Confidence — Jay](https://www.thecodingdelight.com/Memahami-recursion-javascript/)

 ### Videos

 * 🎥 [Recursion dalam JavaScript — techsith](https://www.youtube.com/watch?v=VtG0WAUvq2w)
 * 🎥 [Recursion — Fun Fun Function](https://www.youtube.com/watch?v=k7-N8R0-KY4)
 * 🎥 [Recursion dan Recursive Functions — Hexlet](https://www.youtube.com/watch?v=vLhHyGTkjCs)
 * 🎥 [Recursion: Recursion() — JS Monthly — Lucas da Costa](https://www.youtube.com/watch?v=kGXVsd8pBLw)
 * 🎥 [Recursive Function dalam JavaScript — kudvenkat](https://www.youtube.com/watch?v=uyjsR9eNTIw)
 * 🎥 [What on Earth is Recursion? — Computerphile](https://www.youtube.com/watch?v=Mv9NEXX1VHc)
 * 🎥 [Javascript Tutorial 34: Introduction To Recursion — codedamn](https://www.youtube.com/watch?v=9NO5dXSlbv8)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 24. Collections dan Generators

### Artikel

 * 📜 [ES6 Secara Mendalam: Collections — Jason Orendorff](https://hacks.mozilla.org/2015/06/es6-in-depth-collections/)
 * 📜 [ES6 Collections: Menggunakan Map, Set, WeakMap, WeakSet — Kyle Pennell](https://www.sitepoint.com/es6-collections-map-set-weakmap-weakset/)
 * 📜 [ES6 WeakMaps, Sets, dan WeakSets in Depth — Nicolás Bevacqua](https://ponyfoo.com/Artikel/es6-weakmaps-sets-dan-weaksets-in-depth)
 * 📜 [Pengenalan untuk Sets dalam JavaScript — Alligator.io](https://alligator.io/js/sets-introduction/)
 * 📜 [Pengenalan untuk Maps dalam JavaScript — Alligator.io](https://alligator.io/js/maps-introduction/)
 * 📜 [Map, Set, WeakMap dan WeakSet — JavaScript.Info](https://javascript.info/map-set-weakmap-weakset)
 * 📜 [Maps dalam ES6 - Sebuah Panduan Singkat — Ben Mildren](https://dev.to/mildrenben/maps-in-es6---a-quick-guide-35pk)
 * 📜 [ES6 — Set vs Array — Apa dan Kapan? — Maya Shavin](https://medium.com/front-end-hacking/es6-set-vs-array-what-dan-when-efc055655e1a)
 * 📜 [ES6 — Map vs Object — Apa dan Kapan? — Maya Shavin](https://medium.com/front-end-hacking/es6-map-vs-object-what-dan-when-b80621932373)
 * 📜 [ES6: Bekerja dengan Sets dalam JavaScript — Dead Code Rising](http://www.deadcoderising.com/es6-working-with-sets-in-javascript/)
 * 📜 [Array vs Set vs Map vs Object — Real-time use cases dalam JavaScript (ES6/ES7) — Rajesh Babu](https://codeburst.io/array-vs-set-vs-map-vs-object-real-time-use-cases-in-javascript-es6-47ee3295329b)
 * 📜 [Bagaimana membuat array yang unik dalam JavaScript using Sets — Claire Parker-Jones](https://dev.to/claireparker/how-to-create-an-array-of-unique-values-in-javascript-using-sets-5dg6)
 * 📜 [Apa yang harus anda ketahui tentang ES6 Maps — Just Chris](https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e)
 * 📜 [ES6 Maps yang Mendalam — Nicolás Bevacqua](https://ponyfoo.com/Artikel/es6-maps-in-depth)
 * 📜 [Generator — MDN web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Generator)
* 📜 [Apa itu JavaScript Generators dan bagaimana cara menggunakanya — Vladislav Stepanov](https://codeburst.io/what-are-javascript-generators-dan-how-to-use-them-c6f2713fd12e)
* 📜 [Memahami JavaScript Generators Dengan Contoh  — Arfat Salman](https://codeburst.io/Memahami-generators-in-es6-javascript-with-examples-6728834016d5)
* 📜 [Dasar dari ES6 Generators — Kyle Simpson](https://davidwalsh.name/es6-generators)



 ### Videos

 * 🎥 [JavaScript ES6 / ES2015 Set, Map, WeakSet dan WeakMap — Traversy Media](https://www.youtube.com/watch?v=ycohYSx5h9w)
 * 🎥 [Perbedaan Antara ES6 Maps dan Sets — Steve Griffith](https://www.youtube.com/watch?v=m4abICrldQI)
 * 🎥 [Javascript Generators - MERUBAH SEGALANYA - ES6 Generators Harmony Generators — LearnCode.academy](https://www.youtube.com/watch?v=QO07THdLWQo)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 25. Promises

### Artikel

 * 📜 [Promise — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Referensi/Global_Objects/Promise)
 * 📜 [JavaScript Promises for Dummies ― Jecelyn Yeen](https://scotch.io/tutorials/javascript-promises-for-dummies)
 * 📜 [Memahami promises dalam JavaScript — Gokul N K](https://hackernoon.com/Memahami-promises-in-javascript-13d99df067c1)
 * 📜 [Menjadi Master Wawancara JavaScript : Apa itu Promise? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
 * 📜 [Ikhtisar dari JavaScript Promises — Sandeep Panda](https://www.sitepoint.com/overview-javascript-promises/)
 * 📜 [Bagaimana cara menggunakan Promises dalam JavaScript — Prashant Ram](https://medium.freecodecamp.org/promises-in-javascript-explained-277b98850de)
 * 📜 [Mengimplementasi Promises dalam JavaScript — Maciej Cieslar](https://medium.freecodecamp.org/how-to-implement-promises-in-javascript-1ce2680a7f51)
 * 📜 [JavaScript: Promises dijelaskan dengan analogi dunia nyata yang sederhana — Shruti Kapoor](https://codeburst.io/javascript-promises-explained-with-simple-real-life-analogies-dd6908092138)
 * 📜 [Promises untuk Pemrograman Asynchronous — Exploring JS](http://exploringjs.com/es6/ch_promises.html)
 * 📜 [JavaScript Promises Dijelaskan dengan berjudi di kasino — Kevin Kononenko](https://blog.codeanalogies.com/2018/08/26/javascript-promises-explained-by-gambling-at-a-casino/)
 * 📜 [ES6 Promises: Patterns dan Anti-Patterns — Bobby Brennan](https://medium.com/datafire-io/es6-promises-patterns-dan-anti-patterns-bbb21a5d0918)
 * 📜 [Panduan Singkat ES6 Promises — Brandon Morelli](https://codeburst.io/a-simple-guide-to-es6-promises-d71bacd2e13a)
 * 📜 [_The ES6 Promises_ — Manoj Singh Negi](https://codeburst.io/the-es6-promises-87a979ab27e4)
 * 📜 [ES6 Promises yang Mendalam — Nicolás Bevacqua](https://ponyfoo.com/Artikel/es6-promises-in-depth)
 * 📜 [Bermain dengan Javascript Promises: Pendekatan yang menyeluruh — Rajesh Babu](https://codeburst.io/playing-with-javascript-promises-a-comprehensive-approach-25ab752c78c3)

 ### Videos

 * 🎥 [Mari Belajar ES6 - Promises — Ryan Christiani](https://www.youtube.com/watch?v=vQ3MoXnKfuQ)
 * 🎥 [JavaScript ES6 / ES2015 Promises — Traversy Media](https://www.youtube.com/watch?v=XJEHuBZQ5dU)
 * 🎥 [Promises — Fun Fun Function](https://www.youtube.com/watch?v=2d7s3spWAzo)
 * 🎥 [Error Handling Promises dalam JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=f8IgdnYIwOU)
 * 🎥 [Promises Part 1 - Topics of JavaScript/ES6 — The Coding Train](https://www.youtube.com/watch?v=QO4NXhWo_NM)
 
**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 26. async/await

### Artikel

 * 📜 [async/await — JavaScript.Info](https://javascript.info/async-await)
 * 📜 [Memahami async/await dalam JavaScript — Gokul N K](https://hackernoon.com/Memahami-async-await-in-javascript-1d81bb079b2c)
 * 📜 [Asynchronous Programming — Eloquent JavaScript](https://eloquentjavascript.net/11_async.html)
 * 📜 [Mengoprek Async/Await Functions dalam JavaScript — Alligator.io](https://alligator.io/js/async-functions/)
 * 📜 [Asynchronous Javascript menggunakan async/await — Joy Warugu](https://scotch.io/tutorials/asynchronous-javascript-using-async-await)
 * 📜 [Modern Asynchronous JavaScript dengan async/await — Flavio Copes](https://flaviocopes.com/javascript-async-await/)
 * 📜 [Asynchronous JavaScript: From Callback Hell to Async dan Await — Demir Selmanovic](https://www.toptal.com/javascript/asynchronous-javascript-async-await-tutorial)
 * 📜 [Javascript — ES8 Introducing async/await Functions — Ben Garrison](https://medium.com/@_bengarrison/javascript-es8-introducing-async-await-functions-7a471ec7de8a)
 * 📜 [Bagaimana cara terlepas dari neraka async/await  — Aditya Agarwal](https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)
 * 📜 [Memahami JavaScript’s async await — Nicolás Bevacqua](https://ponyfoo.com/Artikel/Memahami-javascript-async-await)
 * 📜 [JavaScript Async/Await: Serial, Parallel dan Complex Flow — TechBrij](https://techbrij.com/javascript-async-await-parallel-sequence)
 * 📜 [Asynchronous Programming — Exploring JS](http://exploringjs.com/es6/ch_async.html)
 * 📜 [Dari JavaScript Promises menuju Async/Await: Kenapa bother? — Chris Nwamba](https://blog.pusher.com/promises-async-await/)
 * 📜 [Flow Control dalam Modern JS: Callbacks ke Promises ke Async/Await — Craig Buckler](https://www.sitepoint.com/flow-control-callbacks-promises-async-await/)
 * 📜 [JavaScript: Promises dan Kenapa Async/Await Memenangkan Pertarungan — Nick Parsons](https://dzone.com/Artikel/javascript-promises-dan-Kenapa-asyncawait-wins-the-ba)

 ### Videos

 * 🎥 [Async + Await — Wes Bos](https://www.youtube.com/watch?v=9YkUCxvaLEk)
 * 🎥 [Asynchrony: _Under the Hood_ — Shelley Vohr](https://www.youtube.com/watch?v=SrNQS8J67zc)
 * 🎥 [async/await dalam JavaScript - Apa, Kenapa dan Bagaimana — Fun Fun Function](https://www.youtube.com/watch?v=568g8hxJJp4&index=3&list=PL0zVEGEvSaeHJppaRLrqjeTPnCH6)
 * 🎥 [async/await Part 1 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=XO77Fib9tSI&index=3&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)
 * 🎥 [async/await Part 2 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=chavThlNz3s&index=4&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 27. Struktur Data

### Artikel

 * 📜 [Struktur Data dalam JavaScript — Thon Ly](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)
 * 📜 [Algoritma dan Struktur Data dalam JavaScript — Oleksii Trekhleb](https://itnext.io/algorithms-dan-data-structures-in-javascript-a71548f902cb)
 * 📜 [Struktur Data: Objects dan Arrays ― Chris Nwamba](https://scotch.io/courses/10-need-to-know-javascript-concepts/data-structures-objects-dan-arrays)
 * 📜 [Struktur Data dalam JavaScript — Benoit Vallon](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)
 * 📜 [Bermain Dengan Struktur Data dalam JavaScript — Anish K.](https://blog.cloudboost.io/playing-with-data-structures-in-javascript-stack-a55ebe50f29d)
 * 📜 [Panduan Kecil of Queue dalam JavaScript — Germán Cutraro](https://hackernoon.com/the-little-guide-of-queue-in-javascript-4f67e79260d9)
 * 📜 [Semua Algoritma ditulis dengan JavaScript dalam buku 'Algoritma Fourth Edition'](https://github.com/barretlee/algorithms)
 * 📜 [Koleksi dari Paradigma Ilmu Komputer Klasik dalam JavaScript](https://github.com/nzakas/computer-science-in-javascript)
 * 📜 [Semua yang tidak kamu ketahui yang ingin kamu ketahui dari struktur data](https://github.com/jamiebuilds/itsy-bitsy-data-structures)

 ### Videos

 * 🎥 [Algoritma dalam JavaScript — Seth Koch](https://www.youtube.com/watch?v=PylQlISSH8U&list=PLujX4CIdBGCa-65N3uN8CDbUMrYsHBrz-)
 * 🎥 [Algoritma dalam JavaScript | Ace Your Interview — Eduonix Learning Solutions](https://www.youtube.com/watch?v=H_EBPZgiAas&list=PLDmvslp_VR0zYUSth_8O69p4_cmvZEgLa)
 * 🎥 [Struktur Data dan Algoritma dalam JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=Gj5qBheGOEo&list=PLWKjhJtqVAbkso-IbgiiP48n-O-JQA9PJ)
 * 🎥 [Belajar JavaScript Struktur Data dan Algoritma: Sorting — Packt Video](https://www.youtube.com/watch?v=Ymh_AurrMbA)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 28. Expensive Operation dan Big O Notation

### Artikel

 * 📜 [Big O Notation dalam JavaScript — César Antón Dorantes](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)
 * 📜 [Time Complexity/Big O Notation — Tim Roberts](https://medium.com/javascript-scene/time-complexity-big-o-notation-1a4310c3ee4b)
 * 📜 [Big O dalam JavaScript — Gabriela Medina](https://medium.com/@gmedina229/big-o-in-javascript-36ff67766051)
 * 📜 [Big O Pencarian Algoritma dalam JavaScript — Bradley Braithwaite](http://www.bradoncode.com/blog/2012/04/big-o-algorithm-examples-in-javascript.html)
 * 📜 [Time Complexity Analysis dalam JavaScript — Jennifer Bland](https://www.jenniferbland.com/time-complexity-analysis-in-javascript/)
 * 📜 [Algoritma di bahasa Inggris Polos: time complexity dan Big-O Notation — Michael Olorunnisola](https://medium.freecodecamp.org/time-is-complex-but-priceless-f0abd015063c)

### Videos

 * 🎥 [JavaScript: Pengenalan Big O Notation dan Function Runtime — Eric Traub](https://www.youtube.com/watch?v=HgA5VOFan5E)
 * 🎥 [Big O Penting untuk Pengembang JavaScript — Dave Smith](https://www.youtube.com/watch?v=KatlvCFHPRo)
 * 🎥 [Big O Notation - Time Complexity Analysis — WebTunings](https://www.youtube.com/watch?v=ALl86xJiTD8)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 29. Algoritma

### Artikel

 * 📜 [Struktur Data dan Algoritma using ES6](https://github.com/Crizstian/data-structure-dan-algorithms-with-ES6)
 * 📜 [Algoritma dan struktur data implemented dalam JavaScript with explanations dan links to further readings](https://github.com/trekhleb/javascript-algorithms)
 * 📜 [JS: Wawancara Algoritma](http://www.thatjsdude.com/interview/js1.html)
 * 📜 [Algoritma dalam JavaScript — Thon Ly](https://medium.com/siliconwat/algorithms-in-javascript-b0bed68f4038)
 * 📜 [JavaScript Objects, Square Brackets dan Algoritma — Dmitri Grabov](https://medium.freecodecamp.org/javascript-objects-square-brackets-dan-algorithms-e9a2916dc158)
 * 📜 [Atwood's Law applied to CS101 - Classic algorithms dan struktur data diimplementasikan dalam JavaScript](https://github.com/felipernb/algorithms.js)
 * 📜 [Struktur Data dan Algoritma library dalam JavaScript](https://github.com/yangshun/lago)
 * 📜 [Koleksi dari algoritma Ilmu Komputer dan struktur data written dalam JavaScript](https://github.com/idosela/algorithms-in-javascript)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 30. Inheritance, Polymorphism dan Code Reuse

### Artikel

 * 📜 [Class inheritance, super — JavaScript.Info](https://javascript.info/class-inheritance)
 * 📜 [Inheritance dalam JavaScript — MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)
 * 📜 [Inheritance dalam JavaScript — Rupesh Mishra](https://hackernoon.com/inheritance-in-javascript-21d2b82ffa6f)
 * 📜 [Simple Inheritance with JavaScript — David Catuhe](https://www.sitepoint.com/simple-inheritance-javascript/)
 * 📜 [JavaScript — Inheritance, delegation patterns dan Object linking — NC Patro](https://codeburst.io/javascript-inheritance-25fe61ab9f85)
 * 📜 [Object Oriented JavaScript: Polymorphism dengan contoh — Knoldus Blogs](https://blog.knoldus.com/object-oriented-javascript-polymorphism-with-examples/)
 * 📜 [Program Like Proteus — Panduan Pemula untuk _polymorphism_ dalam JavaScript — Sam Galson](https://medium.com/yld-engineering-blog/program-like-proteus-a-beginners-guide-to-polymorphism-in-javascript-867bea7c8be2)
 * 📜 [_Object-oriented_ JavaScript: Menyelam Lebih Dalam ke ES6 Classes — Jeff Mott](https://www.sitepoint.com/object-oriented-javascript-deep-dive-es6-classes/)

  ### Videos

 * 🎥 [Inheritance dalam JavaScript — kudvenkat](https://www.youtube.com/watch?v=yXlFR81tDBM)
 * 🎥 [JavaScript ES6 Classes dan Inheritance — Traversy Media](https://www.youtube.com/watch?v=RBLIm5LMrmc)
 * 🎥 [Polymorphism dalam JavaScript — kudvenkat](https://www.youtube.com/watch?v=zdovG9cuEBA)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 31. Design Patterns

### Artikel

 * 📜 [4 JavaScript Design Patterns Anda Harus Ketahui — Devan Patel](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know)
 * 📜 [JavaScript Design Patterns – Panduan Pemula untuk Mobile Web Development — Soumyajit Pathak](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15)
 * 📜 [JavaScript Pola Desain — Akash Pal](https://medium.com/front-end-hacking/javascript-design-patterns-ed9d4c144c81)
 * 📜 [Javascript Pola Desain: Apa itu & Bagaimana Cara Menggunakanya — Patrick Simpson](https://seesparkbox.com/foundry/javascript_design_patterns)
 * 📜 [JavaScript Pola Desain: Memahami Pola Desain dalam JavaScript - Sukhjinder Arora](https://blog.bitsrc.io/Memahami-design-patterns-in-javascript-13345223f2dd)
 * 📜 [Semua 23 (GoF) Pola Desain diimplementasikan dalam JavaScript — Felipe Beline](https://github.com/fbeline/Design-Patterns-JS)
 * 📜 [Belaja JavaScript Pola Desain — Addy Osmani ](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)


  ### Videos

 * 🎥 [JavaScript Pola Desain — Udacity](https://www.udacity.com/course/javascript-design-patterns--ud989)
 * 🎥 [JavaScript Pola untuk 2017 — Scott Allen](https://www.youtube.com/watch?v=hO7mzO83N1Q)

 **[⬆ Kembali ke Atas](#daftar-isi)**

---

## 32. Partial Applications, Currying, Compose dan Pipe

### Artikel

 * 📜 [Menggunakan function composition dalam JavaScript — Rémi](https://www.codementor.io/michelre/use-function-composition-in-javascript-gkmxos5mj)
 * 📜 [Currying dalam JavaScript ES6 — Adam Bene](https://blog.benestudio.co/currying-in-javascript-es6-540d2ad09400)
 * 📜 [Composition dan Currying Elegance dalam JavaScript — Pragyan Das](https://medium.com/@pragyan88/writing-middleware-composition-dan-currying-elegance-in-javascript-8b15c98a541b)
 * 📜 [Functional JavaScript: Function Composition Untuk Penggunaan Sehari-hari — Joel Thoms](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)
 * 📜 [Functional Composition: compose() dan pipe() — Anton Paras](https://medium.com/@acparas/what-i-learned-today-july-2-2017-ab9a46dbf85f)
 * 📜 [Kenapa The Hipsters _Compose_ Segalanya: Functional Composing dalam JavaScript — A. Sharif](http://busypeoples.github.io/post/functional-composing-javascript/)
 * 📜 [Pengenalan yang Lembut untuk Functional JavaScript pt III: Functions untuk membuat functions — James Sinclair](https://jrsinclair.com/Artikel/2016/gentle-introduction-to-functional-javascript-functions/)
 * 📜 [Curry And Compose (Kenapa kamu seharusnya menggunakan sesuatu yang seperti ramda dalam kode anda) — jsanchesleao](https://jsleao.wordpress.com/2015/02/22/curry-dan-compose-Kenapa-you-should-be-using-something-like-ramda-in-your-code/)
 * 📜 [Function Composition dalam JavaScript dengan Pipe — Andy Van Slaars](https://vanslaars.io/post/create-pipe-function/)
 * 📜 [Practical Functional JavaScript dengan Ramda — Andrew D'Amelio, Yuri Takhteyev](https://developer.telerik.com/featured/practical-functional-javascript-ramda/)
 * 📜 [Keindahan dalam Partial Application, Currying, dan Function Composition — Joel Thoms](https://hackernoon.com/the-beauty-in-partial-application-currying-dan-function-composition-d885bdf0d574)
 * 📜 [Curry atau Partial Application? — Eric Elliott](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8)
 * 📜 [Partial Application dalam JavaScript — Ben Alman](http://benalman.com/news/2012/09/partial-application-in-javascript/)
 * 📜 [Partial Application dari Functions — Functional Reactive Ninja](https://hackernoon.com/partial-application-of-functions-dbe7d9b80760)
 * 📜 [Currying vs Partial Application — Deepak Gupta](https://codeburst.io/javascript-currying-vs-partial-application-4db5b2442be8)
 * 📜 [Partial Application dalam ECMAScript 2015 — Ragan Wald](http://raganwald.com/2015/04/01/partial-application.html)
 * 📜 [Functional Composition dalam JavaScript — Joe Cortopassi](https://joecortopassi.com/Artikel/functional-composition-in-javascript/)
 * 📜 [So You Want to be a Functional Programmer pt. I — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
 * 📜 [So You Want to be a Functional Programmer pt. II — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-2-7005682cec4a)
 * 📜 [So You Want to be a Functional Programmer pt. III — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-3-1b0fd14eb1a7)
 * 📜 [So You Want to be a Functional Programmer pt. IV — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-4-18fbe3ea9e49)
 * 📜 [So You Want to be a Functional Programmer pt. V — Charles Scalfani](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-5-c70adc9cf56a)
 * 📜 [Functional-Light JavaScript Chapter 3: Managing Function Inputs — Kyle Simpson](https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch3.md)
 * 📜 [Pengenalan prinsip dasar dari Functional Programming — TK](https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84)

  ### Videos

 * 🎥 [Compose vs Pipe: Functional Programming dalam JavaScript — Chyld Studios](https://www.youtube.com/watch?v=Wl2ejJOqHUU)
 * 🎥 [JavaScript Functional Programing: Compose — Theodore Anderson](https://www.youtube.com/watch?v=jigHxo9YR30)
 * 🎥 [Function Composition - Functional JavaScript — NWCalvank](https://www.youtube.com/watch?v=mth5WpEc4Qs)
 * 🎥 [JavaScript Function Composition Dijelaskan — Theodore Anderson](https://www.youtube.com/watch?v=Uam37AlzPYw)
 * 🎥 [Mari koding dengan function composition — Fun Fun Function](https://www.youtube.com/watch?v=VGB9HbL1GHk)
 * 🎥 [Partial Application vs. Currying — NWCalvank](https://www.youtube.com/watch?v=DzLkRsUN2vE)
 * 🎥 [JavaScript Partial Application — Theodore Anderson](https://www.youtube.com/watch?v=jkebgHEcvac)

**[⬆ Kembali ke Atas](#daftar-isi)**

---

## 33. Clean Code

### Artikel

 * 📜 [Clean Code konsep diadaptasi untuk JavaScript — Ryan McDermott](https://github.com/ryanmcdermott/clean-code-javascript)
 * 📜 [JavaScript Clean Coding _Best Practices_ — András Tóth](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)
 * 📜 [Function parameters dalam JavaScript Clean Code — Kevin Peters](https://medium.com/@kevin_peters/function-parameters-in-javascript-clean-code-4caac109159b)
 * 📜 [Clean Code JavaScript — Sarah Drasner](https://css-tricks.com/clean-code-javascript/)
 * 📜 [Menjaga kode anda tetap rapih — Samuel James](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)
 * 📜 [Best Practices untuk menggunakan Syntax JavaScript Modern   — M. David Green](https://www.sitepoint.com/modern-javascript-best-practices/)

### Videos
*  🎥 [JavaScript Pro Tips - Koding ini, BUKAN itu](https://www.youtube.com/watch?v=Mus_vwhTCq0)

 **[⬆ Kembali ke Atas](#daftar-isi)**

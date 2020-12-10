---
marp: true
theme: gaia
size: 4K
class: default
paginate: true
footer: @asm0di0 &emsp13;&emsp13;@khudobakhshov
backgroundImage: "linear-gradient(to bottom, #000 0%, #1a2028 50%, #293845 100%)"
color: white
title: Noname
---
<!--
_class: lead
_paginate: false
_footer: ""
-->

<style>
footer {
    display: table
}
.hljs-variable { color: lightblue }
.hljs-string { color: lightgreen }
.hljs-params { color: lightpink }
</style>

# Kotlin for Apache Spark:
# Зачем миру ещё один API

---
<!--
_class: lead
-->

# <!-- fit --> На чём пишут под Spark?

---

<!--
_class: lead
-->

# <!-- fit --> Python

---

<!--
_class: lead
-->

# <!-- fit --> Java

---

<!--
_class: lead
-->

# <!-- fit --> Scala

---

# А ещё

- R (два API)
- C#
- Haskell
- JS (with GraalVM)
- *YouNameIt*

---

<!--
_class: lead
-->

# <!-- fit --> Кто использует

---

# Кто использует

- Дата иженеры
- Дата аналитики
- Дата саентисты


Для всех кроме дата инженеров Python — популярный выбор

---

<!--
_class: lead
-->

# <!-- fit --> Почему Python?

---

<!--
_class: lead
-->

# <!-- fit --> А почему бы и нет?

---

<!--
_class: lead
-->

# <!-- fit --> А что там насчёт R?

---

<!--
_class: lead
-->

# <!-- fit --> А что не так со Scala?

---

<!--
_class: lead
-->

# <!-- fit --> Если всё устраивает — всё так!

---
<!--
_class: lead
-->

![w:1120](images/scala_implicit.png)

Просто `sum` не работает

---
<!--
_class: lead
-->

![w:1120](images/kotlin_ext.png)

Есть в стандатной библиотеке


---
<!--
_class: lead
-->

![w:1120](images/types-hier.png)

---

<!--
_class: lead
-->

![w:1120](images/join.png)



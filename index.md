---
marp: true
theme: gaia
size: 4K
class: default
paginate: true
footer: @asm0di0 &emsp13;&emsp13;@khudobakhshov
backgroundImage: "linear-gradient(to bottom, #000 0%, #1a2028 50%, #293845 100%)"
color: white
title: Kotlin API for Apache Spark
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

Паша Финкельштейн, Виталий Худобахшов
JetBrains

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

# <!-- fit --> А если мы уже пишем на Java?

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
# Type-safe builders
![h:400](images/typesafe.png)

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

---

<!--
_class: lead
-->

![w:1120](images/withspark.png)


---

<!-- _class: lead -->

![h:600](images/withcached.png)

---
<!-- _class: lead -->

# <!-- fit --> Что было сложно

---

# Что не работает

- Поддержка массивов
- UDF не всегда
- Spark 2 (уже скоро)

---

<!-- _class: lead -->

# <!-- fit --> ki-shell

[Kotlin/kotlin-interactive-shell](https://github.com/Kotlin/kotlin-interactive-shell)

---

# Итоги

- Kotlin подходит для дата инжинеров!
- Может работать как первый язык
- Его поддерживает наша любимая IDE

---
<!-- _class: lead -->
# <!-- fit --> Спасибо!

[JetBrains/kotlin-spark-api](https://github.com/JetBrains/kotlin-spark-api)
# Одна цель один селектор

Цели которые вы сможете достичь, при использования данной системы:

-  Cделать работу со стилями удобной для разработчика.
-  Сделать проекты гибкими и модульными, чтобы правки по сайтам вносились без хлопот и легко.
-  Предотвратить бесконечный процесс раздутия css стилей най сайте.
-  С этой системой можно избегать недостатков языка CSS, в своих больших проектах.
-  Превратите обычную традиционную верстку в компонентную верстку, без использования JS фреймворков.
-  Сможете разделять структурные стили от стилей, которые выполняют роль верхней одежды, которая на каждом сайте можно поменять без ущерба структуре.
-  Не зная всех селекторов в проекте, сможете различать в любом своем проекте с данной системой родные стили проекта и стили которые добалены CMS и плагинами. 
- Сохранить долгую жизнь вашему Проекту. Ведь после каждой правки многие бюджетные проекты, получают дополнительные дублирующик куски кода с маленькими изменениями и этот процесс повторяется до тех пор пока сайт не начнет медлено работать в браузерах от обилия руководства по стилям.

---

В первую очередь это Не Фреймворк. А система которую можно использовать и сделать под себя. Но все же для создания общих стандартов. Прошу вас придерживаться главных принципах данной системы.

## Принцип Использование Префиксов.

- **bm_**  -  [bm_ - Классы](bm_-Классы.md)
- **ut_**
- **js_**

Префиксы нужны, чтобы мы могли увидеть какие стили относятся, к самому проекту и отличить стили, которые были добавленны CMS или различными плагинами или библиотеками. Я разделил классы на 2 группы:

-  Тип ( **bm_** ) -  классы компонентные. Это те классы которые можно взять вместе компонентом, и компонент встроится в любое другое удобное место на сайте. 
2.  Тип ( **ut_** ) - классы утилитные( вспомогательные ). Мы удаляем их с компонента. Если нужно перенести компонент в другое место на сайте. И эти классы помогают нам добовлять те свойства компоненту, чтобы встроить его визуально в окружающее среду данного контейнера или данной страницы на сайте.
3. Тип (  **js_**  ) - классы которые использует JS скрипты. Их нельзя использовать для стилей.

---
## Документация и Проект еще дорабатываются, Пишу в свободное время.
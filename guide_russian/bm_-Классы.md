# bm_ - Классы

> В нашей жизни технологии так быстро развиваются, что мы не успеваем оценить по достоинству старые технологии. И возможно они бы решили, часть наших задач, которые мы до сих пор не можем решить.

Одна из таких Технологий, которая не была оценена по достоинству - это методология BEM.  Но возможно заметили, что классы в системе "one Task one Selector " разделены на категории.  Система BEM не смогла решить всех проблем, но принципы которые были заложены в этой методологии, достойны на то, чтобы мы их могли применять и тем самым облегчать жизнь разработчика себе и нашим колегам по работе.

- bm_ + ИмяКласса
- bm_ + ИмяКласса + __ имяЗависимогоКласса

- bm_ + ИмяКласса + -- модификатор
- bm_ + ИмяКласса +  __ имяЗависимогоКласса + -- модификатор

> Одна Задача - один Селектор - означает также мы будем использовать селектор в одном месте. И даже не будем его прописывать в Медиа Запроссах.
> 
> Для Медия Запроссах создаем отдельный модификатор, с отдельными  зарезерированными суффиксами 

- bm_ + ИмяКласса + -- sm
- bm_ + ИмяКласса + __ имяЗависимогоКласса  + -- sm
- bm_ + ИмяКласса + -- модификатор + -- sm
- bm_ + ИмяКласса +  __ имяЗависимогоКласса + -- модификатор + -- sm

Ввиды модификаторов Медия Запросов
- xs
- sm
- md
- lg
- xl
- xxl

> Такие именнования Медия Запросов задал Bootstrap. Сегодня они широко применяются, поэтому нет смысла их менять. 

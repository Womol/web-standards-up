# Я.Cубботник по фронтенду

## 2015-10-17, Москва, Россия

### Список докладов

1. [Роль разработчика интерфейсов в продукте](#talk-1), Сергей Сергеев. ([Страница доклада](https://events.yandex.ru/lib/talks/3204/))
2. [bem-components — как Bootstrap, только лучше](#talk-2), Владимир Гриненко. ([Страница доклада](https://events.yandex.ru/lib/talks/3205/))
3. [Мгновенная Морда](#talk-3), Иван Карев. ([Страница доклада](https://events.yandex.ru/lib/talks/3207/))
4. [Эксперимент как инструмент для принятия решений](#talk-4), Виктор Карпов. ([Страница доклада](https://events.yandex.ru/lib/talks/3208/))
5. [Приручаем SVG](#talk-5), Лев Солнцев. ([Страница доклада](https://events.yandex.ru/lib/talks/3210/))
6. [Производительность WebGL приложений](#talk-6), Кирилл Дмитренко. ([Страница доклада](https://events.yandex.ru/lib/talks/3211/))
7. [Создание модулей для API Яндекс.Карт](#talk-7), Всеволод Шмыров. ([Страница доклада](https://events.yandex.ru/lib/talks/3213/))
8. [API как древнеримский акведук](#talk-8), Сергей Константинов. ([Страница доклада](https://events.yandex.ru/lib/talks/3214/))

### Видео-запись трансляции

[Запись на YouTube](https://www.youtube.com/watch?v=8GRtCC3lVN0).

### Лог твиттер-трансляции

Доброе утро, совсем скоро мы начнем трансляцию с [#yasubbotnik](https://twitter.com/search?q=%23yasubbotnik). Вот вам фото для затравки. [pic.twitter.com/R4zLhwFWUS](http://t.co/R4zLhwFWUS)

![](https://pbs.twimg.com/media/CRgWRZnWUAAWqrs.jpg)

Программа [#yasubbotnik](https://twitter.com/search?q=%23yasubbotnik) на сайте [events.yandex.ru/events/yasubbo…](https://t.co/nJ8SXY1n8X "https://events.yandex.ru/events/yasubbotnik/17-october-2015/#program") \(ну вы и сами знаете\). Или можете поглядывать на эту фотку. [pic.twitter.com/gvIlD2Sr8O](http://t.co/gvIlD2Sr8O)

![](https://pbs.twimg.com/media/CRgXmGRWcAAB4tn.jpg)

Виталий Харисов [@harisov](https://twitter.com/harisov "Vitaly Harisov") открывает [#yasubbotnik](https://twitter.com/search?q=%23yasubbotnik). Презентации будут на сайте одновременно с докладами. [pic.twitter.com/jgeZMbJ57f](http://t.co/jgeZMbJ57f)

![](https://pbs.twimg.com/media/CRgfJg8WoAAXKqS.jpg)

<a id="talk-1"></a> Первый доклад — Сергей Сергеев [@gurugray](https://twitter.com/gurugray "Sergey Sergeev"). «Роль разработчика интерфейсов в продукте»

Команда поиска очень сильно захотела релизиться часто. Но при этом сохранить качество.

Интерфейс — лицо продукта. 

Первое, что подверглось оптимизации — регламент работ \(оптимизация длинного релизного цикла\). 

Тестирование конечного релиза могло занимать неделю. Если находили баг — процесс повторялся. 

Как результат длинного релизного цикла — невозможно прогнозировать нагрузку на разработчиков и тестировщиков. 

RT [@SirAlexRus](https://twitter.com/SirAlexRus "Sir_Alex"): Боль субботы\)\)\)  [pic.twitter.com/q2qD9eGyhD](http://t.co/q2qD9eGyhD)

![](https://pbs.twimg.com/media/CRgfdEJWoAAMNJC.jpg)

Изначально использовался [#gitflow](http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/), но через полгода его несколько изменили 

Результат — переход к коротким, до 1 дня, релизам 

Тестирования не стало меньше, но тесты стали размазаны по всему процессу разработки. Автотесты перед PR, например 

Все пулл-риквесты проходят ревью. В общем, вы все всё делалете правильно, если делаете есть ревью пулл-риквестов. 

Поиск в Турции использует Scrum. Эксперимент получился. Всем понравилось и решили переносить на другие команды. 

Секция вопросов.   
— Откуда берутся идеи для новых фич в продукте?  
— Любой член команды может предложить свою. 

— Используется ли A/B тестирование?  
— Да, все фичи проходят такие тесты на части аудитории. И будет ещё доклад про это на 

— Такой процесс накладывает больше ответственности на разработчика. Как быть?  
— Узкая специализация — это плохо. Мы вернули режим стартапа.

Мы стали быстрее получать больше маленьких качественных фич.

Фича попадает в дев под feature-флагами, которую можно выкатить в A/B тесты из админки.

— Сколько у вас unit-тестов?  
— Много, мы стараемся покрывать большую часть важного функционала. 

Часть фич покрывается gemini-тестами. 

PDF доклада Сергея — [yadi.sk/i/40bZ3iA4jo2pb](https://t.co/qLsbMJtMYf "https://yadi.sk/i/40bZ3iA4jo2pb") 

GitFlow многим не подходит, он очень сложный. 

<a id="talk-2"></a> Второй доклад. Владимир Гриненко [@tadatuta](https://twitter.com/tadatuta "Vladimir Grinenko") «bem-components — как Bootstrap, только лучше»  [events.yandex.ru/lib/talks/3205/](https://t.co/kbw9fnwXJc "https://events.yandex.ru/lib/talks/3205/")

Web Components — будущее веба. Всем нравится. Все выпускают свои библиотеки компонент. 

«Мы делали универсальные компоненты, когда это ещё не было мейнстримом» 

RT [@tadatuta](https://twitter.com/tadatuta "Vladimir Grinenko"): Мурся, с Днем рождения! [#твитдлямурси](https://twitter.com/search?q=%23твитдлямурси) 

Все придумано давно. [pic.twitter.com/DC1zAJVvRB](http://t.co/DC1zAJVvRB)

![](https://pbs.twimg.com/media/CRgnhBmWsAAyf5-.jpg)

Вот такие есть готовые компоненты от Яндекса. Как бустрап, только на [#b\_](https://twitter.com/search?q=%23b_) [ru.bem.info/libs/bem-compo…](https://t.co/tVqpeImGhp "https://ru.bem.info/libs/bem-components/v2.3.0/showcase/") 

Всё это можно уже подключить с CDN, или из бовера, или npm. 

$ bower install bem-components-dist  
$ npm i bem-components-dist  
[github.com/bem/bem-compon…](https://t.co/EKbItl66I1 "https://github.com/bem/bem-components-dist")  


Ну и чем оно лучше, чем Bootstrap?  
Во-первых, оно свёрстано по bem.  


Сверстано по [#b\_](https://twitter.com/search?q=%23b_) — значит стили изолированы и подключение библиотеки скорее всего ничего не сломает в вёрстке.

Темы для компонентов можно легко отстрелить, в отличие от бутстрапа. 

Почему бутстрап скорее плохо, чем хорошо. [gist.github.com/iAdramelk/d328…](https://t.co/0Bv0qKQrq3 "https://gist.github.com/iAdramelk/d328b73c72cab92ef95f") 

Дропдаун бустрапа убивается обёрткой с overflow: hidden Дропдаун от bem-components продолжает работать, работать и работать 

Другие особенности:  
— Кроссплатформенность  
— Доступность  
— Декларативные шаблоны  


Есть тесты не только на JS, но и тесты на шаблоны, и тесты на вёрстку. Всё прогоняется через CI 

Недостатки bem-components:  
— Нет сеток, например  
— Кода больше, потому что нужна надёжность  
— Меньше популярность  


Вопросы:  
— Я вот прикручу всё это на сайт — и он станет выглядеть как Яндекс?  
— Тему всегда можно отодрать и переписать.  


Тему нельзя настраивать переменными из стайлуса. Так задумано изначально, тему нужно скопировать и переписать под себя, а не переопределять.

ПДФ со слайдами доклада про bem-components [yadi.sk/i/8xl3Dpxbjo3gJ](https://t.co/daSqT2c7iX "https://yadi.sk/i/8xl3Dpxbjo3gJ")

— Вот мы хотим использовать bem-components, но для этого нужно изучить [#b\_](https://twitter.com/search?q=%23b_) и вот это вот всё. Что посоветуете?  
— [ru.bem.info](http://t.co/PPriiTVd8Q "http://ru.bem.info/")

Готовая сборка из двух файлов — это реальный прорыв c 2011 года, раньше надо было ставить ноду, настраивать сборку — радуется [@dkushnikov](https://twitter.com/dkushnikov "Dmitry Kushnikov")

Наброшу от себя — bem-components всё-таки нарушает пункт 3 из этого списка [gist.github.com/iAdramelk/d328…](https://t.co/6jAQBEPt7Y "https://gist.github.com/iAdramelk/d328b73c72cab92ef95f#")Что-делает-bootstrap

<a id="talk-3"></a> Следующий доклад — «Мгновенная Морда» от Ивана Карева. [events.yandex.ru/lib/talks/3207/](https://t.co/NojIsRlZyK "https://events.yandex.ru/lib/talks/3207/") 

В Москве — всё хорошо, а вот в далёком Нарьян-Маре страница может открываться десятки секунд 

Первый подход — пререндеринг, который есть в Хроме, например. 

недостатки – пользователь может на страницу и не пойти, а ресурсы уже потрачены. 

Второй подход – расширение для браузера. 

Недостатки — всё равно есть задержки в 100-150 мс, когда показывается белый экран. 

Третий подход — использовать его в экстеншене. 

Примерная схема работы  [pic.twitter.com/KPeRGiaepp](http://t.co/KPeRGiaepp)

![](https://pbs.twimg.com/media/CRg1ElCWcAA6cWw.jpg)

Доклад — очень интересный, но очень сложно вычленять детали в виде твитов. Скоро будет видео, посмотрите. 

ПДФ презентации «Мгновенная Морда» [yadi.sk/i/MuU7kaQrjnwXY](https://t.co/G5aQt8ocQU "https://yadi.sk/i/MuU7kaQrjnwXY") 

Итог — время получения первого байта не зависит от того, где географически расположен пользователь. 

Тот самый несчастный пользователь из Нарьян-Мара теперь получает страницу не через 20 с, а через 4 с. 

Вопросы:  
— Есть ли примеры этого расширения в открытом доступе?  
— Нет, потому что всё это практически невозможно сделать на других сайтах.

— Можно ли написать такое же расширение для другого сайта?  
— Доступ к записи кеша доступно только для этого расширения. 

<a id="talk-4"></a> Следующий доклад: «Эксперимент как инструмент для принятия решений» от Виктора Карпова [events.yandex.ru/lib/talks/3208/](https://t.co/0aKydJooAe "https://events.yandex.ru/lib/talks/3208/")

Промо-страница — это всегда компромисс 

Какая страница лучше? Первая \(красивая\)  или вторая \(быстрая\)?  [pic.twitter.com/OnAMb2YrJl](http://t.co/OnAMb2YrJl)

![](https://pbs.twimg.com/media/CRg7CtlWsAEoQJY.png)

Нужно определить задачи и метрики, и плясать уже от них 

Вопрос — нужно ли видео на промо-странице 

A/B тест — одним показываем видео, другим — нет. 

Важно:  
— обеспечить однородность выборки  
— всегда показываем одну и туже версию  
— не показываем видео на слабом канале. 

Также важно выбрать правильную длительность эксперимента, чтобы избежать шума. Было выбрана длительность в 1 месяц 

Результат — вариант без видео принёс больше новых пользователей, что было несколько неожиданно. 

Эксперимент 2 — как зависит CTR от веса страницы. Ожидаем вот такой график  [pic.twitter.com/RupAovYUz7](http://t.co/RupAovYUz7)

![](https://pbs.twimg.com/media/CRg8kIcWsAApHPh.png)

А может быть так, или вообще вот так  [pic.twitter.com/9q3eM66pMw](http://t.co/9q3eM66pMw)

![](https://pbs.twimg.com/media/CRg82XNWsAACojo.png)

Но второй эксперимент пока что не проводился, поэтому ответа на него нет :\( 

Хочется проводить эксперименты, а не доверять своим гипотезам. 

— Какой объем трафика \(кол-во пользователей\), для успешного эксперимента.  
— Мы ждём, пока «приборы» \(графики\) успокоятся. 

У нас перерыв на обед, вы тоже перекусите  [pic.twitter.com/tTpLn0Qh97](http://t.co/tTpLn0Qh97)

![](https://pbs.twimg.com/media/CRhAkdDXIAAwbm7.png)

<a id="talk-5"></a> Первый доклад после перерыва — «Приручаем SVG» от Льва Солнцева. [events.yandex.ru/lib/people/147…](https://t.co/VEGDSg2SOn "https://events.yandex.ru/lib/people/1470140/") 

Несмотря на то, что это вектор — всё равно всё рендерится в пикселы. Поэтому нужно следить за привязкой к сетке. 

Контуры в SVG — это просто.  [pic.twitter.com/8YE4aioeyk](http://t.co/8YE4aioeyk)

![](https://pbs.twimg.com/media/CRhRXkcW0AANlcf.png)

Зачем знать, как всё это устроено внутри? Можно делать довольно серьёзные оптимизации.  [pic.twitter.com/irsaDMBrxn](http://t.co/irsaDMBrxn)

![](https://pbs.twimg.com/media/CRhRq4eWoAAVcr7.png)

В новом svgo обещают сделать подобные оптимизации. 

&lt;use&gt; + fill="currentColor" = Удобные реиспользуемые иконки  [pic.twitter.com/coplu7hqkF](http://t.co/coplu7hqkF)

![](https://pbs.twimg.com/media/CRhSqpXWEAEUdnO.png)

В xlink:href="[#pin](https://twitter.com/search?q=%23pin)" могуть быть ссылки только на элементы текущей страницы. Почему? Потому что IE, вот почему. 

У svg есть много недостатков. Но всё станет лучше в SVG v2: меши, штриховка, нормальная работа с текстом — вот это всё. 

PDF со слайдами презентации про SVG — [yadi.sk/i/PWTXripojo7qR](https://t.co/P81KdSfbTp "https://yadi.sk/i/PWTXripojo7qR") 

Ссылки для почитать и посмотреть — на последних двух страницах в PDF.  [pic.twitter.com/wSW5MwcbNm](http://t.co/wSW5MwcbNm)

![](https://pbs.twimg.com/media/CRhULucWwAE_r1P.png)

<a id="talk-6"></a> Кирилл Дмитренко расскажет про Производительность WebGL приложений 

Людей, у которых WebGL в продакшне больше, чем тех, у кого он используется в pet-projects. 

И вот вам сразу ссылка на презентацию Производительность WebGL приложений [yadi.sk/i/sjcw4yT8jo4AD](https://t.co/9c0s4eLAFP "https://yadi.sk/i/sjcw4yT8jo4AD")

Основы WebGL можно показать на вот такой, старой как мир, картинке  [pic.twitter.com/O0geFCMwf1](http://t.co/O0geFCMwf1)

![](https://pbs.twimg.com/media/CRhW1SxWIAAwRgn.png)

Профилирование WebGL осложняет то, что часть функций синхронная, часть асинхронная, а часть вызывают неявную синхронизацию всего контекста.

Измерение производительности WebGL упрощает расширение EXT\_disjoint\_timer\_query. 

Это расширение позволяет видеть то, что не может показать профайлер. 

Рекомендации по опитимизации WebGL.  [pic.twitter.com/N1K75VBB2r](http://t.co/N1K75VBB2r)

![](https://pbs.twimg.com/media/CRhYN6bWUAAPDM4.png)

Результат оптимизации — был 200мс, стало 2мс и почти нет нагрузки на CPU. 

Может быть и такое, что тормозит не WebGL, а код вокруг  — Dom, обработка событий и т.п. 

Рекомендации по оптимизации WebGL на одном слайде.  [pic.twitter.com/rIPuK0DXAL](http://t.co/rIPuK0DXAL)

![](https://pbs.twimg.com/media/CRhZfdNXAAES5wy.png)

Демки — [clck.ru/9bKNn](http://t.co/9Mms6KYWYI "http://clck.ru/9bKNn"), работают только в последнем Chrome Canary. 

Вопросы:  
— А зачем это вообще всё?  
— Игры, 3D-модели в браузере, карты.  


— Есть ли аналоги WebGL?  
— Flash и другие плагины, которые либо сдохли, либо на пути к этому.  


Очень сложный вопрос от [@jsunderhood](https://twitter.com/jsunderhood "Разработчик"), мне сложно его записать в 140 символов. 

Какие там дистилляционные шейдеры, вы о чём вообще? Ответ про WebGL2. 

Основное применение WebGL в Я.картах — движок панорам. 

— Сколько человек в Яндексе занимаются WebGL?  
— Примерно в два раза больше, чем вы видите сейчас на сцене. 

Также про WebGL рассказывается в докладе от [@Lik04ka](https://twitter.com/Lik04ka "Климова Василика") на [#wstdays](https://twitter.com/search?q=%23wstdays) [youtube.com/watch?v=V7bnSO…](http://t.co/qse6hLUDKg "http://www.youtube.com/watch?v=V7bnSOwuO4M#"), метка на 03:21:57.

<a id="talk-7"></a> Начинается последний блок докладов — «Создание модулей для API Яндекс.Карт», Всеволод Шмыров. PDF — [yadi.sk/i/ahyaC1\_xjnwXi](https://t.co/TC3Hg0P0LP "https://yadi.sk/i/ahyaC1_xjnwXi") 

— Зачем модули от сторонних разработчиков нам \(картам\)?  
— У нас не безграничное число разработчиков.  


Всё началось с перехода на модульную асинхронную  загрузку зависимостей в Я.Картах в 2.1. 

В основе модульной системы — ymodules [github.com/ymaps/modules](https://t.co/gQDybWUHZ4 "https://github.com/ymaps/modules") 

— Кто работал с ymodules? О, я думал вообще никто не работал! 

Основное отличие ymodules от requirejs — инициализация модуля можно сделать в любой момент времени, а не при объявлении модуля. 

Возможность создания собственных модулей в картах можно было сделать давно, но мы решили подождать и сделать всё лучше. 

Недостатки подключения модулей — нужно руками указывать url к модулю и настройка пространства имён. 

Полезные гет-параметры апи карт:  
— lang — язык карт  
— coordOrder — порядок координат  
— mode — включение дебаг-режима. 

coordOrder=longlat позволяет использовать тот же порядок координат, который используют некоторые другие \(ну, вы поняли\) провайдеры карт.

Также есть свой сборщик проектов на ymodules, работает на основе Gulp. [github.com/yandex/ymb](https://t.co/3F9ORu3BMu "https://github.com/yandex/ymb") 

Полезные сторонние модули для [github.com/yandex/mapsapi-](http://t.co/nDTwWVmoow "http://github.com/yandex/mapsapi-") heatmap — тепловые карты, [github.com/yandex/ymaps-p…](http://t.co/DAIuXYcYd2 "http://github.com/yandex/ymaps-pie-") chart-clusterer — понятные кластеры.

— Почему первичный загрузчик не выложить на другой CDN, не от Яндекса?  
— На самом деле, мы думаем об этом, но не прямо сейчас. 

Если вы хотите скрестить bem с реактом — можете посмотреть на эту организацию [github.com/yummies](https://t.co/EnmC4VdqRM "https://github.com/yummies") 

<a id="talk-8"></a> Последний доклад на сегодня: API как древнеримский акведук, Сергей Константинов. PDF — [yadi.sk/i/yY6dvHr8jnwXr](https://t.co/s684EjWSUM "https://yadi.sk/i/yY6dvHr8jnwXr") 

АПИ — это обязательство связать два контекста. 

Акведук. Ему 2000 лет и он всё ещё работает. Также должен работать хорошо спроектированный API.  [pic.twitter.com/5Fe5qbKATI](http://t.co/5Fe5qbKATI)

![](https://pbs.twimg.com/media/CRhl5CbXIAEVBln.png)

Нужно делать так, чтобы задачи пользователей решались максимально просто. 

А также нужно делать так, чтобы можно было поменять внутренности системы, а интерфейс апи оставался прежним. 

— Не заставляйте людей писать лишний код  
— Частые действия должны иметь шорткат  
— Не давайте доступа к внутренней реализации. 

По настоящему хороший API должен продолжать работать с течением времени. Обратная совместимость — это важно. 

Цена стабильности в будущем — нужно на старте заложиться на функции, которые, возможно, появятся в будущем. 

Но, скорее всего, ваш API уже написан, в нём есть ошибки и нужно просто записать их в блокнотик и жить с этим до следующего мажорного релиза

Как подсказывает [@alexbaumgertner](https://twitter.com/alexbaumgertner "alexbaumgertner") — если вы не смогли посмотреть трансляцию — просто отмотайте назад [youtube.com/watch?v=8GRtCC…](https://t.co/NBFZByIbfj "https://www.youtube.com/watch?v=8GRtCC3lVN0") 

Яндекс-карты поддерживают несколько пресетов для пользователей с различными нарушениями цветовосприятия. 

На этом мы завершаем нашу трансляцию. С вами был [@\_h4\_](https://twitter.com/_h4_ "Михаил Баранов"). Лог трансляции будет совсем скоро будет на гитхабе.
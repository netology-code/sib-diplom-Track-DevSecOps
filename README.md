# Дипломная работа профессии «Специалист по информационной безопасности»

## Track DevSecOps

### Задача

Ваша задача — создать безопасный пайплайн для open-source проекта. Он должен включать в себя статический анализатор, динамический анализатор, чекеры безопасности, Security Gateway и документацию процесса. 

Вы должны сами выбрать проект, для которого будет выстроен пайплайн. Платформа для организации CI/CD тоже на ваш выбор. Рекомендуем взять за основу GitLab CI/CD, GitHub Actions, CircleCI. Сервер для разворачивания даёт дипломный руководитель или методист в виде VPS.  

### Исходные данные
 
1. Требования к проекту.
Проект должен быть с открытым исходным кодом, представлять из себя веб-сервис или сайт с функционалом, использованием баз данных или кеша.
Например, можно взять за основу [Defect Dojo](https://github.com/DefectDojo/django-DefectDojo) или [CMS](https://github.com/BootstrapCMS/CMS), [Netlify-CMS](https://github.com/netlify/netlify-cms).

2. Требования к покрытию проекта тестами безопасности.
Проект должен проверяться на наличие уязвимостей в коде. Ни один язык программирования или фреймворк не должны быть пропущены для конкретного проекта. Весь процесс должен быть задокументирован и описан с аналитикой выбора инструментов и зон роста.

## Этапы проектирования

### Этап 1. CI/CD

Критерии достижения:
1. Настроенный пайплайн по сборке и доставке программного обеспечения.
2. Использование облачных сервисов для раскатки. 
3. Хорошо задокументированный процесс. 

### Этап 2. SAST

Критерии достижения:
1. Покрытие кода проверками.
2. Успешные проверки во время сборки.
3. Выгрузка результатов в CI или систему менеджмента уязвимостей.

### Этап 3. DAST

Критерии достижения:
1. Покрытие сервиса проверками.
2. Успешные сканы по всем имеющимся методам.
3. Выгрузка результатов в CI или систему менеджмента уязвимостей.

### Этап 4. Security Checks

Критерии достижения:
1. Проверка репозиториев на секреты.
2. Проверка конфигурации или образов. 

### Этап 5. Security Gateway \*

Критерии достижения:
1. Имеется триггер на остановку релиза при наличии уязвимостей.
2. Сделаны дополнительные триггеры - оставление комментариев в MR, выгрузка рекомендаций по исправлению уязвимостей.

## Полезные материалы
1. [Что такое CI/CD](https://selectel.ru/blog/what-is-ci-cd/).
2. [Облачные сервисы для CI/CD](https://habr.com/ru/company/southbridge/blog/329262/).
3. [DevSecOps](https://www.perforce.com/blog/kw/devsecops-pipeline-overview).

## Как задавать вопросы руководителю по дипломной работе

1. Если у вас возник вопрос, попробуйте сначала самостоятельно найти ответ в интернете. Навык поиска информации пригодится вам в любой профессиональной деятельности. Если ответ не нашёлся, можно уточнить у руководителя по дипломной работе.
2. Если у вас набирается несколько вопросов, присылайте их в виде нумерованного списка. Так дипломному руководителю будет проще отвечать на каждый из них.
3. Для лучшего понимания контекста прикрепите к вопросу скриншоты и стрелкой укажите, что именно вызывает вопрос. Программу для создания скриншотов можно скачать [по ссылке](https://app.prntscr.com/ru/).
4. По возможности задавайте вопросы в комментариях к коду.
5. Формулируйте свои вопросы чётко, дополняя их деталями. На сообщения «Ничего не работает», «Всё сломалось» дипломный руководитель не сможет дать комментарии без дополнительных уточнений. Это затянет процесс получения ответа. 
6. Постарайтесь набраться терпения в ожидании ответа на свои вопросы. Дипломные руководители Нетологии – практикующие разработчики, поэтому они не всегда могут отвечать моментально. Зато их практика даёт возможность делиться с вами не только теорией, но и ценным прикладным опытом.  

Рекомендации по работе над дипломом:

1. Не откладывайте надолго начало работы над дипломом. В таком случае у вас останется больше времени на получение рекомендаций от руководителя и доработку диплома.
2. Разбейте работу над дипломом на части и выполняйте их поочерёдно. Вы будете успевать учитывать комментарии от руководителя и не терять мотивацию на полпути. 

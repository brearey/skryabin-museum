# Проект Скрябина Николая (10 класс) "Создание сайта Кердёмского музея “Самыртай” с галереей 3D экспонатов"

Наступление мировой пандемии привело к тому, что большинство учреждений, оказывающих услуги, в том числе культурные, были вынуждены закрыться на неопределенный срок. В сложившихся обстоятельствах организации вынуждены переходить в онлайн-формат. Ввиду этого актуальными стали исследования, посвященные новым формам взаимодействия учреждений со своими потребителями через цифровые технологии, что послужило толчком для создания сайта музея "Самыртай".
Для начала я решил проанализировать сайты музеев, чтобы выявить общую структуру и требуемый функционал. Реализация сайта сделана на основе технологий веб разработки: `HTML, CSS, JavaScript` с использованием сторонних библиотек:

> -   bootstrap CSS framework
> -   three.js library
> -   jQuery

Для качественной визуализации экспонатов музея я решил добавить на сайт функцию трехмерного отображения отсканированных экспонатов музея. Чтобы это реализовать я нашел бесплатную библиотеку `three.js` и начал сканировать экспонаты с помощью сканера `Sense`. Отсканированная модель экспортируется в формат `GLTF` и вставляется в разметку главной страницы сайта.
Давайте посмотрим что у меня получилось:
https://oktemsec.ru/museum

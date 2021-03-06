# Лекция 1. Путь создания сайта

1. Как работает интернет.
2. Фронтенд vs. бэкэнд
3. HTML/CSS: общие определения, место в работе.
5. Путь создания сайта: от макета до первого пользователя.  
6. Виды устройств. Роль мобильных и альтернативных устройств. Понятие кроссбраузерности.
7. Рабочие инструменты: обзор конструктора – Тильды.
8. Текстовые редакторы на примете CodePen.
9. Видео интерактивной верстки.
10. Домашнее задание.

## Как работает интернет
Каждый из нас ежедневно пользуется интернетом, но не многие задумываются о том, как данные хранятся, обрабатываются и попадают в наш браузер.
Вы знали, как загружается страница сайта? Из чего она состоит?
Вы знали, что у каждого сайта есть «скелет»?
Если вы выбрали для себя сферу веб-разработки, то вам нужно точно знать, как, где и когда будет работать ваша страница.

Давайте вместе разбираться =)

> Пояснить то, что нарисовано на слайде

Что происходит, когда вы набираете в адресной строке  браузера адрес сайта?
Браузер отправляет запрос на сервер, на котором «хранится» этот сайт.
Сервер в ответ отправляет браузеру файлы с:
- HTML-разметкой;
- CSS-стилями;
- JavaScript-кодом.
Браузер обрабатывает полученные файлы в определенном порядке и отрисовывает страницу.

Для того, чтобы серверу было что отдавать в ответ на запрос браузера как раз и нужны разработчики. ;-)

## Фронтенд vs. Бэкэнд

![Frontend vs Backend](pic/front-back.png)

Среди разработчиков существует разделение по технологиям.
Те, кто занимается хранением и обработкой информации на серверах называются бэкэнд-разработчиками, разработчиками заднего края.
Те же, кто создает файлы, из которых формируются страницы сайта, называются фронтенд-разработчиками, разработчиками переднего края.

## HTML/CSS: общее определение, место в работе.
Давайте внимательнее взглянем на файлы, которые обрабатывает браузер для отрисовки сайта. Помните, я говорила, что у всех сайтов есть скелет?
Для создания скелета используется язык разметки гипертекста - HTML.
Файлы, написанные на HTML называются разметкой - их содержимое говорит браузеру где какие элементы интерфейса находятся. Где заголовок, а где картинка.

[Чистая разметка](https://codepen.io/solarrust/pen/ybWWqJ?editors=1000)

То, что вы видите сильно отличается от привычных сайтов, правда? Где же вся красота? А вот за эту часть отвечает файл, написанный на языке CSS. Такие файлы называют стилями сайта. Когда браузер заканчивает с разметкой, он применяет к этой разметке стили и сайт становится красивым.

Именно с разметкой и стилями мы с вами научимся работать.
Мы вместе создадим скелет вашего сайта, а затем сделаем вашу страницу уникальной при помощи стилей.

Только посмотрите на что способны эти две технологии!

[Разметка+стили](https://codepen.io/solarrust/pen/wdbbNv?editors=1100)

Программирование это невероятный мир магии и фокусов где вы из ничего при помощи букв можете создавать крутейшие сайты.

## Путь создания сайта: от макета до первого пользователя
Как мы с вами выяснили на вводном занятии, для того, чтобы сайт стал доступен пользователям требуется работа не одного специалиста. Как же это происходит с точки зрения людей, а не машин?
Создать макет. На этом этапе заказчик рассказывает все свои пожелания к сайту дизайнеру. Дизайнер на основе требований рисует макет – статичную картинку, показывающую где и что будет расположено.
Сверстать макет. Дизайнер передает макет верстальщику. В ходе верстки при помощи HTML и CSS статичная картинка становится живой, начинает реагировать на основные действия пользователя. Верстку можно открыть на разных устройствах и посмотреть. Если сайт очень простой, то все может ограничиться версткой. По факту это уже готовый сайт с очень простой логикой работы.
Если требуется более сложная логика, чем просто переход между страницами, то дальше вступает в дело программист. Верстка интегрируется в систему управления, через которую можно будет менять контент на страницах и добавлять/удалять страницы. Если нужно хранение и сбор данных, то потребуется реализация серверной части.

Без верстальщика не обходится ни один интернет-проект.
После того, как сайт подготовлен его нужно опубликовать в интернете. Для этого покупается доменное имя и арендуется хостинг. Файлы сайта размещаются на хостинге и становятся доступны по купленному доменному имени. С этого момента пользователи смогут попасть на ваш сайт.

## Виды устройств. Роль мобильных и альтернативных устройств. Понятие кроссбраузерности.
Еще совсем недавно технологии были не настолько развиты как сейчас и выйти в интернет можно было только с домашнего компьютера. Сайты могли быть определенного размера, о понятии адаптивности даже не задумывались. На сегодняшний день пользователь может зайти на ваш сайт с компьютера, планшета, телефона, телевизора и даже холодильника =)
Сегодняшнему верстальщику нужно позаботится о том, чтобы сайт хорошо выглядел и не разваливался на всех доступных операционных системах, во всех браузерах, на всех разрешениях экранов.


## Рабочие инструменты

### Обзор конструкторы – Тильды.
Кто знает, что за вольнистая черта изображена на слайде? Как она называется?
Верный ответ – тильда.

В процессе нашего обучения мы по большей части будем использовать конструктор сайтов под названием Тильда.
Этот конструктор позволит нам с вами быстро достичь поставленной цели – собрать сайт для нашего проекта.

В Тильде уже встроена библиотека готовых блоков, внешний вид которых мы сможем менять по своему желанию.
Все блоки адаптируются – ваш сайт будет отлично выглядеть на любых устройствах.
Ко всему прочему можно создать свой собственный блок, если в библиотеке не нашлось подходящего.
Пожалуйста, обратите на так называемый Zero Block особое внимание – с этой возможностью мы будем активно работать.

Пожалуйста, перейдите по адресу www.tilda.cc и нажмите кнопку «Войти» **(выдать данные для авторизации)**

Вашим домашним заданием будет внимательно изучить видео в разделе «Справочный центр». Это позволит нам с вами приступить к созданию сайта уже на следующем уроке.

### Текстовые редакторы
Но настоящий верстальщик и программист не использует никаких конструкторов. Он делает все сам.

Для создания HTML-разметки и CSS-стилей по факту требуется только текстовый редактор. Подойдет даже обычный блокнот, установленный на любом компьютере. Все потому, что разметка и стили по сути своей простой текст. Их правильной обработкой занимается браузер, а написаны они могут быть где угодно.

Профессионалы используют такие редакторы, как Атом, Саблайм, но они по сути своей являются теми же текстовыми редакторами, только с расширенными возможностями.

Я познакомлю вас с очень удобным онлайн-редактором, который позволяет сразу видеть результат вашей верстки – CodePen.

Пожалуйста, перейдите по адресу www.codepen.io и нажмите кнопку Create, выберите New Pen.

Перед вами открылось окно, поделенное на 4 части: самая большая это окно, в котором будет отображаться результат вашей работы; три поменьше это редакторы HTML, CSS и JavaScript кода. Нам потребуются только первые два.

Работать в этом редакторе просто. Все, что мы с вами дальше будем изучать можно будет побовать здесь и сразу видеть результат.

Давайте для примера в окно HTML напишем:
```html
<h1>Hello, World!</h1>
```

А в окно CSS напишем:
```css
h1 {
  color: red;
}
```

Супер! Вы написали свои первые строчки кода!

Не смотря на то, что Тильда облегчит нам жизнь, без умения писать код руками вы никогда не станете настоящими разработчиками. Как можно больше времени уделяйте практике.

Посмотрим небольшое видео, как в редакторе CodePen можно, например, нарисовать всякие классные картиночки =)
https://www.youtube.com/watch?v=BFsyj7MLbvU

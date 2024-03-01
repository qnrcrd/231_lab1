<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Безруков Никита Вальерьевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №1.«Введение в веб-разработку»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>
<b>Веб-разработка</b> — процесс создания веб-сайта или веб-приложения. Основными этапами процесса являются веб-дизайн, вёрстка страниц, программирование на стороне клиента и сервера, а также конфигурирование веб-сервера.
<br>
<b>Этапы разработки веб-сайта</b>
<br>
На сегодняшний день существуют несколько этапов разработки веб-сайта:
<br>
- Проектирование сайта или веб-приложения (сбор и анализ требований, разработка технического задания, проектирование интерфейсов);<br>
- Разработка креативной концепции сайта;<br>
- Создание дизайн-концепции сайта;<br>
- Создание макетов страниц;<br>
- Создание мультимедиа-объектов;<br>
- Вёрстка страниц и шаблонов;<br>
- Программирование (разработка функциональных инструментов) или интеграция в систему управления содержимым (CMS);<br>
- Оптимизация и размещение[уточнить] материалов сайта;<br>
- Тестирование и внесение корректировок;<br>
- Публикация проекта на хостинге;<br>
- Обслуживание работающего сайта или его программной основы.<br>
<br>
<h1 align = "center">Цели и задачи</h1>
1. Изучить основы языка текстовой разметки HTML, MarkDown<br>
2. Создать сайт с информацией о себе<br>
3. Научится создавать репозитории на Github<br>
<br><br>
<h1 align = "center">Решение задач</h1>
- Воспользовавшись литературой интернета, я изучил основы языков;<br>
- Используя редактор кода Visual Studio Code, я создал сайт в соответствии с требованиями лабораторной работы;<br>
- Прочитав руководство на официальном сайте GitHub, я смог разместить свой репозиторий с кодом сайта и другими файлами;<br>
<br>

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Страница обо мне</title>
</head>

<body>
    <h1>Кто я и откуда?</h1>
    <img width="570px" height="370px"
        src="https://avatars.dzeninfra.ru/get-zen_doc/4515217/pub_634f7024ef4d4128b141dd1a_634f704927c635274ca48538/scale_1200" />
    <p style="font-size: larger;">Меня зовут <b>Безруков никита</b>, я родился в 2004 году
        в <a href="https://ru.wikipedia.org/wiki/Южно-Сахалинск">Южно-Сахалинске</a>, обучался в
        <b>Гимназии №1 им. А.С.Пушкина</b>. В данный момент обучаюсь в<i><b> Сахалинском Государственном Университете
                Естественных наук и техносферной безопасности</i></b> на специальности <u>Прикладная математика и
            информатика</u>
    </p>
    <hr>
    <h1>Хобби:</h1>
    <p style="font-size: larger;">К моим увлечениям можно причислить:</p>
    <ul type="square">
        <li style="font-size: larger;"><b>Работа в <a href="https://ru.wikipedia.org/wiki/FL_Studio">Fl Studio</a>:</b>
            уже на протяжении
            3 лет я пишу небольшие треки в жанре синтвейва и совиетвейва
            (Мое творчество: <a href="https://www.youtube.com/@kosmos_119">@kosmos_119</a>)</li>
        <img width="270px" src="fl.png" alt="fl studio interface">
        <!--Local Photo-->
        <pr style="font-size: larger;"></pr>
        <audio controls>
            <source src="pathless.mp3" type="audio/mp3" />
        </audio>
        <li style="font-size: larger;"><b>Монтаж видеороликов:</b> это уже действительно подходит под описание
            хобби, ведь делаю я ролики исключительно для себя и ограниченного круга друзей. К программам в которых
            я хоть что-то смыслю, можно причислить: <i><b>Vegas Pro, Premier Pro, Movavi.</b></i></li>
        <a href="https://ru.wikipedia.org/wiki/Adobe_Premiere_Pro" target="_blank"><img width="100px"
                src="https://migsoft.ru/upload/iblock/011/011a0e0eb1ad3537d34778ecb0e24911.jpg" alt="APP logo"></a><a
            href="https://ru.wikipedia.org/wiki/Vegas_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0)"
            target="_blank"><img width="100px" src="https://keysprog.ru/wp-content/uploads/2021/07/1-57.png"
                alt="VP logo"></a><a href="https://ru.wikipedia.org/wiki/Movavi_Video_Editor" target="_blank"><img
                width="100px" src="movavi.png" alt="Movavi logo"></a>
        <li style="font-size: larger;"><b>Компьютерные игры:</b> хоть это и относится больше к проведению досуга, нежели
            к
            полноценным хобби, я решил упомянуть и это занятие, ведь провожу я за ним действительно много времени.</li>
        <img width="300px"
            src="https://cybersport.metaratings.ru/storage/images/5a/11/5a11ad1580564da936f4cb506846d49c.jpg"
            alt="Steam logo">
    </ul>
    <h1>Достижения:</h1>
    <p style="font-size: larger;">К моим достижениям относятся:</p>
    <ul type="circle">
        <li style="font-size: larger;">Участие в <b><a
                    href="https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%BB%D0%BE%D0%B4%D1%8B%D0%B5_%D0%BF%D1%80%D0%BE%D1%84%D0%B5%D1%81%D1%81%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8B">World
                    Skills Russia</a></b></li>
        <li style="font-size: larger;">Завершение обучения <i><b>1 и 2 уровней</b></i> в <b><a
                    href="https://kvantorium.ru/">Кванториуме</a></b></li>
</body>
</html>
```
<h1 align = "center">Вывод</h1>
В ходе выполнения этой лабортаорной работы я научился основам языков разметки MarkDown и HTML, познакомился со средой редактирования кода MVS Code, создал простой сайт с информацией о себе, 
а также познакомился c сервисом для хранения
проектов - GitHub.

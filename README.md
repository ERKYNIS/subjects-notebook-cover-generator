<h2>Генератор обложек для тетрадей по школьным предметам</h2>
<p>Данный скрипт генерирует обложки по школьным предметам для печати на весь класс.</p>
<hr>
<h3>Иструкция:</h3>
<p>1. Установить библиотеку <a href="https://pypi.org/project/python-docx/">python-docx</a>.</p>
<p>2. Скачать <a href="/subjects_notebook_cover_generator.py">скрипт</a>.</p>
<p>3. В список <code>peoples</code> (<i>7-ая строка</i>) прописать всех учеников класса в родительном патеже (<strong>строго каждого ученика в ковычках и строго через запятую</strong>).</p>
<p>4. При запуске скрипт спросит несколько вводных данных:</p>
<img src="https://github.com/ERKYNIS/subjects-notebook-cover-generator/assets/76586422/dac2f900-594a-47f0-899a-303c1b06c036">
<li>Название файла с шаблоном (<strong>полное название, включая расширение <code>.docx</code> или <code>.doc</code></strong>)</li>
<li>Класс</li>
<li>Литеру класса</li>
<li>Название школы</li>
<li>Состоит ли название предмета из двух строк? (<i>1 - да, 0 - нет</i>)</li>

<p>5. После ввода всех необходимых данных скрипт сгенерирует обложки и спросит название, под которым сохранить готовый файл (<strong>уже без расширения</strong>).</p>
<p>6. После ввода названия, скрипт сохранит файл в папке "success".</p>
<p>7. Готово!</p>
<hr>
<h3>Как сделать свой шаблон?</h3>
<p>1. Скачать <a href="/template.docx">базовый шаблон</a>.</p>
<p>2. Изменить строки <code>[название предмета]</code> и <code>[2ая строка названия предмета]</code> на название предмета (<i>при необходимости, полностью удалить строку с <code>[2ая строка названия предмета]</code></i>)</p>
<p>3. Сохранить файл под нужным названием с расширением <code>.docx</code> в папке со скриптом.</p>
<hr>
<a href="/template">Пример работы скрипта</a> (там же можно найти готовые шаблоны для предметов "Алгебра и начало математического анализа", "Геометрия" и "Вероятность и статистика")

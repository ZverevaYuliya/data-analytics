# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Юлия, я начинающий аналитик данных. 
На данный момент я работаю, закончила обучение на аналитика данных в Skypro, но продолжаю учиться на доп. курсах (Основы визуализации в Datalens, Power BI для анализа данных). Изучаю английский язык в онлайн-школе Skyeng. У меня есть замечательные дочь и муж, а также четвертый член семьи - кошка. В свободное время посещаю фитнес-клуб. Читаю книги, посещаю онлайн мероприятия (например, <a href="https://github.com/ZverevaYuliya/data-analytics-10month/blob/main/Диплом TimePad - митап со Звуком.pdf">Митап со Звуком: System Analysis</a>) и смотрю полезные вебинары - всё, что связано с аналитикой. А также мы семьей любим выезжать на природу.
<br>
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``, ``Python`` 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``


## Проекты
<p> <b>Проект 1</b>: Калькулятор юнит-экономики онлайн-кинотеатра.</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Определить, что является юнитом в нашей экономике.</li>
  <li>Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.</li>
  <li>Выбрать оптимальный вариант расчета Retention. </li>
  <li>Собрать визуализации основных бизнес-показателей.</li>
  <li>Исследовать данные о пользователях и их поведении.</li>
</ol>

<p>Как решала: С помощью различных сводных таблиц, получала нужные данные, строила графики и делала выводы.<p>
  
>Работа представлена по <a href="https://docs.google.com/spreadsheets/d/1guUPqCy9uCGazdxpoLokM2fSamWIyfl5/edit?usp=sharing&ouid=112150620691900238852&rtpof=true&sd=true">ссылке</a>.<br><br>
>Все выводы и итоги представлены в презентации <br><a href="https://docs.google.com/presentation/d/1SuXsRVd5tsB-rFtU6T8cj5V1kwX1-JQdKj0-pRJDY-Y/edit?usp=sharing">"Бизнес-модель работы кинотеатра «Скай-синема»"</a>.
  
<p><b>Вывод</b>: При расчете калькулятора юнит-экономики выяснилось, что кинотеатр работает в убыток. Чтобы выйти на прибыль в 25%, необходимо было увеличить Retention, цену на подписку, и уменьшить расходы на маркетинг и ФОТ, а также уменьшить объём скидок.
<br>
<br>
<p> <b>Проект 2</b>: Смоделировать изменение балансов студентов.</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Создать таблицу, где будут балансы каждого студента за каждый день.</li>
  <li>Понять, как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков). </li>
</ol>

<p>Как решала: С помощью запросов SQL, с использованием CTE, join (+ по неравеству).<p>
  
>Курсовая работа представлена по <a href="https://docs.google.com/spreadsheets/d/1Yr4cUL4gygZs33tXreI9Zf5KLL1KKZFd/edit?usp=sharing&ouid=112150620691900238852&rtpof=true&sd=true">ссылке</a>.<br><br>
>Код запроса по <a href="https://docs.google.com/document/d/12TeauNlCER5a-njwoGN-i0Q-QUctdv4b/edit?usp=sharing&ouid=112150620691900238852&rtpof=true&sd=true">ссылке</a>.  
  
<p><b>Итог</b>: В результате получился запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день.<p>

<br>
<p> <b>Проект 3</b>: Проанализировать АБ-Тест, проведенный во всех городах крупного ритейлере SkyLenta.</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Проанализировать и визуализировать результаты, провести сегментацию.</li>
  <li>Сделать выводы и сформулировать рекомендации для дальнейших запусков АБ-Теста.</li>
  <li>Построить таблицу, которая будет в удобной форме хранить результаты АБ-Теста.</li>
  <li>Построить калькулятор для расчета выгоды, которая может быть получена от замены механики A на B при условии, что ей воспользуются N клиентов при положительном и отрицательных исходах, а также для нейтральных исходов - расчет кол-ва наблюдений.</li>
</ol>

<p>Как решала: С помощью импорта, анализа и объединения таблиц, чистки данных, расчета общих результатов АБ-Теста и сегментации, а также - построения калькулятора.<p>
  
>Дипломная работа представлена по <a href="https://colab.research.google.com/drive/1nSPT_YmxKruc3Z8QjsKefCUMqgDQuGO3#scrollTo=aVE3Ixg8Y-L1">ссылке</a>.<br><br>
>Калькулятор представлен по <a href="https://docs.google.com/spreadsheets/d/1Ny3b93C57rhvo-_BQ9mHb30avJy4q1HU/edit?usp=sharing&ouid=112150620691900238852&rtpof=true&sd=true))">ссылке</a>.  
  
<p><b>Итог</b>: В результате даны рекомендации по дальнейшему запуску АБ-Тестов и построен калькулятор.<p>

<br>
<p> <b>Проект 4</b>: Оценить результаты АВ-Теста, проведенный в разных городах, на примере агрегатора такси SkyTaxi.</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Исследовать результат и понять, влияет ли понижение цены на конверсию из просмотра в создание заказа.</li>
  <li>Сделать выводы и сформулировать рекомендации для дальнейших запусков АБ-Теста.</li>
</ol>

<p>Как решала: С помощью импорта, анализа и объединения таблиц, расчета общих результатов АБ-Теста и сегментации.<p>
  
>Аттестационная работа представлена по <a href="https://colab.research.google.com/drive/1WpJo9ZQbomZpvDXXt_dX-CxKUg3z5T0V">ссылке</a>.<br><br>  

<p><b>Итог</b>: В результате даны рекомендации по дальнейшему запуску АБ-Тестов.<p>


## Контактная информация
- Email: yu.zvereva86@mail.ru

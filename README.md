<b>Небольшая история этого проекта</b>

Я начал изучать Python почти одновременно с немецким. И то, и другое — самостоятельно. Мы решили скооперироваться с подругой, созваниваться по видео, проверять друг друга и придумывать небольшие задания. 
Чтобы лучше запомнить числительные придумумали такую практику — давали друг другу простые примеры на сложение и вычитание с числами до 100. И спрашивали, и отвечали на немецком, но достаточно быстро столкнулись с тем, что пока один отвечал, второй мог забыть, что спрашивал. Или же один мог ошибиться либо в счёте, либо с переводом, а второй мог не заметить или ошибиться сам.
Решение я тоже придумал быстро — не прерывая звонок, открыл IDE и написал скрипт, который генерировал список примеров с ответами — так мы стали спотыкаться гораздо меньше, да и сама эта практика оказалась весьма полезной и эффективной. Могу порекомендовать всем, кто учит новые для себя зяыки.

<b>Что я добавил потом:</b>
- генерация примеров также на умножение и деление
- функция, которая переводит натуральные положительные числа в строковые значения с тем же числом немецкими словами
- с использованием этой функции — вывод примеров как в числовом виде, так и немецкими словами
- еще один скрипт, генерирующий даты — для их изучения в той же форме.  Так появился перевод и в порядковые числительные, но только до 31
- более умная выдача: вероятность повторов чисел и дат сведена к минимуму. Также сбалансирована и выдача математических операций, а в скрипте с датами — веков

На этом этапе проект стал создавать впечатление, будто он уже может оказаться полезным и для других людей. Потому загрузил его в публичный репозиторий на GitHub, будучи при этом совсем новичком. 
Буду рад, если для кого-то он действительно окажется.

<b>В планах:</b>
- графический интерфейс
- telegram-бот

<b>Файлы в проекте:</b>

- gernan_numbers,py — содержит функцию IntToGermanб название которой отлично отражает, что она делает. Если запускать этот файл, он может запрашивать числа и конвертрировать их в строки с этими числами на немецком
- german_examples.py — примеры с простыми математическими операциями, числами и на немецком.
- dates.py — даты
- core.py — здесь находятся функции, которые используются сразу несколькими модулями

<b>Если вы не знаете, как запусать python-скрипты:</b>

1. Скачайте содержимое репозитория: «Clone or download» → «Download ZIP»
2. Установите интерпретатор Python версии 3.x, если в вашей системе он не установлен. 
3. Запустите командную строку в папке, где находятся скрипты
5. Pапускйте их командами вроде «python3 german_examples.py» или «python3 german_dates.py»

Интерпретатор, в зависимости от настроек в вашей операционной системе, может вызываться иначе — например «python» или «py».
	


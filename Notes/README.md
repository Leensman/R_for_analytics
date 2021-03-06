Привет! Это инструкция к приложению для аналитиков, написанном на R.
Данное приложение содержит следующий функционал:
* Возможность загрузки и редактирования данных в формате .csv, .tsv и .xlsx
* Возможность проводить визуализацию загруженных данных с возможным дальнейшим сохранением полученных графиков в форматы .jpeg, .pdf и .png
* Возможность проведения регрессионного и кластерного анализов загруженных данных с возможностью дальнейшей визуализации и сохранения полученных графиков, а также выводом полученных параметров модели в случае регрессионного анализа

Пользователю предоставляется возможность работы в двух режимах:
1) **Режим эксперта**. В этом режиме пользователь имеет возможность задавать подписи к графикам, переопределять папку сохранения графиков и параметров моделей, а также возможность более гибкого регрессионного и кластерного анализов (а именно, возможность определения произвольного числа признаков для обучения модели)
2) **Режим пользователя (новичка)**. В этом режиме пользователь не имеет доступа к описанному в режиме эксперта функционалу. Весь остальной функционал остаётся всё также доступным пользователю

Выбор режима для визуализации и анализа данных предоставляется пользователю независимо!

Программа запускается с помощью скрипта "**Scripts/main.R**". Корневая папка для окружающей среды R при этом должна быть Work!

Все необходимые зависимости определены в "**Notes/requirements.txt**".

Приятного пользования!
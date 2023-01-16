# SkillFactory

# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Краткая информация о данных
Загадываем число с помощью модуля random.
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
Первая функция перебирает возможные варианты с помощью бинарного поиск и фиксирует количество неправильных ответов - количество попыток.
Вторая функция запускает первую 1000 раз и вычисляет среднее количество попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
В среднем алгоритм отгадывает загаданное число за 6 попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Используйте бинарный поиск для экономии времени :)

:arrow_up:[к оглавлению](.README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарна, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами

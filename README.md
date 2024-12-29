# Проект 1. Анализ резюме на hh.ru
## Оглавление  
[1. Описание проекта](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Результаты)    
[6. Выводы](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Выводы)  

### Описание проекта    
Анализ резюме на hh.ru  

[к оглавлению](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Оглавление)

### Какой кейс решаем?    
Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю. Для расчётов будет браться информация из анкет.  

[к оглавлению](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Оглавление)

### Краткая информация о данных
Исходный файл: [dst-3.0_16_1_hh_database.csv](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view)
Файл с курсами валют: [ExchangeRates.csv](https://lms-cdn.skillfactory.ru/assets/courseware/v1/15abf80f45a2f3e93c3274101b451c67/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/ExchangeRates.zip)  

### Этапы работы над проектом
1. Исследование структуры данных  
2. Преобразование данных  
    * Выделен признак **"Образование и ВУЗ"** из столбца **"Уровень образования год выпуска ВУЗ специальность..."**.
    * Выделены два новых признака **"Пол"** и **"Возраст"** из столбца **"Пол, возраст"**.
    * Преобразован признак **"Опыт работы"** в **"Опыт работы (месяц)"**.
    * Выделены признаки **"Город"**, **"Готовность к переезду"**, **"Готовность к командировкам"** из столбца **"Город, переезд, командировки"**
    * Категории из признаков **"Занятость"** и **"График"** вынесены в отдельные bool признаки.
    * Создан признак **"ЗП (руб)"**, полученный переводом исходных значений ЗП согласно курсу валют на дату обновления резюме.
3. Исследование зависимостей в данных  
4. Очистка данных  
[к оглавлению](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Оглавление)

### Результаты

[к оглавлению](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Оглавление)

### Выводы

[к оглавлению](https://github.com/vokhmianin-da/Project1_HH_analysis/tree/master/README.md#Оглавление)
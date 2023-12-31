#### :briefcase: Это дипломный проект на тему «Модель прогнозирования стоимости жилья для агентства недвижимости»

## Оглавление  
[1. Описание проекта](https://github.com/ElenaSaveleva/Diplom/blob/main/README.md#Описание-проекта)
[2. Входные данные](https://github.com/ElenaSaveleva/Diplom/blob/main/README.md#Входные-данные)  
[3. Выводы](https://github.com/ElenaSaveleva/Diplom/blob/main/README.md#Выводы) 

### Описание проекта
Поставлена задача от агенства недвижимости по разработке модели по предсказанию стоимости домов на основе истории предложений.

### Входные данные
Предстоит работать с датасетом, в котором содержатся сведения о 377 тысячах лотах недвижимости в USA, выставленных на продажу. Модель, которую мы будем обучать, должна предсказывать стоимость для новых лотов на основе имеющихся в датасете данных.

Датасет для работы можно скачать [по ссылке](https://drive.google.com/file/d/1JxQ0jQyZ1TvbRzSokqxxeRLlUQ9QWiS9/view?usp=sharing)
### Выводы:
В процесе работы над проектом мы проведем базовый анализ структуры входных данных, проведем разведывательный анализ данных (EDA), создадим новые признаки. После этого запустим процесс обучения модели. И в конце реализуем процесс подготовки нашей обученной модели к выводу в production 

За время работы над этим проектом, мне удалось:
* Преобразовать данные для того, чтобы ими можно было пользоваться 
* Создать массу новых признаков, тем самым увеличив информативность данных 
* Очистить данные от пропусков, выбросов и неинформативных признаков 
* Провести качественный анализ данных с применением математической статистики 
* Отобрать из данных самые сильные признаки. 
* Перебрать много моделей и на основе нескольких метрик выбрать лучшую 
* Сохранить модель в формат pickle и применить ее в продакшне.

:arrow_up:[к оглавлению](#Оглавление)

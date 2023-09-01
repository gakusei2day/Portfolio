# Исследование объявлений о продаже квартир

## Задача

Используя данные сервиса Яндекс.Недвижимость необходимо выявить основные параметры и факторы, влияющие на рыночную цену квартиры. 

### Используемые библиотеки

<code>pandas</code>, <code>numpy</code>, <code>matplotlib</code>, <code>seaborn</code>

## Данные

Архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет:
- <code>airports_nearest</code> — расстояние до ближайшего аэропорта в метрах (м)
- <code>balcony</code> — число балконов
- <code>ceiling_height</code> — высота потолков (м)
- <code>cityCenters_nearest</code> — расстояние до центра города (м)
- <code>days_exposition</code> — сколько дней было размещено объявление (от публикации до снятия)
- <code>first_day_exposition</code> — дата публикации
- <code>floor</code> — этаж
- <code>floors_total</code> — всего этажей в доме
- <code>is_apartment</code> — апартаменты (булев тип)
- <code>kitchen_area</code> — площадь кухни в квадратных метрах (м²)
- <code>last_price</code> — цена на момент снятия с публикации
- <code>living_area</code> — жилая площадь в квадратных метрах (м²)
- <code>locality_name</code> — название населённого пункта
- <code>open_plan</code> — свободная планировка (булев тип)
- <code>parks_around3000</code> — число парков в радиусе 3 км
- <code>parks_nearest</code> — расстояние до ближайшего парка (м)
- <code>ponds_around3000</code> — число водоёмов в радиусе 3 км
- <code>ponds_nearest</code> — расстояние до ближайшего водоёма (м)
- <code>rooms</code> — число комнат
- <code>studio</code> — квартира-студия (булев тип)
- <code>total_area</code> — общая площадь квартиры в квадратных метрах (м²)
- <code>total_images</code> — число фотографий квартиры в объявлении

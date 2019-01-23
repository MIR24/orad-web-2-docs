Список MySQL VIEW
=================


Вкладка "Топы" - TopsView
-------------------------

* Пример запроса 
    * ``SELECT * FROM TopsView``
* Параметры
    * id
    * category
    * text
    * count
    * themes_count

Вкладка "Срочно" - BreakingView
-------------------------------

* Пример запроса 
    * ``SELECT * FROM BreakingView``
* Параметры
    * id
    * title
    * text

Вкладка "Курс валют" - ExchangeView
-----------------------------------

* Пример запроса 
    * ``SELECT * FROM ExchangeView``
* Параметры
    * Val1
    * Val2
    * Diff
    * Kurs

Вкладка "Промо" - PromoView
---------------------------

* Пример запроса 
    * ``SELECT * FROM PromoView``
* Параметры
    * mir_id
    * mirhd_id
    * age
    * name
    * uc_name
    * header
    * subheader
    * mode
    * pic
    * category

Вкладка "Newsbar" - NewsbarView
-------------------------------

* Пример запроса 
    * ``SELECT * FROM NewsbarView``
* Параметры
    * title
    * text

Вкладка "Погода для эфира" - WeatherForecastsView
-------------------------------------------------

* Пример запроса 
    * ``SELECT * FROM WeatherForecastsView``
* Параметры
    * city
    * morning
    * evening
    * weather_type_id

Вкладка "Погода для подводки" - WeatherForecastsLinerView
---------------------------------------------------------

* Пример запроса 
    * ``SELECT * FROM WeatherForecastsLinerView``
* Параметры
    * city
    * now
    * morning
    * evening
    * weather_type_id

Вкладка "Время" - CityTimeshiftsView
------------------------------------

* Пример запроса 
    * ``SELECT * FROM CityTimeshiftsView``
* Параметры
    * id
    * title
    * text

Вкладка "Счетчик события" - EventCountdownsView
-----------------------------------------------

* Пример запроса 
    * ``SELECT * FROM EventCountdownsView``
* Параметры
    * city
    * timeshift

Вкладка "Сейчас далее потом" - NowFurtherLaterView
--------------------------------------------------

* Пример запроса 
    * ``SELECT * FROM NowFurtherLaterView``
* Параметры
    * id
    * external_id
    * name
    * pic

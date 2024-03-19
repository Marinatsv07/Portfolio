# Portfolio

Здесь собраны некоторые реализованные проекты

| #    | Наименование проекта                                    | Описание проекта                                                  | Навыки и инструменты                                             | Выводы по проекту                                                                                   |
| ---- | ------------------------------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| 1.   | [Прогнозирование оттока клиентов телеком-оператора ТелеДом](https://github.com/Marinatsv07/Portfolio/tree/main/Classification_of%20_TeleDom%20churn) | Оператор связи «ТелеДом» хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, «ТелеДому» нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах. Задача — обучить на этих данных модель для прогноза оттока клиентов. | Python, Pandas, NumPy, Matplotlib, Seaborn, Phik, Sklearn, Scipy, CatBoost, LogisticRegression | Обучена модель классификации для прогнозирования оттока клиентов. Метрика ROC_AUC 0.93, что выше целевой 0.85
| 2.   |  [Определение токсичности комментариев](https://github.com/Marinatsv07/Portfolio/tree/main/Classification_of_comments) | Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.| BERT, pandas,numpy,sklearn, nltk, torch, transformers,tqdm, LogisticRegression | Была обучена модель классификации комментарии на позитивные и негативные со значением метрики качества F1 выше целевых 0.75.
| 3.   | [Статистический анализ данных сервиса аренды индивидуальных средств мобильности (самокаты)](https://github.com/Marinatsv07/Portfolio/tree/main/Statistical_analysis_of_renting_service)| Исследование поведения пользователей на основе исторических данных, анализ активности и проверка статистических гипотез о различиях между подписчиками и не-подписчиками.| Python, Pandas, Numpy, Scipy, Math, Matplotlib, статистический анализ данных |  Проанализирована активность пользователей, используя графические средства MatPlotLib и Seaborn, для визуализации паттернов поведения. С помощью функций из scipy.stats, осуществлена проверка гипотезы о различии в активности между подписчиками и не-подписчиками. Проанализированы экономические показатели активности с целью определения оптимальных условий обслуживания и их потенциального влияния на общую выручку компании.
| 4.   | [Обработка фотографий покупателя](https://github.com/Marinatsv07/Portfolio/tree/main/Processing_client_photos) | Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека.  | python, keras | Построена модель, которая определяет приблизительный возраст человека по фотографии
|5.    [Построение модели определения стоимости автомобиля](https://github.com/Marinatsv07/Portfolio/tree/main/Reccomendation_system_of_car_price)| Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля| pandas,numpy, matplotlib,seaborn, sklearn,lightgbm| Разработана системы рекомендации стоимости автомобиля на основе его описания







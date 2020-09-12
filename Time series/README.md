### Описание проекта  
В датасете собраны исторические данные о заказах такси в аэропортах. **Цель** - спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.  
Значение метрики RMSE на тестовой выборке должно быть не больше **48**.    
### Содержание
- [Предобработка данных](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#1.-%D0%9F%D1%80%D0%B5%D0%B4%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)
- [Анализ данных](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#2.-%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)
- [Обучение моделей](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#3.-%D0%9E%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B5%D0%B9)
- [Тестирование моделей](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#4.-%D0%A2%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B5%D0%B9)
  - [Модель Хольта-Винтерса](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#4.1-%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C-%D0%A5%D0%BE%D0%BB%D1%8C%D1%82%D0%B0-%D0%92%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%81%D0%B0)
  - [Линейная регрессия](https://nbviewer.jupyter.org/github/sigarev-andrey/Yandex.Praktikum/blob/a60da0f106d299ec6be7cbf7ab1484bcabfcb944/Time%20series/time_series.ipynb#4.2-%D0%9B%D0%B8%D0%BD%D0%B5%D0%B9%D0%BD%D0%B0%D1%8F-%D1%80%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%D0%B8%D1%8F)
### Результат  
- произведено ресемплирование данных;
- произведён анализ анализ данных (выявлен тренд, дневная и недельная сезонности);
- добавлены фичи (номер дня и недели, лаги, скользящее среднее);
- обучены модели Хольта-Винтерса и линейной регрессии.
### Стек  
pandas, statsmodels, sklearn, ipywidgets

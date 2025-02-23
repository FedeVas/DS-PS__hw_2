# DS-PS__hw_2
Homework for "Системы хранения и обработки данных" discipline

# Описание файлов
 - HW2_Fede_VV.ipynb           - Jupyter Notebook с решением заданий. В нём реализованы SQL-запросы, объединение данных
 - Schema_Fede_VV.jpg          - Схема базы данных из DBeaver

## Описание решения
В данном домашнем задании реализованы следующие шаги:
1. **Подключение к базе данных:**  
   Использование магического расширения `%load_ext sql` для подключения к локальной или удалённой СУБД.
   
2. **Выполнение SQL-запросов:**  
   - Объединение таблиц с помощью операторов `JOIN`.  
   - Фильтрация данных с использованием `WHERE`, `BETWEEN`, `IN` и других операторов.
   - Преобразование результатов в pandas DataFrame для потенциального дальнейшего анализа.
   
3. **Анализ данных:**  
   Использование функций библиотеки Pandas для настройки отображения DataFrame (например, `pd.set_option('display.max_columns', None)`) и проведения дальнейшего анализа.

## Запуск проекта
1. **Установка зависимостей:**  
   Убедитесь, что установлены необходимые библиотеки. Для этого можно выполнить:
   ```bash
   pip install ipython-sql pandas

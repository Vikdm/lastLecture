# Автоматизируемые сценарии:
        - валидные значения
                - русское распространенное имя и правильны> номер телефона
                - граничные значения (короткое имя до 3 букв) и правильный номер телефона (2 теста)
                - граничные значения (длинные имена(составные, через "-", через пробел, с "ё")) и правильный номер телефона (4-5 тестов)
        - невалидные значения   
                - имя, написанное символами иностранного языка (немецкого, английского, испанского)
                - номер телефона без "+7"
                - заведомо ошибочный номер телефона (из одной цифры(вариант "1(111)111-11-11))
                - номер телефона с кодом иностранного государства (вариант "+375")

# Инструменты: 
        - gradle - более удобная и простая система управления проектом
        - JUnit - облегчение разработки и объединение разных компонентов
        - Selenide - для поиска элементов на веб странице
        - SQL - для просмотра поступивших заявок на обучение (что отображаются в нашей БД, корректно, с сохранением данных введенных пользователем)
        - при большом количестве тестов - виртуальные машины

# Перечень разрешений/данных/доступов:
        - БД со стороны Нетологии (п. 4 из Инструментов)

# Риски:
        - невозможность покрыть 100 % пользовательских данных (как и при ручном тестировании, но % покрытия будет значительно выше)
        - большие временные затраты на первоначальном этапе (написание кода, оптимизация)
        - большие денежные затраты на первоначальном этапе (зп тестировщиков, виртуальные машины)

# Перечень специалистов:
        - QA инженер (автоматизированное тестирование) - 2 человека 
        - Менеджер проекта (для взаимодествия с заказчиком (Нетологией))

# Интервальная оценка:
        - 24 часа (из расчета 1 раб. день - 8 часов)
            - день 1: уточнение у Заказчика норм и правил(принятых/желаемых у Нетологии), получение доступа к БД, поключение Инструментов, создание проекта в IDEA, создание класса Датахелпер
            - день 2: написание автотестов, прогоны автотестов
            - день 3: написание автотестов, прогоны автотестов, финальные "штрихи", создание отчетов для Заказчика (наглядных и человекочитаемых)
           


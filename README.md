## MLOps. Практическое задание №3 (vo-HW)



При выполнении итоговой самостоятельной работы по модулю «Управление потоком операций (xFlow)» вам необходимо:

:white_check_mark:  Определить какой-нибудь внешний источник получения данных и способ получения этих данных (http, curl, wget, API, SQL, SparQL, ...) (3 балла).

:white_check_mark: Поставить задачу для алгоритма машинного обучения, выбрать модель и метрику (4 балла).

:white_check_mark:  Создать инфраструктуру, например, виртуальные машины virtualbox, установить и настроить для работы необходимое программное обеспечение, в том числе airflow и mlflow, а также venv для организации работы виртуального окружения (5 баллов).

_Примечание: Инфру развернул в libvirt_

Создать python скрипты для (6 баллов):

:white_check_mark:  получения данных из внешнего источника,

:white_check_mark:  преобразования данных,

:white_check_mark:  формирования рабочего набора данных для обучения (train) и тестирования (test) модели,

:white_check_mark:  обучения модели на тренировочных (train) данных и ее сохранения,

:white_check_mark:  загрузки модели и проверки качества ее работы на тестовых (test) данных.


:white_check_mark: Добавить код airflow, позволяющий создавать и запускать на регулярной основе описанные операции проекта (6 баллов).

:white_check_mark: Добавить код mlflow, позволяющий мониторить ход выполнения конвейера, сохранять и анализировать полученные артефакты (6 баллов).
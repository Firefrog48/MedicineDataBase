### Описание проекта на GitHub

#### Название проекта:
База данных для хранения информации о пациентах

#### Требования:
- C++17 и выше
- QT creator

#### Описание программы:
Программа предназначена для хранения и управления информацией о пациентах. Она реализована с использованием библиотек QT, для хранения данных используется SQLite. Ввод данных осуществляется через графический интерфейс, а для вывода информации основная программа взаимодействует с скриптом на Python, который способен генерировать отчеты в формате docx.

Программа включает в себя множество полезных функций:
- Различные подстановки в поля
- Изменение дат
- Вычисления доз препаратов
- Функции обработки ошибок
- Защиту от введения некорректных данных

Вывод информации осуществляется с использованием шаблонов, соответствующих приказу 530н. Также предусмотрена возможность редактирования данных для подстановки через JSON и редактирование шаблонов docx без изменения кода основной программы.

#### Инструкция по сборке проекта:

1. Скачайте файлы репозитория.
2. Установите QT creator.
3. Извлеките файлы из папки `source_files` в директорию вашего проекта.
4. Найдите файл `windeployqt6.exe` в папке с установленным QT creator.
5. Перетащите файл `PatientBase` на файл `windeployqt6.exe`, чтобы подтянуть необходимые библиотеки.
6. Запустите файл `PatientBase.exe`.
7. Для настройки базы данных откройте папку `source_files\DepartmentInfo` и отредактируйте необходимые поля в JSON-документе в том же формате, как представлено в примере.
8. Начните использование программы.

#### Ссылки:
- https://www.qt.io
#### Скриншоты:
- ![1111123_1_1656279827](https://github.com/Firefrog48/MedicineDataBase/blob/main/Снимок%20экрана%202024-12-16%20214637.png)
- ![1111123_1_1656279827](https://github.com/Firefrog48/MedicineDataBase/blob/main/2024-12-16_21-56-23.png)
- ![1111123_1_1656279827](https://github.com/Firefrog48/MedicineDataBase/blob/main/2024-12-16_21-57-44.png)

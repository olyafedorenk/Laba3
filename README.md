# Labaratornaya3java
# Приложение для управления базой данных одногруппников

## Описание проекта
Это простое Android-приложение, написанное на языке Java с использованием XML для интерфейса. Приложение взаимодействует с локальной базой данных SQLite и позволяет управлять информацией об одногруппниках. Пользователь может просматривать записи, добавлять новые и изменять существующие записи в базе данных.

### Функционал
Приложение включает следующие функции:
1. Создание локальной базы данных при первом запуске.
2. Создание таблицы `classmates` с полями:
   - **ID** - уникальный идентификатор записи.
   - **Фамилия** - фамилия одногруппника.
   - **Имя** - имя одногруппника.
   - **Отчество** - отчество одногруппника.
   - **Время добавления записи** - время добавления записи в базу данных.
3. Удаление всех записей и добавление 5 начальных записей при каждом запуске приложения.
4. Возможность добавления новой записи.
5. Возможность обновления последней записи с заданными данными.

### технологии
- **Язык программирования**: Java
- **Интерфейс**: XML
- **База данных**: SQLite

## Описание кнопок
На главном экране приложения расположены три кнопки для управления данными:

1. **Просмотреть записи**:
   - Открывает новое активити, где отображаются все записи из таблицы `classmates`.
   - Данные выводятся в удобном для восприятия формате (список одногруппников с их фамилией, именем, отчеством и временем добавления записи).

2. **Добавить запись**:
   - Добавляет новую запись в таблицу `classmates` с фамилией, именем и отчеством, указанными по умолчанию.
   - В базе данных сохраняется новая запись, и время добавления фиксируется автоматически.

3. **Изменить последнюю запись**:
   - Обновляет данные последней записи в таблице.
   - Фамилия, имя и отчество изменяются на "Иванов Иван Иванович" для последней записи.

## Как запустить проект
1. Откройте проект в Android Studio.
2. Запустите приложение на эмуляторе или физическом устройстве Android.
3. Используйте кнопки на главном экране для взаимодействия с базой данных.
   
## Скриншоты
<p align="center">
  <img src="https://github.com/user-attachments/assets/fe3de11b-8faf-47af-bab9-19da6dad6d45" alt="Скриншот" width="200"/>
  <img src="https://github.com/user-attachments/assets/513cd045-0896-4c32-81d9-425996fb0e7b" alt="Скриншот" width="200"/>
  <img src="https://github.com/user-attachments/assets/5f102931-0353-4bc1-b2f2-03c5ae249d3d" alt="Скриншот" width="200"/>
  <img src="https://github.com/user-attachments/assets/01fbb01d-0f34-4227-af7d-52baad9a2386" alt="Скриншот" width="200"/>
  <img src="https://github.com/user-attachments/assets/8268aed3-bdbb-4cd7-8e5a-966a1491a7d8" alt="Скриншот" width="200"/>
  <img src="https://github.com/user-attachments/assets/17ac8b9f-61e7-4c45-b55a-d84de3a75f8e" alt="Скриншот" width="200"/>
</p>



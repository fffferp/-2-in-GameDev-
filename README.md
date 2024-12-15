# -2-in-GameDev-# АНАЛИЗ ДАННЫХ В РАЗРАБОТКЕ ИГР ЛАБОРАТОРНАЯ РАБОТА 2 [in GameDev]
Отчет по лабораторной работе #2 выполнил:
- Шайдуров Савелий Сергеевич
- АТ-05
Отметка о выполнении заданий :

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | |
| Задание 2 | * |  |
| Задание 3 | * |  |
| Задание 4 | * |  |
| Задание 5 | # |  |



##Структура отчета

- #Данные о работе: Работа #2. Шайдуров Савелий Сергеевич, Выполнены задачи 1,2,3,4
- #Научиться передавать в Unity данные из Google Sheets с помощью Python.

  
- # Задание 1. Настроить доступ к google-таблице по api
 Ход работы:
- Перейти в Google Cloud Console .
- Создать новый проект, выбрав Выберите проект - Новый проект .
- Дать имя проекта и нажмите кнопку «Создать» .
- Перейти Панель управления созданного проекта.
- Перейти в Google Drive API , используя текстовый поиск.
- Нажать кнопку Включить API .
- Перейти в раздел «Учетные данные» и создайте учетные данные для ключа API.
- Сохранить файл с ключом в формате JSON на своем компьютере.
- Скопировать адрес сервисного аккаунта.
- создать Google-таблицу и доступ к ней для редактирования с созданного сервисного аккаунта.
  
![image](https://github.com/user-attachments/assets/ff074409-5bb2-4bad-8f1b-8634cba7383d)

![image](https://github.com/user-attachments/assets/63c5d02f-00dc-45ea-9098-3e0fb19f894e)



- # Задание 2.Генерация данных с помощью Python и их передача в google таблицу
 Ход работы:
- Запустить Jupyter Notebook и создать новый .ipynbфайл. 
- В .ipynb файле реализовать передачу данных в созданную ранее Google-таблицу.

![image](https://github.com/user-attachments/assets/9391666f-dabe-4f65-b7fc-720b4469fcc8)

![image](https://github.com/user-attachments/assets/6e94c25f-58a9-48c6-8f06-fe760d06d95f)

![image](https://github.com/user-attachments/assets/78a30e63-80e6-4a10-9498-907ad5dac3e2)


- # Задание 3.Создание ключа API для передачи данных из google-таблицы в Unity
- Создать ключ API для получения данных из таблиц и их обработки в Unity.

  ![image](https://github.com/user-attachments/assets/467b507b-f0a1-40c8-957a-a1f7d2b8a9aa)


- # Задание 4. 4 Новый проект на Unity
- Создать новый 3D-проект на Unity.
- Добавить в файлы проекта jsonPackage и soundPackage.
- Создать на сцене Unity пустой GameObjectи подключите к ней .csскрипт, в котором подключение к Google-таблице по API и подать сигнал в игру в соответствии со считываемыми значениями:
  
![image](https://github.com/user-attachments/assets/4750b8ec-8e83-44ba-bf83-fb0c66a8fd4f)
![image](https://github.com/user-attachments/assets/cf8c7f3c-3a4e-43bc-9be7-804e028c9137)


## Выводы

В ходе выполнения лабораторной работы мы научились передавать данные из Google Sheets в Unity с использованием Python и настроенного API. Реализованы генерация данных на Python, их передача в Google Sheets, а также использование этих данных в игровом движке Unity для передачи звука в соответствии с экономической моделью динамики.

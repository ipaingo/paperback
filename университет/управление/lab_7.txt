ЛАБОРАТОРНАЯ РАБОТА 7: УПРАВЛЕНИЕ ИНФРАСТРУКТУРОЙ СИСТЕМЫ ХРАНЕНИЯ ДАННЫХ

#################### Часть 1: Мониторинг и отчетность ####################

• Шаг 2: Отображаемые оповещения
System > System Alerts

ОТВЕТ: 
Предупреждение: Storage Servers configured for SPB have stopped and will be restarted.
(Серверы хранения, настроенные для SPB, остановились и будут перезапущены)

• Шаг 3: Проверка работоспособности оборудования. 
System > System Health 
DPE > SP A.

SP A Battery
SP A Internal Disk
SP A Memory Module 0
SP A Memory Module 1
SP A Memory Module 2
SP A Ethernet Port 2
SP A Ethernet Port 3
SP A Ethernet Port 4
SP A Ethernet Port 5
SP A Management Port
SP A SAS Port 1
SP A SAS Port 0
SP A I/O Module 0 FC Port 0
SP A I/O Module 0 FC Port 1
SP A I/O Module 0 FC Port 2
SP A I/O Module 0 FC Port 3

ОТВЕТ:
Все оборудование работает исправно

• Шаг 4: Системные ресурсы. 
System > System Capacity 

ОТВЕТ:
Используемое пространство увеличилось с 487,6 ГБ до 1 ТБ.

• Шаг 5: Диаграммы производительности системы
System > System Performance

ОТВЕТ:
Metrics: CPU, Data Mover, Disk, LUN, Storage Processor

• Шаг 6: Экспорт
ОТВЕТ:
Производительность системы._06.03.2025 11-49-13

• Шаг 7: Журналы
System > Logs

ОТВЕТ:
В файле журнала каких-либо предупреждений или критических событий нет.

• Шаг 8: Имя хоста системы
ОТВЕТ:
home-83d97eaea0

Virtual VNXe эмулирует работу реального устройства хранения. Она используется для обучения, тестирования и экспериментов без необходимости использования физического оборудования.

Virtual VNXe не имеет реального подключения к хосту. Это означает, что даже если настроить удалённое ведение журнала, события не будут передаваться на ваш хост, так как виртуальная среда изолирована от реальной сети.


• Шаг 9: Отправка событий на хост
Settings > Management Settings


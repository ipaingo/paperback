ЛАБОРАТОРНАЯ РАБОТА 6: УПРАВЛЕНИЕ СЛУЖБАМИ ЗАЩИТЫ 

#################### Часть 1: Защита на основе массивов ####################

• Шаг 3: Определить параметры расписаний.
Settings->More configuration…->Snapshot Schedules

ОТВЕТ:
Имя                | Частота                 | Время | Настройка (политика) автоматического удаления 
Default Protection | Каждый день             | 11:00 | Хранить в течение 2 дней
Less Protection    | Каждый день             | 11:00 | Хранить в течение 1 дня
More Protection    | Каждый день             | 11:00 | Хранить в течение 7 дней
Schedele00         | Каждый месяц 25го числа | 01:15 | Настройки порога автоматического удаления из пула


• Шаг 4: Назначенная защита для каждого LUN и LUN Group
Storage > LUNs

ОТВЕТ:
Имя            | Защита
LUN00          | Schedule00
LUNGroup00     | Not configured
LUNGroup-FC    | Not configured
LUNGroup-iSCSI | Schedule00

#################### Часть 2: Настройка защиты LUN ####################

• Шаг 2-10: Применить защиту к LUNGroup-FC
Storage > LUNs > LUNGroup-FC

ОТВЕТ:
new rule FC_Snapshot:
- Type of Rule – On Selected Days
- Frequency – Saturday
- Time – 01:00
- Auto-Delete Policy – Expiration value
- Keep for – 7 Days
- Access Type – Hidden
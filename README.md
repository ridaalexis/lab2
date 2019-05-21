# Задание 1

1. Установка
![1](https://user-images.githubusercontent.com/44519124/57974776-5949b900-79c6-11e9-9fe2-6673d617d0af.png)
![2](https://user-images.githubusercontent.com/44519124/57974780-6e264c80-79c6-11e9-8e34-281cbdbf3bbc.png)
![3](https://user-images.githubusercontent.com/44519124/57974781-6f577980-79c6-11e9-8ff2-34ec5c9de8fe.png)
---
2. Настройка RAID
![4](https://user-images.githubusercontent.com/44519124/57974782-7088a680-79c6-11e9-8107-f35ef494cb18.png)
---
3. Настройка LVM
![5](https://user-images.githubusercontent.com/44519124/57974783-71b9d380-79c6-11e9-9ded-eb73ca79e5e5.png)
![6](https://user-images.githubusercontent.com/44519124/57974784-72eb0080-79c6-11e9-9417-eba2770152fc.png)
![7](https://user-images.githubusercontent.com/44519124/57974786-74b4c400-79c6-11e9-9836-d2e47a875b55.png)
![8](https://user-images.githubusercontent.com/44519124/57974787-75e5f100-79c6-11e9-9e45-d8a7270e37f2.png)
---
4. Клонирование содержимого раздела boot с ssd1 на ssd2
![9](https://user-images.githubusercontent.com/44519124/57974862-1b4d9480-79c8-11e9-8140-a66b960060e0.png)
---
5. Вывод fdisk -l
![10_1](https://user-images.githubusercontent.com/44519124/57974790-77afb480-79c6-11e9-8b1b-bda80db9cb10.png)
![10_2](https://user-images.githubusercontent.com/44519124/57974792-7a120e80-79c6-11e9-84d1-15cfcd8bf3e7.png)
---
6. Вывод lsblk -o NAME,SIZE,FSTYPE,TYPE,MOUNTPOINT
![11](https://user-images.githubusercontent.com/44519124/57974908-acbd0680-79c8-11e9-96fe-403b3c3c49fe.png)
---
7. Установка grub на ssd2 и информация о текущем RAID. 
cat /proc/mdstat показывает, что в raid участвуют оба диска.
![12](https://user-images.githubusercontent.com/44519124/57974913-d24a1000-79c8-11e9-8091-c3cfe46b76c0.png)
---
8. Вывод команд pvs, lvs, vgs
![13](https://user-images.githubusercontent.com/44519124/57974948-5603fc80-79c9-11e9-9098-08f55b5149c3.png)
---
9. Вывод команды vgs
![14_1](https://user-images.githubusercontent.com/44519124/57974798-7ed6c280-79c6-11e9-852b-732fe842f4ec.png)
![14_2](https://user-images.githubusercontent.com/44519124/57974799-8007ef80-79c6-11e9-996e-eabfed0fd3af.png)
---
---
# Задание 2.
1. Удаление диска
![1](https://user-images.githubusercontent.com/44519124/57975211-a9784980-79cd-11e9-89a7-e07fb071530f.png)
![2](https://user-images.githubusercontent.com/44519124/57975212-aa10e000-79cd-11e9-82d3-16e838a15fb9.png)
---
2. Добавление нового диска
![3](https://user-images.githubusercontent.com/44519124/57975237-d62c6100-79cd-11e9-9abe-e6904bc32dd4.png)
---
3. Просмотр результата
![3_1](https://user-images.githubusercontent.com/44519124/57980785-2e984880-7a38-11e9-9275-8c7d79a666e5.png)
![4_1](https://user-images.githubusercontent.com/44519124/57975246-f2300280-79cd-11e9-8ee0-28bd40e7da72.png)
![4_2](https://user-images.githubusercontent.com/44519124/57975220-ad0bd080-79cd-11e9-82e6-1c699d480a28.png)
---
4. Копирование таблицы разделов на новый диск
![5_1](https://user-images.githubusercontent.com/44519124/57975332-67e89e00-79cf-11e9-8d5f-c2cec819046c.png)
![5_2](https://user-images.githubusercontent.com/44519124/57975222-af6e2a80-79cd-11e9-874f-80d4179d4737.png)
![5_3](https://user-images.githubusercontent.com/44519124/57975265-3e7b4280-79ce-11e9-9b3d-7884befe7395.png)
---
5. Добавление в RAID-массив нового диска
![6](https://user-images.githubusercontent.com/44519124/57975268-5b177a80-79ce-11e9-84c3-17e5d6b7be0c.png)
![7](https://user-images.githubusercontent.com/44519124/57975273-73879500-79ce-11e9-9a4f-ccfa76e1999a.png)
---
6. Синхронизация разделов, не входящих в RAID
![8](https://user-images.githubusercontent.com/44519124/57975226-b39a4800-79cd-11e9-992f-f0f85dadbb15.png)
---
7. Установка grub и просмотр RAID-массива
![9](https://user-images.githubusercontent.com/44519124/57975280-9023cd00-79ce-11e9-9017-24942b4c0cad.png)
---
---
# Задание 3
1. Эмуляция отказа диска ssd2 и просмотр состояния дисков и RAID
![1](https://user-images.githubusercontent.com/44519124/57985913-77232680-7a77-11e9-9901-3d94f13fb6a9.png)
![2_1](https://user-images.githubusercontent.com/44519124/57985916-7ab6ad80-7a77-11e9-9a0c-1181f26834e4.png)
![2_2](https://user-images.githubusercontent.com/44519124/57985917-7b4f4400-7a77-11e9-8908-14dbacbfc592.png)
![3](https://user-images.githubusercontent.com/44519124/57985918-8013f800-7a77-11e9-8679-2b08894dd2b2.png)
---
2. Добавление нового диска ssd4, просмотр изменений
![4_1](https://user-images.githubusercontent.com/44519124/57985920-81452500-7a77-11e9-958a-86f7751fac57.png)
![4_2](https://user-images.githubusercontent.com/44519124/57985924-82765200-7a77-11e9-9f90-d2c533c12304.png)
![5](https://user-images.githubusercontent.com/44519124/57985926-830ee880-7a77-11e9-87fe-8d1102e2410e.png)
---
3.  Копирование файловой таблицы со старого диска на новый. 
<<<<<<< HEAD
![6_1](https://user-images.githubusercontent.com/44519124/57985927-84401580-7a77-11e9-83c2-d3ce7c5a554f.png)
=======
![6_1](https://user-images.githubusercontent.com/44519124/57985927-84401580-7a77-11e9-83c2-d3ce7c5a554f.png)    
>>>>>>> aa10badfe32eb1d587792058edfc066d85e5bfc8
![6_2](https://user-images.githubusercontent.com/44519124/57985928-84d8ac00-7a77-11e9-9317-121de4e790c0.png)\
После выполнения команды sfdisk на новом диске (sdb) появились разделы sdb1 и sdb2.
![7](https://user-images.githubusercontent.com/44519124/57985930-8609d900-7a77-11e9-9e03-bc4e660b49ba.png)
---
4. Скопировали данные /boot с sda1 на sdb1
---
5. Перемонтировали /boot на новый диск (sdb) и установили grub
![8](https://user-images.githubusercontent.com/44519124/57989029-d5fb9680-7a9d-11e9-8e75-b5552d923cd3.png)
![9](https://user-images.githubusercontent.com/44519124/57985933-87d39c80-7a77-11e9-93eb-4d2859971579.png)\
<<<<<<< HEAD
Мы выполнили команду grub-install /dev/sdb, чтобы установить загрузчик группы на новый диск.
---
6. Создаем новый RAID-массив с включением только одного диска sdb
![10](https://user-images.githubusercontent.com/44519124/57985934-8904c980-7a77-11e9-8564-8e3cb3f49625.png)\
Команда mdadm работает с ключом --force \
Добавился RAID-массив md63 с одним диском \
![11](https://user-images.githubusercontent.com/44519124/57989127-04c63c80-7a9f-11e9-97c1-8a98118db306.png)\
Отображается в дереве lsblk новый RAID-массив на диске sdb \
=======
Мы выполнили команду grub-install /dev/sdb, чтобы установить загрузчик группы на новый диск.\

---
6. Создаем новый RAID-массив с включением только одного диска sdb\
![10](https://user-images.githubusercontent.com/44519124/57985934-8904c980-7a77-11e9-8564-8e3cb3f49625.png)\
Команда mdadm работает с ключом --force\
Добавился RAID-массив md63 с одним диском\
![11](https://user-images.githubusercontent.com/44519124/57989127-04c63c80-7a9f-11e9-97c1-8a98118db306.png)\
Отображается в дереве lsblk новый RAID-массив на диске sdb\
>>>>>>> aa10badfe32eb1d587792058edfc066d85e5bfc8
![12](https://user-images.githubusercontent.com/44519124/57985938-8b672380-7a77-11e9-8f16-cfb19f3e0caa.png)\
В выводе команды pvs появился второй RAID. \
![13](https://user-images.githubusercontent.com/44519124/57985939-8b672380-7a77-11e9-80e7-cd55a054b04e.png)
---
7. Увеличиваем размер Volume Group
![14_1](https://user-images.githubusercontent.com/44519124/57985941-8c985080-7a77-11e9-8e76-ceffc66c887b.png)
![14_2](https://user-images.githubusercontent.com/44519124/57985943-8d30e700-7a77-11e9-87e2-5f5899238945.png)
![14_3](https://user-images.githubusercontent.com/44519124/57985944-8e621400-7a77-11e9-8b54-62d1d4ab36a8.png)
![14_4](https://user-images.githubusercontent.com/44519124/57985947-8efaaa80-7a77-11e9-97ed-9229585bfec2.png)\
LV var, log, root находятся на старом диске (md0) \
![15](https://user-images.githubusercontent.com/44519124/57985949-902bd780-7a77-11e9-9144-88d5c48b119f.png)
![16](https://user-images.githubusercontent.com/44519124/57985950-90c46e00-7a77-11e9-9956-ee0fd6fd3996.png)
---
8. Перемещение данных со старого диска на новый.
![17](https://user-images.githubusercontent.com/44519124/57985952-91f59b00-7a77-11e9-89f0-ff47e319b03a.png)
---
9. Просмотр изменений \
![18_1](https://user-images.githubusercontent.com/44519124/57985953-9326c800-7a77-11e9-83af-9480343e093e.png)
![18_2](https://user-images.githubusercontent.com/44519124/57985955-9457f500-7a77-11e9-9070-a74e0334e5eb.png)
![18_3](https://user-images.githubusercontent.com/44519124/57985956-94f08b80-7a77-11e9-949e-956b239e3919.png)
![18_4](https://user-images.githubusercontent.com/44519124/57985958-96ba4f00-7a77-11e9-8b38-01a3dd1fac24.png) \
После команды pvs видно, что для нового массива появился физический том. LV var, log, root находятся на новом диске. \
![19_1](https://user-images.githubusercontent.com/44519124/57985960-991ca900-7a77-11e9-9c36-b457a65f8258.png)
![19_2](https://user-images.githubusercontent.com/44519124/57985961-9a4dd600-7a77-11e9-8d71-323c9373a8b2.png)
---
10. Удаление старого диска из RAID-массива.
![20](https://user-images.githubusercontent.com/44519124/57985962-9ae66c80-7a77-11e9-8fcc-06d2226119d3.png)
![21](https://user-images.githubusercontent.com/44519124/57988508-135d2580-7a98-11e9-96f8-50c2759bd51e.png)
---
11. Подключение новых дисков.
![22](https://user-images.githubusercontent.com/44519124/58008147-71b7f180-7af4-11e9-8533-c6822d3bccb0.png)
![23_1](https://user-images.githubusercontent.com/44519124/57988510-18ba7000-7a98-11e9-8892-7826442b6c4d.png)
---
12. Копирование таблицы разделов
![24_1](https://user-images.githubusercontent.com/44519124/57988511-1b1cca00-7a98-11e9-82d4-87467906e83e.png)
![24_2](https://user-images.githubusercontent.com/44519124/57988512-1c4df700-7a98-11e9-809f-98700068cd03.png)
---
13. Копирование /boot
![25](https://user-images.githubusercontent.com/44519124/57988513-1ce68d80-7a98-11e9-8264-8e96f4397b9b.png)
---
14. Изменение размера второго диска.
![26](https://user-images.githubusercontent.com/44519124/57988516-1eb05100-7a98-11e9-8563-555b5cae87d2.png)
![27](https://user-images.githubusercontent.com/44519124/57988517-1fe17e00-7a98-11e9-9426-50dff5709988.png)
![28](https://user-images.githubusercontent.com/44519124/58008477-26eaa980-7af5-11e9-973c-ddcf79637ea8.png)
---
15. Добавление диска к текущему RAID-массиву.
![29_1](https://user-images.githubusercontent.com/44519124/57988521-25d75f00-7a98-11e9-8526-4b11b2e3274e.png)
![29_2](https://user-images.githubusercontent.com/44519124/57988524-2a9c1300-7a98-11e9-981a-da561d4c726a.png)
---
16. Расширение количества дисков.
![30](https://user-images.githubusercontent.com/44519124/57988557-6931cd80-7a98-11e9-95d3-b95e56669cef.png)
![31](https://user-images.githubusercontent.com/44519124/57988525-2b34a980-7a98-11e9-9307-a5c93e0b85dd.png)
---
17. Изменение размера первого диска.
![32_1](https://user-images.githubusercontent.com/44519124/57988526-2c65d680-7a98-11e9-92ad-fbd61824b892.png)
![32_2](https://user-images.githubusercontent.com/44519124/57988527-2d970380-7a98-11e9-8b54-9ccc8195f330.png)
![33](https://user-images.githubusercontent.com/44519124/57988528-2e2f9a00-7a98-11e9-8a92-d858392b3403.png)
---
18. Расширение RAID
![34](https://user-images.githubusercontent.com/44519124/57988530-2ec83080-7a98-11e9-90fe-ec238d0b1df7.png)
---
19. Расширение размера PV.
![35](https://user-images.githubusercontent.com/44519124/57988531-2ff95d80-7a98-11e9-8713-dc358b57acc3.png)
![36](https://user-images.githubusercontent.com/44519124/57988532-312a8a80-7a98-11e9-9661-a13303bcaf46.png)
---
20. Создание RAID из дисков sdc и sdd.
![37](https://user-images.githubusercontent.com/44519124/57988533-325bb780-7a98-11e9-9de6-2fa367481fb5.png)
![38](https://user-images.githubusercontent.com/44519124/57988534-32f44e00-7a98-11e9-8343-0276c562a56d.png)
---
21. Создание нового PV.
![39_1](https://user-images.githubusercontent.com/44519124/57988535-338ce480-7a98-11e9-90a1-05d8902b1649.png)
![39_2](https://user-images.githubusercontent.com/44519124/57988536-34be1180-7a98-11e9-8bf8-e73443ccd6f2.png)
---
22. Перенос данных со старого раздела на новый.
![40](https://user-images.githubusercontent.com/44519124/57988548-50291c80-7a98-11e9-8a3e-9d3929740030.png)

![41_1](https://user-images.githubusercontent.com/44519124/57988537-35ef3e80-7a98-11e9-9dd9-18141a45c14a.png)
![41_2](https://user-images.githubusercontent.com/44519124/57988538-3a1b5c00-7a98-11e9-860a-b0d27d59b855.png)
![42](https://user-images.githubusercontent.com/44519124/57988539-3be51f80-7a98-11e9-9bdd-3d7677878e6d.png)
![43](https://user-images.githubusercontent.com/44519124/57988544-469fb480-7a98-11e9-80a4-8030ed591ada.png)
---
23. Перемена разделов.
![44_1](https://user-images.githubusercontent.com/44519124/57988540-3daee300-7a98-11e9-9869-d634d2bdc1e5.png)
![44_2](https://user-images.githubusercontent.com/44519124/57988541-3ee01000-7a98-11e9-897e-759bbed0e4f7.png)
---
24. Изменение /etc/fstab.
![45](https://user-images.githubusercontent.com/44519124/57988896-2e319900-7a9c-11e9-93ff-cfdeaa3cc58a.png)
---
25. Выполнение проверок.
![46](https://user-images.githubusercontent.com/44519124/57988897-3093f300-7a9c-11e9-8e70-85ff3764e07c.png)
![47_1](https://user-images.githubusercontent.com/44519124/57988898-31c52000-7a9c-11e9-9094-ef4ae25769e9.png)
![47_2](https://user-images.githubusercontent.com/44519124/57988899-32f64d00-7a9c-11e9-90f3-d68bbb196cbd.png)

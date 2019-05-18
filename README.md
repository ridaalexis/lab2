# Задание 1

![1](https://user-images.githubusercontent.com/44519124/57974776-5949b900-79c6-11e9-9fe2-6673d617d0af.png)
![2](https://user-images.githubusercontent.com/44519124/57974780-6e264c80-79c6-11e9-8e34-281cbdbf3bbc.png)
![3](https://user-images.githubusercontent.com/44519124/57974781-6f577980-79c6-11e9-8ff2-34ec5c9de8fe.png)

1. Настройка RAID
![4](https://user-images.githubusercontent.com/44519124/57974782-7088a680-79c6-11e9-8107-f35ef494cb18.png)
---
2. Настройка LVM
![5](https://user-images.githubusercontent.com/44519124/57974783-71b9d380-79c6-11e9-9ded-eb73ca79e5e5.png)
![6](https://user-images.githubusercontent.com/44519124/57974784-72eb0080-79c6-11e9-9417-eba2770152fc.png)
![7](https://user-images.githubusercontent.com/44519124/57974786-74b4c400-79c6-11e9-9836-d2e47a875b55.png)
![8](https://user-images.githubusercontent.com/44519124/57974787-75e5f100-79c6-11e9-9e45-d8a7270e37f2.png)
---
3. Клонирование содержимого раздела boot с ssd1 на ssd2
![9](https://user-images.githubusercontent.com/44519124/57974862-1b4d9480-79c8-11e9-8140-a66b960060e0.png)
---
4. Вывод fdisk -l
![10_1](https://user-images.githubusercontent.com/44519124/57974790-77afb480-79c6-11e9-8b1b-bda80db9cb10.png)
![10_2](https://user-images.githubusercontent.com/44519124/57974792-7a120e80-79c6-11e9-84d1-15cfcd8bf3e7.png)
---
5. Вывод lsblk -o NAME,SIZE,FSTYPE,TYPE,MOUNTPOINT
![11](https://user-images.githubusercontent.com/44519124/57974908-acbd0680-79c8-11e9-96fe-403b3c3c49fe.png)
---
6. Установка grub на ssd2 и информация о текущем RAID. 
cat /proc/mdstat показывает, что в raid участвуют оба диска.
![12](https://user-images.githubusercontent.com/44519124/57974913-d24a1000-79c8-11e9-8091-c3cfe46b76c0.png)
---
7. Вывод команд pvs, lvs, vgs
![13](https://user-images.githubusercontent.com/44519124/57974948-5603fc80-79c9-11e9-9098-08f55b5149c3.png)
---
8. Вывод команды vgs
![14_1](https://user-images.githubusercontent.com/44519124/57974798-7ed6c280-79c6-11e9-852b-732fe842f4ec.png)
![14_2](https://user-images.githubusercontent.com/44519124/57974799-8007ef80-79c6-11e9-996e-eabfed0fd3af.png)
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
![4_1](https://user-images.githubusercontent.com/44519124/57975246-f2300280-79cd-11e9-8ee0-28bd40e7da72.png)
![4_2](https://user-images.githubusercontent.com/44519124/57975220-ad0bd080-79cd-11e9-82e6-1c699d480a28.png)
---
4. Копирование таблицы разделов на новый диск
![5_1](https://user-images.githubusercontent.com/44519124/57975332-67e89e00-79cf-11e9-8d5f-c2cec819046c.png)
![5_2](https://user-images.githubusercontent.com/44519124/57975222-af6e2a80-79cd-11e9-874f-80d4179d4737.png)
![5_3](https://user-images.githubusercontent.com/44519124/57975265-3e7b4280-79ce-11e9-9b3d-7884befe7395.png)
---
5. Добавление в RAID-массиы нового диска
![6](https://user-images.githubusercontent.com/44519124/57975268-5b177a80-79ce-11e9-84c3-17e5d6b7be0c.png)
![7](https://user-images.githubusercontent.com/44519124/57975273-73879500-79ce-11e9-9a4f-ccfa76e1999a.png)
---
6. Синхронизация разделов, не входящих в RAID
![8](https://user-images.githubusercontent.com/44519124/57975226-b39a4800-79cd-11e9-992f-f0f85dadbb15.png)
---
7. Установка grub и просмотр RAID-массива
![9](https://user-images.githubusercontent.com/44519124/57975280-9023cd00-79ce-11e9-9017-24942b4c0cad.png)
---
# Задание 3


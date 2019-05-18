#Задание 1

![1](https://user-images.githubusercontent.com/44519124/57974776-5949b900-79c6-11e9-9fe2-6673d617d0af.png)
![2](https://user-images.githubusercontent.com/44519124/57974780-6e264c80-79c6-11e9-8e34-281cbdbf3bbc.png)
![3](https://user-images.githubusercontent.com/44519124/57974781-6f577980-79c6-11e9-8ff2-34ec5c9de8fe.png)

1. Настройка RAID
![4](https://user-images.githubusercontent.com/44519124/57974782-7088a680-79c6-11e9-8107-f35ef494cb18.png)

2. Настройка LVM
![5](https://user-images.githubusercontent.com/44519124/57974783-71b9d380-79c6-11e9-9ded-eb73ca79e5e5.png)
![6](https://user-images.githubusercontent.com/44519124/57974784-72eb0080-79c6-11e9-9417-eba2770152fc.png)
![7](https://user-images.githubusercontent.com/44519124/57974786-74b4c400-79c6-11e9-9836-d2e47a875b55.png)
![8](https://user-images.githubusercontent.com/44519124/57974787-75e5f100-79c6-11e9-9e45-d8a7270e37f2.png)

3. Клонирование содержимого раздела boot с ssd1 на ssd2
![9](https://user-images.githubusercontent.com/44519124/57974862-1b4d9480-79c8-11e9-8140-a66b960060e0.png)

4. Вывод fdisk -l
![10_1](https://user-images.githubusercontent.com/44519124/57974790-77afb480-79c6-11e9-8b1b-bda80db9cb10.png)
![10_2](https://user-images.githubusercontent.com/44519124/57974792-7a120e80-79c6-11e9-84d1-15cfcd8bf3e7.png)

5. Вывод lsblk -o NAME,SIZE,FSTYPE,TYPE,MOUNTPOINT
![11](https://user-images.githubusercontent.com/44519124/57974908-acbd0680-79c8-11e9-96fe-403b3c3c49fe.png)

6. Установка grub на ssd2 и информация о текущем raid. 
cat /proc/mdstat показывает, что в raid участвуют оба диска.
![12](https://user-images.githubusercontent.com/44519124/57974913-d24a1000-79c8-11e9-8091-c3cfe46b76c0.png))

7. Вывод команд pvs, lvs, vgs
![13](https://user-images.githubusercontent.com/44519124/57974948-5603fc80-79c9-11e9-9098-08f55b5149c3.png)

8. Вывод команды vgs
![14_1](https://user-images.githubusercontent.com/44519124/57974798-7ed6c280-79c6-11e9-852b-732fe842f4ec.png)
![14_2](https://user-images.githubusercontent.com/44519124/57974799-8007ef80-79c6-11e9-996e-eabfed0fd3af.png)

#Задание 2.

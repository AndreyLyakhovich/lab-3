# lab-3

## Лабораторная работа №3. Виртуализация.

1. Настроил виртуальную машину А с Ubuntu, обеспечил доступ в интернет через NAT. Проверка доступа в интернет в файле "machine_A_internet_connection.jpeg"

2. Настроил вторую виртуальную машину В и обеспечил сетевой доступ из машины А в машину В с помощью внутренней сети intnet1.
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/A-to-B_connection.jpeg)
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/B-to-A_connection.jpeg)

3. Настроил третью виртуальную машину V и обеспечил сетевой доступ из машины А в машину V с помощью внутренней сети intnet2.
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/A-to-V_connection.jpeg)
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/V-to-A_connection.jpeg)

4. Доступа друг к другу у машин В и V нет, так как они отдельны друг от друга. Внутренняя сеть соединяет их только с машиной А.
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/con_disabled_from_B-to-V.jpeg)
   
   ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/con_disabled_from_V-to-B.jpeg)

Все скриншоты находятся в директории /report/

Интернет соединение Машины А ![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/machine_A_internet_connection.jpeg)
ip машины А 

![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/ubuntu_machine_A.jpeg)

ip машины B 

![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/arch_machine_B.jpeg)

ip машины V 

![](https://github.com/AndreyLyakhovich/lab-3/blob/45edddddc6232b72653aea0a55ab84d697826105/report/kali_machine_V.jpeg)

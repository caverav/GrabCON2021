# GrabCON{345y_R3v} (100 pts)
Categoría: Reversing
## Descripción
![image](https://user-images.githubusercontent.com/66751764/132142305-7b71e095-feaa-4bdc-beb3-3a4c000c6ff8.png)
## Solución
En este desafío lo primero fue ejecutar el archivo:

![image](https://user-images.githubusercontent.com/66751764/132142371-702b3323-b603-4f6d-bbaf-9bd98734a43b.png)

Pero pide una clave, la cual obviamente no sabemos, por lo que ahora iremos a abrirlo con *Ghidra*:

![image](https://user-images.githubusercontent.com/66751764/132142417-8d85934e-afb3-478c-8d6a-d7ab62ea762d.png)

Luego buscando dentro de las funciones, encuentro la función *FUN00101277*, la cual contiene el proceso de la consulta de clave para el usuario:

![image](https://user-images.githubusercontent.com/66751764/132142514-bc5eb21c-883d-46da-b60f-6f22575fded7.png)

Se puede observar que el input que recibe del usuario se guarda en la variable *local_20* para luego en *001012e7 CMP* comparar *local_20* con *local_14*, lo que quiere decir que *local_14* es la clave, la cual tiene asignado el valor de *0x140685*:

![image](https://user-images.githubusercontent.com/66751764/132142581-29ef24fb-226e-4f6d-bdee-ad205cab27a1.png)

Lo que quiere decir que 0x140685 es nuestra clave, pero así como así no funciona, necesita un valor decimal, por lo que lo transformamos a decimal:

![image](https://user-images.githubusercontent.com/66751764/132142618-1c3a8ed6-3b08-4ec5-8cb2-47e4a881f04d.png)

Ahora probemos si funciona:

![image](https://user-images.githubusercontent.com/66751764/132142626-8956c65d-1d65-4109-b63d-844a2491d54e.png)

Finalmente la flag es **GrabCON{y0u_g0t_it_8bb31}**

# GrabCON{V1c71m_1} (150pts)
Categoría: OSINT
## Descripción

![image](https://user-images.githubusercontent.com/66751764/132142766-c3b3b38b-4fc8-41c3-b355-001d80d8140e.png)

## Solución

Lo primero es abrir el link (Live Camera), el cual lleva a una cámara en vivo:

![image](https://user-images.githubusercontent.com/66751764/132142757-5c5ae392-1458-44a9-acb9-cc2d16f6bc07.png)

Pero lo que importa no es lo que se ve, sino la dirección IP del dispositivo (*31.207.115.133*), entonces se procede a buscar información de la IP (en mi caso por ip2location)

![image](https://user-images.githubusercontent.com/66751764/132142761-82fba7c2-9918-4177-81af-eb6228e1b8d6.png)

Donde claramente se ve el código postal (zipcode), por lo que la flag resultante es **GrabCON{39031}**

# GrabCON{V1c71m_1} (150pts)
Categoría: OSINT
## Descripción
We got to know our victims is hiding somewhere. We got access to live CCTV camera of that place. Can you find zip code of that location?

Live Camera (un link a http://31.207.115.133:8080/cgi-bin/faststream.jpg?stream=half&fps=15&rand=COUNTER)

GrabCON{zipcode}

Author: CETACEAN

## Solución

Lo primero es abrir el link, el cual lleva a una cámara en vivo:

![Cam](https://github.com/caverav/GrabCON2021/blob/main/Victim1Cam.png)

Pero lo que importa no es lo que se ve, sino la dirección IP del dispositivo (*31.207.115.133*), entonces se procede a buscar información de la IP (en mi caso por ip2location)

![Info](https://github.com/caverav/GrabCON2021/blob/main/Victim1ip.png)

Donde claramente se ve el código postal (zipcode), por lo que la flag resultante es **GrabCON{39031}**

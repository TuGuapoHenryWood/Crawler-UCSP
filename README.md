# Crawler-UCSP
Integrantes: Santiago Sotillo, Iair Suico, Henry Wood

Este programa nos permite indexar páginas web, buscando la interrelación entre cada una de estas para su posterior uso en un buscador.
CONTENIDO DEL CÓDIGO:
Para comenzar se creó un diccionario el donde las claves sean todos las urls, y los valores sean todos los links distintos encontrados en cada página diferente, a esos links también conocidos como links salientes. A continuación parte del código imprime dos rankings de páginas de acuerdo a:
- El número de links salientes distintos .
- El número de links entrantes distintos.(Invierte el diccionario creado)
Y para finalizar imprime un ranking de las páginas de acuerdo a mayor valor obtenido en:
- Rank = e/s.

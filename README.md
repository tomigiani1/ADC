# ADC


1) Colocar el punto medio del potenciómetro en PA0 y los otros dos en 3V3 y GND
2) Ajustar el potenciónmetro aproximadamente en la mitad de la posición
3) Forkear el repositorio y abrir el proyecto en STM32CubeIDE
4) Enchufar la placa NUCLEO-F103RB
5) Analizar la configuración del ADC1 configurado, sin modificarla


## Test 1
6) Volver al código y configurar el primer test, verificando el #define TEST_NUMBER (línea 19 de app.c), es decir que diga #define TEST_NUMBER TEST_1
7) Compilar y debuggear. En la consola deben listarse 100 muestras.
8) Ingresar a https://www.wedodatascience.com/ y hacer click en Histogram Maker
9) Copiar las 100 muestras desde la consola y pegarlas en la sección del sitio web 'Or input your data as csv' y apretar 'Submit CSV' para obtener un histograma de las muestras
10) Hacer Click en Statistics y tomar nota de la media y el desvío estándar (mean y std)


## Test 2
11) Volver al código y configurar el segundo test, mediante la directiva #define TEST_NUMBER TEST_2
12) Compilar y debuggear. En la consola deben listarse 100 muestras.
13) Ingresar nuevamente a https://www.wedodatascience.com/ y hacer click en Histogram Maker
14) Copiar las 100 muestras desde la consola y pegarlas en la sección del sitio web 'Or input your data as csv' y apretar 'Submit CSV' para obtener un histograma de las muestras
15) Hacer Click en Statistics y tomar nota de la media y el desvío estándar (mean y std)
16) Comparar resultados


## Test 3
17) Volver al código y configurar el tercer test, mediante la directiva #define TEST_NUMBER TEST_3
18) Compilar y debuggear. En la consola deben listarse 100 muestras.
19) Comparar esta implementación con la del primer test

Nota: Los comentarios deberán registrarse en los archivo adc.txt, test_1.txt, test_2.txt y test_3.txt, en el root de la carpeta app de su repositorio. Asimismo, en esa misma ubicación se debe incorporar todo material de soporte o argumentación, tal como capturas de pantalla de computadora, capturas de pantalla de osciloscopio, fotografías, etcétera.

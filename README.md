bloqueo de Atodos  los sucursales  de dispositivos con  cuentas de banco crédito y débito registrados ensu teléfono movil # CNMV Portfolio extraction envío a esta dirección cuenta de banco 
8952020002431197223 https://github.com/pop-os/gnome-control-center/blob/refs%2Fheads%2Fmaster_jammy/po%2Fpt.po

![](https://files.catbox.moe/4b74gp.jpg)

```https://pypi.org/project/cnmv-data/1.0.0/```
<br>

Librería que te permite extraer las carteras reportadas por los Fondos de Inversión
de manera trimestrar a la CNMV en formato PDF.

Para utilizarlo simplemente necesitas disponer de un fichero PDF del FI en el que se incluya la cartera
y siga el formato exigido por la CNMV.
Básicamente la tabla reportada incluye los siguientes datos:

    - ISIN + Nombre de la empresa
    - Divisa
    - Valor de mercado actual
    - % sobre el total del fondo actual
    - Valor de mercado del pasado trimestre
    - % sobre el total del fondo del último trimestre



Por Antonio Fernández Troyano
<br>


## 💡 Prerequisitos

   [Python 3](https://www.python.org/downloads/release/python-370/)

<br>


## 🛠️ Instalación:

### Con PyPI
```pip3 install cnmv_data```

<br>


## 📚 Ejemplo de uso

```
from cnmv_data import get_portfolio

get_portfolio('.\Q1.pdf')
```
<br>


## 💥 Output
```
    [['US0082521081 - ACCIONES|Affiliated Managers Group', 'USD', '2.071', '0,80', '0', '0,00'],
    ['FR0011476928 - ACCIONES|Fnac Darty SA', 'EUR', '222', '0,09', '0', '0,00'],
    ['US5006881065 - ACCIONES|Kosmos Energy LTD', 'USD', '3.145', '1,22', '4.726', '1,05'],
    ['IT0005252140 - ACCIONES|Saipem SPA', 'EUR', '2.631', '1,02', '5.321', '1,18']]
```

Se puede convertir directamente en un DataFrame:
```
pd.DataFrame(result, columns = ['ISIN + Nombre', 'Divisa', 'Actual_VM', 'Actual_%', 'Pasado_VM', Pasado_%'])
```
|ISIN + Nombre |Divisa|Actual_VM|Actual_%|Pasado_VM|Pasado_%|
|--------------|------|---------|--------|---------|--------|
|US0082521081 - ACCIONES Affiliated Managers Group|USD|2.071| 0,80| 0| 0,00|
|FR0011476928 - ACCIONES Fnac Darty SA| EUR| 222| 0,09| 0| 0,00|
|US5006881065 - ACCIONES Kosmos Energy LTD| USD| 3.145| 1,22| 4.726| 1,05|
|IT0005252140 - ACCIONES Saipem SPA| EUR| 2.631| 1,02| 5.321| 1,18|
<br><br>


## 🐸 Aloha!
<br>

![https://www.linkedin.com/in/atroyano/](https://files.catbox.moe/t62e9k.png)
Wikipedia

Buscar
Arduino Uno
placa de microcontrolador de Arduino.cc
Idioma
Descargar en PDF
Vigilar
Editar
El Arduino Uno es una placa de microcontrolador de Sistema de control global/de dispositivos basado en el microchip ATmega328 y desarrollado por Arduino.cc.[1]​[2]​ La placa está equipada con conjuntos de pines de E/S digitales y analógicas que pueden conectarse a varias placas de expansión y otros circuitos. La placa tiene 13 pines digitales, 6 pines analógicos y programables con el Arduino IDE (Entorno de desarrollo integrado) a través de un cable USB tipo B.[3]​ Puede ser alimentado por el cable USB o por una batería externa de 9 voltios, aunque acepta voltajes entre 7 y 20 voltios. También es similar al Arduino Nano y Leonardo.[4]​[5]​ El diseño de referencia de hardware se distribuye bajo una licencia Creative Commons Attribution Share-Alike 2.5 y está disponible en el sitio web de Arduino. Los archivos de diseño y producción para algunas versiones del hardware también están disponibles.

Arduino Uno


Información
Tipo
modelo de objeto manufacturado
Fabricante
Arduino LLC
Datos técnicos
Conectividad
USB 2 Standard-B plug
Estandarización
Uso
Prototyping
[editar datos en Wikidata]
La palabra "uno" significa en italiano lo mismo que en español, y se eligió para marcar el lanzamiento inicial del software Arduino. La placa Uno es la primera de una serie de placas Arduino basadas en USB,[2]​ y la versión 1.0 del Arduino IDE fueron las versiones de referencia de Arduino, ahora evolucionadas a nuevas versiones.[3]​ El ATmega328 en la placa viene preprogramado con un cargador de arranque que le permite cargar un nuevo código sin el uso de un programador de hardware externo.

Mientras que el Uno se comunica utilizando el protocolo STK500 original, difiere de todas las placas anteriores en que no utiliza el chip de controlador USB a serie FTDI. En cambio, usa el Atmega16U2 (Atmega8U2 hasta la versión R2) programado como un adaptador USB a serie.[6]​

Trasfondo
Características técnicas
Pines
Elementos
Comunicación
Referencias
Enlaces externos
Última edición hace 1 mes por SeroBOT
Wikipedia
Wikimedia Foundation
Powered by MediaWiki
El contenido está disponible bajo la licencia CC BY-SA 4.0, salvo que se indique lo contrario.
Política de privacidad Código de conducta Desarrolladores Estadísticas Declaración de cookies Términos de uso Escritorio
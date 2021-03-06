# PCBPrint Buzzer para transistores NPN y patillaje EBC

Un pequeño accesorio para imprimir en 3D y poder utilizar un buzzer con el patillaje del transistor en EBC.(1.Emisor 2.Base 3.Colector)

## Comenzemos!!! 🚀

Esto es lo que te vas a encontrar en este proyecto. Un pequeño accesorio para poder montar un Buzzer y un Led de 5mm pudiendo tener así
una percepcion visual y auditiva en tus proyectos.

<p align="center">
  <img src="https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/blob/master/PCBPrint%20buzzer%20EBC/Imagenes/PCBPrint%20buzzer%20EBC.jpg"></p>
  

Mira la carpeta [**Archivos**](https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/tree/master/PCBPrint%20buzzer%20EBC/Archivos) para descargar el archivo en diferentes formatos.


### Pre-requisitos 📋

Para realizar este proyecto necesitas estas cositas:

- Impresora 3D ya sea de tipo FDM o SLA<br/>
- Buzzer 3-5V<br/>
- Led de 5mm<br/>
- 2 Resistencias (depende del transistor que utilices)<br/>
- Conector macho macho en ángulo recto para placas PCB<br/>
- Un poquito de cable, o alambre fino.<br/>
- Estaño y soldador.<br/>

### Instalación 🔧

**1-** Una vez hayamos descargado el archivo .STL [desde aquí](https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/blob/master/PCBPrint%20buzzer%20EBC/Archivos/PCBPrint%20buzzer%20EBC.stl)
y lo tengamos impreso en 3D lo siguiente que debemos hacer es buscar un transistor NPN con encapsulado TO-92 y el siguiente patillaje, este requisito es obligatorio pues la pieza esta diseñada para transistores con patillaje EBC.

<p align="center">
  <img src="https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/blob/master/PCBPrint%20buzzer%20EBC/Imagenes/Transistor%20EBC.jpg"></p>

**2-**
Utilizar una resistencia para la base de entre 2k2 y 15K ya que el led y el buzzer juntos no consumen mas de 45 Miliamperios (calcular con el datasheed del transistor que utilices)
Para el led y el buzzer puedes poner una resistencia minima de 10 Ohm o de hasta 220 Ohm para no quitarle mucha intensidad al sonido.

**3-**
Montar los componentes siguiendo el siguiente esquema. Tener en cuenta la polaridad del led y el Buzzer
<p align="center">
  <img src="https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/blob/master/PCBPrint%20buzzer%20EBC/Imagenes/PCBPrint%20buzzer%20EBC%20Pistas%20dibujadas.jpg"></p>
  
  **4-**
  El resultado deberia ser algo parecido a esto.
  
  <p align="center">
  <img src="https://github.com/altenife/Things-Cosas-FPGAs-y-Arduino/blob/master/PCBPrint%20buzzer%20EBC/Imagenes/buzzer.jpg"></p>
  

## Construido con 🛠️

* [FreeCad](https://github.com/FreeCAD/FreeCAD) - El software libre de diseño gráfico por excelencia
* [Marlin](https://github.com/MarlinFirmware/Marlin) - Firmware para impresoras RepRap 3D basadas en Arduino
* [Arduino](https://github.com/arduino/Arduino) - Plataforma electronica de codigo abierto.


## Agradecimientos 🖇️

* [Obijuan](https://github.com/Obijuan) Al mejor profesor!!, que gracias a el, a su dedicación, y profesionalidad he sido capaz de aprender todo esto con sus cursos de [FPGAs libres](https://github.com/Obijuan/digital-electronics-with-open-FPGAs-tutorial/wiki) y [FreeCad](https://github.com/Obijuan/tutoriales-freecad)
* [FPGAwars](https://github.com/FPGAwars) - Por el esfuerzo y dedicación que esta realizando todo el equipo.
* [Libreria de componentes de FreeCad](https://github.com/FreeCAD/FreeCAD-library) -Por facilitar los componentes.


## Autores ✒️

* **Alberto Nicas** - *Creador* - [Altenife](https://github.com/altenife)

## Expresiones de Gratitud 🎁

* Si te gusta, comparte este proyecto 📢
* Mencioname si mejoras este proyecto 🤓.
* Mencioname si utilizas este PCBPrint en tus proyectos.


---
⌨️ con ❤️ por [Altenife](https://github.com/altenife) 😊

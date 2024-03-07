# G1T1-2023.MusicLight

## INTEGRANTES
  + Gonzalez Yaguachi David
  + Marquez Aguilar Jaime
  
## DEFINICION DEL PROYECTO
  
  El proyecto consiste en la elaboracion de un modulo regulador de luces led para
  que enciendan al ritmo de la musica. En este se puede regular la intencidad de la     luz y escoger mediante una switchera el color que se desea encender. Es importante    recalcar que se pueden encender varios colores a la vez.

  Para la elaboracion de este modulo, se dividido en 3 etapas:
  + Etapa de regulacion
  + Etapa de amplifiacion de baja potencia
  + Etapa de amplificacion de alta potencia

  ### **Etapa de regulacion**
      Esta etapa consiste en la regulacion de la intensidad de la luz, mediante el          uso de un potenciometro de 100K, lo que tambien limita la sensibilidad del            microfono electrec que recibe el sonido de la musica.

  
  ### **Etapa de amplificacion de baja potencia**
      El transistor 2N2222 se encarga de amplificar la pequeña señal del micrófono y, mediante el emisor, envía una corriente al transistor TIP31C para la siguiente etapa. Cabe mencionar que el 2N2222 controla al TIP31C, que tiene mayor potencia.


  ### **Etapa de amplificacion de alta potencia**
     El transistor TIP31C se encarga de encender y apagar las luces LED que necesitan 12V mediante la señal del 2N2222, dado que el transistor TIP31C tiene una mayor capacidad para manejar altos voltajes.

  
## TABLA DE MATERIALES Y PRECIOS
  La sigueinte tabla describe los materiales usados y el precio de cada uno:
  ![tabla de precios](https://github.com/ProjectsPhycom/G1T1-2023.MusicLight/assets/145176980/eee24e56-e6f6-4237-b24d-b8e573970090)

## POSIBLES MEJORAS
  Una posible mejora del proyecto es hacer que funcione con los mandos que vienen incluidos en las luces led para evitar switcheras y poder usar el control remoto, ya que esto permitiria mayor comodidad.

## DISEÑO DEL CIRCUITO
A continuacion se presenta el circuito de funcionamiento en proteus:
![implementación en proteus](https://github.com/ProjectsPhycom/G1T1-2023.MusicLight/assets/145176980/2ef0ec98-e4c4-4cce-8541-5ede310146f0)

Link de simulacion en proteus: 
[link one drive](https://espolec-my.sharepoint.com/:u:/g/personal/dagoyagu_espol_edu_ec/EeW5ns1FAM9PusF22X_aFMYBNWhQNbyjxmHYlV9QIrSvqg?e=69tee4)

## VIDEO DE FUNCIONAMIENTO
A continuacion se adjunta el link de one drive con el video del funcionamiento:
[video](https://espolec-my.sharepoint.com/:v:/g/personal/dagoyagu_espol_edu_ec/ESzI-ldHZeRAnfh8Id7v0NIB1POX-gterjhPGcaQVJzsDg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0RpcmVjdCJ9fQ&e=eQ2FCr)



<h1 align="center"> [MUSIC LIGHTS] </h1>
<p align="center"><img src="https://www.webdevelopersnotes.com/wp-content/uploads/create-a-simple-home-page.png"/></p> 


## Descripcion  📋
---
 El proyecto consiste en la elaboracion de un modulo regulador de luces led para
  que enciendan al ritmo de la musica. En este se puede regular la intencidad de la     luz y escoger mediante una switchera el color que se desea encender. Es importante    recalcar que se pueden encender varios colores a la vez.



## Pre-requisitos  📋

Para la elaboracion de este modulo, se dividido en 3 etapas:
  + Etapa de regulacion
  + Etapa de amplifiacion de baja potencia
  + Etapa de amplificacion de alta potencia

  ### **Etapa de regulacion**
      Esta etapa consiste en la regulacion de la intensidad de la luz,  
      mediante el uso de un potenciometro de 100K, lo que tambien limita  
      la sensibilidad del microfono electrec que recibe el sonido de la musica.

  
  ### **Etapa de amplificacion de baja potencia**
      El transistor 2N2222 se encarga de amplificar la pequeña señal del micrófono y,  
      mediante el emisor, envía una corriente al transistor TIP31C para la siguiente etapa.  
      Cabe mencionar que el 2N2222 controla al TIP31C, que tiene mayor potencia.


  ### **Etapa de amplificacion de alta potencia**
     El transistor TIP31C se encarga de encender y apagar las luces LED que necesitan 12V  
     mediante la señal del 2N2222, dado que el transistor TIP31C tiene una mayor capacidad  
     para manejar altos voltajes.


## Materiales  📦

A continuación se muestra una lista de los materiales requeridos, junto con la cantidad y el precio de cada uno:


  Nombre del Material  | Cantidad  | Precio Unitario (USD)  
|----------------------|-----------|-------------------------
| Potenciometro de 100K    | 1         | 💲0.30                 |
| Micrófono electrec     | 1         | 💲1                    |
| Transistor 2N2222        | 1         | 💲15                   |
| Transistor TIP31C          | 1 | 💲1.50 por metro       |
| Leds         | 4 | 💲1.50 por metro       |
| Bornera         | 2 | 💲1.50 por metro       |
| Switchera         | 1 | 💲1.50 por metro       |


## Total-estimado  💰

El costo total estimado del proyecto se calcula sumando los precios de todos los materiales:

Total Estimado: $XX.XX USD 💲

## Esquemas 📊

Puedes incluir diagramas, esquemas o gráficos que ayuden a comprender la estructura o funcionamiento de tu proyecto.

## Instalacion-y-simulacion  🔧

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_
Proporciona instrucciones claras sobre cómo instalar y ejecutar tu proyecto en caso de que sea una aplicación o software. Si es un proyecto que se ejecuta en línea o una simulación, proporciona un enlace directo para acceder a él.

_Dí cómo será ese paso_

```
Da un ejemplo
```

_Y repite_

```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_



## Autores ✒️

_Menciona a todos aquellos que ayudaron a crear el proyecto_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](https://github.com/DarinkaTownsend)


## Video-demostrativo 🎥
<!-- "Deben subir un video del funcionamiento a esta carpeta con el nombre de su proyecto:

https://espolec-my.sharepoint.com/:f:/g/personal/phycom_espol_edu_ec/Ev_QF9sXrLdOnNa4bQGy1gUBHgFZhHeYxoOzzLBM-buHsg?e=SjMYeL

No olvidar decirle a su mentor que ya fue subido el video para que el Dep.Proyectos pueda agregar el link en esta sección
"-->
Puedes encontrar un video demostrativo de este proyecto en [este enlace](url_del_video).

## Imagenes 📊

A continuación, se muestran algunas imágenes del proyecto:

![Imagen 1](url_de_la_imagen_1.png)
![Imagen 2](url_de_la_imagen_2.png)

## Informacion-adicional ✒️
---
Esta es la sección que permite agregar más información de contexto al proyecto como alguna web de relevancia, proyectos similares o que hayan usado la misma tecnología.

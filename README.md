#G1T1-2023.MusicLight

<h1 align="center"> [MUSIC LIGHTS] </h1>  

![Módulo](https://github.com/PhycomEspol/G1T1-2023.MusicLight/assets/145176980/01b1c02e-a44a-4215-8752-916a1b037e57)




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
| Potenciometro de 100K    | 1         | 💲0.50                 |
| Micrófono electrec     | 1         | 💲0.25                    |
| Transistor 2N2222        | 1         | 💲0.15                   |
| Transistor TIP31C          | 1 | 💲0.80       |
| Leds         | 4 | 💲0.10       |
| Bornera         | 2 | 💲0.20       |
| Switchera         | 1 | 💲0.20       |


## Total-estimado  💰

El costo total estimado del proyecto se calcula sumando los precios de todos los materiales:

Total Estimado: $2.70 USD 💲

## Esquemas 📊

A continuacion se presenta el circuito de funcionamiento en proteus:  

![implementación en proteus](https://github.com/ProjectsPhycom/G1T1-2023.MusicLight/assets/145176980/2ef0ec98-e4c4-4cce-8541-5ede310146f0)


## Autores ✒️

* **David Gonzalez** - *Elaboracion del proyecto* - [dagoyagu](https://github.com/dagoyagu)


## Video-demostrativo 🎥
<!-- "Deben subir un video del funcionamiento a esta carpeta con el nombre de su proyecto:

https://espolec-my.sharepoint.com/:f:/g/personal/phycom_espol_edu_ec/Ev_QF9sXrLdOnNa4bQGy1gUBHgFZhHeYxoOzzLBM-buHsg?e=SjMYeL

No olvidar decirle a su mentor que ya fue subido el video para que el Dep.Proyectos pueda agregar el link en esta sección
"-->
Puedes encontrar un video demostrativo de este proyecto en [este enlace]([url_del_video](https://espolec-my.sharepoint.com/:v:/g/personal/dagoyagu_espol_edu_ec/ESzI-ldHZeRAnfh8Id7v0NIB1POX-gterjhPGcaQVJzsDg?e=lxdPYz&nav=eyJwbGF5YmFja09wdGlvbnMiOnt9LCJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbE1vZGUiOiJtaXMiLCJyZWZlcnJhbFZpZXciOiJwb3N0cm9sbC1jb3B5bGluayIsInJlZmVycmFsUGxheWJhY2tTZXNzaW9uSWQiOiIxYzU2OGRiMC0zZDJhLTQzZjYtYTQ4ZC1lODUwNTM0NjViMzEifX0%3D).

## Imagenes 📊

A continuación, se muestran algunas imágenes del proyecto:
![Imagen 1](https://github.com/PhycomEspol/G1T1-2023.MusicLight/assets/145176980/02f81e45-7029-48b6-ab54-3bf0a8884420)
![Imagen 2](https://github.com/PhycomEspol/G1T1-2023.MusicLight/assets/145176980/92ab5380-7fce-4288-9033-0763bbb2cc27)

## POSIBLES MEJORAS
  Una posible mejora del proyecto es hacer que funcione con los mandos que vienen incluidos en las luces led para evitar switcheras y poder usar el control remoto, ya que esto permitiria mayor comodidad.

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
  ![image](https://github.com/ProjectsPhycom/G1T1-2023.MusicLight/assets/145176980/eee24e56-e6f6-4237-b24d-b8e573970090)

## POSIBLES MEJORAS
  Una posible mejora del proyecto es hacer que funcione con los mandos que vienen incluidos en las luces led para evitar switcheras y poder usar el control remoto, ya que esto permitiria mayor comodidad.

## DISEÑO DEL CIRCUITO

## VIDEO DE FUNCIONAMIENTO

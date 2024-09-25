Solucion Parcial
Pregunta 1 
  1.Por qué es necesario hacer resize del vector cuando este se llena?
  R/ hacer el resize del vector es necesario cuando un vector ya no tiene mas capacidad de guardar mas elementosy es necesario ya que con ese metodo 
  lo que estamos haciendo es redimensionar el tamaño del vector para poder agregar mas elementos a este. 

  1.1 es necesario seguir almacenando elementos?.
  R/si el programa me esta requiriendo almacenar mas elementos en un vector que ya esta lleno, si es necesario seguir almacenando elementos pero de forma de 
  que se guarden los elementos del vector que ya estan y insertar los nuevos elementos,es decir que se redimensione el vector (resize).
  
  2.Si comparamos el vector con una lista enlazada como la implementada en el curso cree
  usted que la lista pueda ser más eficiente?. Justifique su respuesta.
  para mi la eficiencia en este caso depende en que vamos a utilizar esta estructuras,en cuanto a la inserccion o el eliminar elementos la lista es mucho mas eficiente en el caso de que queramos revomer o añadir un elemento al inicio o al final 
  ya que siempre sabemos la ubicacion en memoria del inicio o el final de la lista y en el caso del vector es mas eficiente porque todo el tiempo tenemos acceso a cualquiera de sus elementos. 
  
  --------------------------------------------------------------------------------------------------------------------------------------------------

Pregunta 2
  1.Para cada uno de los vectores especifique cuál es su capacidad final y el desperdicio en
  el que incurre.
  R/
  VECTOR x: 
  en el vector x esta inicializado en 5 por el constructuor por defecto y tiene un crecimiento de 2.0 lo que nos dice que cada vez que el vector 
  se llena el vector se redimensiona y tendra el doble de su tamaño.
  como dice el codigo que se hara haran 10000 push backs entonces el vector quedara asi
  ANALISI VECTOR X 
  capacidad inicial: 5
  al inserta un elemento 6 con un resize la capacidad del vector quedaria de 10
  cuando este en el elemnto 11 otra vez se hara un resize y quedaria de 20.

  capacidad final: quedaria como capacidad final 10240 elementos en el vector.

  desperdicio en el que incurre: 240 elementos 

   VECTOR Y: inicia con 10 elementos de capacidad inicial y su politica de crecimiento es 1.8
   capacidad inicial: 10

   capacidad final: 

   desperdicio en el que incurre: 6384

  VECTOR Z:
  ANALISI VECTOR z

  capacidad inicial: 

  capacidad final

  desperdicio:

  

  2. Cuál de los vectores resultó ser más eficiente a la hora de ejecutar el programa?
Justifique clara y concisamente su respuesta.

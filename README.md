## Escuela Colombiana de Ingeniería

---

### Arquitecturas de Software
### Laboratorio - Programación concurrente, condiciones de carrera, esquemas de sincronización, colecciones sincronizadas y concurrentes

---

### Joan Acevedo - Cesar Borray

---

**Part I Control de hilos con wait/notify**

1. Se descargó, analizó el proyecto PrimeFinder y lo alojamos en un repositorio externo el cual se encuentra [*Aqui*](https://github.com/AndresSu2342/ARSW-PrimeFender). o en el siguiente direccionamiento:
   
    https://github.com/AndresSu2342/ARSW-PrimeFender

    El cual calcula números primos en un rango determinado utilizando hilos concurrentes.

2. Se implementó un mecanismo de sincronización para pausar la ejecución de los hilos cada t milisegundos utilizando wait() (por mayor practicidad decidimos usar el sleep()) y notifyAll().

![Image](https://github.com/user-attachments/assets/78ac43f2-00ac-42dc-af8f-211711d9e265)

![Image](https://github.com/user-attachments/assets/cc4ebde0-37b9-4910-9bce-79ea9fed11e0)

3. Se agregó la funcionalidad de mostrar los números primos encontrados hasta el momento antes de suspender los hilos.

![Image](https://github.com/user-attachments/assets/6539e643-138a-48c7-8501-b97cf1d7709a)

4. Se modificó la lógica para que el programa espere la entrada del usuario (ENTER) para reanudar la ejecución de los hilos.

![Image](https://github.com/user-attachments/assets/3b211947-72c6-496c-8879-e51a77d78427)

---

**Parte II - SnakeRace**

1. **Análisis del código** Se revisó la estructura del juego para comprender el uso de hilos en el movimiento autónomo de las serpientes.

2 y 3. **Identificación de problemas de concurrencia y soluciones implementadas:** Todo el detalle de estos dos puntos se encuentran en el archivo RESPUESTAS.txt
   
4. **Mejoras en la interfaz del juego:**    

   - Se agregó la opción de Iniciar/Pausar/Reanudar el juego mediante botones en la interfaz.

   - Se mostró información sobre la serpiente más larga y la primera en morir al pausar el juego.

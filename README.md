# Implementación y Análisis de Complejidad de Listas , Pilas y Colas en
Java
> ## Estructuras de Datos (2016699) - Grupo 2
> Profesor: David Alberto Herrera Alvarez - dherreraal@unal.edu.co
>
> Monitor: Daniel Alfonso Cely Infante - dcelyi@unal.edu.co

## Descripción de la tarea:
1. Implementar la Estructura List:
   Estructura de datos "List" basada en lsitas enlazadas realizando un analisis de complejidad de los metodos asociados como PushFront, PushBack, PopFront, PopBack, Find, Erase, AddBefore, AddAfter, etc.
2. Implementacion de Pilas y Colas en Java:
   Implementacion de las interfaaces MyStack<T> y MyQueue<T> con las metodos fundamentales.
3. Analisis de Complejidad:
   Estudio de la eficiencia de cada metodo en las distintas implementaciones .
4. Visualizacion y Graficacion de Resultados:
   Pruebas experimentales para las operaciones implementadas , ademas de graficacion de los resultados obtenidos.
5.  Conclusiones del trabajo:
   Detalles de las condiciones para determinar que metodo es mejor teniendo en cuenta las diferentes implementaciones de los metodos.

### Objetivo:
Implementacion de las estructuras de datos Stack y Queue en Java, usando desde arreglos dinamicos hasta listas enlazadas, igualmente realizando analisis de complejidad de los metodos asociados

#### **Metodos usados en cada estructura de datos:**
### Para 'MyStack<T>'
* `push(T x)`: Inserta un elemento en la cima.
* `pop()`: Elimina y retorna el elemento en la cima.
* `peek()`: Retorna el elemento en la cima sin eliminarlo.
* `isEmpty()`: Verifica si la pila está vacía.
* `size()`: Retorna el número de elementos en la pila.
* `delete(n)`: Elimina el primer valor `n` que encuentra en la estructura.

### Para 'MyQueue<T>'
* `enqueue(T x)`: Inserta un elemento al final.
* `dequeue()`: Elimina y retorna el primer elemento.
* `front()`: Retorna el primer elemento sin eliminarlo.
* `isEmpty()`: Verifica si la cola está vacía.
* `size()`: Retorna el número de elementos en la cola.
* `delete(n)`: Elimina el primer valor `n` que encuentra en la estructura.
**Variables importadas del paquete java.time.*

#### **El sistema debe:**
- Priorización automática: Mantener una fila de espera donde los pacientes con menor nivel de Triage (más graves) siempre estén al principio.
- Acceso directo: Consultar el estado y datos de un paciente mediante su ID.
- Atención: Extraer al paciente de mayor prioridad del sistema cuando un médico quede disponible.
- Estadísticas *(Ad disputandum)*: Listar cuántos pacientes han sido atendidos por cada nivel de severidad.

## Desarrolado por:
- Diego Alejandro Prieto Badillo - diprietob@unal.edu.co
- Julian Ricardo Rodriguez Villamizar - julrodriguezvi@unal.edu.co
- Sara Mariana Sanabria Ortiz - sasanabriao@unal.edu.co
- Carlos Stiven Romero Sicacha - cromerosi@unal.edu.co
- Miguel Angel Suarez Montiel - migsuarezmo@unal.edu.co

--- 

## Herramientas:

-  Java
-  SQL
-  Git

## Estructura del proyecto:
```text
proyecto_ed/
│
├── src/
│   └── main/
│       └── java/
│           └── grupo1/
│               ├── Main.java
│               ├── modelo/
│               ├── estructuras/    
│               └── servicios/
│
├── target/
├── pom.xml
└── README.md
```


# Laboratorio de Rendimiento
--- 

## Objetivo 
Comparar el desempeño de diferentes algoritmos con sus versiones secuenciales y
en paralelo, evaluando su eficiencia en distintos sistemas de cómputo con SO Linux,
determinando cuál presenta mejor aprovechamiento de recursos computacionales y por
qué.

## Descripcion 
La descripcion del objetivo, procedimiento, ejecucion y analisis de resultados del taller puede ser encontrado en el [informe del proyecto](InformeTallerRendimiento.pdf)

---

## Ejecucion 

De manera general el proyecto se puede ejecutar primer compilando los archivos de codigo fuente en C, haciendo uso del Makefile para simplificar la compilacion por medio del siguiente comando:

```bash
make 
```

Para despues modificar los datos de las lineas 20 a 22 del archivo [lanzador](./lanzador.pl). Los cuales representan los parametros de ejecucion del taller (Se recomienda leer el informe).

Para despues proceder a la ejecucion del lanzador con el siguiente comando:

```bash
./lanzador.pl
```

Esto comenzara a ejecutar el programa, el cual al finalizar creara los distintos archivos .dat con la informacion de rendimiento de los programas. 
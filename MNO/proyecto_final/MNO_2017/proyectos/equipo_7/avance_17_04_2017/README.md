## Avance_17_04_2017

---

### Integrantes:

---

- Mariana Carmona Baez
- Omar Díaz Landa

### Trabajo:

---

#### Individual

**Mariana:**

Profundizar en el algoritmo _Odd-even transposition sort_.
Leí las diapositivas acerca de este tema de la siguiente
[referencia](http://www.hpcc.unn.ru/mskurs/ENG/PPT/pp10.pdf).

**Omar:**

Profundizar en el algortimo _Quick sort_. Yo leí este
[documento](https://www.codeproject.com/KB/threads/Parallel_Quicksort/Parallel_Quick_sort_without_merge.pdf)
que detalla el algoritmo en paralelo y nos da una idea de cómo queremos presentar
el reporte, ya que compara el algoritmo secuencial vs. el paralelo.

#### Equipo
Definimos que era necesario leer el capítulo 3 del libro de
[Pacheco](https://www.dc.uba.ar/materias/escuela-complutense/2012/pacheco2011)
con el fin de que ambos tengamos una comprensión más clara de las funciones
que MPI tiene para _collective communication_. Además, leímos sobre los
diferentes algoritmos de ordenamiento y nos enfocamos en comprender
cada uno de ellos.

---

## Comentario sobre avance:

Comentarios sobre avance_07_04_2017 (primer commit):

* Y fue exitosa la replicación? en la sección de trabajo podrían poner esto? quizás un pequeño screenshot de hello worlds para sus nodos y luego un screenshot de su cálculo. Sin embargo, en este primer avance es mejor iniciar con el estudio de los algoritmos de ordenamiento que realizar una replicación de lo hecho en clase pues esto está resuelto. No haré válido este primer avance, su avance avance_17_04_2017 lo tomaré como avance avance_07_04_2017. Pueden poner lo del avance_17_04_2017 en el avance avance_07_04_2017? y el avance avance_17_04_2017 debe ser diferente.

Comentarios sobre avance_17_04_2017 (que después del cambio será avance_07_04_2017---muevan, actualicen lo necesario en sus README's):

* Vi que tienen en el objetivo que es openMP, será entonces en openMP? o MPI? quizás esto lo están determinando a partir de la lectura de las referencias?

* Mi sugerencia es que hagan un plan de trabajo. Primer paso: ordenamiento por quicksort y otros algoritmos (hay alguno que se haya elegido por la comunidad para su implementación en paralelo? o se paraleliza el quicksort?), segundo paso: investigación de algoritmos que realizan ordenamiento en paralelo (creo que lo han hecho parcialmente), tercer paso: elección de la extensión a utilizar mpi,mp,cuda? y pruebas de implementación (estos pasos no quiere decir que sea avance1, avance2, avance3).

* No hay detalle o descripción para su trabajo individual. Las diapositivas dan una idea pero mejor si tenemos un texto o papers. De acuerdo a la referencia de Omar se habla sobre quicksort secuencial, entonces empezamos por investigar sobre este algoritmo. Para el trabajo en equipo sirve que hagan pruebas de collective communication y pongan funciones implementadas por ustedes que realicen esto.

* Observen lo que han hecho los equipos 6, 10 u 11. Debe de haber un primer avance fuerte en alguna de los siguientes rubros: estudio de la teoría e implementación pero no he visto esto en este segundo (primer) avance :(


# Test B3T2: Diseño de Bases de Datos

### 1. ¿Cuál de las siguientes NO es un objetivo perseguido por Codd en la presentación de su modelo relacional?
- [ ] a) Independencia lógica.
- [ ] b) Independencia conceptual.
- [ ] c) Independencia física.
- [ ] d) Uniformidad.

---

### 2. Según la integridad de los datos en el modelo relacional. ¿A qué regla de integridad le corresponde la siguiente definición: “Los valores de claves foráneas deben existir en la clave primaria referenciada o bien deben ser valores nulos”?
- [ ] a) La regla de integridad referencial.
- [ ] b) La regla de integridad de dominio.
- [ ] c) La regla de integridad foránea inversa.
- [ ] d) La regla de integridad de unicidad.

---

### 3. Las consecuencias principales de que una base de datos NO esté normalizada adecuadamente son:
- [ ] a) Errores de inconsistencias, incoherencias, actualización y redundancia de datos.
- [ ] b) Problemas de bloque en las transacciones de las bases de datos.
- [ ] c) Problemas de disponibilidad de la base de datos.
- [ ] d) Dificultad para dimensionar adecuadamente las necesidades de almacenamiento de la base de datos.

---

### 4. ¿Cuál de las siguientes opciones NO representa uno de los niveles de abstracción de bases de datos?
- [ ] a) Interno.
- [ ] b) Externo.
- [ ] c) Sintáctico.
- [ ] d) Conceptual.

---

### 5. ¿Cuál de las siguientes operaciones NO se considera fundamental en el álgebra relacional?
- [ ] a) Proyección.
- [ ] b) Intersección.
- [ ] c) Selección.
- [ ] d) Unión.

---

### 6. El modelo de datos relacional fue introducido por:
- [ ] a) Codd.
- [ ] b) Hamming.
- [ ] c) Ritchie.
- [ ] d) Adleman.

---

### 7. Dentro del modelo relacional, señale la afirmación ERRÓNEA:
- [ ] a) En una relación puede haber varias claves candidatas.
- [ ] b) Una clave primaria es, a su vez, clave candidata.
- [ ] c) Si se elimina un atributo de una clave candidata, ésta deja de serlo.
- [ ] d) Una relación puede no tener clave candidata.

---

### 8. Según la teoría de la normalización, para pasar una relación de 1FN a 2FN hay que eliminar:
- [ ] a) De ella los grupos repetitivos.
- [ ] b) Las dependencias parciales de la clave externas.
- [ ] c) Las dependencias parciales de las claves candidatas.
- [ ] d) Las dependencias transitivas de la clave primaria.

---

### 9. ¿Cuál de los siguientes es un operador fundamental del álgebra relacional?
- [ ] a) Intersección.
- [ ] b) Producto cartesiano.
- [ ] c) Agrupación.
- [ ] d) Cociente.

---

### 10. ¿Cuál de las siguientes afirmaciones sobre la Tercera Forma Normal (3FN) es correcta?
- [ ] a) Una entidad está en 3FN si está en 2FN y todos sus atributos no principales dependen directamente de la clave primaria, es decir, no hay dependencias funcionales transitivas de atributos no principales respecto de las claves.
- [ ] b) Una entidad está en 3FN si está en 2FN y todos sus atributos que no forman parte de las claves candidatas (atributos no principales) tienen dependencia funcional completa respecto de éstas.
- [ ] c) La 3FN es el nivel más elevado de normalización de una tabla.
- [ ] d) Una tabla está en 3FN cuando está en 2FN y además todos los atributos, tanto principales como no principales, son atómicos.

---

### 11. ¿Qué nivel de la arquitectura ANSI/X3/SPARC contiene las vistas externas de la base de datos?
- [ ] a) Nivel físico.
- [ ] b) Nivel conceptual.
- [ ] c) Nivel lógico.
- [ ] d) Las vistas están fuera del modelo de base de datos, ya que son externas.

---

### 12. ¿Cuál de las siguientes tareas NO corresponde a una tarea del diseño físico de una base de datos?
- [ ] a) Traducir el esquema lógico para el SGBD específico.
- [ ] b) Diseñar los mecanismos de seguridad.
- [ ] c) Transformación de entidades.
- [ ] d) Seleccionar los índices secundarios.

---

### 13. ¿Cuál de los siguientes NO es un objetivo de la normalización de base de datos?
- [ ] a) Proporcionar una estructura más regular para la representación de tablas.
- [ ] b) Optimizar la base de datos.
- [ ] c) Evitar anomalías en las operaciones de manipulación de datos.
- [ ] d) La eliminación de dependencias entre atributos.

---

### 14. Una relación, si los atributos que no forman parte de ninguna clave dependen de forma completa de la clave principal se dice que está en:
- [ ] a) Tercera Forma Normal.
- [ ] b) Cuarta Forma Normal.
- [ ] c) Quinta Forma Normal.
- [ ] d) Segunda Forma Normal.

---

### 15. En una tabla, si cada determinante, atributo que determina completamente a otro, es clave candidata se dice que está en:
- [ ] a) Primera Forma Normal.
- [ ] b) Segunda Forma Normal.
- [ ] c) Forma Normal de Boyce-Codd.
- [ ] d) Quinta Forma Normal.

---

### 16. Si en una base de datos relacional tenemos una tabla que contiene una tupla cuya única clave ajena tiene un valor nulo:
- [ ] a) Estaremos incumpliendo la regla de integridad de entidad.
- [ ] b) Estaremos incumpliendo la regla de integridad referencial.
- [ ] c) Dicha tupla no está relacionada con ninguna otra tupla de la entidad a la que hace referencia la clave ajena.
- [ ] d) Existirá una tupla en la entidad a la que hace referencia la clave ajena, con la que estará relacionada.

---

### 17. ¿Cuál es una restricción inherente al modelo relacional de los sistemas gestores de bases de datos?
- [ ] a) El atributo que forma parte de la clave tiene que ser numérico.
- [ ] b) El atributo que forma parte de la clave no puede ser numérico.
- [ ] c) El atributo que forma parte de la clave no puede tomar el valor cero.
- [ ] d) El atributo que forma parte de la clave no puede tomar valore nulos (por nulo se interpreta valores desconocidos).

---

### 18. ¿Cómo se llama el operador del álgebra relacional que aplicado sobre una relación permite obtener un subconjunto de sus atributos manteniendo el mismo número de tuplas?
- [ ] a) Unión de conjuntos.
- [ ] b) Producto cartesiano.
- [ ] c) Selección.
- [ ] d) Proyección.

---

### 19. ¿Cuál de las siguientes afirmaciones NO es correcta?
- [ ] a) Las bases de datos relacionales se normalizan para evitar la redundancia de datos.
- [ ] b) Ningún atributo que compone una clave primara puede ser nulo.
- [ ] c) Un atributo nulo representa el valor cero o una cadena vacía.
- [ ] d) Uno de los objetivos de la normalización es facilitar el mantenimiento de datos y programas.

---

### 20. Una tabla se dice que está en Tercera Forma Normal si se encuentra en Segunda Forma Normal y:
- [ ] a) Las únicas dependencias funcionales elementales son aquellas en las que la clave principal (y claves secundarias) determinan un atributo.
- [ ] b) Todo atributo secundario depende totalmente de la clave completa.
- [ ] c) Los valores que componen los atributos son elementales y únicos.
- [ ] d) No existen atributos no primarios que son transitivamente dependientes de cada posible clave de la tabla.

---

### 21. En una tabla de una base de datos relacional, si no existen grupos repetitivos, и todos los elementos son independientes entre sí и dependen solamente de la clave primaria de forma plena, ¿ante qué forma normal nos encontramos?
- [ ] a) 1FN.
- [ ] b) 2FN.
- [ ] c) 3FN.
- [ ] d) No se encuentra en ninguna forma normal.

---

### 22. En el modelo relacional, una relación R, decimos que está en Segunda Forma Normal (2FN) si:
- [ ] a) Está en Primera Forma Normal (1FN) и todos los atributos que no forman parte de las claves candidatas tienen dependencia funcional completa respecto de éstas.
- [ ] b) Todos los atributos que no forman parte de las claves candidatas tienen dependencia funcional completa respecto de éstas.
- [ ] c) Todos sus atributos no principales dependen directamente de la clave primaria.
- [ ] d) No tiene grupos repetitivos, es decir, un atributo solo puede tomar un único valor de un dominio simple.

---

### 23. La tabla siguiente EMPLEADOS (COD_EMPLEADO, COD_DEPARTAMENTO, TIPO, EDAD, PLANTA_DEPARTAMENTO) donde la clave principal es COD_EMPLEADO и COD_DEPARTAMENTO.
- [ ] a) Cumple la 2FN.
- [ ] b) No cumple la 3FN, pero cumple la segunda.
- [ ] c) No cumple la 2FN.
- [ ] d) No cumple la 4FN, pero cumple la tercera.

---

### 24. Partiendo del diagrama Entidad/Relación de la figura. ¿Cuántas tablas generaría la transformación de este diagrama al modelo relacional?
- [ ] a) Dos.
- [ ] b) Tres.
- [ ] c) Cuatro.
- [ ] d) Cinco.

---

### 25. Se pretende obtener el modelo lógico de datos a partir de este modelo entidad/relación, ¿cómo se reflejará la relación entre las tablas BECAS и ASPIRANTES?
- [ ] a) En una nueva tabla cuya clave primaria será la concatenación de los atributos claves de las tablas BECAS и ASPIRANTES.
- [ ] b) Se propaga la clave primaria BECAS и los atributos de la relación de la entidad ASPIRANTES.
- [ ] c) En una nueva tabla cuya clave primaria será la concatenación de cuatro valores: los atributos clave de las tablas BECAS, ASPIRANTES и los atributos de la relación (“otorgada” и “año_otorgamiento”).
- [ ] d) Se propaga la clave primaria de cualquier de las dos tablas a la otra, и el atributo de la relación también, pero ninguno de estos será clave primaria en la relación dónde se propaguen.

---

### 26. En álgebra relacional la operación que, a partir de dos relaciones del mismo tipo, obtiene una nueva relación formada por las tuplas que pertenecen a las dos relaciones de partida, se llama:
- [ ] a) Unión.
- [ ] b) Intersección.
- [ ] c) Diferencia.
- [ ] d) Producto cartesiano.

---

### 27. Una relación (una tabla) se compone de los campos o atributos A, B, C и D. Solo existe una clave candidata, и es la clave compuesta (A, B). Además, se cumple que (A, B) determina funcionalmente a C, и C determina funcionalmente a D. Indique la respuesta correcta:
- [ ] a) La tabla no cumple ninguna forma normal.
- [ ] b) La tabla está en 1FN, pero no en 2FN, ni en 3FN.
- [ ] c) La tabla está en 1FN и en 2FN, pero no en 3FN.
- [ ] d) La tabla está en 1FN, en 2FN и en 3FN.

---

### 28. Tal и como se muestra en el diagrama de Entidad/Relación, ¿cuál de las siguientes afirmaciones sobre la realidad que representa el diagrama NO es cierta?
- [ ] a) Un Departamento está compuesto por una o varias Unidades и toda Unidad pertenece a un и sólo un Departamento.
- [ ] b) Un Departamento puede ser dirigido por un Titular и todo Titular debe dirigir a un Departamento.
- [ ] c) Cada Unidad es dirigida por un Titular и un Titular puede dirigir a un máximo de una Unidad.
- [ ] d) Un Departamento puede participar en varias Comisiones interministeriales.

---

### 29. Tomando como referencia el modelo E/R anterior, se pretende obtener el modelo lógico de datos, ¿cómo se reflejaría la relación entre las tablas DEPARTAMENTO и COMISIÓN MINISTERIAL?
- [ ] a) Se propaga el identificador de la Comisión Ministerial, así como los posibles atributos de la relación a la tabla de DEPARTAMENTOS.
- [ ] b) Se propaga el identificador del Departamento, así como los posibles atributos de la relación a la tabla de COMISIONES MINISTERIALES.
- [ ] c) Se crea una tabla nueva en la que se incluyen los atributos que forman clave primaria de las tablas DEPARTAMENTOS и COMISIONES MINISTERIALES, и los atributos que tiene la relación, siendo estos últimos la clave primaria de esta nueva tabla.
- [ ] d) Se crea una tabla nueva en la que se incluyen los atributos que forman clave primaria de las tablas DEPARTAMENTOS и COMISIONES MINISTERIALES и que, a su vez, formarán la clave primaria de la nueva tabla. Así como los atributos que pueda tener la relación.

---

### 30. En una base de datos relacional en la que se tiene información guardada en una tabla de provincias и además se dispone de una tabla de municipios donde parte de la clave es la provincia, ¿se puede borrar un elemento de la tabla de provincias manteniendo la integridad del sistema?
- [ ] a) Si, una vez que los municipios ya existen no hay ningún problema.
- [ ] b) Si, aunque no podría dar de alta nuevos municipios de esa provincia.
- [ ] c) Sólo si no hay ninguna población perteneciente a esa provincia.
- [ ] d) No, la tabla de provincias no puede cambiar ya que son un elemento estable.

---

### 31. En la teoría de bases de datos relacionales, cuanto más alta sea la forma normal aplicable a una tabla (acoplamiento = grado de interdependencia entre módulos, cohesión = medida de la relación funcional entre elementos de un módulo):
- [ ] a) Menor será la cohesión relacional.
- [ ] b) Menor será el acoplamiento relacional.
- [ ] c) Menos vulnerable será a inconsistencias и anomalías.
- [ ] d) Más vulnerable será a inconsistencias и anomalías, pero será más eficiente.

---

### 32. Señale cuál de las siguientes afirmaciones sobre la arquitectura ANSI/X3/SPARC es correcta:
- [ ] a) El nivel externo también recibe el nombre de nivel físico.
- [ ] b) El nivel interno también recibe el nombre de nivel lógico.
- [ ] c) El nivel externo define los datos que se almacenan en la base de datos и las relaciones entre ellos.
- [ ] d) El nivel externo contiene las vistas externas de la base de datos и permite ver a cada tipo de usuario solo aquella parte del esquema que es de su interés.

---

### 33. ¿Cuál de las siguientes afirmaciones sobre el proceso de normalización del modelo relacional es cierta?
- [ ] a) Existen solo un total de 3 Formas Normales: 1FN, 2FN и 3FN.
- [ ] b) Una tabla está en 2FN cuando se demuestra que existe dependencia funcional del resto de columnas de la tabla con respecto a las claves candidatas.
- [ ] c) Una tabla está en 1FN cuando se demuestra que existe dependencia funcional completa del resto de columnas de la tabla con respecto a la clave primaria.
- [ ] d) Una tabla que está en 1FN tiene el máximo grado de normalización и, por tanto, cumple también la Segunda и Tercer Forma Normal.

---

### 34. En relación al esquema conceptual en los niveles ANSI/X3/SPARC, ¿qué afirmación de las siguientes NO es correcta?
- [ ] a) Representa el modelo de datos de forma independiente del sistema gestor de bases que se utilizará.
- [ ] b) Refleja la representación de los datos que se van a guardar и sus relaciones a partir del modelo ER.
- [ ] c) Corresponde a la visión de la base de datos que ofrece cada aplicación.
- [ ] d) Debe ser absolutamente independiente del esquema físico.

---

### 35. El operador JOIN del álgebra relacional es un operador compuesto de otros operadores fundamentales, que son:
- [ ] a) Selección, proyección и unión.
- [ ] b) Selección, producto cartesiano и proyección.
- [ ] c) Diferencia de conjuntos, unión и producto cartesiano.
- [ ] d) Unión, proyección и producto cartesiano.

---

### 36. ¿Qué esquema de bases de datos incluye la descripción de todos los datos e interrelaciones entre éstos, así como las restricciones de integridad?
- [ ] a) Esquema interno.
- [ ] b) Esquema conceptual.
- [ ] c) Esquema externo.
- [ ] d) Esquema físico.

---

### 37. En un diagrama entidad/relación:
- [ ] a) Una alta redundancia es buena ya que permite alcanzar la información a través de distintas relaciones.
- [ ] b) Una baja redundancia es buena ya que no aporta información adicional и complica la gestión de la información.
- [ ] c) Si aparece un ciclo entre relaciones и entidades, debemos eliminar una relación para evitar la redundancia.
- [ ] d) Si aparece un ciclo entre relaciones и entidades, no es conveniente romperlo si cada una de las relaciones aporta una información distinta al resto.

---

### 38. Dada una relación ternaria en un diagrama E/R, ¿en cuántas relaciones se transformará en el modelo relacional?
- [ ] a) 1.
- [ ] b) 2.
- [ ] c) 3.
- [ ] d) 4.

---

### 39. La normalización se aplica en:
- [ ] a) El diseño físico.
- [ ] b) El diseño conceptual.
- [ ] c) El diseño lógico.
- [ ] d) El diseño interno.

---

### 40. Señale la afirmación INCORRECTA sobre el modelo lógico relacional:
- [ ] a) La cardinalidad de una relación es el número de tuplas.
- [ ] b) El grado de una relación es el número de atributos.
- [ ] c) Un dominio es un conjunto de valores.
- [ ] d) Cada fila de una relación puede ser única.

---

### 41. La desnormalización controlada del modelo físico de datos se aplica para:
- [ ] a) Tener una estructura de tablas más regular.
- [ ] b) Incrementar la flexibilidad del esquema.
- [ ] c) Mejorar los tiempos de respuesta de las consultas.
- [ ] d) Reducir o simplificar el número de acceso a la base de datos.

---

### 42. En el modelo relacional, señale la respuesta correcta:
- [ ] a) Un valor nulo representa el valor cero.
- [ ] b) Un valor nulo representa un valor desconocido.
- [ ] c) Un valor nulo representa la cadena vacía.
- [ ] d) Un valor nulo representa el valor booleano false.

---

### 43. Según el modelo E/R extendido propuesto en Métrica v3, si 2 entidades se relacionan mediante la relación “ASOCIADA A”, siendo el tipo de correspondencia 1:1 и teniendo en cuenta que la relación “ASOCIADA A” posee el atributo “fecha_asociacion”, ¿en cuántas relaciones se transformará en el modelo relacional?
- [ ] a) 1.
- [ ] b) 2.
- [ ] c) 3.
- [ ] d) 4.

---

### 44. Dada una jerarquía en el modelo Entidad- Relación extendido, se crea una tabla para el supertipo que tenga de clave primaria el identificador и una tabla para cada uno de los subtipos que tengan el identificador del supertipo como clave ajena. Esta solución es apropiada:
- [ ] a) Si los subtipos tienen muchos atributos distintos и se quieren conservar los atributos comunes en una tabla.
- [ ] b) Porque mejora la eficiencia en los accesos a todos los atributos de un subtipo, sean los comunes al supertipo o los específicos.
- [ ] c) Si los subtipos se diferencien en pocos atributos и las relaciones entre los subtipos и otras entidades sean las mismas.
- [ ] d) En todo caso.

---

### 45. La técnica cuyo objetivo consiste en una desnormalización controlada del modelo físico de datos que se aplica para reducir o simplificar el número de accesos a la base de datos, se denomina:
- [ ] a) Optimización.
- [ ] b) Cálculo de accesos.
- [ ] c) Caminos de acceso.
- [ ] d) Normalización inversa.

---

### 46. Respecto a la regla de integridad de entidad, señale la respuesta INCORRECTA:
- [ ] a) Ninguno de los atributos que componen la clave primaria puede ser nulo.
- [ ] b) Ninguno de los atributos que componen la claves candidatas puede ser nulo.
- [ ] c) La clave primaria es irreducible.
- [ ] d) No se aplica a las claves candidatas.

---

### 47. En el modelo relacional, la extensión de una relación es:
- [ ] a) El número de atributos que posee.
- [ ] b) El esquema de esa relación.
- [ ] c) El conjunto de filas o tuplas de esa relación.
- [ ] d) El conjunto de dominios utilizados para los atributos de esa relación.

---

### 48. En el modelo relacional, la cardinalidad de una relación es:
- [ ] a) El número de atributos que posee.
- [ ] b) El número de atributos que componen la clave primaria de esa relación.
- [ ] c) El número de filas o tuplas de esa relación.
- [ ] d) El número de dominios utilizados para los atributos de esa relación.

---

### 49. En el modelo relacional, el grado de una relación es:
- [ ] a) El número de atributos que posee.
- [ ] b) El número de atributos que componen la clave primaria de esa relación.
- [ ] c) El número de filas o tuplas de esa relación.
- [ ] d) El número de dominios utilizados para los atributos de esa relación.

---

### 50. En la transformación al modelo relacional de un diagrama Entidad-Relación extendido, las relaciones de agregación:
- [ ] a) Se transforman del mismo modo que las 1:N.
- [ ] b) Se transforman del mismo modo que las 1:1.
- [ ] c) Se transforman del mismo modo que las N:M.
- [ ] d) Su transformación depende del tipo de correspondencia concreto.

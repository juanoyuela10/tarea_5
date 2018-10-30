# tarea_5
Tarea de redes - manejo de fuerzas
# DATASET
Los datos fueron obtenidos de la bodega de datos institucional de la Universidad de los Andes, seleccionando todos los cursos inscritos por los estudiantes de las diferentes facultades para el primer semestre del año en curso.

# OBJETIVO DE LA VISUALIZACIÓN
Presentar un resumen del volumen de inscripciones de cursos en el semestre 2018-I, para validar de que manera se relacionan las facultades a las que pertenecen los estudiantes y cuales son sus intereses en cursos de otras facultades.

# TECNOLOGÍAS UTILIZADAS
D3 V3
CSS
JSON
HTML
gitHUB pages

# Retos principales
Adaptación de los datos al formato JSON
Manejo del grafo

# ABSTRACCIÓN

## WHAT
Data type: Nodos, Links
Dataset type: Network
Disponibilidad: Estático
Atributos:
Facultad del estudiante: Categórico
Facultad del curso: Categórico 
Número estudiantes: Cuantitativo, secuencial
Periodo: Ordenado, Secuencial

## WHY
Tarea Principal: Descubrir la topología de distribución, principalmente a nivel de facultades y cursos (Discover Topology), que les interesa a los futuros ingenieros? o a los médicos?.
Tareas secundarias: 
Validar el comportamiento de inscripción de una facultad en particular(Browse Features)
Identificar la facultad con oferta mas atractiva de cursos (Explore Paths)

## HOW
Marcas: Puntos (círculos para las facultades a las que pertenece el estudiante, rombos para las facultades a las que pertenece el curso).
Canales: Shape, Color Hue
Encode: Separate 
Facet – Superimpose

# INSIGHTS
Los estudiantes de medicina tienden a mantenerse dentro de sus principales áreas de interés afines a la carrera, manteniendo su aprendizaje especializado dentro de la facultad.

Los estudiantes con mayor dispersión de cursos (numero de links) son los de ingeniería, y teniendo en cuenta que es la facultad con mayor numero de estudiantes, es importante que la universidad evalúe constantemente la gestión de disponibilidad y oferta.

Los cursos de la facultad de Artes y Humanidades despiertan un gran interés en la comunidad UNIANDINA, haciendo necesario que la universidad contemple la posibilidad de abrir mas secciones para cubrir la demanda.

# Proyecto_Java_Poo_ORT

Gestor de Tareas
-------------------------

Descripción del Proyecto:
Este proyecto implementa un sistema de gestión de tareas que categoriza tareas en tres tipos: Bug, Mejora, y Auditoría. Las tareas tienen prioridades, descripciones y fechas de inicio, y se manejan utilizando herencia y polimorfismo para encapsular el comportamiento específico de cada tipo de tarea. El objetivo es demostrar el manejo de relaciones entre clases, encapsulamiento, y uso de TADs.

Características Principales:
Tipos de Tareas:
Bug: Incluye una fecha de vencimiento y un indicador de criticidad. Se considera vencido si la fecha ha pasado.
Mejora: Almacena el nombre del sistema relacionado. No tiene fecha de vencimiento.
Auditoría: Puede ser externa o interna, con fecha de vencimiento para determinar su estado.
Gestión de Tareas: Permite registrar y almacenar tareas, asegurando la ejecución en orden de registro.
Listas por Prioridad: Funcionalidad para listar tareas según su prioridad, ordenadas por descripción.
Manejo de Errores: Captura y maneja errores al registrar tareas inválidas.
Tecnologías Utilizadas:
Lenguaje: Java
Paradigmas: Programación Orientada a Objetos, Polimorfismo
Estructuras de Datos: Tipos Abstractos de Datos (TADs)
Entorno de Desarrollo: Eclipse

-----------------------------------------------------------------------------------------

MultiDeposito
--------------------
Descripción del Proyecto:
Este proyecto es un prototipo de software para la gestión de un depósito que almacena productos de tenis: pelotas, bolsos y raquetas. La aplicación implementa una estantería rectangular con 3 niveles y 4 estantes por nivel, cada uno destinado a un tipo específico de producto. Se enfoca en la correcta aplicación de conceptos de Programación Orientada a Objetos (POO), como herencia, encapsulamiento, y manejo de colecciones.

Características Principales:
Estructura del Depósito: Implementación de una estantería con niveles y estantes, donde cada nivel almacena un tipo específico de producto.
Gestión de Productos: Los productos tienen un ID único, marca, y atributos específicos según el tipo de producto (raquetas, bolsos, pelotas).
Interfaz Mostrable: Implementación de la interfaz para mostrar información de productos.
Operaciones CRUD: Métodos para agregar, retirar y verificar productos en el depósito.
Gestión de Errores: Manejo de excepciones al intentar depositar productos en estantes llenos o retirar productos inexistentes.
Tecnologías Utilizadas:
Lenguaje: Java
Paradigmas: Programación Orientada a Objetos
Estructuras de Datos: Pilas, colas, y listas ordenadas
Entorno de Desarrollo: Eclipse

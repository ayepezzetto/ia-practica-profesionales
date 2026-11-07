# Recorrido de aprendizaje

## Diccionario con un mismo ejemplo
Usar como hilo conductor una consultora ficticia que organiza una capacitación.
- Agente: asistente que puede encadenar pasos y usar herramientas para un objetivo, dentro de los permisos otorgados.
- Contexto: información necesaria para trabajar: público, objetivos, restricciones y antecedentes.
- Proyecto: espacio para reunir conversaciones, archivos e instrucciones de un trabajo, según la plataforma.
- Skill: procedimiento reutilizable con instrucciones y, si hace falta, recursos o scripts. Ejemplo: convertir notas en una propuesta de clase con una estructura acordada.
- RAG (generación aumentada por recuperación): buscar fragmentos relevantes en fuentes y usarlos para responder. Ejemplo: responder sobre el curso citando el programa. No es reentrenar el modelo; cargar un archivo no permite asumir cómo funciona su recuperación.
- MCP (Model Context Protocol): protocolo para conectar aplicaciones de IA con herramientas y fuentes. Ejemplo: consultar una carpeta autorizada. Un conector puede usar MCP, pero no todos lo hacen.
- Tarea programada: ejecución gestionada por un programador a una hora o condición. Ni una skill ni un MCP son, por sí solos, un programador.

## Seis módulos
1. Una ayuda útil hoy: transformar notas ficticias en prioridades, próximos pasos y un borrador.
2. Contexto y proyectos: preparar objetivo, destinatarias, materiales, restricciones y definición de terminado.
3. Skills: detectar un procedimiento repetido, escribir entradas/pasos/salida/límites, probar tres casos, instalar y ajustar.
4. RAG: preparar tres documentos ficticios con títulos y fechas; formular preguntas; pedir documento/sección; preguntar algo que no esté para comprobar que reconoce la ausencia.
5. Conexiones MCP: verificar proveedor, revisar permisos, consultar una carpeta de prueba en modo lectura y aprender a revocar acceso.
6. Programación y publicación: probar una tarea manual, programar si existe soporte, verificar próxima ejecución y cancelación; publicar una guía sin datos privados.

## Primera práctica
Objetivo: convertir pendientes en un plan de trabajo de 30 minutos.
Datos ficticios: revisar una propuesta el martes; preparar una clase el jueves; pedir un presupuesto sin fecha definida.
Texto para copiar:
“Con estos pendientes, armá una tabla de tarea, próximo paso, duración estimada y fecha. Separá fechas dadas de estimaciones. Proponé un bloque de 30 minutos. No envíes mensajes ni modifiques mi calendario. Si falta un dato, marcá pendiente de confirmar.”
Verificar: no inventar fechas ni asumir que los mensajes se enviaron; total de tareas propuestas dentro de los 30 minutos.
Variación: convertir el procedimiento en instrucciones reutilizables y probar un listado vacío y otro con fechas contradictorias.

## Proyectos
Plantilla: objetivo; destinatarias; resultado; fuentes; restricciones; tareas; responsable; fecha; criterio de aceptación.
Ejemplo: diseñar una clase introductoria de 60 minutos con tres ejercicios ficticios y un cierre de verificación.

## Programación
Primero mostrar un ejemplo de pedido: “Cada lunes a las 9, hora de Buenos Aires, recordame revisar mis tres prioridades”.
Distinguir recordar de analizar datos actualizados: lo segundo requiere acceso y soporte de herramientas durante la ejecución.
Confirmar el estado devuelto por el programador y explicar cómo editar o cancelar. Si no hay soporte, entregar la instrucción como ejemplo y declarar que no quedó programada.

# isma

Herramientas clínicas del Dr. Ismael Cañete Campos.

## plantillas.html

Indicación de plantillas ortopédicas con esquema dinámico.

- Datos del paciente (nombre, RUT con validación, edad, N° de calzado, diagnóstico).
- Lateralidad: bilateral igual, ambos pies distinto, solo derecho o solo izquierdo.
- Elementos con medida en mm: realce posteromedial, realce posterolateral, arco longitudinal medial, barra retrocapital, oliva metatarsal, cuña de antepié (medial/lateral), alza de talón, taza talonera, descarga calcánea. Largo completo o 3/4.
- El esquema de la plantilla se actualiza en tiempo real.
- "Generar PDF / Imprimir" abre el diálogo de impresión (tamaño carta). Para PDF, elegir "Guardar como PDF".
- "Limpiar y comenzar de nuevo" borra todo.

No se guarda ni se envía ningún dato del paciente: todo ocurre en el navegador.

### Configuración

- Datos del médico: objeto `DOCTOR` al inicio del script en `plantillas.html`.
- Firma: agregar `firma.png` (fondo blanco o transparente) en esta misma carpeta. Si no existe, se imprime solo la línea de firma.
- Elementos: arreglo `ELEMENTS` en el mismo archivo.

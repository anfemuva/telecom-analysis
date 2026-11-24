# ConnectaTel - Análisis de clientes y planes

Proyecto de análisis de datos de una empresa de telecomunicaciones. Se limpian los datos de clientes y de uso, se agrupa a los clientes por edad y por nivel de uso, y se revisa si los planes Basico y Premium se ajustan a lo que la gente consume.

## Datos

- **users**: datos de los clientes (edad, ciudad, plan, fechas de registro y de baja).
- **usage**: registros de llamadas y mensajes.
- **plans**: mensajes, minutos y precio de cada plan.

## Qué se hizo

- Limpieza de los datos, como el valor -999 en la edad, el símbolo `?` en la ciudad y fechas imposibles.
- Resumen del uso de cada cliente y unión con sus datos personales.
- Revisión de valores atípicos con gráficos.
- Segmentación de los clientes por edad y por nivel de uso.

## Conclusiones

- La mayoría de los clientes tiene un uso medio, y el grupo de edad más grande es el de adultos.
- El uso promedio es muy bajo frente a lo que incluyen los planes.
- No se ve diferencia de consumo entre Basico y Premium, aunque Premium cuesta más.
- Se recomienda revisar el plan Premium y evaluar un plan más económico.

## Herramientas

Pandas, matplotlib, seaborn y Jupyter Notebook.

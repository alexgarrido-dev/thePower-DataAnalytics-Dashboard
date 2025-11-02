# thePower-DataAnalytics-Dashboard

1. Título del Proyecto
   
Exploración, modelado y dashboard de las ordenes y pedidos de Foodpanda.

2. Descripción del Proyecto
   
En este proyecto realiza un análisis exploratorio de las ordeness y los pedidos de la empresa de repartos de comida a domicilio Foodpanda. 
El objetivo es identificar tendencias y patrones para analizar el impacto de las ordenes que no acaban materializándose en pedidos (pedidos cancelados) e intentar encontrar una relación.
Reconocer los motivos por los cuales una orden no se transforma en un pedido efectivo es crucial para optimizar procesos, reducir pérdidas y mejorar la experiencia del cliente. Cada pedido cancelado representa no solo una oportunidad de venta perdida, sino también un posible indicio de insatisfacción o fricción en el proceso de compra.

3. Estructura del Proyecto
   
🗂️ Estructura del Proyecto

├──
data/ https://www.kaggle.com/datasets/ayeshaimran123/foodpanda-order-and-delivery-trends

├──
enlace google sheets/ (https://docs.google.com/spreadsheets/d/1EZuIRWyGUMUf5cD-3fuvqSRldHOHQBh-f-osuEdUUXk/edit?usp=sharing)

├── README.md # Descripción del proyecto
  
5. Resultados y Conclusiones
   
El primer paso para entender qué está ocurriendo es observar el comportamiento de los datos en el dashboard. A partir del análisis realizado, se destacan los siguientes hallazgos:
Factores como el género del cliente, el método de pago utilizado o el periodo temporal no muestran una correlación significativa con el número de pedidos cancelados. Esto sugiere que las cancelaciones no están influenciadas por variables demográficas ni por la forma de pago.

Existe una relación proporcional entre el número total de pedidos y el número de cancelaciones. Es decir, cuando hay más pedidos, también hay más cancelaciones, lo cual es esperable. Sin embargo, esta relación se mantiene proporcional: no se observa un aumento desmedido en las cancelaciones cuando el volumen de pedidos crece.

La calidad de las valoraciones recibidas tiene un impacto directo en la tasa de cancelación. Se ha detectado que a medida que las valoraciones mejoran, el número de cancelaciones disminuye. Esto indica que el principal factor detrás de las cancelaciones podría estar relacionado con la satisfacción del cliente. Un cliente satisfecho es menos propenso a cancelar su pedido, lo que convierte la experiencia del usuario en un indicador clave para la retención.

El año 2024 fue el periodo con mayor volumen de pedidos registrado, marcando un pico significativo en la actividad comercial.
En lo que va de 2025, el número de pedidos supera al de 2023, lo que indica una tendencia positiva. Sin embargo, aún no se alcanza el volumen total de 2024, lo que plantea un reto para igualar o superar el rendimiento del año anterior.

El análisis revela que las cancelaciones no están determinadas por factores externos como género, método de pago o estacionalidad, sino que están más vinculadas a la percepción de calidad y satisfacción del cliente. Esto refuerza la necesidad de invertir en mejorar la experiencia del usuario, desde la atención hasta la entrega, para reducir el gap entre órdenes y pedidos efectivos.

Además, el comportamiento anual sugiere que 2025 tiene potencial de crecimiento, pero requerirá acciones estratégicas para alcanzar los niveles de 2024.

6. Próximos Pasos
   
- Analizar valoraciones negativas Revisa los comentarios o puntuaciones bajas para detectar patrones: ¿se repiten quejas sobre tiempos, calidad, atención?

- Segmentar por tipo de producto o servicio Identifica si ciertos productos o categorías tienen más cancelaciones que otros.

- Estudiar el proceso de entrega Evalúa si hay demoras, errores logísticos o problemas de comunicación que afecten la experiencia.

- Comparar comportamiento por canal de venta ¿Las cancelaciones vienen más de pedidos online, telefónicos, en tienda?

- Realizar encuestas post-cancelación, pregunta directamente a los clientes por qué cancelaron: esto da información valiosa y directa.

7. Contribuciones
   
Me gustaría que al cambiar de filtro, cada estado mantenga su color definido, ¿cómo puedo fijar los colores en los gráficos?

8. Autores y Agradecimientos
   
- Alex Garrido
- [@alexgarrido_dev](https://github.com/alexgarrido_dev)

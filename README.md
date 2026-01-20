Análisis de consumo en planes telefónicos ConnectaTel

2. Descripción del proyecto
2.1 Contexto del negocio: ¿qué problema se busca resolver?

ConnectaTel opera en dos mercados altamente competitivos: México y Colombia. En este contexto, ofrecer planes atractivos no es suficiente. La empresa necesita asegurarse de que su oferta esté alineada con la forma en que los clientes realmente utilizan el servicio.

El punto de partida del proyecto fue una pregunta simple pero poderosa:

¿Nuestros planes actuales reflejan el comportamiento real de nuestros clientes?: Responder esta pregunta es clave para detectar oportunidades de mejora en la oferta comercial, optimizar costos operativos y mejorar la experiencia del usuario. Muchas veces, los datos esconden patrones que no se perciben en la operación diaria: clientes que consumen más de lo esperado, planes que no se ajustan al uso real o segmentos con necesidades específicas que no están siendo atendidas adecuadamente.
Para acercarse a esta comprensión, se integraron tres fuentes de información fundamentales: los planes contratados, el perfil de los clientes y el uso real de llamadas y mensajes.

2.2 Objetivo: ¿para qué sirve este análisis?: El objetivo principal de este proyecto es comprender el comportamiento real de uso de los clientes de ConnectaTel y traducir ese conocimiento en insights accionables para el negocio.

En particular, el análisis busca:

* Identificar patrones de consumo en llamadas y mensajes.
* Detectar comportamientos atípicos que no representan errores, sino oportunidades.
* Evaluar si variables como la edad explican el consumo.
* Segmentar a los clientes según su nivel de uso real.
* Proponer recomendaciones que ayuden a mejorar la oferta de planes, los upgrades y la fidelización.

Más allá de los números, este proyecto tiene como meta contar una historia clara y confiable, apoyada en datos bien preparados, que ayude a entender mejor a los clientes y a tomar decisiones informadas.

3. Dataset utilizado: El análisis se realizó utilizando tres bases de datos en formato CSV:

* plans.csv: Contiene información sobre los planes actuales ofrecidos por la empresa, incluyendo precio, minutos incluidos, gigabytes disponibles y costos por consumo adicional.
* users_latam.csv: Incluye información de los clientes, como edad, ciudad, fecha de registro, plan contratado y fecha de cancelación del servicio.
* usage.csv: Registra el uso real del servicio, detallando llamadas (duración) y mensajes (longitud), así como el tipo de interacción y la fecha.

Estas tres fuentes permiten conectar lo que el cliente contrata con lo que realmente utiliza.

4. Contenido del repositorio: Este repositorio contiene: Un Jupyter Notebook con el desarrollo completo del proyecto, documentado paso a paso.
El notebook incluye exploración de datos, limpieza, análisis exploratorio, segmentación de clientes y conclusiones de negocio.
No se incluyen los datasets originales, ya que se trata de datos utilizados únicamente con fines analíticos.

El enfoque del notebook es didáctico y progresivo, permitiendo seguir el razonamiento desde el inicio hasta las conclusiones finales.

5. Instrucciones de uso: Para obtener el máximo valor de este proyecto, se recomienda:

* Abrir el notebook y revisarlo en orden secuencial, de arriba hacia abajo.
* Leer los comentarios y explicaciones incluidos en cada sección.
* Analizar las visualizaciones junto con los insights que las acompañan.
* Revisar con atención la sección final de conclusiones y recomendaciones.

El proyecto está diseñado para que el lector pueda entender tanto el qué como el por qué de cada decisión tomada durante el análisis.

6. Información técnica: Herramientas utilizadas

El análisis fue desarrollado utilizando las siguientes herramientas:

* Python
* pandas
* numpy
* matplotlib
* seaborn

Estas herramientas permiten manipular datos, crear visualizaciones claras y obtener insights de forma eficiente.

7. Supuestos del análisis: Durante el desarrollo del proyecto se tomaron algunas decisiones importantes:

* Los valores nulos en duración y longitud no fueron imputados, ya que dependen del tipo de uso (mensajes vs. llamadas) y representan información válida.
* Los outliers detectados en consumo no fueron eliminados, ya que corresponden a usuarios reales con patrones intensivos.
* Variables con alta proporción de nulos sin valor analítico, como la fecha de cancelación, fueron excluidas del análisis principal.
* Se priorizó la interpretación de negocio sobre la complejidad técnica.

8. Contacto / Autor
Autor: Caren Russian

Este proyecto fue desarrollado como parte de un ejercicio de análisis de datos aplicado a un contexto real de negocio en telecomunicaciones.

8. Fecha de creación / actualización

20 de enero de 2026

9. Cierre

Este proyecto demuestra que los datos no solo sirven para describir el pasado, sino para revelar oportunidades ocultas. Al analizar el uso real de los clientes, se hizo evidente que la edad no es el factor que explica el consumo, sino el comportamiento. Un pequeño grupo de usuarios genera un impacto significativo y, si se gestiona correctamente, puede convertirse en una palanca clave de crecimiento.
El análisis invita a mirar más allá de los planes contratados y a escuchar lo que los datos cuentan sobre los clientes. Esta es solo una primera aproximación, pero abre la puerta a análisis más profundos y a decisiones de negocio más inteligentes.
Si este proyecto despertó tu interés, el siguiente paso es explorar el notebook, profundizar en los insights y seguir descubriendo qué más pueden contar los datos.

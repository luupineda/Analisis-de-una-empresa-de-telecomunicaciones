# Análisis de una empresa de telecomunicaciones

Entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).  

**Objetivo:** Identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

**Herramientas**
🛠 Python | Numpy | Matplotlib | Seaborn | Jupyter Notebook

**Preguntas clave**
1. ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
2. ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
3. ¿Cómo varía el uso según la edad y el tipo de plan contratado?
4. ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

**Metodología**
- Integré y limpié las bases de datos provenientes de tres fuentes distintas. Aplicando técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construí un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos y detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Por último, se crearon segmentaciones de clientes basadas en edad, país y comportamiento de uso. Luego, se visualizaron diferencias entre segmentos y extraer insights comerciales relevantes.

**Hallazgos y recomendaciones**
- El 75% de usuarios están en "Uso Medio" pero muchos tienen plan Básico esto sugiere: Gran potencial de upgrade a Premium. Además los Jóvenes (<30) ya adoptan Premium más fácilmente y Adultos mayores (70-80) muestran alta disposición de pago se podrían implementar estrategias diferenciadas por grupo etario
- Estrategia de Conversión Masiva en Usuarios de "Uso Medio" con Plan Básico (~2,250 usuarios) por ejemplo: "tu uso actual sugiere que Premium te ahorraría dinero" y en Usuarios de "Alto Uso" (250 usuarios) tener un programa VIP, soporte prioritario y funciones exclusivas.

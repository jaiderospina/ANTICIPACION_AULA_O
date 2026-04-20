# Glosario de Técnicas de Evaluación de Riesgo
> **Actividad en Grupo | Gestión del Riesgo | ESDEG 2026**  
> Ing. MSc. Jaider Ospina Navas

---
Alumnos:
CC Yesid Mesa Mantilla
MY ROMERO FERNANDEZ NELSON

## Técnicas de Evaluación de Riesgo

### 1.  Lluvia de Ideas (*Brainstorming*)
**Definición:** Técnica grupal de identificación de riesgos en la que los participantes generan ideas libremente, sin restricciones ni juicios previos, con el fin de descubrir el mayor número posible de amenazas, causas o consecuencias.

**Ejemplo en Ciberseguridad:** Un equipo de analistas de seguridad se reúne para identificar posibles vectores de ataque contra una nueva plataforma de comando y control militar. Sin filtros, proponen desde phishing dirigido a operadores hasta ataques de cadena de suministro sobre el software embebido.

---

### 2.  Entrevista Estructurada
**Definición:** Técnica de recolección de información mediante preguntas predefinidas aplicadas a expertos o partes interesadas, con el objetivo de identificar y evaluar riesgos de forma sistemática y reproducible.

**Ejemplo en Ciberseguridad:** Un oficial de seguridad entrevista a los administradores de sistemas de una base militar utilizando un cuestionario estandarizado para identificar brechas en la gestión de accesos privilegiados (PAM) y políticas de contraseñas.

---

### 3. Delphi
**Definición:** Método de consulta iterativa a un panel de expertos que responden de forma anónima a cuestionarios sucesivos. Las respuestas se consolidan y retroalimentan hasta alcanzar consenso sobre la valoración de un riesgo.

**Ejemplo en Ciberseguridad:** Se consulta a expertos en inteligencia de amenazas de varios países aliados para estimar la probabilidad de que actores estatales desarrollen capacidades de ataque contra infraestructura crítica de energía en los próximos tres años.

---

### 4. Lista de Verificación (*Checklist*)
**Definición:** Herramienta que contiene un conjunto predefinido de ítems, controles o condiciones que deben verificarse para asegurar que no se omita ningún riesgo conocido o requisito establecido.

**Ejemplo en Ciberseguridad:** Durante una auditoría de seguridad bajo ISO 27001 o el marco NIST CSF, se usa una lista de verificación para comprobar que todos los controles de seguridad estén implementados: cifrado en reposo, autenticación multifactor, registros de auditoría activos, etc.

---

### 5. Análisis Primario de Peligros (*Preliminary Hazard Analysis - PHA*)
**Definición:** Técnica de identificación temprana de peligros realizada en las fases iniciales de diseño de un sistema, antes de que se definan con detalle los procedimientos operativos.

**Ejemplo en Ciberseguridad:** Durante el diseño de una red de comunicaciones táctica militar, se realiza un PHA para identificar peligros iniciales como la interceptación de frecuencias, la suplantación de identidad de nodos de red y la denegación de servicio en canales de mando.

---

### 6. Estudio de Peligros y Operatividad (*HAZOP*)
**Definición:** Técnica estructurada y sistemática que examina cómo las desviaciones de las condiciones de diseño en un proceso o sistema pueden generar peligros o problemas operativos, usando palabras guía como "más", "menos", "ninguno", "inverso".

**Ejemplo en Ciberseguridad:** Se aplica HAZOP a un sistema SCADA que controla una represa. Se analiza qué ocurre si el flujo de datos de los sensores llega tarde (*más lento*), con valores erróneos (*invertido*) o simplemente no llega (*ninguno*), como consecuencia de un ciberataque de manipulación de datos.

---

### 7.  Análisis de Peligros y Puntos Críticos de Control (*APPCC / HACCP*)
**Definición:** Metodología preventiva que identifica, evalúa y controla peligros en puntos críticos de un proceso para garantizar la seguridad del producto o servicio final.

**Ejemplo en Ciberseguridad:** En el ciclo de desarrollo seguro de software (SSDLC) de una aplicación gubernamental, se identifican los "puntos críticos" donde puede introducirse código malicioso: integración de librerías de terceros, compilación y despliegue. Se establecen controles de validación en cada uno.

---

### 8.  Valoración del Riesgo Ambiental
**Definición:** Proceso de identificación y evaluación de los impactos negativos que una actividad, sustancia o sistema puede tener sobre el entorno natural o social.

**Ejemplo en Ciberseguridad:** Se evalúa el impacto ambiental y civil de un ciberataque exitoso contra el sistema de control de una planta de tratamiento de agua, considerando el riesgo de contaminación química por manipulación de dosis de cloro vía acceso remoto no autorizado.

---

### 9.  Estructura "¿Qué Pasa Si?" (*SWIFT — Structured What-If Technique*)
**Definición:** Técnica de análisis de riesgo en la que un equipo experto formula sistemáticamente preguntas del tipo "¿qué pasaría si…?" para identificar escenarios de riesgo que podrían no haberse considerado.

**Ejemplo en Ciberseguridad:** El equipo de ciberdefensa aplica SWIFT a la infraestructura de red preguntando: ¿qué pasa si el firewall principal falla simultáneamente con un ataque DDoS? ¿Qué pasa si las credenciales del administrador son comprometidas durante una actualización?

---

### 10. Análisis de Escenarios
**Definición:** Técnica que construye y examina situaciones hipotéticas detalladas (escenarios futuros posibles) para evaluar cómo distintos eventos podrían afectar a una organización y sus objetivos.

**Ejemplo en Ciberseguridad:** Se construyen tres escenarios de ataque para un centro de operaciones de seguridad (SOC) militar: (1) ataque de ransomware durante operaciones activas, (2) espionaje silencioso de largo plazo (APT), y (3) sabotaje coordinado de comunicaciones durante un ejercicio conjunto.

---

### 11. Análisis de Impacto al Negocio (*BIA — Business Impact Analysis*)
**Definición:** Proceso que identifica y cuantifica los efectos que la interrupción de procesos críticos tendría sobre la organización, permitiendo priorizar la recuperación de recursos y funciones esenciales.

**Ejemplo en Ciberseguridad:** Tras un simulacro de ataque de ransomware en una institución de defensa, el BIA determina que el sistema de gestión de inteligencia es el más crítico (RTO de 2 horas), seguido por las comunicaciones cifradas y la gestión de personal.

---

### 12.  Análisis de Causa Raíz (*Root Cause Analysis - RCA*)
**Definición:** Método que investiga en profundidad un evento adverso ya ocurrido para identificar su causa fundamental, en lugar de tratar solo los síntomas, con el fin de prevenir su recurrencia.

**Ejemplo en Ciberseguridad:** Tras una brecha de datos en un sistema clasificado, el RCA determina que la causa raíz no fue el malware en sí mismo, sino la ausencia de segmentación de red, que permitió el movimiento lateral del atacante desde un equipo no crítico hasta la base de datos sensible.

---

### 13. Análisis de Modo y Efecto de Falla (*AMEF / FMEA*)
**Definición:** Técnica sistemática que analiza los posibles modos de fallo de los componentes de un sistema, sus efectos sobre el funcionamiento global y la criticidad de cada uno, para priorizar acciones de mitigación.

**Ejemplo en Ciberseguridad:** Se aplica FMEA a un clúster de servidores de autenticación. Se identifica que el modo de fallo "saturación del servicio RADIUS" tiene una alta severidad (bloqueo total de accesos), alta ocurrencia (objetivo frecuente de DDoS) y baja detectabilidad, resultando en un número de prioridad de riesgo (NPR) crítico.

---

### 14. Análisis de Árbol de Fallas (*FTA — Fault Tree Analysis*)
**Definición:** Técnica deductiva (de arriba hacia abajo) que parte de un evento no deseado y descompone lógicamente todas las combinaciones de causas y condiciones que podrían ocasionarlo, usando puertas lógicas AND/OR.

**Ejemplo en Ciberseguridad:** Partiendo del evento cima "Compromiso exitoso de un sistema de armas conectado", se construye el árbol: para que ocurra, debe fallar el firewall perimetral **Y** el sistema de detección de intrusos, **O** bien un usuario interno con privilegios debe ejecutar código malicioso.

---

### 15. Análisis de Árbol de Eventos (*ETA — Event Tree Analysis*)
**Definición:** Técnica inductiva (de abajo hacia arriba) que, partiendo de un evento iniciador, modela las secuencias de eventos subsecuentes y sus probabilidades, mapeando todos los posibles resultados finales.

**Ejemplo en Ciberseguridad:** Partiendo del evento iniciador "correo de phishing recibido por un operador", el árbol de eventos mapea: ¿el usuario hace clic? → ¿el antivirus detecta el payload? → ¿el sandbox lo bloquea? → ¿el EDR alerta al SOC? Cada rama lleva a un resultado diferente con su probabilidad asociada.

---

### 16. Análisis de Causa y Consecuencia
**Definición:** Técnica híbrida que combina el Árbol de Fallas (causas) y el Árbol de Eventos (consecuencias), analizando simultáneamente las causas de un evento iniciador y las posibles consecuencias resultantes.

**Ejemplo en Ciberseguridad:** Se analiza un fallo en el sistema de autenticación de una VPN militar: hacia atrás se trazan las causas (vulnerabilidad de día cero, credenciales robadas) y hacia adelante las consecuencias (acceso no autorizado a la red interna, exfiltración de datos, interrupción de operaciones).

---

### 17. Análisis de Causa/Efecto (*Diagrama de Ishikawa / Espina de Pescado*)
**Definición:** Herramienta visual que organiza las posibles causas de un problema en categorías (personas, procesos, tecnología, entorno, etc.) para facilitar la identificación de la causa raíz.

**Ejemplo en Ciberseguridad:** Ante el efecto "Filtración de información clasificada", el diagrama organiza causas en: Personas (ingeniería social, usuario negligente), Tecnología (software sin parches, cifrado débil), Procesos (falta de política de clasificación), y Entorno (acceso físico no controlado a terminales).

---

### 18.  Análisis de Capas de Protección (*LOPA — Layer of Protection Analysis*)
**Definición:** Método semi-cuantitativo que evalúa si las capas de protección independientes existentes son suficientes para reducir la frecuencia de un escenario de riesgo a un nivel tolerable.

**Ejemplo en Ciberseguridad:** Para el escenario "acceso no autorizado a datos de inteligencia", se evalúan las capas: (1) autenticación multifactor, (2) firewall de aplicación, (3) cifrado de datos, (4) monitoreo SIEM, (5) respuesta de SOC. Se calcula si la reducción acumulada de probabilidad es suficiente.

---

### 19.  Árbol de Decisión (*Decision Tree*)
**Definición:** Herramienta gráfica que representa decisiones y sus posibles consecuencias, incluyendo probabilidades y valores de resultado, para apoyar la selección de la mejor opción de respuesta ante un riesgo.

**Ejemplo en Ciberseguridad:** Ante la detección de una amenaza persistente avanzada (APT) en la red, el árbol de decisión guía al equipo: ¿contener ahora (riesgo de alertar al atacante) o monitorear más (riesgo de mayor exfiltración)? Cada rama muestra probabilidades e impactos esperados.

---

### 20.  Análisis de Confiabilidad Humana (*HRA — Human Reliability Analysis*)
**Definición:** Técnica que evalúa la probabilidad de error humano en tareas críticas de un sistema, identificando los factores de rendimiento que pueden degradar o mejorar el desempeño del operador.

**Ejemplo en Ciberseguridad:** Se analiza la confiabilidad de un analista del SOC al revisar alertas de seguridad durante un turno nocturno de 12 horas. Se identifican factores degradantes: fatiga, alta tasa de falsos positivos y falta de contexto automático en las alertas, que elevan la probabilidad de omitir un incidente real.

---

### 21.  Análisis de Esquema de Corbatín (*Bow Tie*)
**Definición:** Técnica visual que combina el árbol de fallas (causas) y el árbol de eventos (consecuencias) en un diagrama con forma de corbatín, donde el nudo central es el evento de riesgo, mostrando barreras preventivas a la izquierda y controles mitigadores a la derecha.

**Ejemplo en Ciberseguridad:** El evento central es "Ransomware ejecutado en red corporativa". A la izquierda: barreras de prevención (filtro de correo, EDR, concienciación del usuario). A la derecha: controles de mitigación (backups offline, plan de respuesta a incidentes, segmentación de red para limitar propagación).

---

### 22.  Mantenimiento Enfocado en la Confiabilidad (*RCM — Reliability Centered Maintenance*)
**Definición:** Metodología que determina los requerimientos de mantenimiento de activos físicos según su función y los modos de fallo que puedan afectarla, optimizando recursos y maximizando la disponibilidad.

**Ejemplo en Ciberseguridad:** Se aplica RCM a los equipos de seguridad de red (firewalls, IDS, switches) de una instalación militar, definiendo planes de mantenimiento preventivo y actualizaciones de firmware priorizadas según la criticidad de cada dispositivo para la continuidad operacional.

---

### 23.  Análisis de Circuito Furtivo (*Sneak Circuit Analysis - SCA*)
**Definición:** Técnica originada en ingeniería electrónica que busca caminos no intencionados (furtivos) en un circuito o sistema que pueden causar operaciones no deseadas sin necesidad de un fallo convencional.

**Ejemplo en Ciberseguridad:** Se aplica para detectar canales encubiertos (*covert channels*) en la red, donde un atacante exfiltra datos clasificados usando protocolos no diseñados para ello, como codificar información en los tiempos de respuesta de consultas DNS o en el campo de identificación de paquetes ICMP.

---

### 24.  Análisis de Markov (*Markov Analysis*)
**Definición:** Técnica cuantitativa que modela el comportamiento de un sistema mediante estados discretos y las probabilidades de transición entre ellos, útil para sistemas que presentan degradación gradual o múltiples estados operativos.

**Ejemplo en Ciberseguridad:** Se modela el ciclo de vida de un sistema de información bajo ataque con los estados: **Seguro → Reconocido (footprint) → Comprometido → Contenido → En Recuperación → Seguro**. Se calculan las tasas de transición entre estados para estimar el tiempo medio de permanencia en cada uno y optimizar la respuesta.

---

### 25.  Simulación Monte Carlo
**Definición:** Técnica cuantitativa que utiliza muestreo aleatorio repetido (miles o millones de iteraciones) para modelar la incertidumbre en las variables de un sistema y obtener distribuciones de probabilidad de los resultados posibles.

**Ejemplo en Ciberseguridad:** Se simula el impacto financiero de un ciberataque durante un año, variando aleatoriamente variables como: probabilidad de ocurrencia de cada tipo de ataque, tiempo de detección, costo de recuperación y multas regulatorias. El resultado muestra que existe un 15% de probabilidad de pérdidas superiores a USD 5 millones.

---

### 26.  Redes Bayesianas (*Bayesian Networks*)
**Definición:** Modelos gráficos probabilísticos que representan las dependencias condicionales entre variables mediante grafos dirigidos acíclicos, permitiendo actualizar la probabilidad de un evento a medida que se dispone de nueva evidencia.

**Ejemplo en Ciberseguridad:** Un sistema de detección de intrusos (IDS) usa redes bayesianas para calcular la probabilidad de que un comportamiento anómalo sea un ataque real, actualizando la probabilidad a medida que se combinan evidencias: hora inusual de acceso, geolocalización atípica, volumen de descarga elevado y usuario sin historial de ese tipo de actividad.

---

### 27. Índices de Riesgo (*Risk Indices*)
**Definición:** Métricas numéricas compuestas que integran múltiples factores de riesgo en un valor único estandarizado, permitiendo comparar y priorizar riesgos de forma rápida y consistente.

**Ejemplo en Ciberseguridad:** Se calcula el Índice de Riesgo Cibernético (CRI) de cada sistema de una organización de defensa combinando: puntuación CVSS de vulnerabilidades conocidas, nivel de exposición a internet, criticidad del activo y madurez de los controles existentes, generando un ranking de priorización para el equipo de seguridad.

---

### 28. Matriz de Consecuencia y Probabilidad (*Risk Matrix*)
**Definición:** Herramienta semicuantitativa que clasifica y prioriza riesgos ubicándolos en una cuadrícula bidimensional según su probabilidad de ocurrencia y la severidad de sus consecuencias, generalmente codificada por colores (verde/amarillo/rojo).

**Ejemplo en Ciberseguridad:** El equipo de ciberdefensa ubica en la matriz los riesgos identificados: un ataque de ransomware (alta probabilidad, consecuencia muy alta = zona roja/crítica), una falla de hardware de firewall (media probabilidad, consecuencia alta = zona naranja), y un intento de acceso físico no autorizado (baja probabilidad, consecuencia media = zona amarilla).

---

### 29.  Análisis de Costo/Beneficio (*Cost-Benefit Analysis - CBA*)
**Definición:** Técnica que compara el costo de implementar un control o medida de tratamiento del riesgo frente al beneficio esperado (reducción del impacto o probabilidad del riesgo), para determinar si la inversión es justificable.

**Ejemplo en Ciberseguridad:** Se evalúa la implementación de un sistema SIEM avanzado con costo anual de USD 200.000. El análisis determina que la reducción en el tiempo de detección de incidentes evitaría pérdidas esperadas de USD 800.000 anuales, resultando en un beneficio neto positivo de USD 600.000 y justificando la inversión.

---

### 30.  Análisis de Decisión por Criterios Múltiples (*MCDM — Multi-Criteria Decision Analysis*)
**Definición:** Conjunto de métodos formales que apoyan la toma de decisiones cuando se deben evaluar simultáneamente múltiples criterios (a veces contrapuestos) para seleccionar la mejor alternativa entre varias opciones de tratamiento del riesgo.

**Ejemplo en Ciberseguridad:** Al seleccionar una solución de gestión de identidades y accesos (IAM) para una organización de defensa, se evalúan cuatro alternativas usando criterios ponderados: nivel de seguridad (40%), integración con sistemas legacy (25%), costo total de propiedad (20%) y facilidad de uso para operadores (15%). La técnica TOPSIS o AHP permite identificar la opción óptima de forma objetiva y trazable.

---

## Resumen Visual por Categorías

| Categoría | Técnicas |
|---|---|
| **Identificación y Brainstorming** | Lluvia de Ideas, Entrevista Estructurada, Delphi, Lista de Verificación, SWIFT |
| **Análisis de Peligros** | PHA, HAZOP, APPCC, Valoración Ambiental |
| **Análisis de Escenarios** | Análisis de Escenarios, BIA, Árbol de Decisión |
| **Análisis de Causas** | RCA, Causa/Efecto (Ishikawa), Causa y Consecuencia |
| **Análisis de Fallas** | AMEF/FMEA, Árbol de Fallas, Árbol de Eventos |
| **Modelos de Protección** | LOPA, Bow Tie, RCM, SCA |
| **Métodos Cuantitativos** | Markov, Monte Carlo, Redes Bayesianas, HRA |
| **Priorización y Decisión** | Índices de Riesgo, Matriz C/P, CBA, MCDM |

---

## Referencias
- ISO 31000:2018 — Gestión del Riesgo: Principios y Directrices
- ISO 31010:2019 — Técnicas de Evaluación del Riesgo
- NIST SP 800-30 — Guide for Conducting Risk Assessments
- https://github.com/jaiderospina/GESTION_RIESGO/tree/main/TECNICAS

---
*Escuela Superior de Guerra "General Rafael Reyes Prieto" — ESDEG 2026*

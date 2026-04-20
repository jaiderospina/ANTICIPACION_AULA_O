# Glosario de Técnicas de Evaluación de Riesgo
## Aplicadas a la Ciberseguridad y Ciberdefensa

> **Asignatura:** Gestión de Riesgos en Ciberseguridad  
> **Carpeta:** `TRABAJOS/TECNICAS/GRUPO_1/`  
> **Referencia normativa:** ISO/IEC 31010:2019 – Gestión del riesgo – Técnicas de evaluación del riesgo

---

## Índice

1. [Lluvia de ideas](#1-lluvia-de-ideas)
2. [Lista de verificación](#2-lista-de-verificación)
3. [Análisis de peligros y puntos críticos de control](#3-análisis-de-peligros-y-puntos-críticos-de-control)
4. [Análisis de escenarios](#4-análisis-de-escenarios)
5. [Análisis de modo y efecto de falla (EMEF/FMEA)](#5-análisis-de-modo-y-efecto-de-falla-emeffmea)
6. [Entrevista estructurada](#6-entrevista-estructurada)
7. [Análisis primario de peligros (APH)](#7-análisis-primario-de-peligros-aph)
8. [Valoración del riesgo ambiental](#8-valoración-del-riesgo-ambiental)
9. [Análisis de impacto al negocio (BIA)](#9-análisis-de-impacto-al-negocio-bia)
10. [Análisis de árbol de fallas (AAF/FTA)](#10-análisis-de-árbol-de-fallas-aaffta)
11. [Delphi](#11-delphi)
12. [Estudio de peligros y operatividad (HAZOP)](#12-estudio-de-peligros-y-operatividad-hazop)
13. [Estructura ¿qué pasa si? (SWIFT)](#13-estructura-qué-pasa-si-swift)
14. [Análisis de causa raíz (RCA)](#14-análisis-de-causa-raíz-rca)
15. [Análisis de árbol de eventos (AAE/ETA)](#15-análisis-de-árbol-de-eventos-aaeets)
16. [Análisis de causa y consecuencia](#16-análisis-de-causa-y-consecuencia)
17. [Análisis de causa/efecto (Ishikawa)](#17-análisis-de-causaefecto-ishikawa)
18. [Análisis de capas de protección (LOPA)](#18-análisis-de-capas-de-protección-lopa)
19. [Árbol de decisión](#19-árbol-de-decisión)
20. [Análisis de confiabilidad humana (HRA)](#20-análisis-de-confiabilidad-humana-hra)
21. [Análisis de esquema de corbatín (Bow Tie)](#21-análisis-de-esquema-de-corbatín-bow-tie)
22. [Mantenimiento enfocado en la confiabilidad (RCM)](#22-mantenimiento-enfocado-en-la-confiabilidad-rcm)
23. [Análisis de circuito furtivo (Sneak Circuit)](#23-análisis-de-circuito-furtivo-sneak-circuit)
24. [Análisis de Markov](#24-análisis-de-markov)
25. [Simulación Monte Carlo](#25-simulación-monte-carlo)
26. [Redes bayesianas](#26-redes-bayesianas)
27. [Índices de riesgo](#27-índices-de-riesgo)
28. [Matriz de consecuencia y probabilidad](#28-matriz-de-consecuencia-y-probabilidad)
29. [Análisis de costo/beneficio](#29-análisis-de-costobeneficio)
30. [Análisis de decisión por criterios múltiples (MCDA)](#30-análisis-de-decisión-por-criterios-múltiples-mcda)

---

## 1. Lluvia de ideas

**Definición:** Técnica cualitativa de generación de ideas en grupo, sin restricciones ni juicios inmediatos, destinada a identificar amenazas, vulnerabilidades u oportunidades de mejora. Facilita la participación de múltiples perspectivas.

**Ejemplo en ciberseguridad:** Un equipo de seguridad realiza una sesión de *brainstorming* para identificar posibles vectores de ataque contra la infraestructura de autenticación de una aplicación bancaria (fuerza bruta, *phishing*, MFA *bypass*, relleno de credenciales, etc.) antes de diseñar los controles de seguridad.

---

## 2. Lista de verificación

**Definición:** Instrumento estructurado que enumera ítems, condiciones o requisitos predefinidos que deben verificarse para garantizar el cumplimiento de controles o la identificación de deficiencias conocidas.

**Ejemplo en ciberseguridad:** Uso de listas de verificación basadas en el marco CIS Controls o en el estándar PCI-DSS para auditar la configuración segura de servidores (*hardening*): verificar deshabilitación de servicios innecesarios, aplicación de parches, configuración de firewall, etc.

---

## 3. Análisis de peligros y puntos críticos de control

**Definición:** Metodología sistemática (originada en la industria alimentaria) que identifica peligros significativos y establece puntos críticos de control (PCC) con límites, monitoreo y acciones correctivas para prevenir daños.

**Ejemplo en ciberseguridad:** Aplicado al ciclo de desarrollo seguro (SSDLC): identificar los puntos críticos donde puede introducirse código malicioso (dependencias de terceros, repositorios de código, proceso de *build*) y establecer controles como análisis SCA (*Software Composition Analysis*) y firma de artefactos.

---

## 4. Análisis de escenarios

**Definición:** Técnica que describe y evalúa situaciones hipotéticas plausibles (favorables, neutras y adversas) para explorar el impacto de diferentes condiciones futuras sobre el objeto de análisis.

**Ejemplo en ciberseguridad:** Elaboración de escenarios de amenazas persistentes avanzadas (APT): ¿Qué ocurriría si un actor patrocinado por un Estado compromete la cadena de suministro de software de un proveedor crítico? Permite planificar respuesta a incidentes y resiliencia.

---

## 5. Análisis de modo y efecto de falla (EMEF/FMEA)

**Definición:** Método proactivo que identifica sistemáticamente los modos de falla potenciales de un sistema, sus efectos y causas, asignando un número de prioridad de riesgo (NPR) para priorizar acciones correctivas.

**Ejemplo en ciberseguridad:** Análisis FMEA sobre un sistema de gestión de identidades (IAM): modo de falla = "token de sesión sin expiración", efecto = "acceso persistente no autorizado tras cierre de sesión", severidad alta, frecuencia media → control: implementar TTL corto y revocación activa de tokens.

---

## 6. Entrevista estructurada

**Definición:** Proceso de recopilación de información mediante preguntas predefinidas formuladas a individuos clave, permitiendo capturar conocimiento experto, percepciones de riesgo y contexto organizacional de forma consistente y reproducible.

**Ejemplo en ciberseguridad:** Entrevistas a administradores de sistemas y usuarios privilegiados para identificar riesgos de amenaza interna (*insider threat*): prácticas de manejo de credenciales, accesos indebidos conocidos, controles eludidos informalmente.

---

## 7. Análisis primario de peligros (APH)

**Definición:** Técnica inductiva preliminar que identifica los peligros más significativos de un sistema en las etapas tempranas de su ciclo de vida, clasificando su severidad de forma cualitativa para orientar análisis posteriores más detallados.

**Ejemplo en ciberseguridad:** Durante la fase de diseño de arquitectura de una plataforma *cloud*, se identifican peligros primarios: exposición de buckets S3 públicos, ausencia de cifrado en tránsito, falta de segmentación de red — priorizando cuáles requieren análisis profundo antes del despliegue.

---

## 8. Valoración del riesgo ambiental

**Definición:** Evaluación de los riesgos derivados del entorno físico y lógico que rodea al sistema analizado, considerando factores externos como ubicación geográfica, condiciones climáticas, regulaciones y contexto geopolítico.

**Ejemplo en ciberseguridad:** Valoración del riesgo para un centro de datos ubicado en una región con inestabilidad política y alto índice de criminalidad cibernética: evalúa riesgos de corte de fibra óptica, ataques DDoS patrocinados por Estados, o requisitos legales de localización de datos (*data residency*).

---

## 9. Análisis de impacto al negocio (BIA)

**Definición:** Proceso que identifica las funciones críticas del negocio y cuantifica el impacto operacional, financiero y reputacional de su interrupción, estableciendo los tiempos máximos tolerables (MTD), objetivos de recuperación (RTO/RPO) y prioridades de continuidad.

**Ejemplo en ciberseguridad:** Tras un ataque de ransomware hipotético, el BIA determina que la plataforma de pagos en línea tiene un RTO de 4 horas y un RPO de 30 minutos, justificando la inversión en replicación en tiempo real y planes de respuesta a incidentes con procedimientos de *failover*.

---

## 10. Análisis de árbol de fallas (AAF/FTA)

**Definición:** Técnica deductiva y gráfica que parte de un evento no deseado (*top event*) y descompone de forma descendente las combinaciones de eventos y condiciones (puertas lógicas AND/OR) que podrían causarlo.

**Ejemplo en ciberseguridad:** Árbol de fallas para el evento "compromiso de cuenta de administrador de dominio": ramas incluyen *phishing* exitoso (AND: clic en enlace + credenciales capturadas), escalada de privilegios (AND: vulnerabilidad sin parche + acceso inicial), o *pass-the-hash* (AND: ausencia de segmentación + Mimikatz ejecutado).

---

## 11. Delphi

**Definición:** Método de consulta iterativa a un panel de expertos de forma anónima, con retroalimentación controlada entre rondas, hasta lograr consenso sobre estimaciones de probabilidad, impacto o prioridad de riesgos.

**Ejemplo en ciberseguridad:** Consulta Delphi a expertos en inteligencia de amenazas para estimar la probabilidad de un ataque a infraestructura crítica nacional en los próximos 12 meses, considerando el panorama geopolítico y las TTPs (tácticas, técnicas y procedimientos) observadas en el MITRE ATT&CK.

---

## 12. Estudio de peligros y operatividad (HAZOP)

**Definición:** Técnica estructurada y sistemática basada en el uso de palabras guía (*No, Más, Menos, Parte de, Además de, Inverso, Otro que*) aplicadas a parámetros del proceso para identificar desviaciones que puedan generar peligros o problemas operativos.

**Ejemplo en ciberseguridad:** HAZOP sobre el flujo de autenticación de una API REST: parámetro = "token de autorización", palabra guía "No" → ausencia de token: ¿el sistema responde correctamente con HTTP 401 o expone recursos? Palabra guía "Más" → token expirado enviado múltiples veces: ¿existe limitación de reintentos?

---

## 13. Estructura ¿qué pasa si? (SWIFT)

**Definición:** Técnica de revisión semi-estructurada que utiliza la pregunta "¿Qué pasa si...?" como disparador sistemático para identificar riesgos, facilitada por un equipo multidisciplinario con apoyo de listas de comprobación predefinidas.

**Ejemplo en ciberseguridad:** Sesión SWIFT en una organización: "¿Qué pasa si el proveedor de servicios de DNS sufre un ataque de envenenamiento de caché?", "¿Qué pasa si el certificado TLS del sitio corporativo expira sin aviso?", "¿Qué pasa si un empleado remoto conecta su equipo corporativo a una red Wi-Fi pública sin VPN?"

---

## 14. Análisis de causa raíz (RCA)

**Definición:** Proceso investigativo retrospectivo que va más allá de los síntomas superficiales de un incidente para identificar la causa fundamental que lo originó, con el objetivo de implementar correcciones duraderas y evitar su recurrencia.

**Ejemplo en ciberseguridad:** Tras una brecha de datos, el RCA determina que la causa raíz no fue solo la vulnerabilidad SQL injection explotada, sino la ausencia de un proceso formal de revisión de código seguro y la falta de pruebas DAST en el pipeline de CI/CD — permitiendo atacar el problema de fondo.

---

## 15. Análisis de árbol de eventos (AAE/ETA)

**Definición:** Técnica inductiva y gráfica que, partiendo de un evento iniciador, traza las posibles secuencias de eventos subsiguientes (éxito o fallo de barreras de seguridad) para estimar la probabilidad de diferentes consecuencias finales.

**Ejemplo en ciberseguridad:** Árbol de eventos iniciado por "detección de malware en endpoint": rama 1 = EDR lo neutraliza automáticamente (sin impacto); rama 2 = EDR falla, pero el SOC lo detecta en < 1 hora (impacto bajo); rama 3 = EDR falla y el SOC no detecta en 24h (movimiento lateral y exfiltración — impacto crítico).

---

## 16. Análisis de causa y consecuencia

**Definición:** Técnica híbrida que combina elementos del árbol de fallas (análisis causal hacia atrás) y del árbol de eventos (análisis consecuente hacia adelante), permitiendo evaluar simultáneamente las causas de un evento y sus posibles consecuencias.

**Ejemplo en ciberseguridad:** Análisis del evento "credenciales administrativas comprometidas": hacia atrás identifica causas (robo por *spear phishing*, reutilización de contraseñas, ausencia de MFA); hacia adelante traza consecuencias (acceso a sistemas críticos, exfiltración de datos, instalación de backdoor, impacto regulatorio).

---

## 17. Análisis de causa/efecto (Ishikawa)

**Definición:** Herramienta visual (diagrama de espina de pescado o diagrama de Ishikawa) que organiza y categoriza sistemáticamente las posibles causas de un problema o efecto no deseado en familias (Personas, Procesos, Tecnología, Entorno, etc.).

**Ejemplo en ciberseguridad:** Diagrama causa-efecto para el problema "alta tasa de infecciones por phishing": causas en Personas (falta de concienciación, fatiga ante alertas), Procesos (ausencia de simulacros regulares, proceso de reporte ineficiente), Tecnología (filtros de email insuficientes, ausencia de DMARC/DKIM).

---

## 18. Análisis de capas de protección (LOPA)

**Definición:** Método semi-cuantitativo que evalúa si las capas de protección independientes (IPL) existentes son suficientes para reducir la frecuencia de un escenario de riesgo hasta un nivel tolerable, calculando la frecuencia de consecuencia residual.

**Ejemplo en ciberseguridad:** LOPA para el escenario "acceso no autorizado a base de datos de producción": capas IPL evaluadas = firewall de red (PFD 0.1), WAF (PFD 0.01), autenticación MFA (PFD 0.01), cifrado de datos en reposo (mitiga impacto). Si la frecuencia residual supera el umbral tolerado, se requieren controles adicionales.

---

## 19. Árbol de decisión

**Definición:** Representación gráfica de secuencias de decisiones y sus posibles consecuencias, incluyendo probabilidades y valores de resultado, utilizada para seleccionar la opción de tratamiento del riesgo más adecuada bajo incertidumbre.

**Ejemplo en ciberseguridad:** Árbol de decisión para respuesta a un incidente de ransomware: rama 1 = pagar rescate (probabilidad de recuperación 60%, costo X, riesgo legal, incentivo a futuros ataques); rama 2 = restaurar desde backup (tiempo de recuperación 48h, costo Y, sin incentivo al atacante) → análisis del valor esperado orienta la decisión.

---

## 20. Análisis de confiabilidad humana (HRA)

**Definición:** Conjunto de técnicas que evalúan la probabilidad de error humano en tareas críticas, identificando los factores de rendimiento (*Performance Shaping Factors*) que influyen en la confiabilidad del operador y las consecuencias de sus errores.

**Ejemplo en ciberseguridad:** HRA aplicado a operadores del SOC: evaluación de la probabilidad de que un analista descarte una alerta de seguridad crítica como falso positivo durante un turno nocturno de alta carga, considerando factores como fatiga, interfaces confusas y volumen de alertas (*alert fatigue*).

---

## 21. Análisis de esquema de corbatín (Bow Tie)

**Definición:** Diagrama visual que combina el árbol de fallas (lado izquierdo: causas y barreras preventivas) con el árbol de eventos (lado derecho: consecuencias y barreras de mitigación), centrados en un evento peligroso (*top event*), ofreciendo una visión integral del riesgo.

**Ejemplo en ciberseguridad:** Bow Tie para el evento central "exfiltración de datos sensibles": lado izquierdo muestra amenazas (APT, empleado malicioso) y controles preventivos (DLP, segmentación de red, control de accesos); lado derecho muestra consecuencias (multa regulatoria, pérdida reputacional) y controles de mitigación (plan de comunicación de crisis, seguro cibernético).

---

## 22. Mantenimiento enfocado en la confiabilidad (RCM)

**Definición:** Metodología que determina los requisitos de mantenimiento de activos físicos en su contexto operacional, identificando las funciones del activo, los modos de falla y las tareas de mantenimiento más eficaces para preservar la funcionalidad con el mínimo riesgo.

**Ejemplo en ciberseguridad:** RCM aplicado a la infraestructura de seguridad: determinar la frecuencia óptima de actualización de firmas de IDS/IPS, pruebas de los sistemas de detección de intrusos y revisión de reglas SIEM, basándose en el historial de fallos y el impacto de la degradación de la detección.

---

## 23. Análisis de circuito furtivo (Sneak Circuit)

**Definición:** Técnica de ingeniería que identifica rutas, condiciones o mensajes no intencionales (*sneak paths*) en sistemas eléctricos o de software que pueden causar funcionamiento no deseado sin que exista un fallo de componente.

**Ejemplo en ciberseguridad:** Análisis de circuitos furtivos en sistemas de control industrial (ICS/SCADA): identificar rutas de comunicación no documentadas entre redes IT y OT que permiten el tráfico lateral no autorizado, o lógica de control que puede ser activada de forma no prevista por una secuencia específica de comandos legítimos.

---

## 24. Análisis de Markov

**Definición:** Técnica cuantitativa que modela sistemas mediante cadenas o procesos de Markov, representando los diferentes estados del sistema (operativo, degradado, fallido) y las tasas de transición entre ellos para calcular disponibilidad, confiabilidad y mantenibilidad.

**Ejemplo en ciberseguridad:** Modelo de Markov para un sistema de autenticación con estados: "Seguro" → "Comprometido" → "Detectado" → "Recuperado" → "Seguro". Permite calcular el tiempo esperado en el estado comprometido antes de la detección (*mean time to detect*, MTTD) y optimizar los controles de monitoreo.

---

## 25. Simulación Monte Carlo

**Definición:** Método estadístico computacional que utiliza muestreo aleatorio repetido a partir de distribuciones de probabilidad de variables de entrada para generar distribuciones de posibles resultados, cuantificando la incertidumbre en las estimaciones de riesgo.

**Ejemplo en ciberseguridad:** Modelo de Monte Carlo para estimar el Valor en Riesgo Cibernético Anualizado (ALE): variables de entrada con distribuciones de probabilidad = frecuencia de ataques DDoS, duración del tiempo de inactividad, costo por hora de caída. Tras 100.000 simulaciones, se obtiene una distribución del ALE que informa las decisiones de inversión en ciberseguridad con intervalos de confianza.

---

## 26. Redes bayesianas

**Definición:** Modelos gráficos probabilísticos que representan variables aleatorias y sus dependencias condicionales mediante grafos acíclicos dirigidos, permitiendo actualizar la probabilidad de eventos a medida que se dispone de nueva evidencia.

**Ejemplo en ciberseguridad:** Red bayesiana para detección de amenazas internas: variables = comportamiento de acceso inusual, descarga masiva de datos, uso de dispositivos USB, baja calificación en evaluaciones de rendimiento. Permite calcular la probabilidad posterior de que un empleado sea una amenaza interna dado el conjunto de indicadores observados.

---

## 27. Índices de riesgo

**Definición:** Métricas cuantitativas o semi-cuantitativas que sintetizan múltiples factores de riesgo en un valor numérico o escalar único, facilitando la comparación, el seguimiento temporal y la comunicación del nivel de riesgo a la dirección.

**Ejemplo en ciberseguridad:** Índice de riesgo de vulnerabilidades basado en CVSS (Common Vulnerability Scoring System): combina métricas de vector de ataque, complejidad, privilegios requeridos, impacto en confidencialidad/integridad/disponibilidad para priorizar el *patchmanagement* en una organización con miles de activos.

---

## 28. Matriz de consecuencia y probabilidad

**Definición:** Herramienta visual semi-cuantitativa que ubica los riesgos en una cuadrícula bidimensional según su probabilidad de ocurrencia y la severidad de sus consecuencias, facilitando la priorización y la asignación de recursos de tratamiento.

**Ejemplo en ciberseguridad:** Mapa de calor de riesgos para una organización financiera: el riesgo "compromiso de credenciales por phishing" se posiciona en alta probabilidad / alto impacto (zona roja), mientras "ataque físico al datacenter" aparece en baja probabilidad / alto impacto (zona amarilla), orientando dónde enfocar los controles.

---

## 29. Análisis de costo/beneficio

**Definición:** Técnica económica que compara el costo de implementar un control o tratamiento de riesgo con los beneficios esperados (reducción de pérdidas, cumplimiento normativo, mejora de confianza), apoyando decisiones de inversión en seguridad bajo restricciones presupuestarias.

**Ejemplo en ciberseguridad:** Análisis costo/beneficio para la implementación de autenticación multifactor (MFA) empresarial: costo = licencias, capacitación, soporte; beneficio = reducción del 99.9% del riesgo de compromiso de cuentas por credenciales robadas (según datos de Microsoft) multiplicado por el impacto económico estimado de una brecha.

---

## 30. Análisis de decisión por criterios múltiples (MCDA)

**Definición:** Conjunto de metodologías que estructuran y resuelven problemas de decisión con múltiples criterios (a menudo conflictivos) y múltiples alternativas, integrando preferencias de los *stakeholders* para seleccionar la opción de tratamiento del riesgo más equilibrada.

**Ejemplo en ciberseguridad:** MCDA para seleccionar un proveedor de servicios SOC gestionado (MSSP): criterios ponderados = capacidades técnicas de detección, cobertura geográfica y horaria, cumplimiento normativo (ISO 27001, SOC2), tiempo de respuesta ante incidentes, costo total. La matriz de evaluación pondera cada alternativa para identificar la opción óptima.

---

## Referencias

- ISO 31000:2018 – Gestión del riesgo – Directrices.
- ISO/IEC 31010:2019 – Gestión del riesgo – Técnicas de evaluación del riesgo.
- NIST SP 800-30 Rev.1 – Guide for Conducting Risk Assessments.
- MITRE ATT&CK Framework – https://attack.mitre.org
- CVSS v3.1 Specification – https://www.first.org/cvss/
- Hubbard, D. W. & Seiersen, R. (2016). *How to Measure Anything in Cybersecurity Risk*. Wiley.

---

*Documento elaborado con fines académicos. Grupo 1 — Técnicas de Evaluación de Riesgo en Ciberseguridad y Ciberdefensa.*

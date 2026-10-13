# Tablero de seguimiento – Proyecto Integrador (Correos internos entre dos sedes)

**Equipo:** Jose Martin Fuel (JF) · Kevin Almache (KA) · Felipe Montenegro (FM)
**Periodo:** Sep 2026 – Ene 2027 (16 semanas)
**Estados:** Pendiente / En curso / Hecho. **Revisado:** Sí / No (la revisión la hace el responsable de la tarea, según el contrato de comunicación).

**Roles:** JF = Investigación cuantitativa y Tecnología y Sociedad · KA = Redes e infraestructura · FM = Software (Go) y Seguridad (FastAPI)

## Resumen por parcial

| Parcial | Semanas | Fases | Estado |
|---|---|---|---|
| Parcial 1 | 1–5 | 1 y 2 | En curso |
| Parcial 2 | 6–10 | 3 y 4 | Pendiente |
| Parcial 3 | 11–16 | 5 a 8 | Pendiente |

---

## Fase 1 – Contexto, planificación y organización (Sem. 1–2)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F1-01 | Documento de contexto y selección del sistema | JF | 1–2 | Hecho | No | `docs/` |
| F1-02 | Matriz de actores, roles y responsabilidades | KA | 1–2 | Hecho | No | `docs/` |
| F1-03 | Contrato de comunicación del equipo | FM | 1–2 | Hecho | No | `docs/` |
| F1-04 | Repositorio Git con README y licencia preliminar | KA | 1–2 | Hecho | No | enlace del repo |
| F1-05 | Declaración de integridad, licencia y uso de IA | FM | 1–2 | Pendiente | No | verificar que esté en el repo |
| F1-06 | Video de presentación y distribución de responsabilidades | Todos (edita FM) | 1–2 | Pendiente | No | enlace del video |

## Fase 2 – Análisis y requisitos (Sem. 3–5)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F2-01 | Objetivo general y objetivos específicos por asignatura | JF | 3 | Pendiente | No | |
| F2-02 | Alcance, restricciones y exclusiones | JF | 3 | Pendiente | No | |
| F2-03 | Requisitos funcionales y no funcionales con códigos (RF-SW, RF-NET, RF-SEC, RNF) | FM | 3–4 | Pendiente | No | |
| F2-04 | Especificación de requisitos con criterios de aceptación | FM | 4 | Pendiente | No | |
| F2-05 | Casos de uso: diagramas y flujos principales/alternativos | FM | 4 | Pendiente | No | |
| F2-06 | Dimensionamiento preliminar de VLAN, servicios y direccionamiento (10.10.0.0/16) | KA | 4 | Pendiente | No | |
| F2-07 | Matriz de trazabilidad inicial | KA | 4–5 | Pendiente | No | |
| F2-08 | Propuesta de investigación cuantitativa: problema, población, muestra, variables, instrumento preliminar | JF | 4–5 | Pendiente | No | |
| F2-09 | Matriz de actores, riesgos y consideraciones éticas (privacidad, datos personales, accesibilidad) | JF | 5 | Pendiente | No | |
| F2-10 | Video explicativo de análisis y alcance | Todos | 5 | Pendiente | No | |

## Fase 3 – Diseño de la solución (Sem. 6–7)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F3-01 | Diagrama integral de arquitectura (lógica y física, 2 sedes) | KA | 6 | Pendiente | No | |
| F3-02 | Plan VLSM, tabla de direccionamiento, VLAN y puertos | KA | 6 | Pendiente | No | |
| F3-03 | Diseño de troncales, EtherChannel, RSTP, Router-on-a-Stick y OSPF | KA | 6–7 | Pendiente | No | |
| F3-04 | Arquitectura cliente-servidor Go; diagramas de componentes/clases/secuencia | FM | 6–7 | Pendiente | No | |
| F3-05 | Modelo de datos FastAPI, flujo de autenticación y políticas de autorización | FM | 6–7 | Pendiente | No | |
| F3-06 | Plan de pruebas (funcionales, conectividad, seguridad, rendimiento) | FM + KA | 7 | Pendiente | No | |
| F3-07 | Plan de análisis estadístico y procedimiento de recolección de métricas | JF | 7 | Pendiente | No | |
| F3-08 | Prototipo visual de la interfaz y criterios de accesibilidad | JF + FM | 7 | Pendiente | No | |

## Fase 4 – Prototipo y desarrollo inicial (Sem. 8–10)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F4-01 | Estructura del repo según la guía (`app-go/`, `auth-service/`, `network/`, `research/`, `docs/`) | KA | 8 | Pendiente | No | |
| F4-02 | App Go: servidor, cliente, operaciones (enviar, bandeja, enviados, leer, eliminar) y validaciones | FM | 8–10 | Pendiente | No | |
| F4-03 | Servicio FastAPI: usuarios, registro, login, hash seguro de contraseñas | FM | 8–10 | Pendiente | No | |
| F4-04 | Config inicial de switches: VLAN, trunk 802.1Q, EtherChannel, RSTP | KA | 8–10 | Pendiente | No | |
| F4-05 | Config inicial de routers OpenWrt (Router-on-a-Stick) | KA | 9–10 | Pendiente | No | |
| F4-06 | Prueba piloto del instrumento y depuración de datos | JF | 9–10 | Pendiente | No | |
| F4-07 | Punto crítico de impacto y propuesta de mitigación (Tec. y Sociedad) | JF | 10 | Pendiente | No | |
| F4-08 | Bitácora de un punto crítico del equipo resuelto con comunicación asertiva | Todos | 10 | Pendiente | No | |
| F4-09 | Backups de configuraciones de red en el repo | KA | 10 | Pendiente | No | |
| F4-10 | Video de avance y demostración parcial | Todos | 10 | Pendiente | No | |

## Fase 5 – Integración y despliegue (Sem. 11–12)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F5-01 | Integración Go ↔ FastAPI (sesión válida para recursos protegidos) | FM | 11 | Pendiente | No | |
| F5-02 | Despliegue de cliente, servidor y autenticación en segmentos/sedes | FM + KA | 11–12 | Pendiente | No | |
| F5-03 | OSPF final entre sedes y verificación de rutas | KA | 11 | Pendiente | No | |
| F5-04 | NAT, DHCP y reglas de firewall | KA | 11–12 | Pendiente | No | |
| F5-05 | Políticas de comunicación entre VLAN y sedes + matriz de conectividad | KA | 12 | Pendiente | No | |
| F5-06 | Pruebas de integración y corrección de errores | FM + KA | 12 | Pendiente | No | |
| F5-07 | Evidencias de autenticación desde la app Go | FM | 12 | Pendiente | No | |
| F5-08 | Registro preliminar de métricas (latencia, tiempo de respuesta, errores) | JF | 12 | Pendiente | No | |
| F5-09 | Demostración de comunicación entre sedes + backups de switches y OpenWrt | KA | 12 | Pendiente | No | |

## Fase 6 – Pruebas, validación estadística y evaluación socio-tecnológica (Sem. 13–14)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F6-01 | Matriz de casos de prueba con resultados (funcionales, credenciales, errores) | FM | 13 | Pendiente | No | |
| F6-02 | Pruebas de conectividad intra-VLAN, inter-VLAN, entre sedes; OSPF, EtherChannel, RSTP, DHCP, NAT, firewall | KA | 13 | Pendiente | No | |
| F6-03 | Prueba de caída controlada de un servicio y manejo de errores | FM + KA | 13 | Pendiente | No | |
| F6-04 | Medición de latencia, tiempo de respuesta, disponibilidad y errores | JF | 13–14 | Pendiente | No | |
| F6-05 | Evaluación básica de usabilidad y accesibilidad | JF | 14 | Pendiente | No | |
| F6-06 | Conjunto de datos y diccionario de variables | JF | 14 | Pendiente | No | |
| F6-07 | Informe estadístico (tablas, gráficos, medidas descriptivas, interpretación) | JF | 14 | Pendiente | No | |
| F6-08 | Matriz de cumplimiento de requisitos (trazabilidad final) | Todos | 14 | Pendiente | No | |
| F6-09 | Análisis socio-tecnológico y recomendaciones | JF | 14 | Pendiente | No | |
| F6-10 | Versión candidata final y video demostrativo | Todos | 14 | Pendiente | No | |

## Fase 7 – Presentación final y defensa (Sem. 15)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F7-01 | Documento final (estructura de 17 puntos de la consigna 7.1) | Todos | 15 | Pendiente | No | |
| F7-02 | README completo (7.2) y repositorio etiquetado con versión final | KA | 15 | Pendiente | No | |
| F7-03 | Presentación académica | Todos | 15 | Pendiente | No | |
| F7-04 | Video demostrativo final | Todos | 15 | Pendiente | No | |
| F7-05 | Ensayo de demo en vivo entre sedes | Todos | 15 | Pendiente | No | |
| F7-06 | Preparar defensa individual (cada integrante domina todo el proyecto) | Todos | 15 | Pendiente | No | |

## Fase 8 – Cierre y entrega definitiva (Sem. 16)

| ID | Tarea / Entregable | Responsable | Semana | Estado | Revisado | Evidencia |
|---|---|---|---|---|---|---|
| F8-01 | Corrección de observaciones de la defensa + acta de correcciones | Todos | 16 | Pendiente | No | |
| F8-02 | Actualización final de documento y repositorio | KA | 16 | Pendiente | No | |
| F8-03 | Entrega de configuraciones, datos, scripts y manual de instalación/ejecución | KA + FM | 16 | Pendiente | No | |
| F8-04 | Retrospectiva: logros, limitaciones, lecciones aprendidas, trabajo futuro | Todos | 16 | Pendiente | No | |
| F8-05 | Autoevaluación y coevaluación individual | Cada integrante | 16 | Pendiente | No | |

---

## Condiciones mínimas de aprobación (revisar antes de cada entrega)

- [ ] App en cliente-servidor real (no solo en una misma máquina)
- [ ] Conectividad entre dos sedes con OSPF y VLAN
- [ ] Acceso a recursos protegidos con autenticación y autorización
- [ ] Contraseñas con hash seguro (no texto plano ni cifrado reversible)
- [ ] Datos, análisis estadístico e interpretación
- [ ] Repositorio, licencia, créditos y declaración de uso de IA
- [ ] Cada integrante demuestra conocimiento y contribución en la defensa

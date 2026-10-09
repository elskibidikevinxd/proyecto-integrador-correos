# Guion de apoyo para el video de fase 1

**Duración aproximada:** tres minutos, con participación de los tres integrantes.  
**Proyecto:** correos internos entre dos sedes.  
**Estado del video:** en elaboración por el equipo.

Este guion fue preparado con apoyo de IA y ajustado a los acuerdos de organización del equipo. Sirve de apoyo para la grabación.

## Jose Martin Fuel: Líder de Investigación Cuantitativa y Análisis Sociotecnológico

Hola, somos Jose Martin Fuel, Kevin Almache y Felipe Montenegro. Presentamos la Fase 1 de nuestro proyecto integrador: un sistema de correos internos entre dos sedes. El caso plantea una empresa de soluciones tecnológicas que abrió una segunda sede y necesita mantener la comunicación entre sus colaboradores, autenticar a sus usuarios y proteger la información. Elegimos la gestión de correos internos porque permite intercambiar mensajes institucionales con un alcance claro, incluyendo bandeja de entrada, enviados, lectura y eliminación de mensajes entre usuarios registrados, sin depender de un servidor de correo externo. En las siguientes fases integraremos la aplicación en Go, la autenticación con FastAPI y la infraestructura de red establecida en la consigna

## Kevin Almache: Administrador de Redes e Infraestructura

A nivel técnico, la solución integra una aplicación cliente-servidor en Go, un microservicio de autenticación con FastAPI y una infraestructura de red robusta. Interconectaremos ambas sedes mediante routers OpenWrt sobre una red Wi-Fi compartida usando enrutamiento dinámico OSPFv2, segmentación por VLANs con direccionamiento VLSM desde el bloque 10.10.0.0/16, enlaces troncales 802.1Q, Router-on-a-Stick y alta disponibilidad en capa dos con EtherChannel y RSTP en nuestros switches Cisco. Todo esto protegido con cifrado y reglas de firewall.

## Felipe Montenegro: Desarrollador de Software y Seguridad

Para llevar a cabo este reto, el equipo cuenta con una planificación estructurada que incluye validación estadística y análisis sociotecnológico sobre privacidad y ética. Nuestros roles fijos quedan distribuidos de la siguiente manera: quien les habla, Kevin Almache, asume Redes e Infraestructura; Felipe Montenegro el desarrollo de Software y Seguridad, Martín Fuel, lidera la Investigación y el Análisis Sociotecnológico

# Tabla de direccionamiento de VLAN futuras

Todas las subredes pertenecen al bloque `10.10.0.0/16`. Son reservas para la fase de segmentación; todavía no están implementadas en el prototipo inicial. Las direcciones usables incluyen la dirección que se propone como gateway.

| Sede | VLAN | Propósito | Hosts requeridos / capacidad | Red / prefijo | Máscara | Rango usable | Broadcast | Gateway propuesto | Asignación | Estado |
|---|---:|---|---|---|---|---|---|---|---|---|
| Site-A | 10 | Usuarios | 50 requeridos; /26 ofrece 62 usables (hasta 61 clientes + gateway) | `10.10.100.0/26` | `255.255.255.192` | `10.10.100.1–10.10.100.62` | `10.10.100.63` | `10.10.100.1` | DHCP | Reservada; pendiente |
| Site-B | 10 | Usuarios | 50 requeridos; /26 ofrece 62 usables (hasta 61 clientes + gateway) | `10.10.100.64/26` | `255.255.255.192` | `10.10.100.65–10.10.100.126` | `10.10.100.127` | `10.10.100.65` | DHCP | Reservada; pendiente |
| Site-A | 20 | Servidores | 20 planificados; /27 ofrece 30 usables (hasta 29 equipos + gateway) | `10.10.100.128/27` | `255.255.255.224` | `10.10.100.129–10.10.100.158` | `10.10.100.159` | `10.10.100.129` | Estática | Reservada; pendiente |
| Site-B | 20 | Servidores | 20 planificados; /27 ofrece 30 usables (hasta 29 equipos + gateway) | `10.10.100.160/27` | `255.255.255.224` | `10.10.100.161–10.10.100.190` | `10.10.100.191` | `10.10.100.161` | Estática | Reservada; pendiente |
| Site-A | 30 | Invitados | Demanda por confirmar; /27 ofrece 30 usables (hasta 29 clientes + gateway) | `10.10.100.192/27` | `255.255.255.224` | `10.10.100.193–10.10.100.222` | `10.10.100.223` | `10.10.100.193` | DHCP | Reservada; pendiente |
| Site-B | 30 | Invitados | Demanda por confirmar; /27 ofrece 30 usables (hasta 29 clientes + gateway) | `10.10.100.224/27` | `255.255.255.224` | `10.10.100.225–10.10.100.254` | `10.10.100.255` | `10.10.100.225` | DHCP | Reservada; pendiente |
| Site-A | 99 | Administración | Demanda por confirmar; /28 ofrece 14 usables (hasta 13 equipos + gateway) | `10.10.101.0/28` | `255.255.255.240` | `10.10.101.1–10.10.101.14` | `10.10.101.15` | `10.10.101.1` | Estática | Reservada; pendiente |
| Site-B | 99 | Administración | Demanda por confirmar; /28 ofrece 14 usables (hasta 13 equipos + gateway) | `10.10.101.16/28` | `255.255.255.240` | `10.10.101.17–10.10.101.30` | `10.10.101.31` | `10.10.101.17` | Estática | Reservada; pendiente |

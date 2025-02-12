#### Sistema Operativo por servicios

**Monousuarios:**
**Multiusuarios:**
**Monotareas:**
**Multitareas:**


#### Sistemas Operativos por proposito
Proposito general: Estan Diseñados para usarse por usuarios comunes y que realicen variedad de tareas
De servidor:
Embebidos:

#### Estructura Generia de un sistema operativo

**Capa de Hardware:** Capa mas baja del S.O se refiere a los componentes fisicos de computadora

**Nucle:** El corazon del S.O, es un intermediario entre el programa y el hardware 

**Espacio de Usuario:** Practicamente seria las interfaces graficas 

**Virualización**
Emular una maquina o algun sistema sin tener que tenerla instalada
- Alfitrion (host): Es el harware o sistema que ofrece la virtualización
- Huesped (guest): Sistema o aplicaciones que se ejecutan en el entorno virtualizado. 

**Emular**
Es para simular el harware completo mediante software, permitiendo ejecutar software.

**Virtualización asistida por hardware**
Técnicas que utilizan características del hardware para mejorar la eficiencia de la virtualización

**Paravirtualización**
EL Huesped ya sabe que esta virtualizado por ende coopera con el anfitrión pero no interactúa con el hardware. 

por ejemplo el XEN
- Xen .- Utilizado por los hipervisores 


## VPS(Virtual Private Server)
Maquina virtual que actua como servidor dedicado en el entorno, tiene recursos asignados de manera exclusiva.
- CPU.
- RAM.
- Almacenamiento. 
- Comparte hardware fisico con otros en el VPS en el mismo anfitrion.
 
**Independencia:** Cada VPS tiene su propio S.O
**Escalabilidad:** Los recursos pueden ajustarse según las necesidades del usuario.
**Aislamiento:** Los vps estan separados, lo que significa que el rendimiento o problema en uno no afectan a los demas.

**Usos de uso**
- Alojamiento web para sitios que requieren más recursos
- Desarrollo y pruebas de aplicaciones en entornos controlados
- Servidores de BD
- Implementación de redes virtuales (VPN)
### Admin System

Permite monitorear el servidor completo: jugadores, vehículos, NPCs y scripts. Además, poder ejercer diferentes acciones frente a ellos:

| **Acciones de jugador** | Descripción |
| :--- | :--- |
| **Movimiento** | Congelar, descongelar, traer, ir al usuario y llevar un usuario a otro |
| **Inventario** | Dar, establecer y retirar dinero, objetos y armas |
| **Permisos** | Otorgar, retirar y visualizar permisos |
| **Visualización** | Espectear un jugador, visualizar líneas y datos en vivo de los jugadores cercanos |
| **Movimiento de staff** | Noclip, modo invencible e invisibilidad |
| **Base de Datos** | Borrar todos los datos de un jugador |
| **Sistema de Reportes** | UI de chat para hablar con el staff, con notificaciones. UI para el staff con asignación de casos y chat. |
| **Capturas de Pantalla** | Mediante JS, se pueden obtener capturas instantáneas del juego del usuario. |
| **Otros** | Otorgar menú de vestimenta, banear, expulsar, avisos, mensajes privados de staff, establecer trabajo y banda. |
| **Servidor** | Programar reinicio de máquina, anuncios generales, cambio de clima y hora... |

<img width="1084" height="685" alt="image" src="https://github.com/user-attachments/assets/abd4bcc5-6393-4cdf-9c8f-02c03ce70abf" />



| **Acciones de vehículo** | Descripción |
| :--- | :--- |
| **Spawn** | Lista de modelos por clase según base de datos (o shared). Persistencia, maximización y elección de color y matrícula. |
| **Vehículos cercanos** | Lista de vehículos cercanos: modelo, matrícula, acción de obtener información y visualización de asientos. |
| **Información** | Listado de datos importantes obtenidos de la base de datos, como propietario, garaje y demás. |
| **Visualización de asientos** | Muestra los asientos del vehículo: NPC, jugador o vacío para cada uno. En caso de ser jugador, se le puede espectear. |

<img width="1083" height="690" alt="image" src="https://github.com/user-attachments/assets/bcddb1cc-2bc0-475c-bf1e-94e30fecccfa" />

<img width="1089" height="692" alt="image" src="https://github.com/user-attachments/assets/9e53a7cf-a00b-4c99-ab55-47e4b9063bb9" />

<img width="1087" height="689" alt="image" src="https://github.com/user-attachments/assets/eac16611-b162-4cd7-952a-b611d1fa0393" />


| **Acciones de scripts** | Descripción |
| :--- | :--- |
| **Visualización** | Lista completa de los scripts cargados por el servidor con su estado |
| **Start** | Si el paquete no está corriendo, lo corre según las aritméticas del servido y permisos. |
| **Stop** | Si el paquete está corriendo, lo apaga- |
| **Ensure** | Apaga y enciende el paquete, lo reinicia. |

Además, se puede filtrar por estado del script y buscar por nombre.

<img width="1082" height="686" alt="image" src="https://github.com/user-attachments/assets/9112dbcf-b7b4-45ca-80a8-96d7fb53f5cd" />


| **Acciones de NPC** | Descripción |
| :--- | :--- |
| **Prohibiciones** | Lista para bloquear modelos de ped |
| **Spawn** | Menú interactivo para crear peds específicas tanto estáticas, con animaciones o creando ambiente. |
| **Borrado** | Usando el pool (parte del mundo cargado en memoria) elimina todos los peds cargados. |

**Acciones de Servidor**: Programar reinicio de máquina, anuncios generales, cambio de clima y hora...

<img width="1097" height="696" alt="image" src="https://github.com/user-attachments/assets/f2e9751c-aab5-4e03-972c-97e5d503f94c" />


Todas las acciones están auditadas por logs de discord y capadas con permisos que se configuran. La configuración es en la parte servidor para evitar hackeos y exploits.
Además, trae consigo una auditoría extendida para staffs y evitar abusos de poder. Con capturas de pantalla cuando realizan una acción establecida.

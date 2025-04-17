🎯 AD 3: Diagramas UML
👩‍💻 Autora: Andreea Teodora Istrate
📁 Repositorio: https://github.com/AndreeaTI15/torneo-esports-uml

🔍 1. Análisis del problema y requisitos del sistema
👥 ¿Quiénes son los actores que interactúan con el sistema?
Los actores que interactúan con la aplicación son:

👨‍💼 Administradores

🧑‍🎮 Jugadores

🖥️ Sistema

🛠️ ¿Cuáles son las acciones de cada actor?
🖥️ Sistema
Se encarga de la gestión de jugadores y equipos ⚙️, siendo el núcleo de control para añadir, modificar o eliminar elementos.

👨‍💼 Administrador

Registra, modifica y elimina jugadores y equipos (una vez validados por el sistema).

Consulta la lista de equipos y jugadores 📋.

🧑‍🎮 Jugador

Consulta la lista de equipos y jugadores 🕵️.

Puede solicitar admisión en un equipo de su interés 📩.

🔗 ¿Cómo se relacionan las entidades del sistema entre sí?
🔄 Sistema ↔️ Administrador
Relación de dependencia. El Administrador utiliza los métodos del Sistema (como añadirJugador, eliminarJugador, etc.). Si el Sistema cambia, el Administrador también se ve afectado.

🤝 Administrador ↔️ Jugador
Relación de asociación simple. El Administrador gestiona a los Jugadores, pero no depende estructuralmente de ellos.

✅ Conclusión
📌 Mi forma de interpretar esta aplicación es entendiendo que:

🖥️ El actor Sistema es quien lleva la organización general de toda la aplicación.
Además, puede ejecutar todos los métodos que también están disponibles para el Administrador.

👨‍💼 El actor Administrador, desde mi punto de vista, es la persona encargada de revisar las solicitudes para agregar jugadores a equipos y crear nuevos equipos.
Todas sus acciones pasan primero por una comprobación del sistema antes de ejecutarse.

🧑‍🎮 El actor Jugador representa a la persona que puede consultar listas de equipos y jugadores 📋, ver las vacantes disponibles y, si lo desea, solicitar unirse a algún equipo.

💡 En cuanto a UML, creo que es una herramienta excelente para representar gráficamente un sistema. Nos ayuda a visualizar cómo se relacionan los elementos y a entender mejor su estructura interna 🔍📊.


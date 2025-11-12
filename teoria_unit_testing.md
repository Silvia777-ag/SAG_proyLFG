Git es un software de control de versiones gratis y de código abierto, sencilla y facil de usar que los desarrolladores instalan localmente en sus ordenadores personales.  Fue creado por Linus Torvalds en 2005.  Esto significa básicamente que Git es un rastreador de contenido. Así que Git puede ser utilizado para almacenar contenido en nuestro caso código. 

GitHub es un servicio de control de versiones basado en Git.  Se utiliza para almacenar el código (guarda el código fuente del proyecto en la nube) y controla los cambios (permite rastrear las modificaciones a lo largo del tiempo).

Git se utiliza a traves de una interfaz de linea de comandos basicos:
git config --global user.name "Tu nombre"
git config --global user.email "tu_email@example.com": Configurar tu nombre de usuario y correo electrónico para que Git pueda identificarte en cada cambio que realices.
git init: Inicializa un nuevo repositorio Git en un directorio existente.
git status: Muestra el estado actual de los archivos en el directorio, indicando los que han sido modificados, añadidos o no rastreados.
git add <nombre_del_archivo> o git add .: Agrega los cambios de uno o más archivos (o todos) al "staging area" (un área de preparación para el próximo "commit").
git commit -m "Mensaje descriptivo": Guarda los cambios preparados en el historial del proyecto con un mensaje que describe lo que se hizo.
git log: Muestra el historial de todos los "commits" realizados.
git push origin <nombre_rama>: Envía los "commits" locales a un repositorio remoto (como GitHub).
git clone <URL>: Clona un repositorio remoto existente a tu máquina local.

Git se usa para gestionar el historial de un proyecto, colaborar con otros y revertir a versiones anteriores.  Detallamos:
Historial completo: Git toma "instantáneas" (commits) del proyecto en diferentes momentos, lo que permite rastrear y revisar cada cambio realizado.
Reversión de cambios: Si introduces un error, puedes volver fácilmente a una versión anterior y funcional del proyecto.
Colaboración: Facilita que múltiples personas trabajen en el mismo proyecto simultáneamente, fusionando sus contribuciones sin entrar en conflicto.
Ramificación: Permite crear ramas separadas para trabajar en nuevas funcionalidades o experimentar sin afectar el código principal. Las ramas son fáciles de crear y fusionar.
Flexibilidad: Es un sistema distribuido, lo que significa que cada copia local del repositorio es un repositorio completo y funcional. Puedes trabajar incluso sin conexión a internet.

Git cuando usar.   En el desarrollo de software, pero también es útil para otros tipos de archivos.
Desarrollo de software: Es una herramienta estándar en la industria para gestionar el código fuente de cualquier proyecto, desde pequeños hasta grandes proyectos.
Cualquier proyecto con archivos que cambian: Aunque es más conocido en el ámbito de la programación, es útil para cualquier tipo de archivo que evolucione, como documentos, configuraciones, o incluso proyectos creativos.
Trabajo en equipo: Siempre que se trabaje en un proyecto de forma colaborativa, es esencial para coordinar los cambios y evitar conflictos.
Proyectos personales: Para tener un historial organizado de tu propio trabajo, poder volver atrás si cometes un error y para acostumbrarte a una práctica profesional estándar.
# Documentación del Juego en Unity
# 1. Información General
**Nombre del juego:**  

Ortografia App

**Género:** 

PC (Windows)Es la plataforma de desarrollo nativa por excelencia.Ideal para Juegos con mecánicas complejas, interfaces con mucho texto o elementos 3D muy detallados.

**Versión actual:**  

En este caso es la primera edicion de nuestro videojuego version 1.0 (primera edicion),Entorno Virtual 3D.Al ser la primera edición (Versión 1.0), el videojuego se centra en establecer las bases mecánicas y lógicas dentro de un entorno tridimensional, donde el estudiante interactúa de forma activa con los retos lingüísticos. Esta versión inicial prioriza la accesibilidad, la respuesta inmediata ante los errores ortográficos y una interfaz limpia que permite validar la efectividad del juego como herramienta de apoyo didáctico en el aula.

**Autores/Equipo de desarrollo:**  
Carlos de Jesus Aleman Calero (Programador)
Milagros Sevilla (Diseñador)

## 2. Concepto del Juego
**Historia / Narrativa breve:**  

Historia del videojuego: Año 2030. La humanidad vive en una ciudad dicción, una ciudad que funciona gracias a un núcleo de energía llamado “MATRIX”. Sin embargo, un virus informático conocido como "El Silenciador" ha infectado el sistema, borrando las tildes y confundiendo las letras dudosas de todos los archivos del mundo.

Sin ortografía, los puentes se caen y la gente ha dejado de entenderse.
un vehículo de alta tecnología. Tu objetivo es recorrer las autopistas de datos que conectan los sectores de la ciudad para recolectar las letras correctas y restaurar los mensajes antes de que el sistema colapse por completo.

**Objetivo principal del jugador:**  
El objetivo principal del jugador en OrtografiaApp 1.0 es restaurar el orden lingüístico del mundo virtual, superando retos ortográficos y de acentuación a lo largo del escenario 3D para desbloquear el portal de salida y consolidarse como un "Experto en Ortografía".

**Características clave:**  
 - Mecánicas principales  

 •	Interactividad 

Al entrar al juego el estudiante podrá moverse con las teclas direccionales para mover al personaje libremente de izquierda, derecha,atrás y adelante.

•	Retroalimentación

Proponemos a nuestros estudiantes la practica esencial de las reglas de acentuación en las palabras agudas y graves en el videojuego. 

•	Escenarios 3D

Nuestro videojuego tendrá una pantalla de menú visual en 3D y sus niveles con assets en 3D para mejorar la calidad del juego y el entretenimiento de los estudiantes.

•	Sistema de puntos 

El estudiante al finalizar cada nivel el juego mostrara una pantalla en la cual se mostrara un puntaje numerico según los aciertos que aplico en videojuego mostrando asi una estrella y si cometio errores esta pantalla no mostrara ni puntaje ni estrella.

•	Narración educativa 

Aprendamos todos de manera interactiva y entretenida con OrtografiaApp un videojuego didáctico memorativo y reconocer las reglas de acentuación para mejorar correctamente nuestra ortografía, mas que un juego es una herramienta eficaz para que los estudiantes tengan una manera de aprendizaje significativo y lograr desarrollar las habilidades ortográficas. 

 - Estilo visual  
 Las letras 3D (para tildes, selección de respuestas) deben tener un diseño claro, con bordes redondeados y un grosor sustancial, haciéndolas parecer objetos físicos que el jugador puede "tocar" e interactuar. AdemasUtilizar colores brillantes y saturados (azules, verdes, amarillos) para los entornos (suelos, paredes) para crear un ambiente alegre.

 - Música y sonido  

•	Música 

Ambiente motivacional de fondo

•	Narraciones 

Mensajes al empezar el videojuego o nivel .

•	Efectos 

Colisiones de letras con efectos de sonido.

## 3. Instalación y Uso

Buscar unity hub e instalar la, una vez instalada entramos y utilizamos nuestro correo.En Unity Hub, ve a la pestaña Installs (Instalaciones) en el menú de la izquierda.
Haz clic en el botón Install Editor (arriba a la derecha).
despues seleccionamos una version en este caso la version 3.16.1f LTS. creamos un projecto ya sea 2D O 3D para crear nuestro videojuego.

### Requisitos del sistema
- Mínimos:

Sistema Operativo: Android 8.0 (Oreo) o superior.

Procesador (CPU): Quad-Core a 1.4 GHz (Arquitectura de 64 bits recomendada).

Memoria RAM: 2 GB de RAM disponibles.

Gráficos: Soporte nativo para OpenGL ES 3.0.

Almacenamiento: 200 MB de espacio libre.

- Recomendados: 

Sistema Operativo: Android 11.0 o posterior.

Procesador (CPU): Octa-Core (Snapdragon serie 600 / MediaTek Helio G80 o superior).

Memoria RAM: 4 GB de RAM (o más).

Almacenamiento: 300 MB de espacio libre.


# 3. Configurar opciones iniciales.  

### Controles
- **Teclado/Mouse:**

Desplazamiento con las flechas o teclas direccionales (Izquierda,Derecha,Atras y Adelante).
De igual manera utilizamos mouse para interactuar con los botones del juego.

## 4. Elementos del Juego
Assets, Personajes , scripts ,botones, componentes , audios


### Personajes
- Protagonista: habilidades, atributos.  

Automovil llamado SCP10,Color negro oscuro, moderno y rápido.

- NPCs: roles, interacción.

Este personaje se encargara de transmitirle un mensaje de ayuda al carro (nuestro usuario).

- Enemigos: tipos, comportamiento. 

letras incorrectas que nos haran perder puntos.

### Escenarios
- Lista de niveles o mapas.
En nuestro videojuego estara programado para 3 escenarios , menu ,nivel 1 y nivel 2 .

- Descripción de ambientes.  

menu: fondo de una ciudad nocturna con 3 botones 1 de ayuda y los demas de nivel 1 y 2.

nivel 1: ciudad con muchas casas objetos carreteras y arboles. 

nivel 2: en este escenario le incluimos un NPCS ciudad mas ambientada y ruidosa que el nivel anterior.

### Objetos y Recursos
- Ítems recolectables.

Letras para completar una palabra en nuestro videojuego

- Power-ups. 

Aumentos de puntos o reduccion de puntos.

- Moneda del juego. 

puntajes elevados  

## 5. Parte Técnica

Unity 3D (Versión LTS). Seleccionado por su alta eficiencia en el manejo de gráficos tridimensionales, optimización de memoria para dispositivos móviles y versatilidad para compilar en PC y Android a partir de un único código base.C# (C Sharp). Utilizado para escribir toda la lógica de juego, sistemas de herencia, control de colisiones y manejo de datos pedagógicos.
### Arquitectura del Proyecto
PlayerController: Captura las señales del teclado o gamepad y las traduce en movimiento físico usando el motor de físicas de Unity.

Trigger Colliders (Colisionadores de Activación): Las letras 3D y las zonas de respuesta actúan como sensores. Al ser tocadas por el personaje, disparan el método OnTriggerEnter(), enviando los datos de la respuesta seleccionada hacia la capa lógica.

GameManager (Patrón Singleton): Coordina los estados globales del juego. Asegura que exista una sola instancia controlando el flujo y que persista durante todo el nivel.

EvaluatorManager: Recibe el identificador de la letra que el jugador tocó. Compara ese dato con la palabra activa almacenada en el ScriptableObject pedagógico. Si la respuesta es correcta o incorrecta, esta clase no cambia el texto en pantalla directamente; en su lugar, dispara un Evento de C# (Action / UnityEvent).

UIManager: Está "suscrito" a los eventos del EvaluatorManager. Cuando escucha el evento de "Respuesta Correcta", actualiza el marcador de texto y activa las animaciones de la interfaz.

EffectsManager: Reacciona a los mismos eventos para reproducir los efectos de sonido (FX) correspondientes y activar los sistemas de partículas (estrellas o destellos) en la posición del jugador.

### Instalación
1. Descargar el archivo ejecutable.

Obtener el paquete comprimido (.zip) o el instalador directo de la aplicación desde el enlace oficial del proyecto.

2. Instalar siguiendo el asistente.  

- Organización de carpetas en Unity.  

Assets, library, logs, packages, projectsetting, usersetting.

- Prefabs principales. 

Elementos pedagogicos, personaje jugador (carro), efectos.

- Scripts clave y su función.  

controladorcarro, logicaeducativa, controladorescenas.

### Integraciones
- Plugins utilizados.

TextMeshPro (TMP), Input System Package (Nuevo Sistema de Entradas).

- Servicios externos (ej. Firebase, Ads, Analytics).  

Unity Analytics / Unity Gaming Services (UGS), Firebase Authentication & Realtime Database (Propuesta para Escalar).

### Optimización
- Estrategias de rendimiento.  

Horneado de Iluminación (Baked Lighting): En lugar de calcular luces y sombras en tiempo real cuadro por cuadro (lo cual consume demasiada GPU), se utilizó el sistema de Lightmapping de Unity. Las luces del escenario 3D fueron "estarcidas" directamente sobre las texturas de los objetos. Esto reduce drásticamente el costo de procesamiento a cero para la iluminación estática.

Oclusión Ambiental y Culling (Occlusion Culling): Se configuró el motor para que Unity no procese ni renderice ningún objeto 3D, letra o plataforma que se encuentre fuera del campo de visión de la cámara del jugador o que esté oculta detrás de paredes grandes.

Uso Eficiente de Prefabs e Instanciación: Los elementos interactivos repetitivos (como las letras coleccionables y partículas de feedback) se gestionan mediante el uso de Prefabs. Para la siguiente fase, se contempla un sistema de Object Pooling para reutilizar los mismos objetos en memoria en lugar de destruirlos y crearlos continuamente.

Batching Estático y Dinámico: Se marcaron todos los elementos decorativos del escenario como "Static" en Unity, permitiendo que el motor agrupe sus polígonos en un solo paquete de dibujo (Draw Call), reduciendo la carga sobre el procesador.

- Configuración de calidad gráfica.  

Resolución de Texturas	Reducidas al 50% (MIP Maps activos)100% Nativo (Alta definición)
Anti-Aliasing (Suavizado)	Desactivado o FXAA (Bajo consumo)	SMAA o MSAA 4x
Sombras Dinámicas	Desactivadas (Solo sombras horneadas)	Activas en tiempo real (Media resolución)
Sistemas de Partículas	Ratio de emisión reducido a la mitad	Cantidad máxima de partículas y destellos
Tasa de Cuadros (FPS)	Limitada a 30/60 FPS estables	Desbloqueada (60+ FPS).

# 🐍 Java Play

## 🎮 Características

### 🎯 Jugabilidad
- **Movimiento fluido** de la serpiente con controles por teclado
- **Sistema de crecimiento** al comer manzanas
- **Detección de colisiones** con bordes y propio cuerpo
- **Dificultad progresiva** - velocidad aumenta con el puntaje
- **Pantalla de Game Over** con mensajes aleatorios

### 🏆 Sistema de Puntuaciones
- **Leaderboard top 10** con persistencia en archivo
- **Registro de nombres** cuando superas records
- **Puntuación mínima** requerida para entrar al ranking
- **Almacenamiento permanente** de scores

### 🎨 Interfaz de Usuario
- **Tres pantallas principales**:
  - 🏠 Lobby con menú navegable
  - 🎮 Pantalla de juego
  - 📊 Leaderboard de puntuaciones
- **Diseño visual limpio** con colores contrastantes
- **Tipografía personalizada** para mejor legibilidad
- **Navegación intuitiva** entre pantallas

## 📋 Requisitos del Sistema

- **Java JDK 8** o superior
- **Sistema operativo**: Windows, macOS o Linux
- **Memoria RAM**: Mínimo 512MB recomendado
- **Resolución de pantalla**: 800x600 mínimo recomendado

## 🚀 Instalación y Ejecución

### Método 1: Ejecución directa
```bash
# Compilar todos los archivos
javac *.java

# Ejecutar el juego
java SnakeGame
```

### Método 2: Usando un IDE
1. Abre el proyecto en IntelliJ IDEA, Eclipse o VS Code
2. Asegúrate de tener el JDK configurado
3. Ejecuta la clase `SnakeGame.java`

## 🎯 Controles del Juego

### En el Lobby (Menú Principal)
- **Flechas ↑/↓** - Navegar entre opciones
- **ENTER** - Seleccionar opción
- **ESC** - Salir del juego

### Durante el Juego
- **Flechas ↑ ↓ ← →** - Mover la serpiente
- **F2** - Reiniciar juego (en pantalla de Game Over)
- **ESC** - Volver al menú principal

### En Leaderboard
- **ESC** - Volver al menú principal


### Clases Principales

| Clase | Responsabilidad |
|-------|----------------|
| `SnakeGame` | Inicialización de la aplicación |
| `SnakeFrame` | Gestión de ventanas y navegación |
| `LobbyPanel` | Interfaz del menú principal |
| `GamePanel` | Lógica del juego y renderizado |
| `LeaderboardPanel` | Visualización de puntuaciones |
| `Score` | Modelo de datos para puntuaciones 

## 🔧 Personalización

### Modificar Tamaño de Pantalla
Edita las constantes en cada panel:
```java
public static final int SCREEN_WIDTH = 800;
public static final int SCREEN_HEIGHT = 600;
```

### Cambiar Velocidad del Juego
En `GamePanel.java`:
```java
public static final int DELAY = 100; // Milisegundos entre actualizaciones
```

## 🔄 Versiones Futuras

### Mejoras Planeadas
- [ ] Sonidos y efectos de audio
- [ ] Diferentes tipos de frutas/poderes
- [ ] Múltiples niveles de dificultad
- [ ] Temas visuales intercambiables
- [ ] Modo dos jugadores
- [ ] Gráficos vectoriales mejorados


## 📄 Licencia

Este proyecto es con fines educativos. Libre para uso y modificación.

## 🤝 Contribuir

1. Haz fork del proyecto
2. Crea una rama para tu feature
3. Realiza tus cambios
4. Envía un pull request



**¡Disfruta del juego!** 🎮

*"Un clásico reinventado para la era moderna"*

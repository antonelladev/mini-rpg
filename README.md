# 🗡️ Dungeon Crawler: C++ Text-Based RPG

¡Bienvenido a **Dungeon Crawler**, un mini-juego de rol (RPG) basado en texto y ejecutado directamente desde la consola! Este proyecto fue desarrollado en C++ utilizando conceptos sólidos de Programación Orientada a Objetos (POO), herencia y gestión limpia de memoria.

El objetivo es simple: adéntrate en la mazmorra, derrota a todos los enemigos que puedas, gestiona tus pociones de vida y descubre cuántas salas eres capaz de limpiar antes de caer en combate.

---

## 🚀 Características del Proyecto

*   **Programación Orientada a Objetos (POO):** Uso estricto de clases, encapsulamiento y polimorfismo mediante una clase base (`Entidad`) y clases derivadas (`Jugador`, `Enemigo`).
*   **Gestión Dinámica de Memoria:** Implementación de punteros con inicialización segura y liberación de memoria mediante destructores implícitos para evitar *memory leaks*.
*   **Lógica Procedural Aleatoria:** Los enemigos (Goblins, Esqueletos, Orcos), los encuentros de las salas y las tasas de crítico en los daños se generan de forma aleatoria en cada partida.
*   **Sin Dependencias Externas:** El código es completamente portable y estándar (C++11 o superior), por lo que corre en cualquier sistema operativo sin instalar librerías adicionales.

---

## 🛠️ Requisitos previos

Para compilar y jugar, solo necesitas un compilador de C++ (como `g++`) instalado en tu sistema.

*   **Linux (Ubuntu/Debian):** `sudo apt install build-essential`
*   **macOS:** Xcode Command Line Tools (`xcode-select --install`)
*   **Windows:** MinGW, MSVC o WSL (Windows Subsystem for Linux).

---

## 💻 Compilación y Ejecución

Sigan estos pasos para poder jugar 

1. **Clonar el repositorio:**
```bash
   git clone [https://github.com/TU_USUARIO/DungeonCrawler.git](https://github.com/TU_USUARIO/DungeonCrawler.git)
   cd DungeonCrawler

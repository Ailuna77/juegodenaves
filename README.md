# Actividad-8-POO-Juego-de-Naves
## Proyecto Integrador Anual - LPR 2026

* **Institución:** E.E.S.T. N.º 1 "Eduardo Ader" - Vicente López
* **Curso:** 5° Año 3° División (Grupos A-B)
* **Materia:** Laboratorio de Programación (LPR)
* **Profesor:** Prof. York Mansilla
* **Actividad:** Actividad 8: Programación Orientada a Objetos (POO) en C++ - Juego de Naves en Consola

---

## Descripción del Proyecto
Este desarrollo implementa un simulador de combate espacial interactivo en consola utilizando el paradigma de **Programación Orientada a Objetos (POO)** en C++. El software migra los conceptos estructurados previos de agrupamiento de datos (`struct`) hacia la encapsulación mediante clases (`class`), garantizando el resguardo de estados internos sensibles (atributos privados) y exponiendo una interfaz controlada de acciones (métodos públicos) para gestionar la física de movimiento, colisiones dinámicas y el ciclo de juego (Game Loop) en tiempo real.

## Alumna (Desarrollo Individual)
* **Mojica, Sofia**  
  * *Rol Técnico:* Ingeniería de software, diseño de diagramas de objetos, maquetado de manuales, implementación de lógica de encapsulamiento y control de versiones en Git.

---

## Requisitos e Instalación
1. Compilador de bajo nivel **MinGW (g++)** mapeado globalmente en las Variables de Entorno del sistema operativo (**PATH**).
2. Entorno de desarrollo **Visual Studio Code** con la extensión oficial de C/C++ de Microsoft activa.

###  Clonar este repositorio:
```bash
git clone https://github.com/Ailuna77/juegodenaves.git
```

### Posicionarse en el directorio raíz correspondiente a la práctica:
```bash
cd juegodenaves
```

---

## Compilación y Ejecución (PowerShell)
Abra una terminal interna en VS Code y ejecute de forma secuencial los comandos de enlace:

### 1. Fase de Compilación
Genera el binario ejecutable personalizado dentro de la carpeta de fuentes locales:
```powershell
g++ src/main.cpp -o src/juegodenaves.exe
```

### 2. Fase de Lanzamiento
Inicializa el motor del videojuego espacial en el entorno de Windows:
```powershell
.\src\juegodenaves.exe
```

### Controles del Juego
* **W**: Mover la nave hacia arriba.
* **S**: Mover la nave hacia abajo.
* **A**: Mover la nave hacia la izquierda.
* **D**: Mover la nave hacia la derecha.
* **ESPACIO**: Disparar ráfaga de proyectiles láser.

---

## Estructura Obligatoria del Repositorio

```text
juegodenaves/
├── .gitignore                      <-- Reglas de exclusión para binarios locales (.exe, .vscode/)
├── LICENSE                         <-- Licencia MIT escolar de uso académico
├── README.md                       <-- Portada técnica de la actividad (Este archivo)
├── docs/                           <-- Carpeta de documentación formal
│   ├── InformeEEST1_LPR2026_ACT08_MojicaSofia_v1.0.0.pdf <-- ENTREGABLE EN PDF (APA v7)
│   ├── CHANGELOG.md                <-- Historial de versiones del software
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf <-- Manual Técnico estructurado (PDF)
│       ├── manual_programador_v1.0.0.md  <-- Manual Técnico estructurado (Markdown)
│       ├── manual_usuario_v1.0.0.pdf     <-- Guía de uso y requerimientos (PDF)
│       └── manual_usuario_v1.0.0.md      <-- Guía de uso y requerimientos (Markdown)
├── src/                            <-- Carpeta para los códigos fuente del proyecto
│   └── main.cpp                    <-- Programa principal del motor de juego en C++
└── capturas/                       <-- Evidencias de ejecución local
    └── combate_consola.png         <-- Captura de la terminal con el nombre de la piloto
```

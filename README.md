# HOLAMUNDO

Primer programa de consola en C++ — **Actividad 2: El Taller del Programador**.

Laboratorio de Programación (LPR), 5° año, 3° grupos A-B.
E.E.S.T. N° 1 "Eduardo Ader" — Vicente López.

## Qué es

Es un proyecto de consola que imprime un saludo por pantalla. Sirve como
primer contacto con el flujo completo de trabajo en C++: escribir el código,
compilarlo con `g++` y ejecutarlo desde la terminal.

## Requisitos

- **Compilador:** GCC (TDM-GCC / MinGW). En esta máquina está en
  `C:\TDM-GCC-64\bin\g++.exe`, versión 10.3.0.
- **Editor:** Visual Studio Code con las extensiones:
  - `C/C++` (Microsoft)
  - `C/C++ Extension Pack`
  - `Code Runner` (opcional)

## Cómo compilar y ejecutar

Abrí la terminal de VS Code (`Ctrl + Ñ`) parada en la raíz de `holamundo`
y corré:

```powershell
# Compilar
g++ src/main.cpp -o src/holamundo.exe

# Ejecutar
.\src\holamundo.exe
```

Salida esperada:

```
=====================================================
  Hola Mundo! Bienvenido al Taller de LPR 2026.
  Estudiante: Malek Cheheid
=====================================================
```

## Estructura

```
holamundo/
├── .gitignore              # ignora carpetas de configuración y compilados
├── README.md               # este archivo
├── LICENSE                 # licencia MIT
├── src/
│   └── main.cpp            # primer código de prueba en C++
├── docs/
│   └── InformeProyectoHOLAMUNDO.pdf   # entregable, formato APA v7
└── capturas/
    ├── gpp_version.png     # consola verificando el compilador
    ├── extensiones_vscode.png
    └── ejecucion_hola_mundo.png
```

## Autor

Malek Cheheid — 5° año, 3° A-B.

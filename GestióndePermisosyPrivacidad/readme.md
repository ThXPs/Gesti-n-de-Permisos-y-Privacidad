# Programa de Control de Información

Este programa en C++ solicita al usuario permiso para mostrar información sensible. Dependiendo de la respuesta del usuario, la información será mostrada o denegada.

## Descripción

El programa utiliza entrada y salida estándar para interactuar con el usuario y una simple estructura condicional para controlar el acceso a la información. Es un ejemplo básico que ilustra cómo manejar entradas del usuario y tomar decisiones basadas en ellas.

## Características

- Solicita permiso al usuario para mostrar información.
- Responde de manera diferente según la entrada del usuario:
  - Muestra la información si el usuario responde `s` o `S`.
  - No muestra la información en cualquier otro caso.

## Requisitos

- Compilador C++ compatible con el estándar C++11 o superior.

## Ejecución

    Para compilar el archivo en C, usa el siguiente comando en la terminal:
    gcc GestióndePermisosyPrivacidad.cpp -o GestióndePermisosyPrivacidad
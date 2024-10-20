# Testing de Software en Sistemas Embebidos - Trabajo Práctico Número 2

Proyecto basado en el TP2 de la materia donde se desarrollo un test para una biblioteca de un controlador de leds.

## Objetivo

Este repositorio contiene la solución para el trabajo práctico número 2, que consiste en desarrollar un controlador de LEDs utilizando la técnica de Desarrollo Guiado por Pruebas o del inglés TDD (Test-Driven Development).

## Tecnologías utilizadas

- Lenguaje de programación: C
- Framework de pruebas: Unity/Ceedling

## Estructura del Repositorio

- `build/` - Contiene los archivos autogenerados por la herramienta ceedling
- `src/` - Contiene el código fuente del controlador de LEDs.
- `tests/` - Contiene las pruebas unitarias desarrolladas con la técnica de TDD.

## Uso del repositorio

1. Clonar el repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
```

2. Entrar al directorio del repositorio clonado

```bash
cd <NOMBRE_DEL_REPOSITORIO>
```

3. Instalar Ceedling (si no está instalado)

```bash
gem install ceedling
```

4. Ejecutar todas las pruebas unitarias con Ceedling

```bash
ceedling test:all
```

## Autor

Ing. Iván Podoroska

## License

Este proyecto está bajo los términos de la [licencia MIT](https://spdx.org/licenses/MIT.html).

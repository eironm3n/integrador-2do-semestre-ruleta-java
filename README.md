# Ruleta del Casino — Proyecto Integrador (Java)

> **Continuación individual de un proyecto académico** · Base: proyecto integrador del 2.º semestre
> de la Tecnicatura Universitaria en Programación — UTN, Facultad Regional San Rafael (2024),
> realizado con el equipo **Código Enigma**. Ver [Origen del proyecto](#origen-del-proyecto).

Juego de escritorio que simula una ruleta de casino, con ventanas de diálogo. El jugador arranca con un saldo
de fichas y puede apostar a números específicos (pago 35:1), a color (rojo/negro,
1:1) o de forma combinada. El programa valida las apuestas, genera el número
ganador de forma aleatoria y actualiza el saldo ronda a ronda; la partida termina
si el jugador se queda sin fichas.

## Tecnologías

- **Java SE** — interfaz con ventanas de diálogo de Swing (`JOptionPane`), validación de apuestas y número ganador con `Random`
- Estructura de proyecto **NetBeans / Ant** (`build.xml`, `manifest.mf`)

## Ejecución

```bash
javac Proyecto_Ruleta/src/proyecto_ruleta/Proyecto_Ruleta.java
java -cp Proyecto_Ruleta/src proyecto_ruleta.Proyecto_Ruleta
```

## Origen del proyecto

Este repositorio toma como **base el proyecto integrador de la Tecnicatura
Universitaria en Programación** (UTN, Facultad Regional San Rafael). El proyecto
se comenzó en **octubre de 2024** y se realizó durante el 2.º semestre con el
equipo **Código Enigma**, hasta su entrega final en **noviembre de 2024**.

El trabajo se organizó con **rotación de roles** entre los integrantes
(desarrollo, gestión de tareas y seguimiento de avances semanales), y la
publicación en el repositorio de la cátedra la centralizaban algunos integrantes
por turno.

**Integrantes:** Aguirre Cerullo Rocío, Colombo Agustín, Dicalbo Juan Cruz,
Domínguez Eliana, Elías Francisco, Ramos Dilan, Rojas Arón.

### Continuación individual

A partir de esa base, **Arón Rojas**, integrante del equipo, mantiene el proyecto
de forma individual en este repositorio, con documentación propia (este README)
y la descripción técnica corregida: la interfaz usa ventanas de diálogo de Swing.

### Repositorio original de la cátedra

<https://github.com/PowerSystem2024/CodigoEnigma-ProyectoIntegradorJava>

El README original del equipo se conserva como [`README-original.md`](./README-original.md).

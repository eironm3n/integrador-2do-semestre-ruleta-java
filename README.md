# Ruleta del Casino — Proyecto Integrador (Java)

> **Trabajo académico** · Tecnicatura Universitaria en Programación — UTN, Facultad Regional San Rafael
> **Entrega final del 2.º semestre** (2024) · Equipo **Código Enigma**

Juego de consola que simula una ruleta de casino. El jugador arranca con un saldo
de fichas y puede apostar a números específicos (pago 35:1), a color (rojo/negro,
1:1) o de forma combinada. El programa valida las apuestas, genera el número
ganador de forma aleatoria y actualiza el saldo ronda a ronda; la partida termina
si el jugador se queda sin fichas.

## Tecnologías

- **Java SE** — aplicación de consola (`Scanner` para E/S, validación de apuestas, RNG)
- Estructura de proyecto **NetBeans / Ant** (`build.xml`, `manifest.mf`)

## Ejecución

```bash
javac Proyecto_Ruleta/src/proyecto_ruleta/Proyecto_Ruleta.java
java -cp Proyecto_Ruleta/src proyecto_ruleta.Proyecto_Ruleta
```

## Contexto y autoría

Proyecto grupal desarrollado por el equipo **Código Enigma** como entrega final
del 2.º semestre de la carrera. El trabajo se organizó con **rotación de roles**
entre los integrantes: desarrollo, gestión de tareas y seguimiento de avances
semanales. La publicación en el repositorio de la cátedra la centralizaban
algunos integrantes por turno.

**Integrantes:** Aguirre Cerullo Rocío, Colombo Agustín, Dicalbo Juan Cruz,
Domínguez Eliana, Elías Francisco, Ramos Dilan, Rojas Arón.

Repositorio original de la cátedra:
<https://github.com/PowerSystem2024/CodigoEnigma-ProyectoIntegradorJava>

El README original del equipo se conserva como [`README-original.md`](./README-original.md).

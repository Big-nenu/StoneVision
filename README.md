# StoneVision (SV)

**Agente autónomo experimental · Percepción · Memoria · Aprendizaje · Iniciativa**

> **Estado:** fase de concepto y diseño. Las funciones descritas aquí son objetivos de investigación, no capacidades implementadas.

## ¿Qué es StoneVision?

StoneVision es un proyecto experimental para explorar el desarrollo de un agente de inteligencia artificial capaz de **observar su entorno, construir una memoria propia, aprender de sus experiencias y desarrollar iniciativas**.

La intención no es crear otro chatbot ni un asistente que se limite a esperar instrucciones. La pregunta que guía el proyecto es:

**¿Cómo construir un agente que aprenda a desenvolverse en su entorno a partir de lo que observa y experimenta?**

La inspiración conceptual incluye a Vision (Marvel), Samantha (*Her*) y Rocky (*Project Hail Mary*): distintas maneras de imaginar entidades con las que es posible convivir, colaborar y aprender. Son referencias creativas, **no** una afirmación de que StoneVision vaya a tener conciencia o capacidades equivalentes.

## Objetivos de investigación

- **Percepción:** explorar cómo un agente puede interpretar información de su entorno digital mediante observaciones de pantalla, ventanas y otros datos autorizados.
- **Memoria propia:** conservar experiencias, relacionarlas y recuperarlas para dar continuidad a su aprendizaje.
- **Aprendizaje a partir de experiencias:** experimentar con mecanismos que permitan adaptar su comportamiento a partir de observaciones, resultados y retroalimentación.
- **Iniciativa:** investigar cuándo y cómo podría proponer una acción o hacer una pregunta sin esperar siempre una orden.
- **Interacción con el entorno:** estudiar formas de interactuar con el escritorio como un personaje o acompañante digital.
- **Expansión física futura:** explorar, más adelante, cámaras, sensores, microcontroladores y actuadores como interfaces con el mundo físico.

Estos puntos representan **líneas de exploración**, no un listado de funciones disponibles.

## ¿En qué se diferencia de StoneBot?

| Proyecto | Propósito |
| --- | --- |
| **[StoneWave (SW)](https://github.com/Big-nenu/StoneWave)** | Motor de memoria semántica y relacional reutilizable. |
| **[StoneBot (SB)](https://github.com/Big-nenu/StoneBot)** | Agente asistente personal enfocado en colaborar y ejecutar tareas solicitadas. |
| **StoneVision (SV)** | Agente autónomo experimental enfocado en percepción, experiencias, aprendizaje e iniciativa. |

**StoneBot ayuda a realizar tareas. StoneVision investiga cómo un agente podría aprender a desenvolverse por sí mismo.**

## Relación con StoneWave y StoneBot

Los proyectos son independientes, aunque pueden compartir componentes reutilizables.

- **StoneWave** puede servir como motor tecnológico de memoria.
- **StoneBot** utiliza ese motor para asistir al usuario; su objetivo es diferente al de StoneVision.
- **StoneVision** deberá contar con **recuerdos propios**, separados de la memoria personal del asistente.

Se contempla **evaluar la reutilización o migración de la base de memoria que se creó originalmente para StoneBot** como punto de partida para StoneVision. Esa decisión requiere revisar primero su contenido, su compatibilidad y las implicaciones de privacidad. **La migración no se ha realizado.**

## Principios de diseño

1. **Identidad independiente:** StoneVision no debe convertirse accidentalmente en otra interfaz de StoneBot.
2. **Aprender no significa solo acumular datos:** registrar experiencias debe tener una utilidad observable en decisiones futuras.
3. **Separar observación, interpretación y acción:** una percepción o hipótesis no equivale automáticamente a una instrucción.
4. **Autonomía gradual y verificable:** experimentar primero en entornos controlados y evaluar el comportamiento antes de aumentar permisos.
5. **Control del usuario:** acceso a pantalla, archivos, aplicaciones, red y dispositivos físicos mediante permisos explícitos y límites configurables.
6. **Arquitectura modular:** reutilizar componentes existentes cuando sea útil, sin copiar todo StoneWave ni StoneBot.
7. **Sin promesas de conciencia:** se investiga comportamiento autónomo y aprendizaje adaptativo, no se presume conciencia artificial.

## Primeras etapas propuestas

- [ ] Definir un alcance mínimo para el primer prototipo.
- [ ] Diseñar una representación visual que pueda interactuar con el escritorio.
- [ ] Crear un ciclo básico de **observar → interpretar → recordar → decidir si actuar**.
- [ ] Elegir una fuente inicial de percepción y establecer sus permisos.
- [ ] Diseñar y probar una memoria independiente.
- [ ] Registrar experiencias y evaluar si afectan respuestas o decisiones posteriores.
- [ ] Probar iniciativas simples y reversibles, con supervisión del usuario.
- [ ] Evaluar futuras conexiones con herramientas MCP y hardware.

> El orden y el alcance de estas etapas pueden cambiar conforme avancen los experimentos.

## Estado actual

**Planificación.** Este repositorio inicia con la definición del concepto, sus diferencias respecto de los demás proyectos y una ruta experimental inicial. Aún no hay una implementación funcional de StoneVision documentada aquí.

---

### Ecosistema NucleoStone

StoneVision forma parte de **[NucleoStone](https://github.com/NucleoStone)**, junto con StoneWave y StoneBot.

*Tres proyectos distintos. Un mismo núcleo.*

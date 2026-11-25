# CP2 – Requerimientos y Pruebas: Direfact, Fábrica de Derivadas (Juego de Cálculo)

**Universidad Estatal de Milagro · Facultad de Ciencias e Ingeniería · Carrera de Ingeniería de Software**
**Asignatura:** Introducción a la Ingeniería de Software

**Grupo:** grupo1

## Integrantes

- Anthony Ariel Álava Alarcón
- Michelle Anahi Ayovi Huacon
- Fernando Lenin Camba Jaramillo
- Adalberto Alexander Fuentes Bonilla
- Mia Brithany León Rivas
- José Antonio Mogrovejo Bravo

## Descripción del proyecto

Direfact, Fábrica de Derivadas es un videojuego educativo desarrollado en Roblox, pensado para que los estudiantes de primer semestre de Ingeniería de Software practiquen Cálculo de forma dinámica y colaborativa. Los jugadores se organizan en equipos de seis integrantes y recorren seis salas con cuatro niveles de dificultad: fácil, medio, difícil y extremo. En cada sala deben cumplir una misión y resolver ejercicios de Cálculo para avanzar hasta la sala de victoria. Si se equivocan dos veces, el equipo queda congelado un tiempo. El proyecto busca motivar la práctica, la competencia sana y la retroalimentación inmediata, y puede usarse también con gafas de realidad virtual.

- **Problema o necesidad:** los estudiantes de primer semestre practican Cálculo de forma poco dinámica, con poca participación y retroalimentación inmediata.
- **Objetivo del sistema:** reforzar el aprendizaje de Cálculo mediante práctica, competencia y trabajo en equipo en un videojuego educativo.
- **Usuarios principales:** estudiantes de primer semestre de Ingeniería de Software y el docente de Cálculo.

## Requisitos y casos de prueba

| ID | Tipo | Descripción del requisito | Caso de prueba propuesto | Resultado esperado |
| --- | --- | --- | --- | --- |
| RF-01 | Funcional | El sistema permitirá a cada integrante seleccionar el portal de su equipo en el lobby y, al ingresar, iniciar el contador regresivo de 25:00. | Entrar al portal de un color con "Presiona X / Clic / Gatillo VR" y observar el estado del juego. | El jugador queda asignado a su equipo y el contador inicia en 25:00. |
| RF-02 | Funcional | El sistema validará la respuesta marcada de cada ejercicio de Cálculo y habilitará la salida de la sala solo si es correcta y la misión está cumplida. | Cumplir la misión (apagar el fuego con extintores) y marcar la alternativa correcta; repetir sin cumplir la misión o con una opción incorrecta. | Con misión y respuesta correcta se habilita el paso a la siguiente sala; en los demás casos la salida sigue bloqueada. |
| RF-03 | Funcional | El sistema aplicará una penalización cuando el equipo agote sus dos oportunidades con respuestas incorrectas. | Marcar dos respuestas incorrectas seguidas en un ejercicio. | El equipo queda congelado 1 min 30 s, sin acceso a portales, y luego continúa. |
| RNF-01 | No funcional (usabilidad / compatibilidad) | El simulador deberá poder usarse con gafas de realidad virtual (Meta Quest 2). | Recorrer una sala con las gafas: moverse, leer carteles, pulsar una respuesta y cruzar un portal con el gatillo VR. | Las cuatro acciones se completan sin fallas. |
| RNF-02 | No funcional (rendimiento / fiabilidad) | El sistema validará cada respuesta en un máximo de 3 segundos y mantendrá el contador sincronizado en el equipo. | Marcar respuestas en varias salas, cronometrar la reacción y comparar el contador entre dos jugadores. | Cada validación responde en 3 s o menos y los contadores difieren en 1 s o menos. |

## Documentación

- [`CP2_Requerimientos_y_Pruebas.pdf`](CP2_Requerimientos_y_Pruebas.pdf): documento completo con el análisis de requisitos, la propuesta de pruebas y, al final, la evidencia de configuración de colaboradores.

> Los casos de prueba son propuestas teóricas; no se ejecutaron.
## Documentación

- [`CP2_Requerimientos_y_Pruebas.pdf`](CP2_Requerimientos_y_Pruebas.pdf): documento con el análisis de requisitos y la propuesta de pruebas.


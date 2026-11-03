# Repaso ATC

Web interactiva para repasar el sistema de clasificación ATC (anatómico-terapéutico-química), el nivel 1, el nivel 2 y algunos principios activos comunes.

## Contexto educativo

Esta actividad se engloba dentro del **CFGM Farmacia y Parafarmacia**, en el módulo **0101 - Dispensación de productos farmacéuticos**, y recoge algunos Criterios de evaluación (CE) incluidos en el **Resultado de aprendizaje (RA) 2** "Dispensa medicamentos relacionándolos con las aplicaciones terapéuticas y las condiciones de uso.", que se citan a continuación:

- **2.a)** Se han descrito las clasificaciones anatómico-terapéuticas de los medicamentos.
- **2.b)** Se han identificado los principios activos más representativos relacionándolos con las aplicaciones terapéuticas.
- **2.c)** Se han relacionado los grupos terapéuticos con lugar de acción, principales aplicaciones, condiciones de uso y efecto producido.

## Qué se puede repasar

| Bloque | Contenido |
|---|---|
| Organización del sistema ATC | Niveles del código, qué indica cada uno, cuántas letras o dígitos lleva, criterios de clasificación y desglose de códigos |
| Nivel 1 · Grupos anatómicos | Asociar cada letra con su sistema y cada sistema con su letra |
| Nivel 2 · Grupos terapéuticos | Para qué sirve cada grupo, a qué sistema pertenece y qué principios activos incluye (por sistema o todos juntos) |

Nunca se pregunta el número de código de un grupo terapéutico: solo la letra del sistema, el nombre del grupo, su utilidad y sus ejemplos.

## Cómo funciona

- El alumnado elige qué bloques y qué sistemas quiere repasar, el tipo de pregunta (test a/b/c/d, verdadero/falso o relacionar) y el número de preguntas por intento (10, 20 o 30).
- Cada intento selecciona preguntas al azar de un banco amplio y baraja tanto el orden como las opciones.
- Cada respuesta se corrige al momento con una breve explicación.
- En las preguntas de nivel 2 el sistema se mantiene oculto y se puede consultar con el botón **Pista**.
- Al terminar se muestra la nota por bloque, las preguntas falladas y la opción de repetir solo los fallos.
- En la pantalla de inicio, **Tus preguntas más falladas** muestra las preguntas que más le cuestan a cada alumno o alumna y permite practicarlas. Esta estadística se guarda solo en su navegador: no se envía a ningún sitio y se pierde si cambia de ordenador o borra el historial.
- La pestaña **Tablas de repaso** reúne todo el contenido en forma de tablas.
- En la cabecera, **Ver relación curricular** muestra el ciclo, el módulo, el RA y los CE que trabaja la actividad, y el selector **Auto / Claro / Oscuro** cambia el tema de color (Auto sigue el del navegador).

## Uso

La web es un único archivo `index.html`, sin dependencias que instalar. Se puede abrir directamente en el navegador o publicar con GitHub Pages:

1. Sube `index.html`, `README.md` y `LICENSE` a un repositorio público.
2. En **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.
3. La web quedará disponible en `https://<usuario>.github.io/<repositorio>/`.

## Modificar o ampliar el contenido

Todo el contenido está en el bloque `SYS`, al principio del `<script>` de `index.html`. Cada grupo terapéutico tiene un nombre, una utilidad y una lista de ejemplos de principios activos. Al añadir o cambiar una entrada, las preguntas se generan automáticamente a partir de ella.

## Licencia

“Web interactiva para repasar el sistema ATC, nivel 1, nivel 2 y algunos principios activos comunes” por Pablo A. Sendra Lleó (2026), disponible bajo licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Este material fue desarrollado con la asistencia del modelo de inteligencia artificial [Claude (Anthropic)](https://claude.ai/). 

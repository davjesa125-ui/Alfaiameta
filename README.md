# ALFA · ¿La IA se descontrola?

Agente web local que responde 10 preguntas sobre el documental de Netflix "La IA se descontrola" (27 min).

## Uso
1. Abrí `index.html` con doble clic en Chrome (para que funcione el micrófono).
2. Tocá un número del 1 al 10, escribí una pregunta o activá "Hablar con Alfa" (conversación automática).

## Editar respuestas
En `index.html`, buscá el arreglo `ANSWERS`. Las respuestas con `[COMPLETAR]` están cortadas: reemplazalas por el texto del documental.

## GitHub Pages
Subí `index.html` al repo, andá a Settings > Pages y elegí la rama `main` (carpeta raíz).

## Fuentes de la información del caso
- Infobae (27/08/2026) y (01/10/2026), informe de OpenAI, METR y Redwood Research
- El Tribuno (10/10/2026), Quever (13/10/2026), Malwarebytes (28/08/2026), AI Magazine

Los datos están en los arreglos `ANSWERS` (10 preguntas base) y `FACTS` (preguntas libres) dentro de `index.html`.
Nota: el documental habla de "unos 2 días"; el análisis de Hugging Face reconstruye actividad del 9 al 13 de julio.

# 🗺️ Las Marcas de Bosquecuervo — Bóveda de Campaña (Nimble TTRPG)

Bienvenido/a a la bóveda de **_Las Marcas de Bosquecuervo_**, una campaña para el sistema **Nimble**, un TTRPG narrativo centrado en facilitar un combate fluido y rapido.

Esta bóveda sirve como **centro de control** para el/la Director/a de Juego (DJ) y los jugadores, con herramientas para organizar personajes, sesiones, mecánicas y el mundo de juego.

---

## 🧭 Estructura General

```
📂 Las-Marcas-de-Bosquecuervo/
├── @ 🗂️ /                        → Carpeta para elementos misceláneos
│   ├── @Imágenes/               → Recursos visuales (mapas, retratos, referencias)
│   └── @Plantillas/             → Plantillas de notas, personajes, lugares, escenas, etc.
├── 📜 Lore/                      → Historia, cronología, reinos, dioses y culturas
├── 🧙‍♂️ Personajes/              → Fichas de personajes (PJ y PNJ)
│   ├── PJs/                      → Personajes jugadores (PJs)
│   └── PNJs/                     → Personajes no jugadores (PNJs)
├── 🏰 Lugares/                   → Ciudades, regiones, mazmorras y lugares clave
├── 🎲 Reglas-y-Mecánicas/        → Reglas, movimientos y “homebrew” del sistema Nimble
├── 🪶 Sesiones/                  → Resúmenes, notas y registros de sesiones jugadas
├── 🧾 Objetos-y-Reliquias/       → Objetos mágicos, artefactos, tesoros y equipo
├── 🧭 Facciones/                 → Gremios, clanes, reinos, órdenes, cultos
├── 📖 README.md                  → El documento que estás leyendo ahora
└── 🌐 Mapa del Mundo.md          → Mapa de contenido principal con enlaces al mundo
```

> 💡 Cada carpeta puede tiene su propio **índice (`_index.md`)** para navegar fácilmente entre notas.

---
- [[Lore]]
- [[Lugares]]
- [[Objetos y Reliquias]]
- [[Personajes]]
	- [[PJs]]
	- [[PNJs]]
- [[Reglas y mecanicas]]
## 🎮 Convenciones de Notas

**Metadatos YAML recomendados:**
```YAML
---
title: "LOC - Bosquecuervo"
type: "Location"
tags: [bosque, frontera, misterioso]
status: "explorado"
connected_to: ["Ruinas de Thalmar", "Torre de Ceniza", "`S01 - Inicio`"]
---
``` 

**Nombres sugeridos por tipo:**

- Personajes → `PJ - Nombre`, `PNJ - Nombre`

- Sesiones → `SXX - Título`

- Lugares → `LOC - Nombre`

- Objetos → `ITEM - Nombre`

- Facciones → `FAC - Nombre`

**Etiquetas útiles (`#tag`):**
- Etiquetas de tipo de nota
	- `#pj`, `#pnj`, `#ubicacion`, `#sesion`, `#misterio`, `#artefacto`, `#enemigo`, `#evento`

---

## 🧰 Plugins recomendados para Obsidian (TTRPG)

|Plugin|Uso principal|
|---|---|
|**Dataview**|Listas automáticas de personajes, sesiones o lugares|
|**Templater**|Crear fichas y registros de sesión con un clic|
|**Canvas**|Mapas de relaciones entre personajes o facciones|
|**Fantasy Calendar / Periodic Notes**|Seguir cronología del mundo|
|**Map View / Excalidraw**|Mapas interactivos del mundo o regiones|
|**QuickAdd**|Crear nuevas sesiones o PNJ con comandos rápidos|
|**Tag Wrangler**|Organización avanzada de etiquetas de juego|

---

## 🎭 Flujo de Juego

### 📅 Antes de la sesión

- Revisar la última nota de sesión en `/Sessions/`
    
- Actualizar fichas de PJs y PNJs relevantes
    
- Consultar los conflictos o ganchos activos en `/Factions/` o `/Lore/`
    

### 🎲 Durante la sesión

- Crear una nueva nota `SXX - [Título de sesión]` usando la plantilla
    
- Registrar tiradas, decisiones clave, lugares visitados y objetos obtenidos
    
- Marcar vínculos entre notas con `[[ ]]` (ej: `[[Bosquecuervo]]`, `[[Thalmar]]`)
    

### 📘 Después de la sesión

- Actualizar las fichas de personajes
    
- Anotar nuevas relaciones, rumores o facciones descubiertas
    
- Añadir entradas al mapa de contenido del mundo
    

---

## 🧩 Ejemplo de Plantilla: Sesión

`--- title: "S05 - Sombras sobre Bosquecuervo" date: 2025-10-13 players: ["Lira", "Taron", "Vex"] location: "Bosquecuervo" summary: "" --- ## 🧭 Resumen Breve descripción de los eventos de la sesión.  ## 🎲 Momentos clave -  -   ## 🪶 Consecuencias -  -   ## 📍 Lugares visitados - [[Bosquecuervo]] - [[Santuario de la Llama]]  ## 🧙 PNJs relevantes - [[PNJ - Capitán Merrow]]`

---

## 🗺️ Filosofía de Campaña

> “En las fronteras del bosque, el eco de lo desconocido es la promesa de aventura.”

- **Colaborativa:** el mundo evoluciona según las acciones de los jugadores.
    
- **Narrativa:** las reglas son herramientas al servicio de la historia.
    
- **Orgánica:** los vínculos entre notas son tan importantes como los personajes mismos.
    
- **Viva:** cada sesión deja huellas visibles en la bóveda.
    

---

## 🔒 Sincronización y Seguridad

- La bóveda se sincroniza con  **Git**.
    
- Los archivos `.md` aseguran potabilidad y compatibilidad con cualquier editor.
    
- Copias de seguridad manuales antes de cada sesión.
    

---

## 🧙 Créditos
Campaña iniciada por **Roberto Maldonado Losada**  
Dirigida por **[Añadir masters extras]**
Basado en el sistema **_Nimble TTRPG_**  
Ambientación: **_Las Marcas de Bosquecuervo_**  
Versión del mundo: 1.0
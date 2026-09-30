# PASSPORT-CONTEXT · SOYMOISESVERA (MOSHEQUANTUM)

> **Línea Base Canónica, Memoria Operativa y Arquitectura de Contexto Portátil**  
> *Moisés David Vera · Founding AI Product Engineer & Design Engineer*  
> *Multiversa Group LLC · MultiversaLab*

---

Este directorio contiene la arquitectura canónica oficial **`passport-context`** de Moisés David Vera (`SoyMoisesVera` / `MosheQuantum`). Construido bajo el estándar de ingeniería de contexto de **Multiversa Group** y diseñado para ser compatible con la ingesta y despliegue del **MultiversaOS Cloud Runtime**.

Su función es ordenar el cerebro del creador, preservar su cosmovisión y dotar a los modelos de lenguaje de un marco de referencia soberano, coherente y criptográficamente verificable.

---

## 1. Mapa de Capas del Paquete

| Capa / Archivo | Tipo / Función | Propósito Central & Contenido Clave |
|---|---|---|
| **`MASTER-PROMPT.md`** | Intérprete y Orquestador | Directiva maestra de activación, jerarquía de 8 niveles y directivas de voz. |
| **`01-IDENTITY.md`** | 01 — Identidad Durable | Perfil de Moisés Vera, dualidad SoyMoisesVera / MosheQuantum, firmas oficiales y fronteras con Multiversa. |
| **`02-DOCTRINE.md`** | 02 — Doctrina y Axiomas | Conceptos > Código, IA subordinada al humano, anti-postureo y pedagogía sin humillación. |
| **`03-VOICE.md`** | 03 — Voz y Registro | Matriz anti-slop, analogías mecánicas y musicales, soliloquios y aperturas vivas. |
| **`04-OFFER.md`** | 04 — Oferta y Capacidades | Roles B2B de contratación ($3,500–$5,000+ USD/mes), ejecución 0 a 1, HITL y consultoría. |
| **`05-GOVERNANCE.md`** | 05 — Gobernanza y Ética | Zero-Data Retention, blindaje de clientes bajo NDA, principio fail-closed en agentes. |
| **`06-CURRENT-STATE.md`** | 06 — Estado Temporal | Setup real (Dell 2015, 8GB RAM), stack 2026 (SvelteKit/Cloudflare/PostgreSQL), álbum Suno. |
| **`07-EVIDENCE.md`** | 07 — Evidencia Histórica | 16+ años en producción, HackerRank verificado, EF SET B2, Ktharsys y álbum "Hablemos del tiempo". |
| **`runtime/adapters.json`** | Runtime — Adaptadores | Declaración hexagonal desacoplada de adaptadores (modelos, memoria, audio, cloud). |
| **`runtime/runtime-state.json`** | Runtime — Estado | Capacidades operativas, denegación por defecto y disparadores de actualización. |
| **`private/founder-private.md`** | Capa Privada Reservada | Perfil cognitivo, hiperfoco, resiliencia biográfica y alianza fundadora con Marian Bolívar. |
| **`manifest.json`** | Integridad Criptográfica | Inventario formal con algoritmo SHA-256, auto-hash determinista de 64 ceros y perfiles de carga. |

---

## 2. Perfiles Exportables de Contexto

El manifiesto define 4 proyecciones de uso según el objetivo de la sesión o la plataforma:

1. **`core-public`:** Para entender identidad, doctrina y voz sin datos comerciales ni operativos.
   * *Archivos:* `README.md`, `MASTER-PROMPT.md`, `01-IDENTITY.md`, `02-DOCTRINE.md`, `03-VOICE.md`, `05-GOVERNANCE.md`.
2. **`commercial-public`:** Para plataformas profesionales (Contra, GetOnBrd, Torre.ai), propuestas y postulaciones.
   * *Archivos:* Añade `04-OFFER.md`, `06-CURRENT-STATE.md` y `07-EVIDENCE.md`.
3. **`operational-private`:** Para trabajo interno en MultiversaLab y despliegues con el Cloud Runtime.
   * *Archivos:* Añade la suite de `runtime/` (`adapters.json`, `runtime-state.json`).
4. **`founder-private`:** Para asistencia directa personalizada y privada a Moisés.
   * *Archivos:* Incluye el paquete completo junto con `private/founder-private.md`.

---

## 3. Protocolo de Carga con LLMs

1. Cargar como contexto base el archivo `MASTER-PROMPT.md`.
2. Incorporar los archivos del perfil requerido en el orden estricto indicado en `manifest.json`.
3. Emitir el prompt de tarea específico.

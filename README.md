# Movi-Dick

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

**Barco recolector y reciclador de plásticos marinos. Proa de 8 m, captura pasiva, procesamiento industrial a bordo.**

Movi-Dick es un barco de 20–25 m de eslora diseñado para recolectar plásticos flotantes y sumergidos en el mar, procesarlos a bordo y convertirlos en lingotes de material reciclado listos para su reutilización. Opera con motores diésel marinos estándar, energía eléctrica propia, y un sistema de captura pasiva tipo corneta ajustable hidráulicamente.

---

## ¿Cómo funciona?

1. **Captura pasiva** — La proa en forma de corneta (8 m de largo) se sumerge hasta 3 m bajo la superficie, guiando los plásticos hacia la cinta transportadora.
2. **Cinta N°1** — Transporta el material hacia el interior, con malla de retención que permite recircular el agua al mar.
3. **Cinta N°2** — Eleva el material hacia la zona de procesamiento.
4. **Clasificación** — Tamices, flotación y sensores separan plásticos por tipo (PE, PP, PET, etc.).
5. **Trituración y lavado** — Molinos reducen el tamaño; centrifugas eliminan impurezas.
6. **Fundición** — Hornos eléctricos funden el plástico y lo moldean en lingotes.
7. **Almacenamiento** — Los lingotes se almacenan en bodega para su venta en puerto.

---

## Arquitectura del sistema

┌─────────────────────────────────────────────────────────────────────────┐
│ MOVI-DICK (20–25 m) │
│ │
│ ┌───────────────────────────────────────────────────────────────────┐ │
│ │ PROA (corneta de 8 m) │ │
│ │ ┌─────────────────────────────────────────────────────────────┐ │ │
│ │ │ Estructura tubular en V invertida, 1 m bajo flotación │ │ │
│ │ │ Altura ajustable hidráulica (Y), hasta 3 m bajo nivel │ │ │
│ │ └─────────────────────────────────────────────────────────────┘ │ │
│ │ │ │ │
│ │ ▼ │ │
│ │ ┌─────────────────────────────────────────────────────────────┐ │ │
│ │ │ CINTA TRANSPORTADORA N°1 (goma marina) │ │ │
│ │ │ Captura pasiva, malla de retención para recircular agua │ │ │
│ │ └─────────────────────────────────────────────────────────────┘ │ │
│ │ │ │ │
│ │ ▼ │ │
│ │ ┌─────────────────────────────────────────────────────────────┐ │ │
│ │ │ CINTA TRANSPORTADORA N°2 (perpendicular, elevación) │ │ │
│ │ └─────────────────────────────────────────────────────────────┘ │ │
│ └───────────────────────────────────────────────────────────────────┘ │
│ │ │
│ ▼ │
│ ┌───────────────────────────────────────────────────────────────────┐ │
│ │ PROCESAMIENTO (en línea industrial) │ │
│ │ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐ │ │
│ │ │ CLASIFICACIÓN│→│ TRITURACIÓN │→│ LAVADO │ │ │
│ │ │ (tamices, │ │ (molinos) │ │ (centrífugas)│ │ │
│ │ │ flotación) │ │ │ │ │ │ │
│ │ └─────────────┘ └─────────────┘ └─────────────┘ │ │
│ │ │ │ │
│ │ ▼ │ │
│ │ ┌─────────────────────────────────────────────────────────────┐ │ │
│ │ │ HORNOS ELÉCTRICOS (fundición y compactación) │ │ │
│ │ │ Moldes para lingotes de plástico reciclado │ │ │
│ │ └─────────────────────────────────────────────────────────────┘ │ │
│ └───────────────────────────────────────────────────────────────────┘ │
│ │ │
│ ▼ │
│ ┌───────────────────────────────────────────────────────────────────┐ │
│ │ BODEGA DE LINGOTES │ │
│ └───────────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────┘


---

## Especificaciones clave

| Parámetro | Valor |
|-----------|-------|
| Eslora total | 20–25 m |
| Manga | 6–8 m |
| Calado | 2–3 m |
| Proa (corneta) | 8 m de largo, ajustable hidráulicamente (0–3 m bajo flotación) |
| Cintas transportadoras | 2, de goma marina (1.5–2 m ancho, malla de retención en N°1) |
| Capacidad de captura | 5–10 toneladas/día |
| Capacidad de procesamiento | 2–5 toneladas/día (lingotes) |
| Propulsión | 2 motores diésel marinos (500–1000 HP c/u) |
| Generación eléctrica | Alternador acoplado a motores, 100–200 kW |
| Autonomía | 30–60 días (combustible + bodega) |
| Tripulación | 2–4 personas (operación, mantenimiento) |

---

## Componentes principales

| Componente | Función | Tecnología / Proveedor |
|------------|---------|------------------------|
| **Proa corneta** | Captura pasiva de plásticos | Acero naval, hidráulica ajustable |
| **Cintas transportadoras** | Traslado de material | Goma marina, motores eléctricos |
| **Clasificadores** | Separación por tipo de plástico | Tamices, flotación, sensores ópticos |
| **Trituradoras** | Reducción de tamaño | Molinos de cuchillas industriales |
| **Centrífugas** | Lavado y secado | Equipos de reciclaje estándar |
| **Hornos eléctricos** | Fundición y moldeo | Modulares, por tipo de plástico |
| **Motores diésel** | Propulsión + generación | Motores marinos estándar (Caterpillar, MAN, etc.) |

---

## Estado actual

✅ Concepto definido  
✅ Arquitectura del sistema  
✅ Especificaciones preliminares  
🔲 Diseño estructural de proa corneta  
🔲 Selección de cintas y mallas  
🔲 Definición de línea de reciclado (capacidades específicas)  
🔲 Simulación de consumo energético  
🔲 Prototipo escala reducida (1:10)

---

## Próximos pasos

1. **Diseño estructural** — Detalle de la proa corneta, sistema hidráulico de ajuste.
2. **Selección de equipos** — Cintas, trituradoras, hornos, motores.
3. **Simulación** — Consumo energético, capacidad de captura, autonomía.
4. **Prototipo a escala** — Pruebas en piscina con materiales reales.
5. **Modelo de negocio** — Costos, ingresos por lingotes, créditos de carbono.

---

## Proyectos relacionados

- **Goliat-Orbital** — captura y reciclaje de basura espacial  
  [Repositorio](https://github.com/enriqueherbertag-lgtm/Goliat-Orbital)

- **ShieldAir** — torres de producción de oxígeno (urbanas y marcianas)  
  [Urban](https://github.com/enriqueherbertag-lgtm/ShieldAir-Urban) | [Mars](https://github.com/enriqueherbertag-lgtm/ShieldAir-Mars)

- **HidroFix** — seguridad para celdas de hidrógeno  
  [Repositorio](https://github.com/enriqueherbertag-lgtm/Hidrofix)

---

## Licencia

Apache 2.0 con restricción de uso comercial.  
*Este es un framework base open-source. El que quiera más precisión, menor latencia o features avanzadas… que lo modifique y contribuya.*

---

## Autor

**Enrique Aguayo H.**  
Investigador independiente, Mackiber Labs  
Contacto: eaguayo@migst.cl  
ORCID: 0009-0004-4615-6825  
GitHub: [@enriqueherbertag-lgtm](https://github.com/enriqueherbertag-lgtm)

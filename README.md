# Rehabilitacion COT

Ejercicios terapeuticos SERMEF y protocolos de rehabilitacion postquirurgica COT. Dos modulos: **Ejercicios** (programas SERMEF por region anatomica) y **Protocolos** (guias postquirurgicas por fase y semana).

## Acceso directo
[Abrir la aplicacion](https://jmacot.github.io/rehabilitacion-cot/)

## Modulos

### Ejercicios
- **23 protocolos de ejercicios terapeuticos** de la SERMEF (Sociedad Espanola de Rehabilitacion y Medicina Fisica)
- **7 regiones anatomicas**: Hombro (6), Codo (2), Columna (3), Rodilla (3), Tobillo (3), Cadera (4), Osteoporosis (2)
- Dos acciones por protocolo: ver PDF o personalizar programa en ejercicios.sermef.es
- Sidebar con pills por region y colores distintivos

### Protocolos
- **64 protocolos** de rehabilitacion postquirurgica organizados por region anatomica
- Calculo automatico de fase segun fecha de cirugia/lesion o semanas postoperatorias
- Timeline visual D3.js con barra de progreso y marcador de semana actual (rojo)
- Gantt de fases con semanas y marcador temporal
- Contenido clinico: objetivos, precauciones, carga de peso, intervenciones por categoria, criterios de progresion
- Videos de ejercicios enlazados a YouTube en 15 protocolos
- Filtro por region, busqueda por nombre de patologia
- Copiar fase al portapapeles

## Protocolos incluidos (64)

| Region | N | Protocolos |
|--------|---|------------|
| Rodilla | 22 | Reconstruccion LCA, LCA Tratamiento Conservador, LCA Pediatrico, LCP, Meniscectomia Parcial, Sutura Meniscal, PTR, Reconstruccion MPFL, MPFL Pediatrico, Microfractura Condilo/Patela, ACI Condilo Femoral, ACI Rotula, Osteotomia Tibial Alta, Mosaicoplastia, Reparacion Tendon Rotuliano, Reparacion Isquiotibial Proximal, Fractura Rotula RAFI, Fractura Meseta Tibial, Esguince LCM, Cintilla Iliotibial, Osteocondritis Disecante Pediatrica, Dolor Patelofemoral |
| Hombro | 20 | Bankart Anterior, Bankart Posterior, Manguito Rotador (peq-med), Manguito Rotador (grande-masivo), Manguito Rotador Grande/Masivo (tratamiento conservador), Manguito Rotador Masivo (tratamiento conservador), SLAP II, Latarjet, Artroplastia Total Anatomica, Protesis Inversa, Pectoral Mayor, Reconstruccion AC, Transferencia Dorsal Ancho, Tenodesis Biceps, Fractura Clavicula RAFI, Transferencia Trapecio Inferior, Reparacion Subescapular, Fractura Humero Proximal RAFI, Reconstruccion Esternoclavicular, Reparacion Pectoral Mayor |
| Cadera | 6 | Protesis Total, Artroscopia FAI/Reparacion Labral, Pubalgia Atletica, Reparacion Musculatura Core, Lesion Isquiotibiales, Reparacion Isquiotibial Proximal |
| Pie y Tobillo | 6 | Rotura Tendon Aquiles, Fractura Tobillo RAFI, Tendones Peroneos, Protesis Total Tobillo, Esguince Tobillo, Reparacion Brostrom |
| Columna | 6 | Lumbalgia con Deficit de Movilidad, Espondilosis Lumbar, Inestabilidad Espinal, Estenosis Lumbar, Hernia Discal Lumbar, Retorno al Deporte tras Concusion |
| Codo | 3 | Epicondilalgia Medial/Lateral, Reparacion Biceps Distal, Reconstruccion LCU |
| Mano | 1 | Fractura Radio Distal |

## Funcionalidades generales
- Modo oscuro con auto-deteccion
- Responsive para movil y escritorio
- Navegacion por modulos (Ejercicios / Protocolos)

## Tecnologia
- HTML5, CSS3 y JavaScript puro
- D3.js para graficas de timeline y Gantt
- Tipografias: Inter, Lora (Google Fonts)
- Sin frameworks, sin dependencias adicionales

## Licencia
MIT

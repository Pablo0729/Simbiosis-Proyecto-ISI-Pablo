# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como persona interesada en la cocina, quiero encontrar una receta que se adapte a mis preferencias alimenticias, incluyendo o excluyendo ingredientes, para después poder preparar, paso a paso y con los ingredientes que yo desee, esa receta en mi cocina.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** [Buscar mediante una palabra o frase.]

Como persona interesada, quiero buscar una receta mediante la introducción de una palabra clave o frase, para obtener en la web esa receta.

**Fuentes:** UR-08; UC-21; FR-085; acta, Criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dada un ingrediente específico, cuando lo introduzco en la barra de búsqueda, el buscador encuentra diferentes resultados coincidentes con mi ingrediente.
- **CA-02.** Dado un ingrediente, cuando lo introduzco en la barra de búsqueda el buscador no encuentra ningún resultado coincidente con mi ingrediente.
- **CA-03.** Dado un ingrediente, cuando lo introduzco de forma errónea, es decir, con faltas de ortografía,  el buscador no coincide.

## US-02

**Título:** [Buscar por ingredientes incluidos]

Como persona interesada, quiero buscar una receta  mediante la exclusión de ingredientes, para obtener en la web esa receta.

**Fuentes:** UR-08; UC-21; FR-086; acta, Criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dados unos ingredientes que me muestra el sistema, cuando los añado a mis criterios de búsqueda, el sistema muestra los resultados coincidentes con mi selección.
- **CA-02.** Dados unos ingredientes que me muestra el sistema, cuando los añado a mis criterios de búsqueda pero introduzco uno que no coincide con ninguna receta, el sistema no muestra ninguna receta coincidente.
- **CA-03.** Dados unos ingredientes que me muestra el sistema, introduzco un ingrediente que contiene mi receta y otro que no contiene, el sistema solo me muestra los resultados que coinciden con ambos ingredientes por lo que no me va a mostrar el resultado que deseo.
## US-03

**Título:** [Excluir ingredientes]

Como persona interesada, quiero buscar una receta mediante la exclusión de ingredientes , para obtener en la web esa receta.

**Fuentes:** UR-08; UC-21; FR-087; acta, Criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dados unos ingredientes , cuando los selecciono para que el buscador no me los tenga en cuenta cuando se ponga a buscar las recetas, entonces el sistema encuentra unos resultados coincidentes con mis criterios de búsqueda.
- **CA-02.** Dados unos ingredientes , cuando los selecciono para que el buscador no me los tenga en cuenta cuando se ponga a buscar las recetas, entonces el sistema no encuentra unos resultados coincidentes con mis criterios de búsqueda.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST 

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]

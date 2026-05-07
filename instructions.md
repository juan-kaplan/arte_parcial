# Instrucciones para continuar el HTML de estudio

## Objetivo del proyecto

Este workspace contiene una herramienta de estudio en HTML para preparar un parcial oral de Historia del Arte / Cultura Argentina. La presentación principal elegida es:

**La Generación del 80 y el debate sobre el “arte nacional”**

La consigna a responder es:

> A partir de la generación del 80 y hacia el Centenario, ¿cómo se vinculó el concepto de “arte y civilización” con la creación de instituciones artísticas en Argentina y el surgimiento de un “arte nacional”? Explique la relación entre los viajes de formación a Europa y la adaptación de esos temas y lenguajes a la realidad local.

El HTML debe funcionar principalmente como **herramienta de estudio compartida para dos personas**. No es solo una presentación visual final: tiene que contener tesis, guion oral, imágenes para analizar, ideas importantes y preguntas posibles.

Importante: los **5 minutos de preparación privada** corresponden a las otras consignas que vendrán más adelante, no a la consigna elegida. Para la consigna elegida se prepara una exposición más completa.

## Prioridad actual

La prioridad principal sigue siendo **cerrar bien la consigna elegida**, pero las cuatro consignas alternativas ya fueron incorporadas como secciones breves de repaso. No ampliarlas al nivel de la consigna principal salvo que el usuario lo pida.

La página actual debe servir en dos modos diferenciados:

- **Consigna elegida preparada:** entender la lógica de la consigna principal, los autores, las instituciones, las obras y el reparto oral.
- **Repaso de consignas alternativas:** entrar rapido a la consigna que toque, mirar primero imagenes/artistas/autores y despues usar una respuesta oral breve.

Tambien existe una vista secundaria:

- `presentacion.html`: version mas visual y sintetica para mostrar o usar como apoyo oral. Debe mantenerse basada en la guia completa, no reemplazarla.

## Criterio de trabajo con agentes

Cuando haya varias tareas separables, intentar usar múltiples agentes o líneas de trabajo en paralelo si el entorno lo permite. La idea es mantener el contexto principal más limpio, dividir mejor la investigación, la implementación y la revisión, y después integrar solo los resultados útiles.

Ejemplos:

- Un agente revisa contenido histórico y otro revisa diseño/responsive.
- Un agente busca fuentes o imágenes y otro prepara estructura del HTML.
- Un agente verifica deploy/Pages y otro hace QA visual.

Si no se pueden usar múltiples agentes por limitaciones del entorno o de la tarea, mantener igualmente esa lógica de separación: explorar, implementar y verificar en bloques claros.

## Archivos principales

- `tema_arte_civilizacion_estudio.html`: archivo principal de estudio.
- `presentacion.html`: vista secundaria visual, con bloques, imagenes grandes, palabras clave y link de vuelta a la guia.
- `instructions.md`: estas instrucciones para continuar el trabajo.
- `assets/`: imágenes locales usadas por el HTML.
- `resumenes/`: resúmenes operativos de los textos y presentación de apoyo.
- `textos/`: PDFs base para bibliografía; están escaneados y no siempre extraen texto directamente.

## Bibliografía base

1. Laura Malosetti Costa, “Arte y civilización”, en *Los primeros modernos. Arte y sociedad en Buenos Aires a fines del siglo XIX*, Buenos Aires, Fondo de Cultura Económica, 2011, cap. 1.
2. Fernando Devoto, *El país del primer centenario cuando todo parecía posible*, Buenos Aires, Capital Intelectual, 2010, cap. 1: “Argentina en 1910”.
3. Resúmenes y presentación de apoyo sobre Malosetti ubicados en `resumenes/`.

Usar los PDFs de `resumenes/` como fuente práctica principal para redactar o corregir contenido. Los PDFs de `textos/` funcionan como bibliografía base, pero al estar escaneados pueden requerir lectura visual/OCR si se necesita volver al original.

## Tesis que debe sostener la respuesta

> Desde la Generación del 80 hacia el Centenario, el arte fue pensado como una prueba de civilización y también como una herramienta para producirla. Por eso se impulsaron instituciones artísticas, becas, salones, museos y viajes de formación a Europa. El “arte nacional” surgió de una paradoja: buscaba representar temas locales, pero usando lenguajes y criterios de legitimación europeos.

No convertir el tema en una lista de artistas ni en una cronología suelta. Cada dato debe conectarse con la consigna.

## Ideas que no deben perderse

### Arte y civilización

- Para Malosetti, las bellas artes no eran vistas como decoración.
- Eran prueba del grado de civilización alcanzado por una nación.
- También eran una herramienta para civilizar: educar el gusto, disciplinar sensibilidades, formar público y elevar costumbres.
- La autora analiza críticamente esa idea: estaba atravesada por elitismo, positivismo, jerarquías raciales y la oposición civilización/barbarie.
- La noción de civilización no es neutral: ordena jerarquías entre Europa/América, ciudad/campo, elite/sectores populares, civilizado/bárbaro.

### Devoto y el Centenario

- Argentina hacia 1910 aparece como un país de fuerte crecimiento y optimismo.
- Hay expansión económica, inmigración, ferrocarriles, urbanización, educación y consolidación estatal.
- Pero también hay tensiones: desigualdad, conflicto social, integración problemática de inmigrantes, crisis política y preocupación por construir una identidad nacional.
- Este contexto explica por qué el arte se vuelve importante: el progreso material no alcanzaba para mostrar una nación civilizada.

### Taine, positivismo y raza latina

- Taine permite pensar el arte desde raza, medio y momento.
- Esa idea habilita imaginar un arte propio para cada pueblo, pero también arrastra jerarquías racializadas.
- Schiaffino y otros usaron la idea de “raza latina” y herencia hispánica para imaginar un destino artístico argentino.
- Mencionar esto con distancia crítica: no presentarlo como verdad, sino como discurso histórico.

### Instituciones artísticas

Incluir siempre:

- Sociedad Estímulo de Bellas Artes.
- Ateneo.
- Salones y exposiciones.
- Becas o pensiones para estudiar en Europa.
- Crítica de arte y prensa.
- Museo Nacional de Bellas Artes.

Idea clave:

> El arte nacional no nace solo de obras individuales. Nace también de instituciones que forman artistas, educan al público, organizan exposiciones y crean criterios de legitimación.

### Viajes de formación a Europa

- París funcionaba como centro de legitimación.
- Viajar a Europa era aprender técnicas, normas y lenguajes considerados universales.
- La paradoja: para construir un arte nacional argentino había que formarse en Europa.
- No se trata de simple copia: esos lenguajes se adaptan a temas locales.
- Schiaffino es figura clave porque fue pintor, crítico, gestor cultural, historiador y organizador institucional.

### Crisis de 1890

- La crisis económica y política atenúa el optimismo del progreso material.
- La Revolución del Parque y obras como *Sin pan y sin trabajo* muestran el reverso del proyecto modernizador.
- La crisis no elimina el discurso arte/civilización; lo vuelve más urgente y defensivo.
- En ese clima aparecen cuestionamientos al otorgamiento de becas o pensiones para artistas en Europa: se vuelve más fuerte la objeción utilitaria contra financiar formación artística.
- Augusto Belín Sarmiento defiende en *La Prensa* el lugar de las artes plásticas después del Salón del Ateneo de 1894: no las presenta como lujo, sino como parte del progreso civilizatorio y también material, porque el dibujo está en la base del diseño industrial.
- Idea oral: para Belín Sarmiento, abandonar la formación artística no era una decisión moderna o práctica, sino aceptar un destino limitado de país agropecuario y “bárbaro”.

### Arte nacional

El “arte nacional” surge de combinar:

- Lenguajes europeos: pintura histórica, composición académica, naturalismo, desnudo de salón, criterios de exposición.
- Temas locales: pampa, frontera, gaucho, indígena, cautiva, historia patria, religiosidad colonial, inmigración, trabajo urbano.

Tensión crítica:

> Muchas imágenes nacionales se construyen desde una mirada urbana, elitista y europeizante. Lo indígena, la pampa o el gaucho pueden aparecer como símbolos nacionales, pero también como figuras de barbarie o atraso.

## Imágenes locales ya incorporadas

Las imágenes están en `assets/` con nombres simples:

1. `della-valle-vuelta-del-malon.jpg`
   - Ángel Della Valle, *La vuelta del malón* (1892).
   - Uso: arte nacional, pampa, indígena, cautiva, frontera, civilización/barbarie.

2. `sivori-despertar-criada.jpg`
   - Eduardo Sívori, *El despertar de la criada / Le lever de la bonne* (1887).
   - Uso: formación francesa, modernidad artística, escándalo en Buenos Aires, regreso del lenguaje europeo al medio local.

3. `schiaffino-reposo.jpg`
   - Eduardo Schiaffino, *Reposo* (1889).
   - Uso: legitimación internacional, Exposición Universal de París, artista argentino medido por criterios europeos.

4. `seba-1893.jpg`
   - Fotografía de la Sociedad Estímulo de Bellas Artes, 1893.
   - Uso: institucionalización del arte argentino.

5. `pabellon-argentino-1889.jpg`
   - Pabellón Argentino en la Exposición Universal de París de 1889.
   - Uso: representación internacional de Argentina como nación moderna y civilizada.

6. `carcova-sin-pan-sin-trabajo.jpg`
   - Ernesto de la Cárcova, *Sin pan y sin trabajo* (1894).
   - Uso: reverso del optimismo del progreso, crisis social, conflictividad posterior a 1890.

7. `schwartz-rendicion-parque.jpg`
   - Alberto Schwartz, *Rendición del Parque* (1891).
   - Uso: crisis política de 1890 y quiebre del optimismo del orden conservador.

8. `goya-3-mayo.jpg`
   - Francisco de Goya, *El 3 de mayo de 1808* (1814).
   - Uso: herencia hispana invocada como linaje artístico; contrapunto para discutir violencia europea y “civilización”.

9. `blanes-conquista-desierto.jpg`
   - Juan Manuel Blanes, *Ocupación militar del Río Negro / La conquista del desierto*.
   - Uso: representación de la violencia estatal como gesta de orden y civilización.

Tambien hay assets para las consignas alternativas:

- Consigna 1: `vidal-cabildo-recova.jpg`, `bacle-recova-1835.jpg`, `bacle-peinetones-casa.jpg`, `bacle-trages-sra-portena.jpg`, `el-museo-americano-cover.jpg`.
- Consigna 2: `pellegrini-guerrico-retrato.jpg`, `descalzi-rosas.jpg`, `goulu-cirila-crespo-miniatura.jpg`, `san-martin-daguerrotipo.jpg`.
- Consigna 3: `garcia-del-molino-rosas.jpg`, `morel-familia-gaucho.jpg`, `morel-la-partida.jpg`, `morel-payada-pulperia.jpg`, `morel-gaucho-traje-pueblo.jpg`, `rosas-luto-ezcurra-divisa.png`.
- Consigna 5: `pueyrredon-rodeo.jpg`, `pueyrredon-alto-campo.jpg`, `sivori-pampa-chacra-portena.jpg`, mas las obras de Della Valle y Blanes ya listadas.

## Estilo de escritura

- Usar español claro, directo y oral.
- Priorizar lo que se puede decir en voz alta.
- Evitar párrafos demasiado largos.
- Cada obra debe explicar para qué sirve en la consigna.
- Cada concepto debe conectarse con una imagen, una institución o un problema histórico.
- Evitar frases vagas como “esto es importante” sin explicar por qué.
- Mantener una mirada crítica, pero no perder la respuesta principal.

## Criterio para consignas alternativas

Las consignas 1, 2, 3 y 5 ya estan agregadas como secciones breves. Mantener esta estructura fija:

```html
<section id="tema-x">
  <h2>Tema X - Título de la consigna</h2>
  <h3>Imagenes / artistas / autores para ubicar primero</h3>
  <!-- fichas visuales -->
  <div class="callout">
    <p><b>Tesis rápida:</b> ...</p>
  </div>
  <h3>Conceptos clave</h3>
  <ul>
    <li>...</li>
  </ul>
  <h3>Obras o imágenes posibles</h3>
  <ul>
    <li><b>Obra:</b> cómo usarla.</li>
  </ul>
  <h3>Respuesta oral en 2 minutos</h3>
  <p>...</p>
</section>
```

Criterio de contenido:

- Arrancar siempre por imagenes, artistas y autores.
- Responder la consigna y nada mas: no hacer desarrollo enciclopedico.
- Usar los PDFs de `textos/` como bibliografia base y los textos extraibles o paginas renderizadas como apoyo de verificacion.
- Para PDFs escaneados, renderizar paginas relevantes y revisar visualmente si hay dudas.
- Mantener tono oral y util para dos personas.

Consignas incorporadas:

- `#consigna-1`: artistas viajeros, expediciones cientificas, litografia, periodicos ilustrados y costumbrismo.
- `#consigna-2`: retrato burgues, de aparato, miniatura, litografia y daguerrotipo como herramientas de estatus y sociabilidad.
- `#consigna-3`: rosismo, retratistica, costumbrismo federal, punzo, litografia y propaganda politica.
- `#consigna-5`: paisaje pampeano, pampa/desierto, cautiva, malon, conquista, Pueyrredon, Della Valle, Blanes y Sivori.

## Reparto oral para el tema elegido

### Persona A

- Presenta la consigna.
- Explica contexto de Devoto.
- Introduce arte/civilización según Malosetti.
- Explica por qué el progreso material no alcanzaba y por qué civilización no es neutral.

### Persona B

- Explica SEBA, Ateneo, becas, salones, crítica y museo.
- Explica viajes a Europa y paradoja de París.
- Analiza Sívori, Schiaffino y/o Della Valle.
- Cierra con arte nacional, adaptación local y tensiones civilización/barbarie.

## Cierre recomendado

> En síntesis, la Generación del 80 pensó el arte como parte de un proyecto civilizatorio. Crear instituciones, mandar artistas a Europa y exhibir obras en circuitos internacionales era una forma de demostrar que Argentina era una nación moderna. Pero el “arte nacional” que surgió de ese proceso fue contradictorio: buscó representar lo propio con lenguajes europeos y muchas veces construyó la identidad nacional desde una mirada elitista, urbana y excluyente.

## Pendientes próximos

- Ensayar el guion y medir duración real.
- Ajustar qué obras van a usar en la presentación oral definitiva.
- Revisar si alguna consigna alternativa necesita mas precision segun lo que pida la catedra.
- Mantener `presentacion.html` sincronizada cuando cambien tesis, obras o palabras clave de la guia principal.
- Si se agregan más imágenes, usar fuentes oficiales o estables y dejar el crédito en la ficha.

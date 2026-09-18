# Demarquía Digital: Una Política sin Políticos

**Arquitectura de un Estado Descentralizado, Criptográfico y de Representación Aleatoria**

**Versión:** v0.4.4  
**Fecha:** 18 de septiembre de 2026  
**Licencia:** Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional (CC BY-SA 4.0). Puedes copiar, compartir y mejorar este texto con libertad, siempre que des crédito al autor original y publiques tus cambios bajo la misma licencia, gratis y en público.  
**Autoría:** crédito al autor original; iteración v0.4-v0.4.4 en conversación de diseño.  
**Repositorio:** https://github.com/AlwaysBrokenJC/demarquia-digital

---

## Declaración de proyecto abierto

Esta es una propuesta abierta: cualquiera, en cualquier lugar, puede mejorarla, corregirla o hacer su propia versión.

Sabemos que todo diseño humano es imperfecto. Por eso lo publicamos con licencia abierta: para que quienes viven las consecuencias de la política puedan intervenir, corregir y hacer su propia versión de este modelo hacia algo más justo.

El objetivo es devolver el poder al pueblo y construir, juntos y a lo largo del tiempo, el mejor sistema que la humanidad pueda imaginar en cada momento de su historia.

---

## Posición filosófica (en corto)

> Demarquía Digital es un proyecto libertario que apunta a una minarquía demárquica digital: un Estado sin políticos de carrera, con cargos por sorteo, voto directo del pueblo (sin que nadie vote por ti), derechos que protegen tu libertad frente al poder, y tecnología que hace difícil hacer trampa.
>
> Hay impuestos y un Estado con fuerza pública acotada. La meta es que el Estado gaste como máximo cerca del 15% del producto interno bruto (PIB), con un techo duro del 20%. Para romper ese techo hace falta la Triple Llave (el mismo blindaje que para cambiar la Constitución). El gasto se recorta, caduca si no sirve y se limpia de grasa burocrática.
>
> Quien quiera una variante más minimalista o más social puede hacer una versión propia bajo la misma licencia, y debe decir con claridad qué rompe del tronco.

## Prefacio filosófico

### 1. Diagnóstico honesto

Demarquía Digital diseña un Estado: impuestos (también si eliges no votar), policía, defensa limitada, presupuesto, pago por el tiempo cívico, División de Desastres y un fondo soberano de largo plazo. Quien quiere abolir el Estado por completo deja de estar hablando de este documento.

El código base privilegia derechos negativos (libertad frente a la coerción), Triple Llave al 75% popular, leyes iguales para todos, financiamiento político solo de personas (no de empresas) y un motor de presupuesto que encoge la grasa en vez de maximizar el gasto. Eso lo aleja de una socialdemocracia expansiva.

La etiqueta del tronco es minarquía demárquica digital.

### 2. Tres posiciones

| Posición | Encaje |
|----------|--------|
| **Minarquía clásica** | Espíritu cercano; el tronco es un poco más grueso (créditos de edu/salud, educación cívica, cascada de excedentes). |
| **Minarquía demárquica digital** | **Tronco.** Libertad negativa + sorteo + voto directo + hardware que asume ataques + techo fiscal. |
| **Otras variantes** | Versiones propias con otro énfasis (más minimalistas o más sociales), bajo la misma licencia, declarando qué dejan fuera del tronco. |

### 3. Lo no negociable del tronco

1. Nadie vota por ti (no hay delegación de voto).
2. Derechos negativos + Triple Llave.
3. Demarquía + pools (sin carrera política permanente).
4. Separación entre terminales de voto y terminales administrativas.
5. Honestidad sobre la transición y sobre los problemas abiertos (Cap. 10).
6. Techo fiscal: meta 15% / duro 20% (Capítulo de Economía).

Una versión propia que rompa estos puntos debe cambiar de nombre.

### 4. Opt-Out cívico (1.8)

Es el derecho a no participar en la vida pública: renuncias al voto. Dejas intactas las obligaciones fiscales y el orden legal (no es secesión). Es distinto del opt-out del beneficio de educación o salud (rebaja fiscal del 80% del crédito que no usas).

### 5. Economía (ver Cap. 5A)

- Propiedad privada por defecto; sin topes a cuánto puedes acumular.
- El peso como unidad fiscal (regla dura) + libertad de usar otras monedas entre privados.
- Voucher educativo y seguro de salud en competencia (el Estado paga al proveedor; puedes cambiarte).
- Banca libre; sin rescates a amigos del poder; depósitos con tope; el fondo soberano no hace favores.
- Gasto fijo en seis partidas: justicia, seguridad, defensa limitada, infraestructura del voto, Desastres, y créditos mínimos de edu/salud.

### 6. Una frase sobre el Opt-Out (1.8)

> El Opt-Out cívico deja intactas las obligaciones fiscales y el orden legal (no es secesión).

### 7. Gobernanza del repo

Con el tiempo el repositorio tendrá una carpeta de variantes (`forks/`) y plantillas breves (por ejemplo variantes más minimalistas o más sociales) que digan con claridad qué cláusulas del tronco deja fuera cada variante.

---

## Resumen Ejecutivo

Este documento propone una "Política sin Políticos": devolverle al pueblo el poder de decidir, sin intermediarios de carrera.

La democracia representativa actual es fácil de corromper, cansa a la gente y deja que el presupuesto se secuestra. Por eso este diseño apunta a un Estado sin intermediarios de carrera.

La votación pasa por máquinas físicas difíciles de hackear (tres chips de orígenes distintos) y una credencial con biometría que vive en tu tarjeta, no en un servidor del gobierno. No hace falta un político que vote por ti: hay democracia directa (tú decides) y demarquía (cargos por sorteo).

Las leyes nacen en un Ágora Digital abierta a cualquier ciudadano. Pasan un filtro constitucional. Un Congreso de 500 personas (mitad sorteadas de quien se ofreció, mitad de quienes aprobaron un examen práctico del sistema) las pulen con ayuda de traductores legales. Al final, el pueblo aprueba o rechaza. Nadie delega su voto.

El dinero público se controla con recorte ponderado, cascada de excedentes y la regla de que ninguna decisión importante la toma una sola métrica automática. Hay un presidente que representa al país hacia afuera, pero sin poder ejecutivo. Una División de Desastres coordina emergencias bajo vigilancia del Congreso y del pueblo.

El tronco se llama minarquía demárquica digital: el Estado apunta a gastar ≤15% del PIB, con techo duro al 20% (solo rompible con Triple Llave). El gasto fijo se limita a seis partidas. Propiedad, moneda, banca y créditos de edu/salud van en el Capítulo 5A.

El destino es un país. El camino natural es la adopción nacional en capas: primero opinión y normas voluntarias a escala país; luego soberanía parcial donde una jurisdicción abra espacio; al final el orden constitucional demárquico, junto con los escenarios A, B y C del Capítulo 9 (paralelo gradual, pacto con élites, post-colapso). Meterlo de golpe en un Estado consolidado ha tenido, históricamente, un precio de violencia organizada, como todo cambio sistémico real. El detalle del camino está en el plan de adopción nacional en capas.

---

## Capítulo 1: El Código Base (Cimientos Constitucionales)

### 1.1 Los Derechos Negativos y la Triple Llave de Reforma

La Constitución de la Demarquía Digital se apoya en derechos negativos: protegen tu libertad individual, evitan que el poder se concentre y ponen el método técnico-científico por encima de la tradición.

Para que nadie cambie la Constitución a la ligera, existe la Triple Llave de Reforma. Hace falta el acuerdo escalonado del Congreso Demárquico, del Tribunal Supremo y de una supermayoría del 75% en votación popular directa.

El derecho de asociación política es absoluto para toda persona. Puedes organizarte en asociaciones, movimientos o partidos con la forma e ideología que quieras. Cómo se financian esas organizaciones se explica en el Capítulo 6.

### 1.2 Principio de Universalidad de las Leyes

Ninguna ley puede dar derechos, obligaciones o castigos distintos según quién seas: origen, profesión, creencia o grupo. Si el Estado reparte recursos de forma distinta, el criterio debe ser objetivo, medible, temporal y abierto a cualquiera que lo cumpla, y aplicarse solo.

Hay una diferencia clara:

- **Prohibido:** leyes que crean derechos u obligaciones distintos según la identidad de la persona.
- **Permitido:** una ley general con un criterio universal; el apoyo llega a quien lo cumple, sin nombrar grupos.

Ejemplo: en vez de “ley de apoyo a discapacitados”, se dice “toda persona cuya capacidad funcional certificada sea inferior a X% recibe apoyo Z mientras esa condición dure”. Cualquiera entra o sale según cumpla o no el criterio. No hay castas permanentes de beneficiarios. La verificación debe ser digna y respetar la privacidad: esto no se convierte en vigilancia social.

### 1.3 Derecho Universal al Voto

Si eres ciudadano activo, votas. Sin examen, sin certificado, sin filtro de alfabetización. La única condición es activar tu Credencial de Soberanía Criptográfica (CSC), tu credencial cívica con chip seguro, al cumplir la mayoría de edad.

### 1.4 Régimen de Ciudadanía, Residencia y Refugio

**Ciudadanía:** nacer en el país y residir ahí de forma continua al menos 10 años. Si naciste ahí pero no cumpliste esos 10 años seguidos, presentas un examen general (historia, conocimiento del país, sistema demárquico). La naturalización está abierta a residentes legales con al menos 5 años continuos; ellos pueden presentar el mismo examen.

**Residentes legales:** no votan ni entran al sorteo de cargos, pero participan en Asambleas Consultivas de Residentes. Su voz se publica; el Congreso debe leerla y responder por escrito. Al obtener ciudadanía, pasan a ser agentes plenos.

**Refugiados y solicitantes de asilo:** se tratan como residentes legales en lo consultivo. El camino a la ciudadanía es más largo: primero residencia formal durante el proceso de protección; desde ahí corren los 5 años para el examen.

**Menores:** ciudadanos o no, participan en Asambleas Consultivas de Menores (en escuelas y también fuera de ellas). Su voz se publica; el Congreso responde por escrito.

### 1.5 Niveles de Participación Configurables

Cada ciudadano elige cuánto participa:

- **Local-local:** solo municipio y estado.
- **Federal-federal:** solo lo nacional.
- **Ambos:** local y federal.
- **Ninguno:** Opt-Out cívico: no votas, pero conservas tu ID civil y tus obligaciones legales y fiscales.

Puedes cambiar esto en la app, en cualquier terminal administrativa (**TMC**, Terminal de Módulo Cívico) o en la terminal de voto (**TVM**, Terminal de Votación Malla) al empezar la sesión, antes de votar. Es inmediato, sin castigo y sin tener que justificarte.

### 1.6 Pueblos Originarios: Autonomía con Piso Universal de Derechos

Las comunidades originarias pueden organizarse a su manera (asamblea, consejo de ancianos, sistemas de cargos, etc.) y resolver disputas entre sus miembros con sus propias normas. No pueden imponer esas normas a personas externas en su territorio, ni quitar a sus propios miembros los derechos negativos universales si prefieren ampararse en el sistema demárquico. Toda persona conserva el derecho de salida y de apelación al sistema general.

### 1.7 El Tribunal Supremo de Consenso (TSC)

El Tribunal es el antivirus constitucional del Estado. Sus miembros salen por sorteo del Pool Judicial: profesionales del derecho que aprobaron un examen ciego abierto.

Para declarar inconstitucional una ley o un presupuesto hace falta un consenso interno del 70% al 80%. Si no se alcanza, impera la duda razonable y se respeta lo que el pueblo ya votó. El Tribunal está siempre bajo auditoría ciudadana y puede revocarse por voto popular si se detectan sesgos deliberados.

### 1.8 El Opt-Out Cívico: Derecho a la Desconexión

El sistema reconoce el derecho libertario a no participar en la vida pública. Cualquier ciudadano puede pedir el Opt-Out cívico: se borran de inmediato sus registros del padrón de votación. A cambio recibe una Credencial de Identidad Simple.

Sigue obligado a cumplir las leyes y a pagar impuestos como cualquier otro. No hay castigo fiscal ni sanción por desconectarse.

Conservas todos tus derechos negativos: expresión, asociación, culto, reunión y debate público. Puedes opinar, militar ideas, financiar campañas con tu propio dinero, organizar movimientos y publicar. El Opt-Out es renuncia al voto; no renuncia a la ciudadanía ni a los derechos civiles.

El Opt-Out cívico deja intactas las obligaciones fiscales y el orden legal (no es secesión). Es distinto del opt-out del beneficio de educación o salud (rebaja fiscal del 80% del crédito que no usas), explicado en el Capítulo 5A: aquel solo recupera el valor del beneficio rechazado; este renuncia al voto y sigue pagando el núcleo fiscal.

Puedes revertir el Opt-Out en cualquier momento, sin castigo ni trámite extra.

### 1.9 Renuncia Voluntaria a Datos Biométricos

Puedes pedir el borrado de tus datos biométricos cuando quieras. Pierdes el derecho a voto (que necesita autenticación de tres factores), pero conservas tu ID civil para contratos, propiedad, identificación y servicios.

Excepción: si tienes antecedentes penales o procesos activos, el poder judicial puede conservar lo estrictamente necesario para esos procesos. Es interés legítimo de la sociedad frente a crímenes graves.

Puedes revertir la renuncia re-registrando biometría y recuperando el voto.

---

## Capítulo 2: Infraestructura y Hardware (La Capa Física)

### 2.1 Presunción Constitucional de Compromiso

Olvidamos la fantasía del “hardware inviolable”. Partimos de lo contrario: asumimos que parte del equipo está comprometido y diseñamos para sobrevivir a eso. La seguridad no depende de confiar en un fabricante; depende de redundancia, diversidad y auditoría continua.

### 2.2 La Credencial de Soberanía Criptográfica (CSC)

Tu identidad cívica vive en una tarjeta con chip seguro (CSC): la huella y los datos biométricos se guardan en la tarjeta, encriptados. No viajan por la red ni se guardan en un servidor central del Estado.

Para votar: metes la credencial, pones el dedo e ingresas una frase que solo tú memorizas. Hacen falta tres cosas a la vez: la tarjeta (lo que tienes), la biometría (lo que eres) y la frase (lo que sabes). Solo si las tres coinciden, el chip libera la llave que firma tu voto en la cadena de bloques.

Esa misma frase admite una Frase de coacción (Capítulo 9): si te amenazan, puedes dar conscientemente la versión “bajo coacción”. La máquina muestra que el voto se registró (para protegerte), pero en la cadena de bloques ese voto se anula en silencio.

### 2.3 Terminales de Votación Malla (TVM)

El voto que cuenta solo se emite en Terminales de Votación Malla (TVM): máquinas físicas en jornadas electorales. No se vota desde el celular. Motivo: coacción remota, programas maliciosos, capturas de pantalla y pérdida del secreto del voto. El voto presencial también cuida el ritual cívico.

Cada TVM tiene tres microprocesadores de diseños distintos, fabricados en fábricas de chips de países rivales (por ejemplo: un chip occidental, uno de diseño abierto hecho en el país, uno de una fábrica asiática no alineada). Los tres calculan la huella digital del voto en paralelo. Si no coinciden bit a bit, la máquina se bloquea y reporta el incidente. Para falsificar un voto, esos países rivales tendrían que conspirar juntos: casi imposible.

Las TVM tienen antenas y routers de baja frecuencia para una red entre terminales: cada máquina se conecta con las vecinas. Cada voto se encripta y viaja en milisegundos a la cadena de bloques nacional.

Al empezar la sesión, tras autenticarte, la TVM te muestra tu nivel de participación (local, federal, ambos o ninguno) y te deja cambiarlo antes de votar. Quien no use la app puede gestionar todo desde la terminal el día de la votación.

Las TVM solo se encienden en jornadas electorales (Trimestrales; Mega Anual, la votación anual grande del ciclo; y Extraordinarias). Fuera de eso están apagadas y custodiadas. Para trámites cívicos el resto del año usas las **Terminales de Módulo Cívico (TMC)** o la app.

#### Verificación diferida por firma de terminal

Al cerrar la jornada, cada TVM imprime **una sola boleta resumen** firmada con su clave única. Esa boleta trae:

- Huella digital agregada de todos los votos de esa terminal.
- Conteo por opción (sin vincular a personas).
- Firma criptográfica verificable.
- Hora y ubicación.

Se deposita en urna sellada. Nunca se imprime el contenido de un voto individual. Ni siquiera el votante recibe comprobante de *su* voto concreto: solo la confirmación de que se registró.

Después, las boletas se escanean y se cruzan con la cadena de bloques. Si los números coinciden con firma válida, la integridad queda verificada. Si no, auditoría inmediata.

Esto da:

- Verificación matemática sin romper el secreto del voto.
- Respaldo físico si la red o la cadena de bloques fallan.
- Privacidad absoluta: solo existe el agregado por terminal.

Si hay interferencia de red, la TVM sigue guardando votos encriptados en local hasta recuperar conexión o emitir la boleta al cierre.

### 2.4 Auditorías Destructivas Internacionales

Cada año se sortea el 1% de las TVM para auditoría destructiva: equipos internacionales rotativos abren los chips con microscopía electrónica. Las máquinas se sacrifican a propósito por la confianza pública. Los hallazgos se publican enteros y obligan a actualizar si hay anomalías.

### 2.5 Diseño Universal y Accesibilidad

Las TVM incluyen conector de audio, audífonos inalámbricos y Text-to-Speech. La interfaz se adapta con voz e iconografía de alto contraste para quien tiene debilidad visual, analfabetismo o límites motrices.

### 2.6 La App Cívica Complementaria

Hay una app oficial gratuita. No permite votar. Sí permite:

- Leer propuestas en el Ágora y respaldar a favor o en contra.
- Ver las Consideraciones de las asambleas deliberativas.
- Recibir avisos de votaciones.
- Acceder a materiales educativos.
- Marcarte disponible (o no) para sorteos de Congreso, asambleas o jurados (también en TMC).
- Configurar tu nivel de participación (también en TMC y en la TVM el día de la votación).
- Pedir tutoría cívica.
- Consultar tu historial.
- Reportar incidencias.

Es código abierto y también se distribuye fuera de tiendas comerciales.

### 2.7 Terminales de Módulo Cívico (TMC)

Las TMC son distintas de las TVM. No pueden emitir voto vinculante, bajo ninguna configuración. Solo sirven para gestión cívica.

Están permanentes en puntos públicos: módulos electorales locales, bibliotecas, centros comunitarios, oficinas municipales. Así quien no usa app ni celular propio sigue teniendo acceso.

Desde una TMC puedes:

- Cambiar tu nivel de participación.
- Marcarte disponible para Congreso, asambleas o jurados.
- Presentar el examen de alfabetización operativa o exámenes de pools técnicos.
- Consultar estado, historial y compensaciones.
- Acceder a materiales educativos y pedir tutoría.
- Reportar incidencias.

La autenticación es más simple (CSC + frase), porque no procesan voto. El hardware es de diseño abierto y con varios fabricantes.

La separación TVM / TMC es constitucional e irreversible. Ningún software puede convertir una TMC en urna.

### 2.8 El Protocolo BIOS (Plan post-colapso)

Si cae la infraestructura eléctrica más de 72 horas (pulso electromagnético, tormenta solar, etc.), el Estado entra en hibernación: Protocolo BIOS. Las TVM tienen jaula de Faraday y paneles solares propios.

El nivel federal se pausa; el poder baja a los municipios. Un Consejo de Supervivencia de 7 ciudadanos locales, elegidos por tómbola física en cada alcaldía, gestiona logística de supervivencia por 12 meses. Si no hay recuperación, los cabildos deciden federación, autonomía o reconstrucción del núcleo nacional (versión propia de soberanía en papel y asamblea).

Es el momento más vulnerable. La tómbola física puede ser tomada por grupos armados. Sin organización comunitaria previa y lealtad cultural al sistema, el Protocolo BIOS no garantiza nada.

---

## Capítulo 3: El Motor Legislativo (Creación y Blindaje de Leyes)

### 3.1 El Ágora Digital

El Ágora es el portal abierto donde cualquier ciudadano activo registra propuestas de ley. Ahí:

- Se vota a favor o en contra; el score visible es la suma neta.
- Está prohibido el “trending” personalizado, la promoción pagada o el feed a la medida. Todos ven lo mismo, en el mismo orden.
- Puedes ordenar por score, fecha, tema o región.
- Cada propuesta necesita un mínimo de respaldos firmados con CSC para pasar a la fase técnica.
- El score marca prioridad: lo más respaldado sube primero al Congreso.

### 3.2 Filtro Constitucional del Tribunal Supremo

Antes de llegar al Congreso, el Tribunal Supremo revisa solo si la propuesta respeta la Constitución, los derechos negativos y la universalidad de las leyes. No juzga si la idea “es buena”; juzga si es válida.

Si es inconstitucional, la regresa con explicación escrita de qué viola y por qué. El autor puede corregirla y reingresarla sin reiniciar el conteo de respaldos.

### 3.3 El Congreso Demárquico

Ya no hay políticos de carrera. Son 500 ciudadanos, mitad y mitad:

- 250 sorteados del padrón general entre quienes se marcaron disponibles (sin examen). Capa de sentido común.
- 250 sorteados del Pool del Congreso: quienes aprobaron el examen de alfabetización operativa y se marcaron disponibles. Capa analítica. El examen se presenta en cualquier TMC, todo el año.

Marcarte disponible es voluntario y revocable. No te obliga a nada hasta que el sorteo caiga en ti.

El Congreso no legisla por ideología: audita procesos y pule propuestas, con apoyo de Abogados Traductores.

### 3.4 El Pool del Congreso y su Examen

Para entrar al pool de los 250 “filtrados” hay que aprobar un examen práctico del propio sistema.

**Qué incluye:** cómo funciona el sistema, derechos constitucionales y negativos, principios deliberativos básicos, leer un presupuesto, detectar falacias, conflicto de interés, Triple Llave, rol del Tribunal, recorte ponderado y cascada de excedentes.

**Qué no incluye:** ideología, doctrina política ni juicios sobre sistemas económicos.

**Anti-exclusión:** gratis, todo el año, ilimitado de intentos, materiales públicos en muchos formatos y en todas las lenguas del país.

**Obligación del Estado:** cursos gratuitos, programas en cárceles para reclusos cumplidos, acompañamiento a quien tenga poca escolaridad formal.

### 3.5 Bancos de Preguntas Competitivos

No hay un solo banco de preguntas. Hay cuatro (A, B, C y D), mantenidos por equipos sorteados distintos que no se comunican entre sí. Cada examen toma 30 preguntas de cada banco (120 en total). Los cuatro son públicos, versionados en GitHub y abiertos a propuestas de cambio en GitHub de cualquiera.

Si un banco está en auditoría, el examen se reparte entre los otros tres. Un banco con muchas impugnaciones exitosas pierde peso hasta resolverse o reemplazarse. Ningún equipo lleva el mismo banco más de dos ciclos seguidos.

Reglas clave:

- Cada pregunta cita fuente verificable.
- Cualquier ciudadano puede impugnar vía app o TMC. Si el 5% del padrón respalda en 30 días, la pregunta se congela y un panel sorteado decide: conservar, modificar o retirar.
- El sistema vigila si dos o más validadores coinciden “demasiado” (por ejemplo >90% en varios ciclos). Eso dispara alerta de posible coordinación; pueden quedar fuera mientras se audita.
- Si una sola escuela concentra >15% de los aprobados de un pool en dos ciclos seguidos, se audita esa institución y las preguntas relacionadas, para evitar que el pool se vuelva club de egresados privilegiados.
- Banco consistentemente impugnado pierde peso.

### 3.6 Pools Técnicos Especializados

Las funciones técnicas las ejercen profesionales sorteados desde pools con examen ciego abierto. Una vez dentro del pool, el puesto concreto también se sortea.

**Pools confirmados:** Judicial, Diplomático, Seguridad Pública (jefes municipales), Abogados Traductores, Auditores Presupuestales, Ciberseguridad, Presidencial, Educación (tutores cívicos de plaza fija).

**Reglas comunes:** umbral alto de examen (75-80% en objetivas), doble ciego en redacción con tres evaluadores, revalidación cada 4-5 años, cooldown mínimo de 8 años tras ejercer, sorteo del puesto desde el pool.

### 3.7 Las Dos Figuras del Traductor

**Figura A: Traductor Personal del Proponente.** asesor uno a uno, asignado por sorteo (tú no lo eliges). Te acompaña desde que entra la iniciativa hasta el voto final. Traduce en vivo lo que pasa en el Congreso a tu lenguaje. Puedes traer además un asesor externo de confianza; si ambos discrepan, se publican las dos lecturas. Se puede recusar por conflicto o incompetencia.

**Figura B: Cuerpo de 5 Traductores del Congreso.** equipo rotativo sorteado del pool, cada uno de una jurisdicción distinta (para no converger ideológicamente). Producen cinco versiones públicas comparables de cada sesión. Con el tiempo construyen un corpus de “legal en lenguaje claro”.

---

### 3.8 Argumentos Críticos Obligatorios

Toda propuesta en el Ágora debe traer una sección de Argumentos Críticos antes de pasar al Tribunal y al Congreso. Es un requisito, no un adorno. Así toda ley llega con sus debilidades ya a la vista.

Los Argumentos Críticos son una colección abierta de razones por las que la propuesta podría estar mal, ser difícil de aplicar, tener efectos no deseados, vacíos legales o mejoras pendientes: un conjunto vivo, no un solo “contra”.

**Quién puede aportar:**

- Cualquier ciudadano con CSC, por app o TMC.
- El propio autor. Identificar tus puntos débiles y publicarlos es madurez, no debilidad.

**Condición de avance:** si tienes respaldo suficiente pero cero argumentos críticos, no avanzas hasta que haya al menos uno. Eso empuja a criticar de verdad.

**En el Congreso:** los Traductores los presentan al inicio. El Congreso no tiene que “resolverlos todos”, pero sí pronunciarse por escrito sobre cada uno: atendido, descartado (y por qué), o limitación no resuelta documentada en la ley.

**Si llegan sin resolver a la votación ciudadana:** aparecen en la TVM marcados como “puntos débiles reconocidos”. Votas con esa información a la vista.

**Calidad:** la comunidad puede respaldar o no cada argumento. Los más útiles suben; los de mala fe bajan. No se borran: se ordenan.

**Fallback:** si una propuesta tiene mucho respaldo pero lleva más de 21 días sin ningún argumento crítico, el sistema genera uno a partir del archivo histórico de críticas similares, marcado como “generado por sistema”. Desbloquea el avance, pero deja claro que faltó crítica humana.

### 3.9 Asambleas Deliberativas Previas

Antes de cada Trimestral o Mega Anual se reúnen asambleas de 100 a 500 ciudadanos por jurisdicción (según el tamaño del lugar). Solo se sortea entre voluntarios inscritos. El algoritmo busca diversidad demográfica, geográfica, etaria y socioeconómica.

Estas asambleas no deciden: deliberan. Escuchan a expertos de todos los lados, discuten días y publican un documento de Consideraciones que aparece en la TVM junto al voto (también en audio). No estás obligado a leerlo; está disponible. Es la forma principal de bajar la carga cognitiva sin meter intermediarios.

Los participantes reciben honorarios (Capítulo 4).

### 3.10 El Veto del Autor

Si en el Congreso le cambian el sentido a tu iniciativa, tienes el Veto del Autor:

- **Total:** retirar y destruir la propuesta antes del voto masivo.
- **Parcial, frase por frase:** marcar segmentos y exigir volver a tu versión o una nueva traducción.

Se ejerce con tu Traductor Personal, para que entiendas cada matiz.

---

## Capítulo 4: Ciclo Electoral, Compensaciones y Protecciones del Ejercicio Cívico

### 4.1 Ciclo Anual de Votaciones

Cuatro votaciones regulares al año, más Extraordinarias si hace falta:

- **3 Asambleas Trimestrales** (marzo, junio, septiembre): ajustes, cambios presupuestales chicos, retoques a leyes en marcha, lo local-local.
- **1 Mega Asamblea Anual** (diciembre): leyes mayores, tratados, presupuesto del año siguiente, reformas grandes.
- **Votaciones Extraordinarias:** urgencias que no pueden esperar.

### 4.2 Clasificación de Propuestas

Tras pulir, el Congreso clasifica por mayoría simple:

- **Menor** → próxima Trimestral.
- **Estructural** → Mega Anual.
- **Urgente** → Extraordinaria.

Se publica con justificación. Cualquier ciudadano puede impugnar vía Ágora: 1% del padrón en 14 días obliga a revisar; 5% sube automáticamente la clasificación un nivel.

### 4.3 Plazos Mínimos

- **Trimestrales y Mega Anual:** mínimo 30 días desde el texto final hasta el voto (tiempo para deliberar, traducir, leer e impugnar).
- **Extraordinarias:** mínimo 21 días.
- **Excepción:** tratados con plazo impuesto por la contraparte → mínimo 10 días.

### 4.4 Activación de Extraordinarias

Dos vías:

- El Congreso clasifica como urgente (mayoría simple, justificación impugnable).
- La ciudadanía junta 3% del padrón en 30 días en el Ágora.

Una sola propuesta por convocatoria. No se cuelan otras “de relleno”.

### 4.5 Tope de Propuestas por Boleta

- Trimestral: máximo 15-20.
- Mega Anual: máximo 25-30 estructurales.
- Extraordinaria: una.

Si hay más listas que cupo, suben las de mayor score; el resto espera.

### 4.6 Interfaz de Acordeón

En la TVM puedes:

- Validar el presupuesto general de un solo golpe (Paquete Maestro), o
- Desglosar y aprobar o rechazar sectores por separado (Defensa, Salud, Infraestructura, etc.).

Ambos modos son soberanía directa: ninguno delega el voto.

### 4.7 Abstención sin Penalización ni Cómputo

Votar es derecho, no obligación. Si no entiendes un tema o no quieres decidirlo, no votes en ese punto. Tu abstención no cuenta como sí ni como no. Solo cuentan los votos emitidos.

Cada decisión la toman quienes sí se sintieron listos para votarla, directo y sin intermediarios. Baja la fatiga sin abrir la puerta a “representantes”.

### 4.8 No Delegación

No existe delegación de voto bajo ningún esquema. No se transfiere, no se presta, no se acumula, no se vende. Aceptamos la fatiga residual a cambio de cerrar la puerta a carreras políticas por acumulación de seguidores.

### 4.9 Blindaje Laboral del Ejercicio Cívico

Votar, deliberar, servir en Congreso o jurado, o participar en asamblea escolar es derecho constitucionalmente protegido.

- El patrón debe permitir la ausencia con aviso mínimo de 48 horas (en sorteos puede ser menos).
- El patrón no paga esas horas: las cubre el Estado.
- Prohibido despedir, sancionar, quitar bonos, dañar evaluaciones, reducir horas o cualquier represalia.
- Represalia documentada = delito grave, con sanción automática: indemnización de 12 meses al trabajador y multa al patrón al fondo público.
- Conservas puesto, antigüedad y prestaciones como si no hubieras faltado.

### 4.10 Compensaciones por Ejercicio Cívico

Esto es pago por servicio democrático, distinto de un salario mínimo económico del mercado laboral.

**Voto regular en TVM:** el Estado paga el 20% del salario promedio nacional o de tu salario, lo que sea mayor, por jornada. Transferencia automática al autenticarte.

**Trabajo cívico extendido** (asambleas deliberativas, Congreso, jurados): 10% del salario promedio nacional por hora. Una semana cívica vale varias semanas de salario promedio.

**Piso absoluto:** al menos el equivalente a una canasta básica nacional por jornada (indexable a inflación y zona). Si el porcentaje da menos, se paga el piso. Protege a informales, desempleados, jubilados, estudiantes y quien vive en precariedad.

Aplica a formal, informal, autoempleado, desempleado activo, jubilado y estudiante en edad de voto.

---

## Capítulo 5: El Motor Financiero (Control Absoluto del Dinero)

### 5.1 Recorte Ponderado con Punto de Quiebre

Cada partida del presupuesto trae un punto de quiebre: el porcentaje bajo el cual el programa deja de ser operable. Lo calcula el Pool de Auditores Presupuestales.

- Si el pueblo vota un recorte por debajo del punto de quiebre → se recorta el gasto discrecional en proporción.
- Si el recorte supera el punto de quiebre → el programa se cancela entero y el 100% va a la Cascada de Excedentes.
- Ves esa información antes de confirmar el voto.

La metodología del punto de quiebre es pública e impugnable.

### 5.2 Ruido Aleatorio en Umbrales (Anti-trampa)

Cada trimestre, los umbrales del punto de quiebre se mueven al azar ±5% sin aviso. Así la burocracia no puede “optimizar” métricas justo por encima del corte para sobrevivir.

### 5.3 Freno de emergencia con jurado físico

Si una métrica automática dispara la cancelación de algo crítico (Filtro 3), se activa un freno: 100 ciudadanos locales sorteados van a ver las instalaciones o servicios en persona. Pueden vetar la decisión del tablero automático si la realidad contradice los números. Nada de gobernar solo por pantallas.

### 5.4 Algoritmo de Prelación de Recortes

| Filtro | Qué toca | Qué hace |
|--------|----------|----------|
| 0 | Recorte cruzado | Primero eliminar duplicidades entre ministerios. |
| 1 | Grasa burocrática | Bonos extras, subidas salariales sobre inflación, cajas VIP, seguros médicos de alta burocracia: se absorben al 100%. |
| 2 | Gasto de vanidad | Viáticos internacionales, flotillas nuevas, remodelación de oficinas, publicidad oficial: se cancelan. |
| 3 | Diferir obra | Solo si lo anterior ya está en cero. Pausar infraestructura nueva no prioritaria. Activa el freno de emergencia con jurado físico. |

**Gasto Fijo Operativo intocable** (seis partidas; coherente con el Cap. 5A):

1. **Justicia operativa:** jueces y equipos sorteados en funciones (no burocracia VIP).
2. **Seguridad:** policías operativos / seguridad local.
3. **Defensa en aislamiento operativo:** fuerzas armadas con misión y alcance acotados.
4. **Infraestructura de soberanía:** TVM, CSC, auditoría, red entre terminales, boleta física.
5. **División de Desastres:** capacidad operativa (no clientela).
6. **Créditos universales del paquete:** voucher educativo + prima mínima del seguro (catastrófico y enfermedades transmisibles), pagados a instituciones y aseguradoras. El monto lo ajusta el pueblo en la Mega Anual; la burocracia sola no lo tumba.

Todo lo demás es gasto condicionado: entra al recorte, a las cláusulas de caducidad y a las métricas anti-trampa.

### 5.5 Prohibición de Decisiones Automáticas con una Sola Métrica

Ninguna política grande puede depender de un solo número. Toda asignación importante necesita métricas múltiples, auditoría humana adversarial y evaluación ciudadana. Los algoritmos solo recomiendan; la decisión final es humana (sorteada o votada).

### 5.6 Redundancia Conflictiva de Métricas

Se usan indicadores que chocan a propósito. Si optimizas uno, otro empeora. Eso evita “mejorar” una cifra a costa de todo lo demás. Ejemplo: eficiencia de gasto vs. cobertura territorial vs. calidad vs. tiempos de respuesta.

### 5.7 Auditoría anual anti-trampa de métricas

*(Cuando una métrica se vuelve el objetivo, deja de medir bien lo que importaba. Aquí se audita esa trampa.)*

Cada año los Auditores publican un análisis de métricas manipuladas (por ejemplo: etiquetar grasa burocrática como “gasto esencial”). Si hay manipulación documentada, recorte automático extra del 10% al ministerio infractor.

### 5.8 Cláusulas de Caducidad

Toda política grande caduca sola en N años si no demuestra resultados según métricas acordadas de antemano. Para extenderla hace falta nueva votación ciudadana con evaluación pública de impacto.

### 5.9 Cascada de Excedentes de Soberanía

El dinero que sobra de los recortes se reparte por reglas de pago automáticas inalterables:

1. **Alpha, Bóveda de Resiliencia (30%):** reserva líquida para desastres y protección civil. Tope: 2% del PIB. Si se llena, rebosa a la siguiente.
2. **Beta, Amortización de Deuda (40%):** pago de capital de la deuda con mayor tasa.
3. **Gamma, Fondo de Inversión Soberano (30% + rebose de Alpha):** fondo global de propiedad nacional (modelo Noruega) para pensiones de largo plazo. No presta ni capitaliza amigos del poder.

---

## Capítulo 5A: Economía y Régimen de Propiedad

*Este capítulo cierra, en el tronco, la economía y el régimen de edu/salud (antes abiertos como 10.12 y 10.11).*

### 5A.0 Principio rector

1. La propiedad privada es la regla; la propiedad estatal es la excepción temporal y justificada.
2. El Estado no dirige la economía; protege contratos, personas y propiedad, y financia solo lo que el pueblo autoriza bajo el motor del Cap. 5.
3. Ninguna empresa o asociación captura el fisco ni la política (coherente con Cap. 6): el capital organizado no compra leyes.

Esto es minarquía con demarquía: mercado libre + Estado delgado sorteado + presupuesto bajo cuchillo popular.

### 5A.1 Régimen de propiedad

**Propiedad privada.** Toda persona física y moral puede adquirir, usar, transferir y heredar bienes lícitos. El título se registra en un sistema público auditable. Se permite pluralidad de registradores certificados bajo estándares universales; no hace falta un monopolio estatal único de registros.

**Expropiación.** Solo por ley de aplicación universal, con compensación a valor de mercado independiente, plazo corto y recurso judicial. Si toca el código base de derechos negativos, exige Triple Llave. Prohibidas las expropiaciones por identidad, clase, sector o “interés estratégico” indefinido.

**Bienes comunes y naturales.** Recursos no apropiables por ocupación pacífica (aire, cuencas críticas, espectro de uso público) se rigen por reglas universales de uso, no por nacionalización automática de industrias. Concesiones temporales, subastas transparentes, caducidad obligatoria.

**Sin topes a la acumulación.** La minarquía no castiga el éxito. No hay techos patrimoniales ni impuestos confiscatorios al stock. La contención del poder económico se hace por: (a) prohibición de financiar política con capital de personas morales, (b) leyes universales antirust solo contra coerción, fraude o monopsonio coercitivo demostrado, (c) transparencia de contratos con el Estado. No por redistribución patrimonial forzada.

### 5A.2 Impuestos (mal necesario acotado)

El impuesto existe solo para financiar el núcleo minárquico y los servicios que el pueblo mantenga vivos vía Cap. 5. No sirve de herramienta de ingeniería social ni de igualdad de resultados.

**Gasto fijo operativo:** las seis partidas del Cap. 5.4. Todo lo demás es gasto condicionado.

**Forma tributaria preferida.** Pocas bases, universales, predecibles. Preferencia por impuestos al consumo, uso de suelo o externalidades medibles sobre impuestos a la renta del trabajo o al capital productivo, salvo que el pueblo vote lo contrario en Mega Anual con Argumentos Críticos. Prohibido: impuesto retroactivo; impuesto por identidad; tasas punitivas a sectores nombrados.

**Opt-Out cívico.** Quien ejerce Opt-Out cívico sigue pagando impuestos (1.8). La protección de derechos negativos tiene costo fiscal; la secesión fiscal queda fuera del tronco.

**Meta y techo fiscal (clavado).**

- **Meta operativa:** la carga total del Estado apunta a ≤ 15% del PIB. Cada Mega Anual publica la carga real, la brecha respecto a la meta y el mapa de prelación; el motor del Cap. 5 empuja hacia esa meta.
- **Techo duro constitucional:** 20% del PIB. Superarlo no se decide en una Mega ordinaria: exige Triple Llave (Congreso Demárquico + TSC + 75% de votación popular directa).
- Por debajo del techo, el pueblo puede subir o bajar gasto vía Cap. 5; el 20% es el muro anti-Leviatán.

### 5A.3 Empresas y “lo estratégico”

Crear o mantener empresa pública exige: ley universal, caducidad ≤ N años, métricas públicas y reautorización ciudadana. Sin reautorización, liquidación o privatización competitiva.

**Prohibido:** monopolios estatales permanentes en sectores competitivos (comercio, banca minorista, manufactura, medios).

**Excepción estrecha:** redes naturales de difícil rivalidad (cierta infraestructura de malla) pueden quedar bajo concesión regulada o propiedad pública temporal, siempre con caducidad y auditoría. “Estratégico” no basta por sí solo.

### 5A.4 Banca, moneda y crédito

**Banca privada libre** de entrar y salir bajo reglas universales de solvencia transparente y anti-fraude, sin privilegios ni licencias-casta.

**Prohibido** el crédito dirigido a campeones nacionales, sectores amigos o banca de desarrollo clientelar.

**Rescates** de personas morales con dinero público o expansión monetaria: prohibidos, salvo desastre sistémico declarado bajo División de Desastres + ratificación popular en 72 h.

**Seguro de depósitos acotado** con prima (no garantía ilimitada que socializa pérdidas). El tope exacto lo fija la Mega Anual dentro del techo 15/20.

**Fondo Gamma** (Cascada, Cap. 5.9): reserva/pensiones de largo plazo; no presta ni capitaliza amigos del poder.

**Crédito entre privados:** libre. El tronco no fija techos mágicos de tasas; fraude, violencia y dolo sí son delito.

**Moneda (régimen A+).**

- **Unidad fiscal:** el peso (u homólogo local en versiones regionales) es la unidad de curso legal para impuestos, contabilidad del Estado y medición de la carga vs. PIB (meta 15% / techo 20%).
- **Regla dura de emisión:** parámetros públicos auditables; expansión de emergencia solo con declaración bajo División de Desastres + ratificación popular en 72 h. Prohibidos los rescates clientelares con expansión monetaria o fiscal.
- **Libertad monetaria privada:** personas físicas y morales pueden contratar, ahorrar y pagar entre sí en cualquier moneda, cripto o trueque. El Estado no prohíbe ni impone medios privados de pago.
- **Interoperabilidad:** obligaciones fiscales se liquidan en pesos (o equivalencia transparente al tipo publicado); anti-fraude sin vigilancia masiva del patrimonio privado.
- Una versión propia de competencia fiscal total (impuestos en N monedas) queda fuera del tronco: pelea con el techo 15/20.

### 5A.5 Mercados, trabajo y regulación

**Libertad contractual.** Contratos entre adultos capaces son válidos; el Estado no “mejora” el contenido salvo dolo, violencia, fraude o incapacidad.

**Regulación.** Solo reglas universales (seguridad mínima medible, externalidades, información). Prohibidas las licencias que crean castas gremiales sin evidencia de daño. Toda licencia profesional entra a caducidad y revisión anti-trampa de métricas.

**Trabajo.** Libertad de asociación laboral (coherente con 1.1). El Estado no fija precios ni salarios del mercado. El salario mínimo económico queda fuera del tronco; si el pueblo lo quiere, debe aprobarlo como ley universal ordinaria (1.2), no como supuesto constitucional. Sí permanece la compensación cívica del Cap. 4 (pago por servicio democrático: voto/trabajo extendido), que es otra cosa.

El blindaje laboral cívico del Cap. 4 se mantiene: protege el ejercicio del voto, no al proteccionismo industrial.

### 5A.6 Redistribución

La minarquía admite transferencias acotadas y rechaza la redistribución como fin.

- Asignaciones focalizadas **permitidas** solo bajo 1.2: criterio objetivo, temporal, universalmente accesible (ej. capacidad funcional < X%).
- Prohibidas las transferencias por identidad, voto, afiliación o “reparación” indefinida.
- El Fondo Gamma es reserva intertemporal bajo reglas de cascada, no un cheque clientelar.

### 5A.7 Salud y educación (cierra 10.11)

**Principio.** El Estado no opera escuelas ni hospitales. Financia créditos universales; la prestación es privada y competitiva. Todo cuenta contra la meta 15% / techo 20% del PIB.

**Educación (voucher).**

- Crédito/voucher universal orientado al menor (y a alfabetización de adultos bajo criterio 1.2 si el pueblo lo mantiene).
- Los padres (o tutores) eligen la institución. El Estado paga directamente a la institución contra el voucher, nunca en efectivo a la familia.
- Condiciones de pago: **matrícula activa** en proveedor registrado + evidencia periódica de que el servicio se está prestando (asistencia y/o progreso verificable respecto al piso de lectoescritura/numeracy + capa cívica del Cap. 8). Sin matrícula/servicio verificable, no hay desembolso.
- **Portabilidad:** en cualquier momento los padres pueden retirar al menor y asignar el voucher a otra institución; el financiamiento sigue al estudiante y no crea plaza cautiva.
- Sin monopolio curricular estatal ni universidad estatal de tronco.

**Salud (seguro en competencia).**

- Crédito universal a prima de seguros privados que compiten.
- La persona elige aseguradora. El Estado paga directamente a la aseguradora el crédito; no deposita el valor en el bolsillo del asegurado (salvo el opt-out fiscal del 80%).
- Condiciones de pago: póliza activa válida del paquete mínimo + evidencia de cobertura vigente. Sin póliza activa, no hay desembolso del crédito (salvo opt-out).
- **Portabilidad total:** se puede cambiar de aseguradora en cualquier momento; el crédito sigue a la persona y no crea cliente cautivo.
- El paquete mínimo de tronco prioriza **cobertura catastrófica + enfermedades transmisibles / externalidades sanitarias**. Lo rutinario tiende al mercado y a planes voluntarios por encima del mínimo.
- El Estado no es dueño de la red hospitalaria.

**Opt-out del beneficio (≠ Opt-Out cívico 1.8).**

- Cualquier adulto puede renunciar al crédito de seguro de salud (y, en su caso, a créditos educativos propios, no al del menor a cargo) y recibir rebaja fiscal del 80% del valor del crédito. El 20% restante financia administración y colchón de selección adversa del pool.
- Solo recuperas el valor del beneficio rechazado; no hay secesión fiscal general.
- Sigue vigente la ley, los impuestos del núcleo minárquico y el techo 15/20.

**Focalización extra (1.2).** Apoyos adicionales solo por criterio objetivo, temporal y universalmente accesible, nunca por identidad.

### 5A.8 Relación con el Cap. 5

Este capítulo justifica el motor financiero; no lo sustituye:

| Pieza Cap. 5 | Lectura minárquica |
|--------------|-------------------|
| Recorte ponderado | El pueblo encoge el Estado |
| Punto de quiebre + ruido | Anti-burocracia, no anti-mercado |
| Gasto fijo operativo | Núcleo de protección + infra cívica |
| Cascada Alpha/Beta/Gamma | Resiliencia, no deuda eterna, no clientelismo |
| Caducidad + anti-trampa de métricas | Toda política pública es sospechosa hasta prueba |

### 5A.9 Qué queda fuera (versiones propias)

- Abolición de impuestos / defensa privada pura → versión propia con otro énfasis (más minimalista); fuera del tronco.
- Nacionalización amplia / planificación / topes patrimoniales → versión propia no-minárquica (debe renunciar a este capítulo).
- Renta básica universal sin criterio 1.2 → requiere Triple Llave si se constitucionaliza; queda fuera del default.

### 5A.10 Qué queda cerrado en el tronco (edu/salud y economía)

> **Cerrado en tronco (minarquía):** propiedad privada por defecto, sin topes de acumulación, impuestos acotados al núcleo + gasto condicionado, empresas públicas bajo caducidad, no rescates clientelares, regulación universal, salud/educación vía voucher + seguro competitivo con opt-out fiscal, banca libre sin rescates con depósitos acotados.  
> **Clavado:** meta 15% PIB / techo duro 20% PIB (Triple Llave).  
> **Clavado:** régimen A+ (peso como unidad fiscal con regla dura + libertad monetaria privada).  
> **Clavado:** salario mínimo económico fuera del tronco (compensación cívica Cap. 4 sí).  
> **Clavado:** edu/salud (voucher + seguro competitivo + opt-out con rebaja 80%/20% al pool).  
> **Clavado:** banca libre + sin rescates + depósitos acotados + Gamma limpio.  
> **Clavado:** gasto fijo operativo en 6 partidas.  
> **Parámetro abierto:** tope numérico del seguro de depósitos (Mega Anual).

---

## Capítulo 6: Justicia, Seguridad y Defensa Cognitiva

### 6.1 Justicia Dinámica

Los juzgados de primera instancia operan bajo Justicia Dinámica.

- Casos simples (faltas, procedimientos menores): el juez se sortea del Pool Judicial la misma mañana de la audiencia. Así no hay tiempo de sobornar con anticipación.
- Casos complejos (fraude grande, crimen organizado, evasión estructurada): el sorteo es 30 a 90 días antes. Al juez se le asigna un equipo técnico también sorteado, que rota con él. Se elimina el personal burocrático permanente del juzgado. Los registros se auditan en tiempo real por software que detecta anomalías.

### 6.2 Ejército en aislamiento operativo

Para evitar golpes de Estado, las Fuerzas Armadas viven en aislamiento operativo: misión limitada a defensa de fronteras y control técnico de ciberseguridad nacional. No pueden movilizar tropas internas sin autorización explícita de una Asamblea de Emergencia ratificada por el pueblo.

### 6.3 Separación de Capacidades Coercitivas

Ninguna fuerza armada o policial controla a la vez las cuatro capacidades críticas: inteligencia, logística, armamento pesado y comunicaciones. Cada una la ejerce una estructura independiente, con mando rotativo sorteado del Pool de Seguridad.

- Rotación territorial obligatoria: ningún mando más de 2 años en la misma jurisdicción.
- Supervisión cruzada civil: comités de ciudadanos sorteados supervisan operaciones con acceso a información clasificada bajo juramento.

### 6.4 Seguridad Local Modular

Policías municipales con jefes sorteados del Pool de Seguridad Pública. Financiamiento aprobado en Asambleas Trimestrales por vecinos. Revocación inmediata activable por la comunidad si se documentan abusos.

### 6.5 Honestidad sobre la Violencia Última

El sistema no resuelve del todo el problema de la violencia como poder último. Si las fuerzas se alinean unánimemente contra el sistema o las captura un actor externo, no hay mecanismo constitucional que lo impida. La viabilidad última depende de:

- Lealtad cultural cultivada entre fuerzas de seguridad.
- Modo Resistencia con versiones municipales en papel si cae la infra digital.
- Defensa civil distribuida y arraigada en comunidad.

No se diseña milicia armada distribuida (riesgo de señores de la guerra). Se acepta depender en parte de cultura y lealtad institucional.

### 6.6 Defensa Cognitiva

**Modo Ciego opcional en TVM:** ves propuestas sin nombres de autores, partidos legacy ni métricas sociales. Decides sobre el contenido, no sobre marcas.

**Registro Público de Influencia Política:** quien alcance umbral de difusión política masiva debe registrar financiamiento, automatización, segmentación y datos de entrenamiento si usa inteligencia artificial (IA). Información auditable.

**Etiquetado obligatorio de contenido IA:** todo contenido político generado o asistido por IA debe etiquetarse. Las plataformas que operan en el territorio responden por incumplimiento con multas automáticas.

**Latencia democrática:** mínimo 30 días de exposición pública entre publicación y voto vinculante (ya en Cap. 4). Protege contra pánicos morales de 48 horas.

**Equipos que buscan fallas a propósito, permanentes:** financiados constitucionalmente. Intentan manipular Ágora, votaciones, pools y exámenes para revelar huecos antes que lo hagan actores hostiles. Publican hallazgos.

Esto no detiene por completo la manipulación memética. Influencia extranjera, iglesias, redes familiares y plataformas externas seguirán moldeando opinión. Es defensa de daños, no vacuna total.

### 6.7 Financiamiento político: personas físicas vs. personas morales

La libertad de expresión política es derecho negativo absoluto de toda persona física. Cualquier ciudadano (activo o en Opt-Out) puede:

- Expresar opiniones en cualquier medio.
- Militar ideas, ideologías o críticas.
- Financiar con su patrimonio personal la difusión de sus ideas o las de otros.
- Organizar movimientos.
- Publicar o pagar publicación ajena.
- Donar a campañas de ideas, propuestas, candidatos a pools o iniciativas del Ágora.
- Participar en redes, asambleas informales y cualquier asociación voluntaria.

**Restricción a personas morales** (empresas, corporaciones, sindicatos, ONGs, fundaciones, asociaciones civiles, partidos legacy, iglesias como entidades legales): no pueden financiar contenido político, campañas, propaganda, propuestas del Ágora ni publicidad de candidatos a pools o presidencia.

Motivo: las personas morales agregan capital de muchos individuos para fines específicos; desviar ese capital hacia influencia política distorsiona la voluntad de quienes lo aportaron.

Las personas físicas vinculadas (dueños, directivos, miembros, fieles) conservan su derecho individual a financiar política con patrimonio personal separado. La multa por incumplimiento va al fondo público; no cae sobre quien actuó a título personal.

### 6.8 Asociaciones y partidos

Cualquier grupo puede organizarse libremente: asociación, movimiento, partido, colectivo. Sin tope de número, tamaño, ideología ni estructura interna.

**Financiamiento:** solo aportaciones voluntarias de personas físicas. Nada de personas morales.

**Uso de recursos:** solo gastos operativos e ideológicos propios (sueldos internos, publicidad de sus ideas, eventos, oficinas, publicación, campaña de ideas en el Ágora).

**Prohibición de transferir recursos hacia afuera:** no a ciudadanos del Ágora, no a candidatos a pools, no a otras organizaciones, no a publicidad de personas específicas.

Una asociación es un vehículo de ideas, no un intermediario financiero. Puede hablar con su propia voz y su propio dinero. No puede prestar esa voz ni ese dinero a nadie más.

Cada miembro conserva su derecho individual a destinar su patrimonio personal. El incumplimiento genera multa proporcional + sanción al fondo público.

---

## Capítulo 7: Representación Exterior y Gestión de Emergencias

### 7.1 El Presidente (sin poder ejecutivo)

Función: rostro del país hacia el mundo. Diplomacia ceremonial, comunicación, representación. El poder real está en el Congreso Demárquico, los pools técnicos y el voto popular.

**Acceso al Pool Presidencial:** profesionales de cualquier pool técnico pueden aplicar con examen adicional: conocimientos generales, relaciones internacionales, comunicación pública, protocolo, al menos dos idiomas (inglés más uno adicional).

**Mandato:** 3 años, máximo dos consecutivos. La reelección requiere ratificación popular al final del primero. Si pierde, sale del pool presidencial de forma permanente. Valoración a mitad de mandato (mes 18) con posibilidad de revocación.

**Puede:** representar al país, transmitir mensajes del Congreso, diplomacia básica, declaraciones de calma o condolencia.

**No puede:** dar opiniones personales (solo representa), aprobar tratados sustantivos sin Congreso y voto popular, ni ejercer poder ejecutivo sobre pools o presupuesto.

**Emergencias:** puede declarar Estado de Emergencia y activar la División de Desastres. En 72 horas el Congreso debe ratificar o rechazar y llevar a votación popular.

Tras el mandato: regresa a su pool técnico original. Nunca vuelve a Presidencia. Si es destituido: sale del Pool Presidencial; para volver a su pool de origen debe re-presentar examen (tres oportunidades). Si las tres fallan, queda fuera de todos los pools.

### 7.2 División de Desastres

División permanente con personal técnico de pools especializados (logística, ingeniería de emergencias, salud pública, comunicaciones, seguridad).

**Declaración del Estado de Emergencia:**

- Vía 1: Congreso por unanimidad de los 500.
- Vía 2: Presidente declara, División activa, Congreso ratifica en 72 horas o va a voto popular inmediato.
- Vía 3: División declara emergencia provisional (válida 72 horas) si más del 30% del Congreso está incapacitado. Sin ratificación, termina sola.

**Durante la emergencia:** poder de coordinación y asignación de recursos, no de mando directo sobre dependencias. Despliegue logístico del Ejército, recursos extraordinarios, contratos ágiles con proveedores validados.

**Límites absolutos:** no puede suspender derechos negativos; no cancelar Congreso ni Ágora; no modificar Constitución; no intervenir el sistema electoral; no censurar comunicación entre ciudadanos.

Revisión cada 30 días con voto popular de ratificación o terminación. Sin revisión periódica, la emergencia termina sola.

Post-emergencia: auditoría completa. Abuso documentado → proceso ante Tribunal Supremo: destitución, salida permanente del pool, inhabilitación, juicio penal.

### 7.3 Diplomacia Híbrida

**Gestión técnica autónoma:** acuerdos rutinarios, trámites consulares y convenios menores los ejecuta el Cuerpo Diplomático (Pool Diplomático) bajo auditoría ordinaria. El Presidente da la cara; no compromete unilateralmente.

**Ratificación popular obligatoria:** tratados comerciales grandes, convenios bilaterales de seguridad, declaraciones de neutralidad o conflicto pasan por las TVM en Mega Anual o Extraordinaria (mínimo 10 días si la contraparte impone plazos). Ningún tratado importante se firma sin voto popular.

---

## Capítulo 8: Educación Cívica y Tutoría

### 8.1 Educación cívica permanente sin examen

El Estado tiene obligación activa de producir y mantener materiales sobre el sistema:

- Gratuitos, públicos y de código abierto.
- En múltiples formatos: escrito, audio, video, lenguaje sencillo, lenguas indígenas, lenguas extranjeras relevantes.
- Sin examen, sin certificado, sin requisito. Cualquier ciudadano accede cuando quiera.

Quien quiera aprender aprende. Quien no quiera, no. Quien quiera ser tutor se ofrece. La alfabetización cívica crece de forma orgánica y voluntaria.

Aceptamos que algunos ciudadanos nunca se informarán bien y votarán mal informados. Ese es el precio de la libertad real, preferible a crear filtros que excluyen.

### 8.2 Tutores Cívicos Voluntarios (Nivel 1)

Cualquier ciudadano puede inscribirse como tutor cívico voluntario en la app, declarando temas y disponibilidad.

- Los aprendices solicitan tutoría por tema.
- El sistema empareja por sorteo, no por elección, con prohibición de asignar familiares directos o personas con historial previo de interacción.
- Cada sesión se registra cuando ambas partes confirman.
- Compensación: tarifa cívica por hora alineada al trabajo cívico extendido del Cap. 4 (10% del salario promedio nacional por hora), vía contrato automático. *(Distinto del salario mínimo económico del mercado.)*
- Tope semanal de horas compensadas por persona, para que no se vuelva ingreso principal.
- El aprendiz evalúa la sesión. Tutores con baja evaluación promedio pierden la opción hasta revalidación.
- Auditoría aleatoria contra sesiones fantasma o fraude.
- Hasta tres reasignaciones al año por incompatibilidad.

### 8.3 Tutores Cívicos Plaza Fija (Nivel 2)

Tutores Nivel 1 con evaluación promedio alta (arriba de 4.5/5) durante 100 sesiones evaluadas o 12 meses pueden postularse a plaza fija.

- La plaza se otorga por sorteo entre los calificados, no por selección discrecional.
- Salario completo de funcionario equivalente a maestro o técnico medio del Estado, con prestaciones.
- Si el promedio baja de 3.5/5 durante 6 meses seguidos, pierde la plaza automática. Puede regresar a Nivel 1 sin castigo.
- Tope estructural: máximo 1 tutor Nivel 2 fijo por cada 10,000 ciudadanos activos.

Así la alfabetización cívica deja de ser solo tarea del Estado y se vuelve trabajo cooperativo de la sociedad consigo misma.

---

## Capítulo 9: Seguridad Asimétrica y Plan de Transición

### 9.1 Resistencia a la Coacción Asimétrica

Tres mecanismos contra monopolios armados locales (carteles, mafias):

**Frase de coacción:** si te fuerzan a votar bajo amenaza, ingresas la frase mental en su versión preconfigurada de coacción. La TVM muestra “Voto registrado con éxito” (te protege), pero el voto se anula en silencio en la cadena de bloques y se emite un reporte geolocalizado encriptado al Comando de Seguridad.

**Triple factor:** credencial + biometría + frase mental a la vez. Robar tarjeta y dedo no basta sin la frase consciente.

**Inanición económica del crimen:** sin alcaldes ni diputados que muevan presupuesto a mano, no hay intermediarios a quienes extorsionar para adjudicar contratos. Pagos vía contratos automáticos directos a proveedores validados: se reduce el incentivo financiero del control territorial delictivo.

### 9.2 Tres escenarios realistas de transición

La implementación pacífica desde un Estado consolidado y polarizado es altamente improbable. Los escenarios realistas son tres:

**Escenario A: Estado paralelo gradual.** En sociedades con instituciones funcionales y baja violencia se avanza por capas hacia una república demárquica a escala nacional: primero opinión pública y normas voluntarias; después soberanía parcial donde un estado, región o zona adopte el núcleo del manifiesto como cabeza de playa; más adelante el salto constitucional. En el camino caben presupuesto participativo, arbitraje ciudadano, auditoría pública y votaciones no vinculantes, a veces a escala local como módulo técnico del proyecto nacional. Se escala solo cuando baja la corrupción medible y crece la legitimidad, sin confrontación armada y sin intentar controlar ejército ni policía en fases tempranas. El plan de adopción nacional en capas desarrolla este camino.

**Escenario B: Pacto con élites legacy.** Élites tradicionales aceptan transición negociada a cambio de “paracaídas dorado”: amnistía local, inmunidad de tránsito, protección de activos legales, espacio ceremonial sin poder presupuestal por un periodo acordado. La transición es real; los actores existentes no se destruyen. Modelos históricos: España post-franquismo, Sudáfrica post-apartheid.

**Escenario C: Post-colapso.** Territorios donde el Estado tradicional ya falló (post-guerra, post-crisis terminal, post-catástrofe). El sistema funciona como reinicio cívico desde cero. Requiere capacidad técnica y voluntad comunitaria. Modelos: democracias post-WWII, post-dictaduras latinoamericanas.

### 9.3 Costo histórico de implementación

Implementar este sistema mediante reemplazo total y rápido de un Estado grande consolidado no tiene precedente histórico pacífico. Toda transición sistémica grande tuvo costo de violencia organizada.

Este manifiesto no promueve la violencia y tampoco oculta que ese ha sido históricamente el precio de un reemplazo sistémico. La decisión de pagarlo o no le corresponde a cada pueblo, no a este documento. Cualquier pueblo, en cualquier momento, puede legítimamente decidir reclamar su soberanía. Demarquía Digital se ofrece como herramienta para ese momento, sea pacífico o no.

---

## Capítulo 10: Modelado de Amenazas e Issues Abiertos

Esta sección documenta problemas no resueltos. Su publicación abierta es deliberada: invita a contribuciones específicas.

### 10.1 Complejidad Computacional Institucional

El sistema introduce verificación criptográfica, auditorías, jurados aleatorios, métricas dinámicas, transparencia total, rotación continua. Puede superar la capacidad de cualquier Estado real. Riesgo: colapso por complejidad, dependencia extrema de expertos, errores emergentes, imposibilidad de auditoría completa, parálisis administrativa.

### 10.2 Tiranía de los mantenedores centrales del repositorio

El manifiesto vive en GitHub y evoluciona por propuestas de cambio. Alguien tiene permisos finales para incorporar cambios. Si los mantenedores se corrompen o secuestran, controlan el Estado. Requiere gobernanza del repositorio (ver Cap. 11.5; sigue abierto).

### 10.3 Escalabilidad Nacional y Fragmentación Regulatoria

En países grandes con diversidad regional, la aplicación local desigual de leyes nacionales puede generar inconsistencia masiva. El federalismo radical es ventaja en autonomía y riesgo en coherencia.

### 10.4 Captura por IA Avanzada en el Ágora

Generación industrial de propuestas y argumentos por IA que supera la capacidad humana de revisión. Tema emergente sin diseño concreto aún.

### 10.5 Captura del Pool de Auditores Presupuestales

Quien controla el cálculo del punto de quiebre controla efectivamente el gasto. Mitigaciones (doble certificación, metodología abierta, impugnación, ruido aleatorio) reducen pero no eliminan.

### 10.6 Riesgo de Hardware Residual

Aún con triple chip, fábricas en países rivales, papel paralelo y auditorías destructivas, ataques coordinados a la cadena de suministro a escala estatal siguen siendo riesgo.

### 10.7 Conflictos Transfronterizos

Cómo opera Demarquía Digital cuando es minoría en un mundo de Estados tradicionales. Tratados, conflictos comerciales, extradiciones. Sin desarrollar.

### 10.8 Discapacidad Cognitiva Severa

Quién decide cuándo una persona no puede ejercer voto autónomamente. Cómo prevenir abuso tutelar. Sin diseño.

### 10.9 Verificación Digna de Criterios Objetivos

Para leyes universales con criterio objetivo: protocolos concretos de verificación que no sean vigilancia social ni humillación burocrática. Pendiente.

### 10.10 Sistema Penal y Filosofía de la Justicia

Tema grande no desarrollado: filosofía del castigo, sistema penitenciario, justicia restaurativa, garantías procesales detalladas, libertad condicional, reinserción.

### 10.11 Educación, Salud y Sistemas Públicos (cerrado en tronco, v0.4)

> Ver Cap. 5A.7: el Estado no opera escuelas ni hospitales; financia voucher educativo (pago a institución + matrícula + evidencia de servicio + portabilidad) y crédito a aseguradora en competencia (pago a aseguradora + portabilidad + paquete mínimo catastrófico/transmisibles); opt-out del beneficio con rebaja fiscal 80%/20% al pool. Detalles de currículo fino y protocolos médicos clínicos quedan al mercado y a la Mega Anual; el régimen institucional ya está en el tronco.

### 10.12 Economía y Régimen de Propiedad (cerrado en tronco, v0.4)

> Ver Cap. 5A completo: propiedad privada por defecto, sin topes de acumulación, meta fiscal 15% / techo 20% (Triple Llave), moneda A+ (peso fiscal + libertad privada), banca libre sin rescates clientelares, depósitos acotados, Gamma limpio, seis partidas de gasto fijo, sin salario mínimo económico en tronco. Parámetro aún abierto: tope numérico del seguro de depósitos (Mega Anual).

### 10.13 Tribunal Supremo como Cuello de Botella Soberano

Quien interpreta la Constitución tiene poder metapolítico. El consenso 70-80% mitiga pero no resuelve. Tensión clásica de teoría constitucional.

### 10.14 Contradicción Filosófica entre Descentralización y Blindaje

Mientras más se blinda contra irracionalidad, más tecnocrático. Mientras más se democratiza, más vulnerable a irracionalidad colectiva. Tensión central sin solución elegante. Se acepta como condición permanente del sistema.

---

## Capítulo 11: Gobernanza del Proyecto Open Source

### 11.1 Infraestructura

Repositorio público en GitHub. Motivo: uso general consolidado, mentalidad de código abierto, herramientas nativas de propuestas de cambio, incidencias, versionado y discusión pública.

### 11.2 Componentes del Repositorio

- Manifiesto principal versionado.
- Bitácora de iteración con historial de decisiones.
- Bancos de preguntas para cada pool técnico y para el pool del Congreso.
- Guía de contribución (`CONTRIBUTING.md`).
- Código de conducta (`CODE_OF_CONDUCT.md`).
- Plantillas estandarizadas para incidencias y propuestas de cambio.
- Documentación técnica de hardware (TVM, CSC) con especificaciones abiertas.
- Carpeta de variantes regionales y nacionales (`forks/`), con plantillas para versiones con otro énfasis (más minimalistas o más sociales).

### 11.3 Filosofía de Contribución

Cualquier persona en el mundo puede proponer cambios con una propuesta de cambio. Las contribuciones se evalúan por la comunidad activa y por los mecanismos de validación que cada componente exige.

Las versiones propias son bienvenidas. Si una región, país o comunidad quiere adaptar el modelo, o explorar otras variantes filosóficas con otro énfasis, puede crear su copia adaptada bajo la misma licencia CC BY-SA 4.0. La proliferación de variantes auditables entre sí enriquece el ecosistema.

### 11.4 Versionado

Versionado semántico. Cambios menores incrementan patch (v0.4.4). Cambios significativos incrementan menor (v0.5). La transición a v1.0 representa la primera implementación nacional efectiva del sistema.

### 11.5 Gobernanza de Mantenedores (Issue Abierto)

La cuestión de quién tiene permisos finales de merge queda como issue abierto crítico (sección 10.2). Cualquier diseño futuro debe garantizar que los mantenedores no se conviertan en dictadores de facto. Propuestas iniciales pendientes:

- Comité rotativo de mantenedores sorteados internacionalmente.
- Decisiones de merge con consenso multipartito.
- Auditoría continua del código mergeado.
- Posibilidad de una versión propia legítima y respaldada si los mantenedores se desvían.

---

## Glosario

- **CSC:** Credencial de Soberanía Criptográfica; tarjeta con chip seguro que guarda tu identidad cívica y biometría en el dispositivo.
- **TVM:** Terminal de Votación Malla; máquina física donde se emite el voto vinculante.
- **TMC:** Terminal de Módulo Cívico; terminal administrativa (trámites, examen, configuración); no emite voto.
- **TSC:** Tribunal Supremo de Consenso; filtro constitucional; miembros sorteados del Pool Judicial.
- **Protocolo BIOS:** plan post-colapso si cae la electricidad más de 72 horas; hibernación del Estado con tómbola física.
- **Triple Llave:** blindaje para cambiar la Constitución o romper el techo fiscal (Congreso + Tribunal + 75% popular).
- **Opt-Out cívico:** renuncia al voto; dejas intactas obligaciones fiscales y el orden legal.
- **Opt-out del beneficio:** renuncia al crédito de edu/salud con rebaja fiscal del 80% (el 20% va al pool); distinto del Opt-Out cívico.
- **PIB:** producto interno bruto; medida del tamaño de la economía frente a la cual se fija la meta/techo de gasto.
- **Frase de coacción:** versión preconfigurada de tu frase mental; si te fuerzan a votar, el sistema finge éxito y anula el voto en silencio.
- **Ágora:** portal abierto donde cualquier ciudadano activo registra propuestas de ley.
- **Pool:** lista de personas disponibles para sorteo de un cargo o función (Congreso, judicial, seguridad, etc.).
- **Anti-trampa de métricas:** cuando una métrica se vuelve el objetivo, deja de medir bien; la auditoría anual busca esa trampa. (En teoría de métricas a veces se llama Goodhart.)
- **Alpha / Beta / Gamma:** cascada de excedentes: reserva de desastres (Alpha), pago de deuda (Beta), fondo soberano de largo plazo (Gamma).
- **Equipo que busca fallas a propósito:** grupo permanente que intenta romper el sistema para revelar huecos antes que lo hagan actores hostiles.
- **Voucher:** crédito educativo que el Estado paga a la institución elegida; sigue al estudiante.
- **Caducidad automática:** toda política o empresa pública vence si no se reautoriza.
- **Mega Anual:** votación anual grande del ciclo (asuntos estructurales).
- **Cadena de bloques:** registro distribuido donde se asientan los votos firmados.
- **Huella digital (del voto):** comprobación digital de un dato; sirve para verificar integridad sin revelar el contenido.
- **Aislamiento operativo:** las fuerzas armadas operan con misión y alcance acotados, sin movilización interna libre.
- **Propuesta de cambio:** en GitHub, el mecanismo para sugerir una edición al texto o al código.
- **Versión propia / copia adaptada:** adaptación del modelo bajo la misma licencia; en software a veces se llama *fork*.
- **Núcleo (del manifiesto / del sistema):** el tronco no negociable y las reglas base que una jurisdicción adopta.
- **Red entre terminales:** cada TVM se conecta con las vecinas para enviar votos sin depender de un solo centro.
- **Freno de emergencia con jurado:** corte de seguridad: 100 ciudadanos sorteados revisan en persona antes de aceptar una cancelación automática crítica.
- **Contrato automático / reglas de pago automáticas:** pago que se ejecuta según reglas públicas fijadas de antemano, sin intermediario discrecional.
- **IA:** inteligencia artificial.

---
## Historial de versiones del manifiesto

- **v0.1:** Documento original. Estructura inicial con énfasis en hardware criptográfico, Congreso por sorteo, Recorte Ponderado y Cascada de Excedentes.

- **v0.2 (24 mayo 2026):** Refinamiento iterativo. Eliminación del examen como condición de voto. Principio de universalidad de leyes. Régimen detallado de ciudadanía, residencia y refugio. Pueblos originarios con autonomía y piso universal. Asambleas consultivas de menores y residentes. Doble figura de Traductores. Argumentos Críticos obligatorios. Asambleas deliberativas. Punto de quiebre presupuestal. Triple factor de autenticación. Hardware abierto. Bancos de preguntas open source. Presidente sin poder ejecutivo. División de Desastres. Capítulo de modelado de amenazas e issues abiertos. Gobernanza open source en GitHub.

- **v0.3 (24 mayo 2026):** Auditoría adversarial externa (Grok, Gemini, ChatGPT) procesada. Bifurcación 50/50 del Congreso (250 sorteo puro + 250 con examen). Democracia directa pura sin delegación. 4 votaciones anuales (3 Trimestrales + 1 Mega Anual) más Extraordinarias. Plazos mínimos. Filtro constitucional previo del TSC. Tope flexible por boleta. Niveles de participación configurables. Abstención sin penalización. Renuncia voluntaria a biometría. Asambleas Deliberativas por voluntariado. Educación cívica permanente sin examen con tutoría en dos niveles. Blindaje laboral constitucional. Compensaciones detalladas. Hardware multi-chip con bloques geopolíticos rivales y papel paralelo. Modo ciego en TVM. Latencia democrática. Red teams permanentes. Prohibición de decisiones automatizadas monocriterio. Ruido aleatorio en umbrales. Circuit breaker con jurado físico. Sunset clauses. Separación radical de capacidades coercitivas. Reconocimiento honesto de violencia última. Tres escenarios de transición: paralelo gradual, pacto con élites, post-colapso.

- **v0.4 (18 septiembre 2026):** Reescritura completa en **lenguaje sencillo** (apto para video / lectura fácil). Prefacio filosófico explícito: tronco = **minarquía demárquica digital**; ancap = fork. Frase clavada en 1.8: *«El Opt-Out cívico no es secesión fiscal ni salida del orden legal.»* Nuevo **Cap. 5A Economía y Propiedad**: cierra issues **10.11** (edu/salud) y **10.12** (economía). Clavados: meta fiscal 15% PIB / techo duro 20% (Triple Llave); moneda A+ (peso fiscal + libertad privada); sin salario mínimo económico en tronco (sí compensación cívica Cap. 4); voucher educativo (Estado paga a institución; matrícula + evidencia; portabilidad); salud vía crédito a aseguradora en competencia (Estado paga a aseguradora; portabilidad); opt-out del beneficio con rebaja 80%/20% al pool; banca libre sin rescates salvo desastre+72h; depósitos acotados; Gamma limpio; gasto fijo operativo en 6 partidas. Gasto fijo del Cap. 5 alineado (ya no salarios de médicos/maestros ni “luz de hospitales” como fijo: el tronco no opera escuelas ni hospitales). Plantillas de fork ancap/social previstas en Cap. 11.

- **v0.4.1 (18 septiembre 2026):** Humanización del relato y destino país desde el día 1. Repositorio público enlazado. Resumen ejecutivo y Capítulo 9 alineados con adopción nacional en capas (escenarios A-C); la viabilidad deja de centrarse en municipios piloto. Prefacio de forks en tono breve.

- **v0.4.2 (18 septiembre 2026):** Pass humanizer (blader/humanizer). Menos contraste not-X-but-Y espurio y defensas a objeciones que el lector frío no trae. Cero em dashes en prosa. Menos negritas decorativas. Declaración con el objetivo de frente.

- **v0.4.3 (18 septiembre 2026):** Glosario al final; glosas en primeras menciones (PIB, Frase de coacción, Opt-Out, IA, hash, cadena de bloques, RISC-V, pull request, Mega Anual, caducidad). Se retiró ancap del relato del tronco: el tronco se afirma como libertario → minarquía demárquica digital; forks como variantes con otro énfasis (más minimalistas o más sociales). NIP de Coacción renombrado a Frase de coacción.

- **v0.4.4 (18 septiembre 2026):** Lenguaje más ciudadano: menos jerga de ingeniería. Hash → huella digital; blockchain → cadena de bloques; RISC-V → chip de diseño abierto; pull request → propuesta de cambio; sandbox → aislamiento operativo; mesh → red entre terminales; circuit breaker → freno de emergencia; kernel → núcleo; fork (en el cuerpo) → versión propia / copia adaptada; Red Team → equipo que busca fallas a propósito; Goodhart solo en glosario; malware → programas maliciosos; datasets → datos de entrenamiento; smart contract → contrato automático / reglas de pago automáticas. Glosario reescrito en llano.

---

*Demarquía Digital · manifiesto v0.4.4 · lenguaje claro · CC BY-SA 4.0 · 18 sep 2026*


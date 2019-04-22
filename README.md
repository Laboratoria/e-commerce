# E-COMMERCE

## PREÁMBULO

México tiene un gran potencial de crecimiento en materia de comercio electrónico, pues ya es el segundo mercado más importante en Latinoamérica para este tipo de transacciones en internet. De acuerdo con un estudio sobre venta online, presentado recientemente por la Asociación Mexicana de Venta Online (AMVO) en 2018, el promedio de visitas mensuales a los sitios de comercio electrónico en el país se incrementó un 30%.

Además, el comprador en línea está aumentando la frecuencia con la que adquiere productos por Internet. Mientras que en 2017, solo 7% recurría al comercio electrónico de manera semanal; durante 2018 esa cifra subió a 38%. El 34% de los compradores lo hace de manera mensual y el 16%, cada dos o cinco meses.

Lo que más consumen los mexicanos en internet es moda, comida a domicilio y electrónicos; así como los servicios de suscripción de series, películas, música, banca por internet, entretenimiento, cine y conciertos.

## INTRODUCCIÓN

El comercio electrónico ha logrado ser una de las principales actividades digitales que está logrando impulsar la economía de nuestro país. Este tipo de comercio ha logrado crecer a través de diversas plataformas desarrolladas y enfocadas a las demandas de los consumidores, permitiendo mayor alcance a diferentes públicos que prefieren este modelo por su disponibilidad e inmediatez.

## CONTEXTO

La venta online ha generado un nuevo nicho de mercado desde donde han surgido nuevas oportunidades de empleo y negocio no sólo para las grandes empresas logísticas y de retail sino para start ups emergentes. La automatización de almacenes, trazabilidad de mercancía y control de paquetería son algunas de las operaciones que están generando que cada vez más en logística se demanden profesionales del mundo IT, buscando una mayor efectividad, acortando tiempos, costes e incidencias. Por lo tanto, no sería raro que dentro de tu trayectoria profesional en algún momento tengas que abordar un proyecto de esta naturaleza.

## OBJETIVOS DE APRENDIZAJE

- Tendrás la oportunidad de experimentar no sólo el proceso de ideación de un negocio con un equipo (UX y FE), sino que juntas deberán ejecutar sus ideas a través de la construcción de un MVP funcional de comercio electrónico.

- Conocerás qué elementos y funcionalidades básicas contiene un e-commerce, así como los aspectos técnicos y de experiencia que se deben considerar al echar a andar un emprendimiento de este tipo.

- Crear y manipular tu propia data, manipula y consumir API`s de diferentes proveedores.

## RETO

Aprovechando las múltiples oportunidades de negocio que el comercio electrónico ofrece en la actualidad, tus compañeras y tú han decidido emprender juntas a través de una propuesta de plataforma de tienda en línea.

Emprendimiento en conjunto, nunca olvidar que son parte de un equipo y que el trabajo de una repercute en el trabajo de todas.

Crear y/o consumir API’s.

Validar el producto o productos que van a vender, el segmento que van a explotar, el usuario al que se van a dirigir.

Tomar en cuenta todo el flujo de compra, tanto desde el aspecto técnico como desde la experiencia del usuario.

### PARTE OBLIGATORIA

- Cómo validaron a su usuario.
- Cómo respaldan la demanda del o los productos que van a vender
- Justificar la idoneidad de la distribución de dicho producto(s) a través de comercio electrónico.
- Replicar el flujo de una e-commerce (buscar, filtar, selecciona un producto, agregar y/o quitar un pruducto del carrito, seleccionar método de pago, y terminar el proceso de compra).

### HACKER EDITION

- Implementar SEO en su plataforma (Search Engine Optimization, Optimización del posicionamiento en los Motores de Búsqueda).

- Si decidiste crear tu propia data ahora te recomendamos explorar Mongo DB para el despliegue.

## CONSIDERACIONES GENERALES

- Este proyecto se debe "resolver" de manera grupal.

- Toma en cuenta que cuando queremos crear una tienda online, también necesitamos crear una audiencia y poder comunicarnos con ella de manera constante, rápida y económica. Considera que hoy en día la oferta es tal, que se vuelve muy difícil vender a la primera.

- Una buena plataforma de e-Commerce, además debería ser escalable y eventualmente, permitirte gestionar una gran cantidad de productos de un catálogo.

## CONSIDERACIONES TÉCNICAS

- Deberás crear una web app bajo los principios de SPA (Single page aplication).

  Quizá primero quieras entender y aplicar los siguientes conceptos.

  - Templating
  - Routing (URLs)
  - DOM & Event Handling (State)
  - Patrón de arquitectura de software (MV\*)

- Tu reto será desarrollar una app e-commerce, para ello utilizarás.

  - Crear tu propia data ó consumir alguna API de productos (Descripción, precios, etc). Si gustas puedes usar la de _**[Mercado Libre](https://developers.mercadolibre.com.mx/es_ar/api-docs-es)**_ ó _**[Etsy](https://rapidapi.com/community/api/etsy?utm_source=google&utm_medium=cpc&campaign=1672506610&keyword=&gclid=EAIaIQobChMIpNWtsInf4QIVA7XACh2V_wHCEAAYASAAEgIIK_D_BwE)**_.

  - Consumir una _**API**_ que permita el pago de los productos via online por parte del usuario, que puede ser Paypal, Stripe o cualquier otra que encuentres que sirva para lo mismo.

  - El diseño es libre.

  - Despliega tu repositorio a GH Pages o cualquier otra plataforma ([Firebase Hosting](https://firebase.google.com/docs/hosting/?gclid=EAIaIQobChMIhrP5t5Hf4QIVRvbjBx3D5AuBEAAYASAAEgLeAPD_BwE), [Now](https://zeit.co/now#features)).
  - Siempre considera realizar la documentación de tu produto en el README.md

- Los tests unitarios deben cubrir un mínimo del 70% de statements, functions, lines y branches. Te recomendamos explorar Jest para tus pruebas unitarias.

- Antes de comenzar a codear, es necesario crear un plan de acción. Esto debería quedar detallado en el README.md de tu repo y en una serie de issues y milestones para priorizar y organizar el trabajo, y para poder hacer seguimiento de tu progreso.

- Dentro de cada milestone se crearán y asignarán los issues que cada quien considere necesarios.

- También te sugerimos que empieces a utilizar los project boards de github que te ayudaran a organizar y priorizar su trabajo.

NOTA: Aquí te damos algunas API´s que puedes usar para tu proyecto pero si encuentras otras, adelante! Sorpréndenos

### **Archivos del proyecto**

- **README.md:** Con descripción del módulo, instrucciones de instalación/uso, documentación del API y ejemplos. Todo lo relevante.
- **index.js:** Desde este archivo debes exportar tus modules necesarios.
- **package.json:** Con nombre, versión, descripción, autores, licencia, dependencias, scripts (pretest, test, ...)
- **.editorconfig:** Con configuración para editores de texto.
- **.eslintrc:** Con configuración para linter.
- **.gitignore:** para ignorar node_modules u otras carpetas que no deban incluirse en control de versiones (git).
- **test/\*.spec.js:** Debe contener los tests unitarios para las funciones. Tu implementación debe pasar estos test.

Nota: Seguramente querrás experimentar o investigar como se realiza un deploy.

# Comportamiento de compra de productos digitales — primera síntesis

**Versión:** 0.2.0

**Estado:** evidencia de contexto y pago; no mide conversión de gratuito a pagado.

**Países:** México, Chile, España, Colombia, Argentina y Brasil.

**Actualización:** 2026-10-22 20:08 UTC.

## Respuesta corta

**Hecho observado:** comprar online es una práctica establecida en los seis mercados, pero los datos disponibles suelen medir e-commerce general y no productos digitales como cursos, apps o membresías.

**Inferencia:** para un producto digital, la decisión no termina cuando existe interés. La compra depende de que la oferta sea entendible, el proveedor parezca confiable y el pago encaje con los hábitos locales. La importancia de cada factor cambia por país.

**Vacío:** no se encontró una fuente pública comparable que mida, para los seis países, cuántas personas pasan de consumir contenido gratuito a pagar por educación, software, comunidad o suscripción.

## Panorama comparativo

| País | Comportamiento/pago observado | Implicación limitada |
|---|---|---|
| México | AMVO reporta 77,2 millones de compradores online en 2025. Las fuentes revisadas describen comportamiento omnicanal, uso de tarjeta/digital y preocupación por confianza. | El checkout debe cubrir pagos digitales y explicar con claridad quién vende, qué se recibe y bajo qué condiciones. No permite inferir disposición a pagar cursos. |
| Chile | La FNE recoge estimaciones de 64 % de compradores online en abril de 2025 y 75 % de chilenos con al menos una compra online en agosto de 2025. | Hay adopción relevante, pero los datos no distinguen productos digitales ni explican por sí solos el paso de gratuito a pagado. |
| España | ONTSI informa tarjeta de crédito o débito en 55,6 % de transacciones; un estudio de compras online recoge alta percepción de seguridad entre compradores. | Precio final en EUR, condiciones y confianza siguen siendo información de conversión; hábito de compra no elimina la evaluación de valor. |
| Colombia | CCCE reportó 684,6 millones de compras online en 2025 y débito/PSE con 57,2 % del valor transaccionado. | PSE/débito debe considerarse en pruebas de checkout. No hay evidencia de que ese método aumente por sí solo la compra de formación. |
| Argentina | CACE reporta tarjeta de crédito como principal medio y 8 de cada 10 personas compradoras consideran claves las cuotas. | Mostrar precio en moneda local y cuotas es una hipótesis operativa prioritaria; debe validarse para cada tipo de producto. |
| Brasil | En una encuesta Visa, tarjeta (47 %) y Pix (45 %) estuvieron casi empatados en la última compra online; otras fuentes reportan presencia fuerte de Pix y preocupaciones por seguridad. | Brasil requiere pago local, idioma portugués y una experiencia de confianza propia. |

## Recorrido de compra: evidencia disponible

| Etapa | Hecho observado | Qué no se puede concluir |
|---|---|---|
| Descubrimiento | En Colombia una fuente sectorial señala redes sociales como vía de descubrimiento para dos de cada cinco usuarios de internet. | No equivale a descubrir o comprar cursos/productos digitales en particular. |
| Consumo gratuito | Existen modelos de contenido abierto, demos, certificaciones de pago y planes freemium en las ofertas relevadas en otras líneas del repositorio. | No hay tasa comparable de conversión gratuita→pagada. |
| Evaluación | Fuentes de México, España, Argentina y Brasil incluyen confianza, seguridad, métodos de pago, devoluciones o cuotas dentro de sus estudios de compra. | No ordenan causalmente cuál factor decide la compra de cada producto. |
| Checkout | PSE/débito en Colombia, cuotas en Argentina y Pix en Brasil son señales concretas de adaptación local. | No prueban que una sola integración resuelva el abandono. |
| Uso/renovación | No se encontró una fuente común sobre cancelación, retención o reembolso de productos digitales en los seis mercados. | No puede diseñarse una conclusión regional sobre membresías o suscripciones todavía. |

## Lectura por mecanismo

### 1. Utilidad frente a lo gratuito

**Hecho observado:** el material disponible no cuantifica este mecanismo por país y categoría.

**Inferencia:** un producto pagado necesita hacer visible qué cambia frente a seguir usando contenido suelto: estructura, ahorro de tiempo, acompañamiento, soporte, acceso, especialización o certificación. Esta es una hipótesis a probar, no una tasa observada.

### 2. Pago y precio

**Hecho observado:** los medios y condiciones de pago difieren materialmente: PSE/débito en Colombia, cuotas en Argentina y Pix en Brasil; tarjeta continúa relevante en España y México.

**Inferencia:** mostrar un precio sin un método de pago familiar, moneda comprensible o financiamiento pertinente puede detener una compra que ya tenía interés.

### 3. Confianza y riesgo

**Hecho observado:** fuentes mexicanas y brasileñas muestran preocupación por fraude o seguridad digital; estudios españoles incluyen confianza, devolución y seguridad dentro del comportamiento de compra.

**Inferencia:** identidad del proveedor, descripción precisa, precio final, soporte y políticas visibles son requisitos de reducción de riesgo antes de pedir pago.

## Límites y siguiente etapa

- La mayoría de las fuentes mide e-commerce general, no cursos, apps, ebooks o membresías por separado.
- No se deben usar cifras de bienes físicos como sustituto de disposición a pagar productos digitales.
- Faltan al menos dos fuentes metodológicamente comparables para cerrar la ficha de Chile y Colombia bajo el umbral original de cinco fuentes por país.
- No es viable estimar con la evidencia pública disponible una tasa de paso de contenido gratuito a producto pagado para estos países. Ese objetivo se retira como métrica central de esta iteración.
- Las entrevistas pueden aportar lenguaje, objeciones y fricciones, pero no son requisito para elegir el primer checkout. Una muestra pequeña no permitiría estimar el mercado ni una tasa de conversión.

## Aplicación operativa: checkout para un programa de respiración de siete días

**Contexto declarado por el creador:** el programa es de fundamentos, dura siete días y se ofrece a una audiencia que ya conoce a Fernando y a *Respiro y Conecto*. Por tanto, la confianza previa existe en alguna medida, pero no sustituye la claridad de la oferta, el precio final ni las condiciones de compra.

### Decisión recomendada para el primer lanzamiento

**Recomendación (inferencia operativa):** lanzar con **pago único** y un único flujo internacional en **Hotmart + Hotmart Club/área de miembros**, enlazado desde una página propia de Respiro y Conecto. No usar suscripción ni crear tres integraciones de pago nacionales en esta primera versión.

| Componente | Decisión inicial | Motivo y límite |
|---|---|---|
| Modelo de cobro | Un pago único por los siete días | El producto tiene inicio y final definidos. No hay evidencia de que una suscripción mejore su compra o uso. |
| Plataforma / checkout | Hotmart | Hotmart declara más de 30 medios de pago en más de 180 países, tarjetas de crédito y débito en Latinoamérica y Europa, PayPal y cuotas configurables para compradores de Chile y México. Confirma el alta fiscal y bancaria antes de publicar; las condiciones pueden variar por cuenta, país y moneda. |
| Acceso | Área de miembros y liberación por día | La plataforma permite alojar contenido y programar acceso. La secuencia diaria hace tangible la diferencia frente a audios o publicaciones sueltas. |
| Página de venta | Dominio / página de Respiro y Conecto → botón de pago | Conserva identidad propia y evita pedir al visitante que “descubra” una plataforma antes de comprender el programa. |
| Cobertura | México, Chile y España desde un mismo enlace | Es una forma de reducir fricción operativa, no evidencia de que todos los métodos conviertan igual. Revisar los métodos que realmente se muestren en cada país con compras de prueba. |

### Qué debe ver una persona antes de pagar

Esto no requiere más “prueba social” si el vínculo con Fernando ya está construido; requiere precisión transaccional.

1. **Qué es:** “Siete días para explorar respiración consciente y construir un lenguaje común para seguir trabajando”.
2. **Qué recibe:** número de prácticas, formato (audio/video/vivo), duración estimada y cómo se libera cada día.
3. **Qué no promete:** evitar promesas clínicas, terapéuticas o resultados garantizados si no están sustentadas.
4. **Para quién es / no es:** nivel de experiencia, condiciones relevantes y alternativa si no corresponde.
5. **Precio final, moneda, cuotas si aparecen y política de devolución.**
6. **Qué sucede tras pagar:** correo de acceso, inicio, soporte y periodo de acceso.

**Hecho observado:** Hotmart permite métodos de tarjeta/débito en las regiones relevantes y cuotas configurables para Chile y México. **Inferencia:** informar el precio final y las condiciones antes del botón reduce una incertidumbre evitable; no se afirma que produzca una tasa de conversión concreta.

### Plataformas y pasarelas: comparación acotada

| Opción | Encaje para México, Chile y España | Cuándo elegirla | Reserva importante |
|---|---|---|---|
| **Hotmart** | Alto para un primer lanzamiento regional: checkout, acceso al producto y medios de pago en una plataforma. Chile figura entre países productores elegibles en funciones de la plataforma y hay cuotas configurables para Chile/México. | Cuando se prioriza salir rápido, no desarrollar tecnología y operar un curso corto. | Verificar durante el onboarding las tarifas, moneda, impuestos, datos bancarios y métodos que se exhibirán por país. Google Pay no está disponible en México ni Chile. |
| **Teachable Pay** | Alto si se desea una experiencia de escuela más personalizable: su documentación actual lista Chile, México y España como países elegibles y el cobro/pago se configura mediante Stripe Express. | Si la presentación, la estructura de cursos y la administración de alumnos pesan más que los métodos locales de LatAm. | Comparar comisiones y reservas antes de contratar. La documentación indica que algunas ventas pueden tener reservas; no asumir liquidación inmediata. |
| **Sitio propio + Mercado Pago** | Bueno como alternativa de control de marca para Chile y México; Mercado Pago ofrece Payment Link, Checkout Pro y suscripciones en ambos ecosistemas. | Si el foco inicial se acota a Chile/México y se cuenta con soporte técnico o un integrador. | No resuelve España como pasarela local. El esquema transfronterizo requiere cuenta comercial y habilitación específica; no es la vía inicial recomendada. |
| **Webpay / Transbank** | Bueno para una experiencia local chilena; ofrece tarjetas de crédito y débito y plugins, por ejemplo para WooCommerce. | Sólo si las ventas chilenas justifican una optimización local posterior. | No es una solución única para México y España; añade operación e integración. |
| **Checkout propio con Stripe** | No recomendado como base de una entidad chilena. Stripe admite cuentas directas en México y España, pero Chile no está en su lista pública de disponibilidad. | Únicamente si la entidad que cobrará está establecida y habilitada en un país admitido o si se evalúa un intermediario de merchant-of-record. | No abrir una arquitectura sobre esta suposición sin confirmar la entidad legal, banco y cumplimiento fiscal. |

### Secuencia mínima de implementación

1. Crear el producto como pago único; cargar los siete módulos y configurar la liberación diaria.
2. Completar el alta de productor con datos fiscales y bancarios reales; revisar moneda, tarifas, devolución e impuestos aplicables antes de comunicar precio.
3. Crear una página de venta corta en Respiro y Conecto y dirigir un único botón al checkout.
4. Realizar tres compras de prueba —una desde Chile, una desde México y una desde España— o usar revisores ubicados allí. Registrar qué métodos aparecen, moneda, confirmación y acceso.
5. Al cerrar la primera cohorte, preguntar a quienes no terminaron el pago una sola pregunta opcional: “¿Qué te detuvo?”. Clasificar respuestas; no convertirlas en porcentajes de mercado.

### Entrevistas: proporción adecuada

**Recomendación:** no hacer ahora un estudio de entrevistas amplio. Si se necesita afinar el lenguaje antes de lanzar, bastan **cinco conversaciones de 15–20 minutos** con personas que ya conocen el trabajo, separando: quienes comprarían, quienes dudan y quienes no comprarían. Su propósito es encontrar vocabulario y objeciones para la página, no demostrar demanda nacional. La alternativa más eficiente es recoger esa misma señal después del lanzamiento mediante la pregunta corta de checkout y conversaciones voluntarias.

## Hipótesis para validar

| Hipótesis | Prueba mínima |
|---|---|
| Una ruta estructurada convierte mejor que una biblioteca de contenidos sueltos. | Landing A/B con mismo tema, muestra y precio; medir comprensión, intención y motivo declarado. |
| Un método de pago local reduce abandono en Colombia, Argentina y Brasil. | Checkout con eventos por método; no interpretar intención como venta. |
| Precio final y condiciones visibles aumentan confianza previa al pago. | Entrevistas cognitivas y prueba de dos páginas equivalentes. |
| La prueba gratuita útil funciona mejor que contenido gratuito genérico. | Comparar una muestra representativa con una pieza introductoria; preguntar qué valor esperaban obtener. |

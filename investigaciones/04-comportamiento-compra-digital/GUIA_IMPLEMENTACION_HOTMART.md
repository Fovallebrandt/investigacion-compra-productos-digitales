# Guía operativa — Hotmart para «7 días para explorar tu respiración»

**Versión:** 0.1.0  
**Estado:** investigación aplicada; no configura una cuenta ni publica el curso.  
**Actualizado:** 2026-10-22 18:11 CLST  
**Alcance:** productor con residencia/operación en Chile; compradores iniciales en Chile, México y España.

## Resultado

**Hecho observado:** Hotmart permite registrar un curso online con pago único, alojarlo en Hotmart Club, organizar módulos, crear una oferta con enlace de pago y programar la liberación de contenido según la fecha de compra. También ofrece plazos de garantía de 7, 15, 21 o 30 días para cursos online. [Curso online: creación y configuración](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso) · [Módulos en Hotmart Club](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club) · [Liberación programada](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)

**Inferencia operativa:** la arquitectura más simple para esta primera versión es: landing de Respiro y Conecto → enlace de pago de una oferta Hotmart → Hotmart Club para el curso. No requiere construir cuentas, pagos ni un LMS propio antes de vender.

**Límite:** ninguna fuente revisada permite asegurar qué moneda o medios aparecerán en un checkout concreto antes de completar el alta y realizar pruebas con una cuenta/producto reales.

## Configuración recomendada del producto

| Elemento | Configuración propuesta | Estado de decisión |
|---|---|---|
| Tipo | Curso online | Compatible con la estructura del programa. |
| Cobro | Pago único | Acordado para la primera versión. |
| Entrega | Hotmart Club / Área de Miembros | Propuesta operativa; no está configurado. |
| Estructura | Módulos Día 0 a Día 7 | Compatible con el programa existente. |
| Landing | Página propia de Respiro y Conecto que dirige al enlace de pago | Acordado como dirección de implementación. |
| Precio y moneda | Una oferta inicial | **Pendiente de decisión.** No publicar sin definirlos. |
| Garantía | 7, 15, 21 o 30 días | **Pendiente de decisión.** Hotmart ofrece esas alternativas para cursos online. |
| Tiempo de acceso | Definir expresamente en el producto | **Pendiente de decisión.** No asumir acceso vitalicio ni limitado. |

## Pasos para dejarlo funcional

### 1. Crear y validar la cuenta de productor

1. Crear la cuenta de Hotmart como productor.
2. Completar los documentos solicitados por el flujo de verificación.
3. Esperar la aprobación documental antes de registrar la cuenta bancaria de retiro. Hotmart indica que el análisis puede tomar hasta cinco días hábiles. [Documentos de cuenta](https://help.hotmart.com/es/article/216440217/-que-documentos-debo-enviar-para-crear-mi-cuenta-en-hotmart-)
4. Registrar la cuenta bancaria de retiro y revisar la moneda disponible para recibir pagos. [Cuenta bancaria y transferencias](https://help.hotmart.com/es/article/24183626321165/-como-configurar-mi-cuenta-bancaria-para-la-transferencia-automatica-de-comisiones-)
5. Confirmar con un contador o asesor tributario chileno la emisión de documentos tributarios, declaración de ingresos e impuestos aplicables. Hotmart no reemplaza esa revisión local.

**Pendiente que requiere a Fernando:** datos de identidad, datos tributarios y cuenta bancaria. No es posible completar ni simular legítimamente esta etapa sin ellos.

### 2. Registrar el curso y la oferta

1. Crear un producto de tipo **curso online**.
2. Seleccionar **pago único**.
3. Definir el precio, la moneda y la garantía. La guía de Hotmart indica que se puede elegir pago único y que la garantía puede ser de 7, 15, 21 o 30 días. [Curso online: creación y configuración](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso)
4. Crear una **oferta**: allí se define el precio base y Hotmart genera el enlace de pago. [Crear una oferta para pago único](https://help.hotmart.com/es/article/215827788/como-criar-uma-oferta-para-o-meu-produto-de-pagamento-unico)
5. Mantener una única oferta inicial. No crear descuentos, bundles, afiliados ni suscripciones antes de validar la compra básica.

### 3. Preparar el Área de Miembros

Crear estos módulos:

| Módulo | Contenido mínimo que debe existir antes de publicar |
|---|---|
| Día 0 — Bienvenida y preparación | Video de bienvenida, seguridad y cómo usar el cuaderno. |
| Día 1 — Observación | Práctica guiada y acceso al Cuaderno Digital. |
| Días 2–6 | Video educativo y/o práctica correspondiente; enlace al cuaderno. |
| Día 7 — Integración | Práctica, cierre y reflexión final. |
| Soporte | Correo o formulario de contacto y una explicación breve de acceso. |

**Hecho observado:** Hotmart Club permite agrupar clases, videos, cuestionarios y recursos en módulos. También permite liberar contenido en una fecha concreta o un número de días después de la compra. [Módulos](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club) · [Liberación programada](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)

**Decisión pendiente:** la investigación no dicta si Día 0 y Día 1 deben aparecer ambos al comprar. Dos opciones coherentes son:

- Día 0 y Día 1 disponibles inmediatamente; Día 2 se libera un día después de la compra y así sucesivamente.
- Sólo Día 0 disponible inmediatamente; Día 1 se libera al día siguiente.

**Inferencia:** la primera opción reduce espera y permite que la bienvenida lleve directamente a la primera práctica. Debe confirmarse antes de configurar fechas.

### 4. Conectar la landing al checkout

1. Finalizar una página breve de venta en Respiro y Conecto.
2. Incluir un único botón principal: “Comenzar los 7 días” o equivalente.
3. Vincular ese botón al enlace de pago generado por la oferta Hotmart.
4. Antes del botón, mostrar: qué incluye, formato, liberación diaria, precio final, moneda, garantía, tiempo de acceso, advertencias de seguridad y canal de soporte.
5. No prometer resultados clínicos ni usar el checkout para ocultar condiciones de pago o reembolso.

### 5. Revisar pagos por país sin asumir disponibilidad

**Hecho observado:** Hotmart documenta tarjetas de crédito y débito para Latinoamérica y Europa, PayPal y más de 30 métodos para compradores en más de 180 países. También documenta cuotas para productos vendidos a compradores de Chile y México. [Métodos para vender](https://help.hotmart.com/es/article/25588460435085/-que-metodos-de-pago-estan-disponibles-y-como-puedo-habilitarlos-para-mi-producto-) · [Cuotas en Chile y México](https://help.hotmart.com/es/article/4404509205005/-como-funciona-el-pago-en-cuotas-para-quienes-venden-en-chile-peru-mexico-colombia-y-brasil-) · [Métodos para comprar](https://help.hotmart.com/es/article/25648853025037/-cuales-son-los-metodos-de-pago-disponibles-para-comprar-en-hotmart-)

| Mercado | Métodos mencionados en documentación de Hotmart | Lo que falta verificar |
|---|---|---|
| Chile | Tarjeta; MACH, Sencillito y Servipag aparecen en documentación de compras/reembolsos. | Cuáles aparecerán en esta oferta, en qué moneda y bajo qué condiciones. |
| México | Tarjeta; Mercado Pago, SPEI y OXXO aparecen en documentación de compras/reembolsos. | Cuáles aparecerán en esta oferta y si el flujo es adecuado para un curso de bajo precio. |
| España | Tarjeta; Klarna está documentado para compradores en España en productos digitales de pago único, con elegibilidad y límites locales. | Qué opciones concretas verá una persona según importe y perfil; no están garantizadas para todo comprador. |

**Advertencia:** no anunciar públicamente MACH, OXXO, Klarna u otro método hasta comprobar que el checkout real lo muestra para ese país. La disponibilidad depende de país, importe, producto, cuenta y evaluación del proveedor. [Klarna en Hotmart](https://help.hotmart.com/es/article/38465293543309/como-vender-con-klarna-en-hotmart)

### 6. Operación, acceso y soporte

- Tras una compra aprobada, la persona accede con el correo utilizado en la compra desde el entorno de Hotmart. [Acceso de la persona compradora](https://help.hotmart.com/es-LA/article/215827338/como-accedo-al-producto-que-compre-en-hotmart)
- Definir un correo de soporte de Respiro y Conecto para: problemas de acceso, preguntas del curso y consultas sobre el contenido.
- Explicar de forma visible el plazo de garantía elegido. Una solicitud de devolución o un chargeback no debe atenderse con promesas informales: revisar el estado de la transacción y las reglas de Hotmart.
- Revisar ventas, pagos y retiros desde el panel antes de comunicar una nueva cohorte o inversión publicitaria.

## Pruebas obligatorias antes de abrir ventas

| Prueba | Resultado que debe comprobarse |
|---|---|
| Enlace desde la landing | Lleva a la oferta correcta, con producto, precio y moneda correctos. |
| Checkout desde Chile | Métodos visibles, precio, moneda y condiciones reales. |
| Checkout desde México | Métodos visibles, precio, moneda y condiciones reales. |
| Checkout desde España | Métodos visibles, precio, moneda y condiciones reales. |
| Compra aprobada de prueba | Correo de confirmación y acceso sin intervención manual. |
| Área de miembros | Sólo se muestran los módulos que corresponden al día de acceso. |
| Liberación diaria | Día siguiente se abre en el momento configurado respecto de la compra. |
| Móvil | Landing, checkout, videos, audios, enlaces y Cuaderno Digital funcionan en teléfono. |
| Soporte y devolución | Correo de soporte visible; garantía y proceso comunicados con claridad. |
| Retiro | Cuenta bancaria y moneda de retiro confirmadas en el panel. |

## Orden de trabajo

### Sin datos personales o bancarios

1. Terminar contenidos y archivos de cada día.
2. Elegir cuál de las dos reglas de liberación usar.
3. Preparar la página de venta y el texto de soporte/garantía.
4. Definir una propuesta de precio, sin publicarla todavía.

### Con datos personales, tributarios y bancarios

5. Crear/verificar cuenta de productor y registrar retiro.
6. Crear curso, módulos, oferta, precio y garantía.
7. Insertar el enlace de pago en la landing.

### Antes de lanzamiento

8. Ejecutar las pruebas de la tabla anterior, idealmente con personas reales ubicadas en Chile, México y España.
9. Corregir fricciones observadas.
10. Abrir ventas sólo cuando compra, acceso, entrega y soporte estén comprobados.

## Decisiones que siguen abiertas

- Precio y moneda base.
- Plazo de garantía.
- Periodo de acceso al curso.
- Disponibilidad inmediata de Día 1 o liberación al día siguiente.
- Texto final de términos, privacidad, soporte e impuestos; requiere revisión local cuando corresponda.
- Métodos de pago efectivamente disponibles para esta cuenta y oferta.

## Fuentes oficiales consultadas

- [Hotmart: curso online, creación y configuración](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso)
- [Hotmart: documentos de cuenta](https://help.hotmart.com/es/article/216440217/-que-documentos-debo-enviar-para-crear-mi-cuenta-en-hotmart-)
- [Hotmart: oferta de pago único](https://help.hotmart.com/es/article/215827788/como-criar-uma-oferta-para-o-meu-produto-de-pagamento-unico)
- [Hotmart: módulos del Área de Miembros](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club)
- [Hotmart: liberación programada](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)
- [Hotmart: métodos de pago](https://help.hotmart.com/es/article/25648853025037/-cuales-son-los-metodos-de-pago-disponibles-para-comprar-en-hotmart-)
- [Hotmart: Klarna](https://help.hotmart.com/es/article/38465293543309/como-vender-con-klarna-en-hotmart)

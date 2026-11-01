# 🌊 Ketheryon — Goggles para Aguas Abiertas y Triatlón

![Estado](https://img.shields.io/badge/estado-activo-brightgreen)
![Tecnología](https://img.shields.io/badge/tecnología-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)
![Deploy](https://img.shields.io/badge/deploy-GitHub%20Pages-black)
![Tipo](https://img.shields.io/badge/tipo-Sitio%20de%20marca%20%2F%20E--commerce-blue)
![Tienda](<https://img.shields.io/badge/tienda-demo%20(sin%20pasarela)-lightgrey>)

**Ketheryon** es el sitio de marca y tienda en línea de una línea de goggles diseñados en México para **nadadores de aguas abiertas y triatletas**. Es una página única (_single-page_) que reúne la historia de la marca, el catálogo, la tecnología del producto, preguntas frecuentes, testimonios, noticias y agenda de eventos del deporte, además de un **carrito de compra del lado del cliente**.

🔗 **Demo en vivo:** [https://giomerida.github.io/ketheryon/](https://giomerida.github.io/ketheryon/)

---

## 📋 Tabla de Contenidos

- [Sobre el proyecto](#-sobre-el-proyecto)
- [Capturas de pantalla](#-capturas-de-pantalla)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Identidad visual](#-identidad-visual)
- [Instalación y uso](#-instalación-y-uso)
- [Secciones del sitio](#-secciones-del-sitio)
- [Catálogo de productos](#-catálogo-de-productos)
- [Tecnología del producto](#-tecnología-del-producto)
- [Noticias y agenda](#-noticias-y-agenda)
- [Carrito de compra](#-carrito-de-compra)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Roadmap](#-roadmap)
- [Créditos](#-créditos)

---

## 📌 Sobre el proyecto

Bajo el lema **"Adáptate al agua"**, Ketheryon comunica una marca nacida del mar y no de una oficina: su nombre representa transformación, adaptación y renacimiento, y su símbolo es la **ballena**. El sitio está pensado para convertir visitas en preventas y suscriptores mientras los productos aún figuran como _"Próximamente"_.

**Qué incluye:**

- Narrativa de marca: historia, misión y visión.
- Catálogo con dos ediciones: **White** y **Black**.
- Sección de tecnología con las claves técnicas del producto.
- Preguntas frecuentes en formato acordeón, a modo de reseñas de usuarios.
- Testimonios de atletas y espacio para reseña en video.
- **Noticias** del sector y **agenda** de competencias de aguas abiertas.
- Formulario de suscripción para rutas de entrenamiento y acceso anticipado.
- **Carrito de compra** funcional en frontend.

**Cifras destacadas en el sitio:**

| Indicador             | Valor |
| --------------------- | ----- |
| Campo de visión       | 180°  |
| Sellado probado desde | 12 °C |
| Ediciones disponibles | 2     |

---

## 📸 Capturas de pantalla

### 🏠 Hero — Portada

![Hero](assets/screenshots/hero.png)

### 🥽 Catálogo de productos

![Catálogo](assets/screenshots/catalogo.png)

### 🔬 Sección de tecnología

![Tecnología](assets/screenshots/tecnologia.png)

### 📰 Noticias y agenda

![Noticias y agenda](assets/screenshots/noticias-agenda.png)

### 🛒 Carrito de compra

![Carrito](assets/screenshots/carrito.png)

---

## 🛠️ Tecnologías utilizadas

| Tecnología               | Uso                                                        |
| ------------------------ | ---------------------------------------------------------- |
| **HTML5**                | Estructura semántica del sitio                             |
| **CSS3**                 | Estilos, animaciones y diseño responsivo                   |
| **JavaScript (Vanilla)** | Carrito, acordeón de FAQ, suscripción y contenido dinámico |
| **GitHub Pages**         | Hosting y despliegue continuo                              |

> El sitio está construido como un **archivo autocontenido** (HTML, CSS y JS en un solo documento), sin dependencias de build ni backend.

---

## 🎨 Identidad visual

- **Paleta:** azul marino y aqua, en línea con el universo del agua abierta.
- **Tipografía:** _Big Shoulders Display_ para titulares, con un carácter deportivo y compacto.
- **Símbolo:** la ballena, que representa fuerza, libertad e inteligencia.

---

## 🚀 Instalación y uso

No requiere instalación de dependencias ni backend. Clona el repositorio y abre el archivo principal.

### Clonar el repositorio

```bash
git clone https://github.com/giomerida/ketheryon.git
cd ketheryon
```

### Ejecutar localmente

```bash
# Con Python 3
python -m http.server 8080

# Con Node.js
npx serve .
```

Visita `http://localhost:8080` en tu navegador.

### Despliegue en GitHub Pages

Activa GitHub Pages en la configuración del repositorio apuntando a la rama `main` (o `gh-pages`).

---

## 🧩 Secciones del sitio

| Sección               | Ancla         | Descripción                                                                            |
| --------------------- | ------------- | -------------------------------------------------------------------------------------- |
| **Hero**              | `#top`        | Presentación de marca, tagline y accesos a catálogo e historia                         |
| **La marca**          | `#intro`      | Pilares del producto: visión, sellado y transición (T1)                                |
| **Historia**          | `#historia`   | Origen de la marca, significado del nombre, misión y visión                            |
| **Catálogo**          | `#productos`  | Ediciones White y Black con ficha técnica y precio                                     |
| **Tecnología**        | `#tecnologia` | Óptica curva, silicona de doble densidad y recubrimiento antiempañante                 |
| **Preguntas**         | `#preguntas`  | Acordeón con reseñas de usuarios (agua, empañado, comodidad, distracción, competencia) |
| **Atletas**           | `#voces`      | Testimonios y espacio para reseña en video                                             |
| **Noticias y agenda** | —             | Nota del sector y calendario de competencias de noviembre 2026                         |
| **Suscripción**       | —             | Rutas de entrenamiento en aguas abiertas y acceso anticipado a nuevos modelos          |

---

## 🥽 Catálogo de productos

Ambas ediciones comparten ficha técnica e incluyen **funda y ajuste de nariz intercambiable**.

|                 | **White** (Edición 01) | **Black** (Edición 02) |
| --------------- | ---------------------- | ---------------------- |
| Precio          | $599 MXN               | $599 MXN               |
| Estado          | Próximamente           | Próximamente           |
| Perfil          | Bajo / anti-arrastre   | Bajo / anti-arrastre   |
| Hebilla         | Liberación rápida      | Liberación rápida      |
| Sellado         | Anti-empañante         | Anti-empañante         |
| Uso recomendado | Sprint a Full          | Sprint a Full          |

---

## 🔬 Tecnología del producto

1. **Óptica curva de gran ángulo** — amplía el campo periférico para ubicar boyas y nadadores sin perder el ritmo de brazada.
2. **Empaque de silicona de doble densidad** — una capa firme sostiene la forma y otra suave sella con agua fría y oleaje.
3. **Recubrimiento antiempañante de larga duración** — resiste más lavadas que el recubrimiento estándar, pensado para entrenamientos largos.
4. **Hebillas de liberación rápida** — ajuste sin herramientas para ganar segundos en la transición T1.

---

## 📰 Noticias y agenda

La sección de **noticias** destaca el panorama del deporte en México, con una nota del 29 de julio de 2026 sobre los resultados de la selección mexicana de aguas abiertas en los Juegos Centroamericanos y del Caribe y la próxima parada de la Copa del Mundo de Natación en Aguas Abiertas en Cancún.

**Agenda — noviembre 2026**

| Fecha  | Evento                  | Sede                    |
| ------ | ----------------------- | ----------------------- |
| 7 nov  | Aqua Race La Paz        | La Paz, BCS             |
| 7 nov  | 1.ª Edición Cortés Open | Guaymas, Sonora         |
| 8 nov  | Súper Fondo 20 km       | Telchac Puerto, Yucatán |
| 14 nov | Nadando Los Cabos       | San José del Cabo, BCS  |

---

## 🛒 Carrito de compra

Carrito funcional en frontend con:

- Contador de artículos en el encabezado.
- Panel con resumen de productos y total en MXN.
- Botón **Finalizar compra**.
- Aviso de confirmación al agregar un producto.

> ⚠️ Es una **demo de tienda**: no hay pasarela de pago conectada, por lo que no se procesan cobros reales. Para vender se puede integrar Stripe, Mercado Pago o Conekta.

---

## 📁 Estructura del proyecto

```
ketheryon/
├── index.html              # Sitio completo (HTML, CSS y JS autocontenidos)
├── img/                    # Logotipo, fotografías de producto, ilustraciones y galería
└── README.md               # Este archivo
```

---

## 🗺️ Roadmap

- [ ] Integrar pasarela de pago real (Stripe / Mercado Pago / Conekta)
- [ ] Habilitar la venta cuando los modelos pasen de "Próximamente" a disponibles
- [ ] Conectar el formulario de suscripción a un servicio de email (Mailchimp, Brevo, etc.)
- [ ] Publicar la reseña en video de un atleta
- [ ] Actualizar noticias y agenda de eventos de forma periódica
- [ ] Versión en inglés (ES / EN) para el mercado internacional

---

## 🙌 Créditos

**Marca:** Ketheryon — _Adáptate al agua_ 🌊🐋

**Desarrollo:** [Giodev](https://giomerida.dev)

- 🐙 GitHub: [@giomerida](https://github.com/giomerida)
- 🌐 Sitio: [giomerida.dev](https://giomerida.dev)

---

<div align="center">

© 2026 **Ketheryon**. Todos los derechos reservados.
Realizado por **Giodev**.

</div>

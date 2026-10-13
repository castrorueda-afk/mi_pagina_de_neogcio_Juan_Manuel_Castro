# 🍔 BurgerLab - Sitio Web de Negocio Local (HTML5 y CSS3)

Sitio web multipágina desarrollado para **BurgerLab**, un negocio de hamburguesas artesanales, diseñado para resolver una problemática real de los negocios locales que operan en los barrios[cite: 1, 3]. Proyecto estructurado bajo estrictas normas de semántica HTML, metodología BEM en CSS, diseño responsivo y documentación técnica rigurosa[cite: 2, 3].

---

## 1. El proyecto
* **¿Por qué se eligió este negocio?** Se seleccionó una hamburguesería artesanal de barrio debido a que muchos establecimientos locales similares dependen exclusivamente de chats de WhatsApp o redes sociales (como Instagram) para vender. Esto genera cuellos de botella donde pierden clientes potenciales al no poder responder con agilidad, mostrar un menú detallado con precios claros, listar ingredientes o facilitar reservas y pedidos directos[cite: 1, 3].
* **Objetivo del cliente:** Proveer un sitio web sencillo, de carga rápida, adaptado a dispositivos móviles (360px), que transmita una identidad visual fuerte (estética rockera/oscura) y centralice la información de productos, tarifas, opiniones y un formulario de pedidos estructurado[cite: 1, 3].
* **Estrategia de desarrollo y Commits:** El repositorio se estructuró mediante commits atómicos y descriptivos que reflejan la evolución técnica del software:
  1. `git commit -m "Primer commit: Estructura base de index.html y segunda-pagina.html"` (Creación de la arquitectura HTML semántica inicial y navegación multipágina).
  2. `git commit -m "feat: implementacion de estilos css con variables root y diseño rockero"` (Creación del sistema visual, paleta de colores con canal alfa, gradientes y tipografías).
  3. `git commit -m "feat: integracion de imagenes tematicas y ajuste de tarjetas BEM"` (Incorporación de multimedia optimizada y componentes reutilizables con metodología BEM).
  4. `git commit -m "docs: documentacion tecnica README completa y capturas añadidas"` (Consolidación de la documentación técnica y análisis de especificidad).

---

## 2. Estructura y Mapeo de Elementos Obligatorios en el Código
La organización de carpetas y el mapeo exacto de dónde se encuentran los elementos requeridos por la rúbrica son los siguientes:
```text
burger-lab/
├── index.html
├── segunda-pagina.html
├── README.md
├── css/
│   └── styles.css
├── images/
│   ├── hamburguesa-clasica.jpg
│   ├── hamburguesa-bbq.jpg
│   └── hamburguesa-vegetariana.jpg
└── capturas/
    ├── desktop-index.png
    ├── desktop-precio.png
    ├── mobile-360-index.png
    └── mobile-360-precio.png
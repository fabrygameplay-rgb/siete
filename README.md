# Blog de Letras Cajamarquino

Proyecto web desarrollado con **HTML5 y CSS3** que presenta una reseña literaria de una obra cajamarquina, aplicando diseño responsivo mediante media queries personalizadas.

---

## Descripción

**Blog de Letras Cajamarquino** es una página web estática que publica una reseña de la obra:

**“Don Jasho: la fe que resiste y da sentido a un pueblo” – Miguel Garnett**

El sitio combina estructura semántica en HTML con diseño adaptativo en CSS, priorizando:

* Organización clara del contenido
* Identidad visual coherente
* Adaptabilidad a distintos dispositivos
* Control manual de márgenes y posicionamiento

---

## Tecnologías Utilizadas

* HTML5
* CSS3
* Media Queries
* Diseño Responsivo tradicional (uso de `float` en desktop)
* Ajustes progresivos por breakpoints personalizados

---

## Diseño Responsivo

El proyecto se adapta mediante tres rangos principales:

### Desktop (1200px en adelante)

* Imagen alineada a la izquierda usando `float`
* Texto principal con margen izquierdo amplio
* Distribución tipo blog tradicional

### Tablet (601px – 985px)

* Ajuste progresivo de márgenes
* Reducción de padding en el encabezado
* Reposicionamiento visual de imagen y subtítulo
* Corrección de desbordamientos

### Mobile (≤ 600px)

* Eliminación de `float`
* Imagen centrada automáticamente
* Márgenes reducidos
* Texto optimizado para lectura
* Ajuste de tamaño de título

---

## Características de Diseño

* Encabezado con fondo rosado y bordes redondeados
* Bloque principal de texto con fondo bisque
* Imagen con subtítulo alineado visualmente
* Footer estilizado
* Enlace externo con control de `word-break`
* Tipografías combinadas (serif, sans-serif y monospace)

---

## Estructura del Proyecto

```
Blog-Letras-Cajamarquino/
│
├── index.html
├── style.css
└── FotosMagenta/
    └── donjasho.jpg
```

---

## Contenido Incluido

* Título principal
* Subtítulo descriptivo
* Autores de la reseña
* Imagen representativa de la obra
* Subtítulo de imagen
* Reseña crítica completa
* Citas textuales del libro
* Preguntas de reflexión
* Referencia externa al PDF
* Footer institucional

---

## Aprendizajes Aplicados

Durante el desarrollo se trabajó:

* Control manual de márgenes para evitar scroll horizontal
* Manejo de `float` y su desactivación en móviles
* Ajustes específicos por rangos de pantalla
* Alineación precisa de imagen y subtítulo
* Optimización visual en tablet
* Adaptación progresiva del padding del encabezado

---

## Cómo Ejecutarlo

1. Descargar o clonar el repositorio.
2. Abrir `index.html` en el navegador.
3. Probar en modo responsive (DevTools).

---

## 📌 Estado del Proyecto

✔ Finalizado
✔ Responsivo funcional
✔ Sin scroll horizontal
✔ Imagen correctamente integrada en cada dispositivo

---

## Autores de la Reseña

* Becerra Villalobos Iris Yareli
* Burga Tarrillo Maycol
* Leyva Burgos Gleysi Natali
* Rodriguez Zaldaña Luz Yanira

---

## Licencia

Proyecto desarrollado con fines académicos.

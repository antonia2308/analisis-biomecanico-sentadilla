# Evaluación 1: Análisis Biomecánico de Sentadilla 2D

* **Asignatura:** Análisis Bioinstrumental del Movimiento Humano
* **Institución:** Universidad de Chile - Departamento de Kinesiología
* **Integrantes:** Antonia Carreño y Constanza García
* **Gesto Evaluado:** Sentadilla en el plano sagital

---

## 🔗 Enlaces del Proyecto
* 🌐 **Plataforma Web Activa (Netlify):** https://analisis-biomecanico-sentadilla.netlify.app

* 💻 **Repositorio de Código Fuente (GitHub):** https://github.com/antonia2308/analisis-biomecanico-sentadilla

---

## 1. Descripción del Proyecto
Interfaz web interactiva desarrollada para la evaluación cinemática en tiempo real del gesto motor de la sentadilla. La herramienta procesa archivos de video (optimizada para grabaciones a alta velocidad de 240 FPS) para calcular el ángulo interior de flexión de rodilla, detectar de manera automatizada las fases del movimiento (excéntrica, punto de máxima flexión y concéntrica) y estimar perfiles de activación muscular (EMG) basados en la literatura biomecánica.

---

## 2. Requisitos y Dependencias
La aplicación está desarrollada con estándares web nativos (HTML5, CSS3, JavaScript ES6) y **no requiere la instalación previa de entornos de desarrollo ni servidores locales**.

Las librerías requeridas se cargan de forma directa mediante CDN:
* **MediaPipe Pose (v0.5):** Detección e inferencia de puntos de referencia articulares (Landmarks 24, 26 y 28).
* **Chart.js (v3.x):** Renderizado dinámico de los gráficos cinemáticos y de estimación EMG.

---

## 3. Instrucciones de Ejecución

### Opción A: Ejecución Web Pública (Recomendada)
Acceder directamente al enlace público desplegado en Netlify:
👉 https://analisis-biomecanico-sentadilla.netlify.app

### Opción B: Ejecución Local
1. Descargar o descomprimir el repositorio de código de GitHub.
2. Hacer doble clic sobre el archivo `index.html` para abrirlo en cualquier navegador web moderno (Google Chrome, Microsoft Edge o Mozilla Firefox).
3. Asegurarse de contar con conexión a Internet activa para la carga inicial de los modelos de MediaPipe y Chart.js desde sus CDN.

---

## 4. Estructura de Archivos

```text
├── index.html                    # Código fuente principal (HTML5, CSS3 y JavaScript integrado)
├── README.md                     # Documentación y guía de ejecución del proyecto
├── Informe_Bioinstrumental.pdf   # Documento escrito de evaluación 
└── Video_Presentacion_3min.mp4   # Demostración del funcionamiento y resultados cinemáticos

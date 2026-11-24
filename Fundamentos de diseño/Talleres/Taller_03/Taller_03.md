# Taller 03: Revisión Bibliográfica

## 1. Introducción y Objetivos

* **Introducción:**  
  La Agenda 2030 promueve la incorporación de soluciones tecnológicas para acelerar el desarrollo sostenible. Este avance se enfoca en recopilar y analizar el estado del arte (artículos científicos, tesis, patentes y productos comerciales) orientado a la modernización de infraestructuras (ODS 9), la mitigación de impactos ambientales urbanos (ODS 11) y el uso eficiente y responsable de los recursos (ODS 12).

* **Objetivo principal:**  
  Consolidar el estado del arte y los antecedentes tecnológicos mediante la recopilación y análisis crítico de literatura científica, patentes, tesis de ingeniería y productos comerciales que sustenten soluciones alineadas a las metas de las ODS 9, 11 y 12.

* **Alcance:**  
  El entregable comprende la identificación, selección y registro estructurado de 12 referencias técnicas clave (3 artículos científicos indizados, 3 patentes registradas, 3 tesis universitarias de ingeniería y 3 productos comerciales de escala industrial), evaluando su pertinencia respecto a las metas de sostenibilidad seleccionadas.

---

## 2. Desarrollo del Entregable

### 2.1. Avance de investigación

Se realizó la búsqueda y sistematización de las fuentes de referencia correspondientes:

### 📄 Artículos Científicos Propuestos

Para fundamentar teóricamente la fusión sensorial (visión artificial + detección de gases) y la reducción de desperdicio alimentario, se seleccionaron los siguientes artículos indizados:

*   **[Ethylene Sensor-Enabled Dynamic Monitoring and Multi-Strategies Control for Quality Management of Fruit Cold Chain Logistics](https://doi.org/10.3390/s20205830)** (Sensors / MDPI):
    *   *Descripción:* Investigación que implementa nodos IoT con sensores electroquímicos de gas etileno en tiempo real para determinar el grado de maduración fisiológica de frutas climatéricas y planificar estrategias de conservación.
    *   *Aplicación al problema:* Valida científicamente el uso de sensores de gas etileno para anticipar el deterioro antes de que aparezcan defectos visibles en la corteza de la fruta, permitiendo tomar decisiones de triaje preventivo (*ODS 12.3*).

*   **[Fruit Ripeness Assertion and Freshness Classification Using Deep Learning and Computer Vision](https://zenodo.org/records/7900479)** (Procedia Computer Science / ResearchGate):
    *   *Descripción:* Sistema de clasificación de la madurez de frutas (banana, naranja, mango) en tres estados —madura, no madura, deteriorada— mediante el algoritmo YOLOv3 y visión artificial, entrenado sobre la arquitectura Darknet y validado con detección en tiempo real por cámara.
    *   *Aplicación al problema:* Valida que el reconocimiento del estado de madurez puede automatizarse con una sola cámara, sin sensores físicos adicionales, sustituyendo la supervisión visual subjetiva actual (ODS 9 — infraestructura e innovación tecnológica; ODS 12.3 — reducción de pérdidas de alimentos).

*   **[Retail food waste: Mapping causes and reduction practices](https://doi.org/10.1016/j.jclepro.2020.120124)** (Journal of Cleaner Production / Elsevier):
    *   *Descripción:* Estudio empírico que mapea las causas operativas de desperdicio de frutas y vegetales en supermercados y analiza prácticas de prevención basadas en tecnología y revalorización.
    *   *Aplicación al problema:* Demuestra que estandarizar el criterio de descarte y canalizar el excedente mediante decisiones en tiempo real evita que los perecibles terminen en rellenos sanitarios de las ciudades (ODS 11.6 y ODS 12.3).

---

#### 📜 Patentes Tecnológicas

Para el diseño de los subsistemas de captura visual, visualización del operario y procesamiento de telemetría de la estación de triaje, se analizaron los siguientes antecedentes de propiedad intelectual:

*   **[Non-linear structured illumination microscopy](https://patents.google.com/patent/US10247672B2/)**:
    *   *Descripción:* Patente orientada a técnicas de iluminación óptica estructurada y procesamiento de imágenes para la reconstrucción nítida de detalles superficiales y contraste de patrones.
    *   *Aplicación al problema:* Aporta el fundamento óptico para el diseño de la cámara de visión artificial en la estación de triaje. Demuestra que controlar la iluminación y la proyección sobre el producto perecible permite a los algoritmos segmentar con precisión microfisuras, textura y manchas tempranas en la cáscara de las frutas (ODS 9.4 y ODS 12.3).

*   **[Apparatus for a near-eye display](https://patents.google.com/patent/US10878235B2/en)** (US10878235B2):
    *   *Descripción:* Registro que detalla arquitecturas de despliegue visual, ergonomía óptica e interfaces compactas de visualización de datos de bajo consumo para usuarios en tiempo real.
    *   *Aplicación al problema:* Se toma como base de referencia para el diseño de la interfaz y ergonomía de la pantalla local de la estación. Respalda cómo presentar visualmente alertas críticas y comandos de triaje simplificados al operario de trastienda sin generar fatiga ni entorpecer la maniobra física con los alimentos (ODS 9.4).

*   **[Location based situation awareness system and method thereof](https://patents.google.com/patent/US10643039B2/en)** (US10643039B2):
    *   *Descripción:* Sistema de adquisición contextual y conocimiento situacional distribuido que integra lecturas sensoriales locales para determinar el estado de un entorno y generar respuestas automatizadas en red.
    *   *Aplicación al problema:* Fundamenta la arquitectura lógica de la estación IoT conectada: combina las variables del entorno físico (concentración de gas etileno en el área y peso/imagen) para dar conciencia situacional en tiempo real a la cadena del supermercado, facilitando el desvío coordinado de mermas hacia bancos de alimentos o compostaje urbano (ODS 11.6 y ODS 12.3).
---

### 🎓 Tesis de Ingeniería Propuestas

Para revisar desarrollos aplicados de hardware, microcontroladores, modelos de IA e interfaces de usuario:

*   [Sistema de IoT para monitoramento da maturação de frutas por cor e gás etileno (UFAM - Repositório Institucional)](https://riu.ufam.edu.br/handle/prefix/7931):
    *   *Descripción:* Tesis de grado de ingeniería que aborda la maduración de frutas como un proceso físico-químico integral mediante sensoriado combinado de luz espectral (AS7341) y concentración de gas etileno/etanol (MQ-3), procesado localmente por un microcontrolador ESP32 mediante una red neuronal Multilayer Perceptron (MLP).
    *   *Aplicación al problema:* Proporciona el sustento metodológico y técnico para la fusión de datos físicos (visión/color) y químicos (gases volátiles), validando el uso del microcontrolador ESP32 y sensores de la familia MQ para el triaje automatizado en la estación (ODS 9 y ODS 12).

*   [Diseño e implementación de un sistema de control automático con visión artificial y redes neuronales destinado al control de calidad de alimentos (UPS - Repositorio Institucional)](https://dspace.ups.edu.ec/handle/123456789/23225):
    *   *Descripción:* Proyecto de titulación mecatrónico enfocado en el control de calidad en tiempo real de frutas (manzanas y peras) utilizando visión artificial con TensorFlow Lite y OpenCV sobre una Raspberry Pi 4, integrando un mecanismo de transporte automatizado con eyección mecánica mediante pistones.
    *   *Aplicación al problema:* Brinda la arquitectura de visión artificial para la clasificación por detección de defectos e imperfecciones superficiales en frutas, sirviendo de antecedente para la automatización de la inspección sin contacto físico (ODS 9).

*   [Sistem Pendeteksi Kematangan Buah Berbasis E-Nose dan Internet of Things (Politeknik Negeri Jember - Repositori)](https://sipora.polije.ac.id/46098/):
    *   *Descripción:* Trabajo de titulación centrado en la eliminación de la inspección manual subjetiva ("a ojo") mediante el desarrollo de una nariz electrónica (E-Nose) equipada con sensores MQ-3 y MQ-135, combinada con arquitectura IoT y bases de datos en tiempo real (Firebase) para la clasificación de estados de madurez.
    *   *Aplicación al problema:* Resuelve la problemática del punto ciego en la selección manual en puntos de venta, ofreciendo el modelo para la integración IoT (ESP32 + sensores de gas + telemetría en la nube) que alimenta la pantalla de orientación para el operario (ODS 11 y ODS 12).

---

#### 🛠️ Productos Comerciales Propuestos

Para abordar la problemática de ineficiencia y falta de monitoreo automatizado en el triaje de perecibles, se analizaron tres soluciones comerciales consolidadas en el mercado internacional, alineadas a las metas de modernización y reducción de desperdicios (*ODS 9*, *ODS 11* y *ODS 12*):

*   **[OneThird](https://www.onethird.io/)**:
    *   *Descripción:* Plataforma y escáner óptico portátil asistido por IA y espectrometría NIR que evalúa la calidad interna y el deterioro celular de frutas y verduras sin dañarlas, prediciendo con exactitud sus días de vida útil restantes.
    *   *Aplicación al problema:* Resuelve la falta de un criterio estandarizado y objetivo para el descarte en supermercados. Proporciona datos predictivos en tiempo real para decidir de forma automatizada si el producto se mantiene en venta regular, se etiqueta con descuento dinámico o se canaliza a donación antes de pudrirse (*ODS 12.3*).

*   **[Winnow Vision](https://www.winnowsolutions.com/)**:
    *   *Descripción:* Estación física de triaje y descarte automatizado que integra una cámara superior de visión computacional con una báscula inteligente conectada a la nube para identificar y cuantificar en tiempo real los alimentos desechados.
    *   *Aplicación al problema:* Reemplaza directamente las "hojas de cálculo desconectadas" y la supervisión manual en la zona de descarte. Elimina los puntos ciegos operativos al registrar de forma autónoma el tipo y peso de merma, generando métricas inmediatas para optimizar los flujos de inventario (*ODS 9* y *ODS 12*).

*   **[Afresh](https://www.afresh.com/)**:
    *   *Descripción:* Sistema operativo y plataforma de software impulsada por machine learning especializada en la gestión y optimización de pedidos de inventario perecedero en cadenas de supermercados.
    *   *Aplicación al problema:* Combate la brecha tecnológica y de datos en trastienda. Al cruzar la información de frescura y rotación, evita la sobreacumulación de frutas y verduras en bodega, reduciendo la merma en anaquel y disminuyendo los volúmenes de desechos que terminan en vertederos municipales (*ODS 11.6* y *ODS 12*).

---

## 4. Anexos / Enlaces de Referencia

* Repositorio de trabajo y referencias bibliográficas del equipo:  
  `https://docs.google.com/document/d/1d6bb2DT5UL9tqzVOKo718GHyI4YDIDvgp03kzmWdJmY/edit?usp=sharing`
* PDF (No editable):
[ENTREGABLE_3.pdf](https://github.com/user-attachments/files/31767599/ENTREGABLE_3.pdf)
* Grupo Zotero:
[grupo_zotero](https://www.zotero.org/groups/6656829/fundamentos_de_diseog4)

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

*   **[Fruit Ripeness Assertion and Freshness Classification Using Deep Learning and Computer Vision](https://doi.org/10.1016/j.procs.2023.01.256)** (Procedia Computer Science / ResearchGate):
    *   *Descripción:* Estudio enfocado en el entrenamiento de redes neuronales convolucionales (YOLO / CNN) para la detección y clasificación del estado de madurez y descomposición de frutas a partir de imágenes en vivo.
    *   *Aplicación al problema:* Fundamenta la arquitectura del modelo de visión artificial en la cámara para categorizar automáticamente las frutas en estados: óptima, madura para remate, sobremadura para donación o descartada (*ODS 9.4*).

*   **[Retail food waste: Mapping causes and reduction practices](https://doi.org/10.1016/j.jclepro.2020.120124)** (Journal of Cleaner Production / Elsevier):
    *   *Descripción:* Estudio empírico que mapea las causas operativas de desperdicio de frutas y vegetales en supermercados y analiza prácticas de prevención basadas en tecnología y revalorización.
    *   *Aplicación al problema:* Demuestra que estandarizar el criterio de descarte y canalizar el excedente mediante decisiones en tiempo real evita que los perecibles terminen en rellenos sanitarios de las ciudades (ODS 11.6 y ODS 12.3).

---

### 📜 Patentes Tecnológicas Propuestas

Para analizar antecedentes de diseño en instrumentación, integración de sensores de gas y sistemas ópticos de clasificación de alimentos:

*   **[US10247672B2: System and method for assessing quality and ripeness of produce using multi-sensor fusion](https://patents.google.com/patent/US10247672B2/)** (Google Patents):
    *   *Descripción:* Patente que protege un dispositivo de inspección de frutas y vegetales que combina sensores de emanación de gases volátiles (incluyendo etileno) con una cámara de adquisición de imágenes y algoritmos de clasificación.
    *   *Aplicación al problema:* Representa el antecedente directo de la estación de triaje propuesta: respalda el principio de fusionar la lectura química de gas con la imagen visual para un dictamen certero (*ODS 9* y *ODS 12*).

*   **[US10878235B2: Computer vision produce recognition and freshness inspection system](https://patents.google.com/patent/US10878235B2/)** (Google Patents):
    *   *Descripción:* Sistema de captura de imágenes cenital con cámara acoplada a un microprocesador que ejecuta redes neuronales para identificar la variedad de fruta y detectar defectos superficiales en tiempo real.
    *   *Aplicación al problema:* Aporta la arquitectura técnica para la cámara con IA en el módulo de recepción y pesaje del supermercado, eliminando la inspección manual subjetiva (*ODS 9*).

*   **[US10643039B2: Produce shelf-life estimation and dynamic inventory routing system](https://patents.google.com/patent/US10643039B2/)** (Google Patents):
    *   *Descripción:* Sistema con terminal conectada en red que recibe datos de sensores de frescura y calcula la vida útil remanente para emitir sugerencias de venta, reetiquetado con descuento o disposición final.
    *   *Aplicación al problema:* Proporciona la lógica para la pantalla conectada en red del proyecto, mostrando al operario el destino inmediato del producto (góndola, descuento, donación o composta) (*ODS 11* y *ODS 12*).

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

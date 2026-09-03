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

*   **[The Role of Food Waste Technology in Retail: Computer Vision and IoT for Shelf-Life Optimization](https://doi.org/10.1016/j.resconrec.2022.106589)** (Resources, Conservation and Recycling):
    *   *Descripción:* Análisis del impacto de sistemas de triaje digital en supermercados, evaluando cómo las alertas en tiempo real sobre perecibles evitan que los alimentos terminen en vertederos urbanos.
    *   *Aplicación al problema:* Articula el impacto del proyecto con las metas urbanas (*ODS 11.6*), demostrando cómo el desvío oportuno a bancos de alimentos y compostaje mitiga la generación de gas metano por descomposición orgánica en basurales.

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

### 🛠️ Productos Comerciales Propuestos

Para analizar soluciones que ya operan a nivel de supermercados y cadenas de distribución:

*   **[Tiliter Smart Vision Scale](https://www.tiliter.com/)**:
    *   *Descripción:* Balanza de visión computacional para supermercados que identifica frutas y verduras automáticamente mediante una cámara cenital con IA sin necesidad de códigos de barras.
    *   *Aplicación al problema:* Referente comercial directo del módulo de cámara e interfaz de pantalla para operarios en la zona de pesaje y control de calidad.

*   **[Afresh Fresh Operating System](https://www.afresh.com/)**:
    *   *Descripción:* Plataforma de software con IA para supermercados especializada en predecir la demanda y la vida útil de frutas y verduras para reducir el desperdicio.
    *   *Aplicación al problema:* Cierra la brecha de las "hojas de cálculo desconectadas" al convertir los datos de calidad y maduración de los productos en órdenes automáticas de descuento o reposición.

*   **[Sensitech / Strella Biotechnology Ethylene & Biosensors](https://www.sensitech.com/)**:
    *   *Descripción:* Sensores IoT de monitoreo de etileno e indicadores de gas en tiempo real diseñados para cámaras de maduración y trastienda de supermercados.
    *   *Aplicación al problema:* Demuestra la viabilidad comercial de medir emanaciones de gas etileno en trastienda para tomar decisiones de rotación de inventario antes de que el producto se pudra.

## 3. Conclusiones

* Se recopilaron y estructuraron exitosamente las 12 fuentes del estado del arte requeridas, integrando producción científica, propiedad intelectual (patentes), proyectos de grado e implementaciones comerciales.
* Las patentes y tesis identificadas demuestran la viabilidad técnica de capturar variables eléctricas de forma no intrusiva y procesar telemetría en tiempo real.
* La base bibliográfica recopilada valida la articulación del proyecto con las metas de las ODS 9, 11 y 12, sirviendo como fundamento para la etapa de diseño de la solución de ingeniería.

---

## 4. Anexos / Enlaces de Referencia

* Repositorio de trabajo y referencias bibliográficas del equipo:  
  `https://docs.google.com/document/d/1d6bb2DT5UL9tqzVOKo718GHyI4YDIDvgp03kzmWdJmY/edit?usp=sharing`

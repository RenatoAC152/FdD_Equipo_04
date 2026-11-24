# HORIZON | Equipo 04

**Estación IoT de triaje de plátano de seda y pimiento rojo**

Fundamentos de Diseño 2026-II · Universidad Peruana Cayetano Heredia

HORIZON propone una estación de inspección con visión artificial y sensores para apoyar el triaje de productos y reducir las mermas de alimentos.

## Integrantes y fotografías

Las fotos actuales se enlazan como referencia. La última columna indica dónde cargar cada foto con vestimenta elegante.

| Integrante | Carrera | Función | Foto actual | Ruta para la foto formal |
| --- | --- | --- | --- | --- |
| Alarcon Camones, Renato Angelo | Ingeniería Industrial | Diseño | ![Alarcon Camones, Renato Angelo](Recursos/Im%C3%A1genes/Renato.jpeg) | `Recursos/Imágenes/Renato Alarcon.png` |
| Barzola Anglas, Sebastian Omar | Ingeniería Informática | Investigación | ![Barzola Anglas, Sebastian Omar](Recursos/Im%C3%A1genes/Sebastian.jpeg) | `Recursos/Imágenes/Sebastian Barzola.png` |
| Cortez Dominguez, Jherson David | Ingeniería Informática | Programación | ![Cortez Dominguez, Jherson David](Recursos/Im%C3%A1genes/Jherson.jpeg) | `Recursos/Imágenes/Jherson Cortez.png` |
| Machco Cueva, Rodolfo Aaron Giovanni | Ingeniería Industrial | Liderazgo | ![Machco Cueva, Rodolfo Aaron Giovanni](Recursos/Im%C3%A1genes/Aaron.jpeg) | `Recursos/Imágenes/Rodolfo Machco.png` |
| Veramendi Minaya, Mathias Andre | Ingeniería Informática | Documentación | ![Veramendi Minaya, Mathias Andre](Recursos/Im%C3%A1genes/Mathias.jpeg) | `Recursos/Imágenes/Mathias Veramendi.png` |

### Fotografía grupal

[Ver fotografía grupal actual](<Recursos/Im%C3%A1genes/grupo.jpeg>). La foto grupal con vestimenta elegante se cargará en `Recursos/Imágenes/Foto grupal.png`.

## Navegación

- [Fundamentos de diseño](<Fundamentos%20de%20dise%C3%B1o/README.md>)
- [Entregable 4](<Fundamentos%20de%20dise%C3%B1o/Entregables/Entregable%204/README.md>)
- [Proyecto y módulos](<Proyecto/README.md>)
- [Recursos de apoyo](<Recursos/README.md>)

## Antecedentes del proyecto

## 🌍 Descripción del Equipo
Somos el **Equipo 04** del curso **Fundamentos de diseño 2026-II**, conformado por estudiantes de la carrera de Informática / Industrial.
Nuestro objetivo es aplicar la metodología de diseño para generar soluciones innovadoras con impacto social, tecnológico y ambiental.

## 🎯 ODS Seleccionadas
Como equipo trabajaremos con tres ODS de forma conjunta: una principal y dos secundarias, que en conjunto nos dan el marco para abordar la problemática descrita más abajo.

### 🏭 ODS Principal: ODS 9 — Industria, Innovación e Infraestructura

**📌Descripción General:**
El ODS 9 se enfoca en construir infraestructuras resilientes, promover la industrialización inclusiva y sostenible, y fomentar la innovación tecnológica. Es un pilar fundamental para encontrar soluciones duraderas a los desafíos económicos y ambientales, facilitando la integración del desarrollo tecnológico dentro de los procesos industriales tradicionales.

<p align="center"><img src="Recursos/Im%C3%A1genes/ods9.gif" width="180"/>

**🎯Meta 9.4:**
> 💡De aquí a 2030, modernizar la infraestructura y reconfigurar las industrias para que sean sostenibles, utilizando los recursos con mayor eficacia y promoviendo la adopción de tecnologías y procesos industriales limpios y ambientalmente racionales.

### 🏙️ ODS Secundaria: ODS 11 — Ciudades y Comunidades Sostenibles

**📌Descripción General:**
El ODS 11 busca lograr que las ciudades y los asentamientos humanos sean inclusivos, seguros, resilientes y sostenibles, mejorando el acceso a vivienda, transporte, servicios básicos y espacios públicos, al tiempo que se reduce el impacto ambiental de las zonas urbanas e industriales.

<p align="center"><img src="Recursos/Im%C3%A1genes/ods11.gif" width="180"/>

**🎯Meta 11.6:**
> 💡De aquí a 2030, reducir el impacto ambiental negativo per cápita de las ciudades, incluso prestando especial atención a la calidad del aire y la gestión de los desechos municipales y de otro tipo.

### 🔄 ODS Secundaria: ODS 12 — Producción y Consumo Responsables

**📌Descripción General:**
El ODS 12 tiene como objetivo garantizar modalidades de consumo y producción sostenibles, promoviendo el uso eficiente de los recursos naturales, la reducción de desperdicios mediante prevención, reducción, reciclado y reutilización, y la adopción de prácticas empresariales sostenibles.

<p align="center"><img src="Recursos/Im%C3%A1genes/ods12.gif" width="180"/>

**🎯Meta 12.2:**
> 💡De aquí a 2030, lograr la gestión sostenible y el uso eficiente de los recursos naturales.

---
## ⚠️Problemática
Esta es la problemática central que el proyecto busca combatir, abordada desde el marco conjunto de las tres ODS seleccionadas (industria e innovación, ciudades sostenibles, y producción y consumo responsables).

**🏷️Tema:** Ineficiencia y falta de monitoreo automatizado de mermas en el sector retail alimentario (supermercados y minimarkets).

**🔍Descripción del problema:**

Actualmente, el sector de los supermercados opera con pérdidas significativas de recursos materiales, principalmente en la categoría de frutas y verduras, debido a que sus procesos de selección y descarte dependen de control manual, supervisión visual subjetiva y registros en hojas de cálculo desconectadas. La falta de recolección de datos en tiempo real sobre el estado de conservación de estos productos orgánicos genera "puntos ciegos" operativos.

​Desde la ingeniería industrial, la falta de un criterio estandarizado para evaluar la calidad de las frutas y verduras impide aplicar principios de optimización y mejora continua, como la redistribución eficiente o el remate oportuno de alimentos próximos a caducar. Desde la ingeniería informática, el problema radica en la brecha tecnológica y la ausencia de infraestructura IoT con modelos de Inteligencia Artificial (IA) integrados en la zona de almacenamiento y descarte.

​Nuestro enfoque será implementar una Estación IoT de Triaje que elimine esta desconexión de datos mediante reconocimiento de imágenes con IA y visión artificial. Este sistema analizará con alta precisión el estado de maduración, manchas o deterioro físico en frutas y verduras específicas, determinando de manera automatizada y objetiva el descarte u homologación del producto (venta con descuento, donación o composta). Con esto, se generarán métricas en tiempo real para reducir la merma y alinearse con los ODS 9, 11 y 12.

---

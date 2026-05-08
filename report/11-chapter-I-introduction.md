# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
Somos TechnoByteLambders, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con el uso de la tecnología para mejorar la conservación y monitoreo de medicamentos en el sector salud, enfocados en el desarrollo de soluciones innovadoras orientadas al control de condiciones ambientales en el Perú.
Nuestra misión es diseñar soluciones tecnológicas que permitan garantizar el almacenamiento adecuado de medicamentos mediante el monitoreo en tiempo real de variables como temperatura, humedad y luz, mejorando la seguridad, la eficiencia y la toma de decisiones en organizaciones del sector salud.
Nuestra visión es contribuir a la modernización de la gestión del almacenamiento y transporte de medicamentos en el país, impulsando el uso de tecnologías como IoT y plataformas digitales para lograr un control más eficiente, confiable y basado en datos.
Nuestro producto principal es MediTrack Sensor, una plataforma web que permite a clínicas, farmacias, hospitales y entidades de distribución supervisar en tiempo real las condiciones ambientales de los medicamentos, generando alertas, almacenando datos históricos y facilitando la gestión de la conservación. Esta solución reemplaza procesos manuales y limitados, ofreciendo un sistema centralizado que mejora la trazabilidad y reduce riesgos en la calidad de los productos farmacéuticos.

### 1.1.2. Perfiles de integrantes del equipo
| Código     | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Foto                                 |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| U202216240 | **Luis Angel Tufiño Argüelles**<br>Ingeniería de Software<br><br>Elegí la carrera de Ingeniería de Software motivado por mi interés inicial en comprender el funcionamiento de un programa básico como Scratch. Posteriormente, durante la pandemia, comencé a modificar juegos sencillos, lo que representó mis primeros acercamientos al mundo de la programación.<br><br>Cuento con conocimientos en lenguajes como C++, Python y JavaScript. Además, durante el verano reforcé mis habilidades en el desarrollo de páginas web utilizando HTML y CSS, así como en la creación de bots para Discord y Telegram empleando el lenguaje Python.<br><br>Considero que mi capacidad para generar ideas, junto con mi disposición para escuchar y trabajar en equipo, pueden aportar de manera positiva al desarrollo de este proyecto. | ![Foto](./assets/luis-tufino.png)                   |
| U20221587  | **Franco Diego Rioja Nuñez** <br>Ingeniería de Software<br><br>Tengo 21 años y actualmente curso el séptimo ciclo de la carrera. Me considero una persona proactiva y comprometida en el desarrollo de proyectos, además de ser colaborativa y atenta a las necesidades y problemas de mis compañeros de equipo. En paralelo, me encuentro llevando cursos de especialización en Análisis de Datos, con el objetivo de ampliar mis conocimientos y fortalecer mis competencias profesionales.<br>                                                                                                                                                                                                                                                                                                                                    | ![Foto](./assets/Franco-Rioja.png)   |
| U20231e443 | **Mateo Sebastian Urviola Condori** <br>"Soy estudiante del programa para ingeniería en software, tengo 20 años y estoy buscando mi lugar en el mundo de la tecnología. Llevo año y medio estudiando programación y me gustaría seguir mejorando constantemente, creo que tengo potencial para desarrollar sistemas muy buenos.Tengo conocimientos en C++ basico-intermedio, dominio básico en python con el cuál he hecho web scraping y ya he manejado openGL como motor gráfico.<br>                                                                                                                                                                                                                                                                                                                                              | ![Foto](./assets/mateo-urviola.png)  |
| U202419440 | **Dhilsen Armil Mallqui Vilca** <br><br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | ![Foto](./assets/dhilsen-malqui.png) |
| U202319037 | **Diego Fernando Herrera Enriquez** <br>Con creatividad, responsabilidad y con disposición para aprender y crecer junto a mi equipo, pienso en entregar una aportación sobresaliente. Me adapto con facilidad a distintos retos, aportando ideas y soluciones prácticas que buscan mejorar cada proyecto. Valoro las buenas prácticas en esta profesión para servir a las personas con pasión por lo que hacemos. Conocimientos competentes en Frontend (HTML, CSS, JS) y experimentado en el diseño de proyectos a nivel integral. Mi enfoque está orientado a desarrollar soluciones prácticas y efectivas, siempre priorizando la satisfacción del usuario y con visión a seguir mejorando en futuros proyectos<br>                                                                                                               | ![Foto](./assets/diego-herrera.png)  |
---

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
#### Who (¿Quiénes son los involucrados?)
Los principales involucrados son hospitales, clínicas, farmacias, almacenes farmacéuticos y entidades del Estado encargadas de la distribución de medicamentos en el Perú. Asimismo, los pacientes se ven directamente afectados, ya que dependen de que los medicamentos se conserven en condiciones adecuadas para garantizar su efectividad y seguridad.

#### What (¿Qué se necesita?)
Existe la necesidad de un sistema que permita monitorear en tiempo real las condiciones ambientales de almacenamiento de medicamentos, como temperatura, humedad y exposición a la luz, debido a la falta de control continuo y herramientas tecnológicas que aseguren su correcta conservación.

#### Where (¿Dónde ocurre el problema?)
El problema se presenta en hospitales y almacenes de medicamentos a nivel nacional, especialmente en zonas de provincias como Tingo María, así como en centros de distribución donde no se cuenta con infraestructura adecuada para el almacenamiento de productos farmacéuticos.

#### When (¿Cuándo surge esta necesidad?)
Esta necesidad surge de manera constante durante todo el proceso de almacenamiento y distribución de medicamentos, especialmente en contextos donde no existen sistemas automatizados de monitoreo y control, lo que hace que el problema sea continuo y vigente en la actualidad.

#### Why (¿Por qué existe esta necesidad?)
La problemática se origina debido a la falta de infraestructura adecuada, deficiencias en la gestión de almacenes y ausencia de sistemas de monitoreo en tiempo real. Según reportes de la Contraloría General de la República, se han identificado casos de almacenamiento inadecuado en hospitales, mientras que el Estado ha reconocido la necesidad de mejorar la infraestructura de almacenamiento, lo que evidencia que las condiciones actuales no garantizan la correcta conservación de medicamentos.

#### How (¿Cómo se manifiesta el problema?)
El problema se manifiesta mediante el almacenamiento de medicamentos en condiciones inadecuadas, como exposición al sol, humedad, polvo o cercanía a zonas contaminantes. Además, se observa la falta de control de temperatura y la ausencia de sistemas automatizados, lo que obliga a depender de procesos manuales e improvisados que incrementan el riesgo de deterioro de los productos farmacéuticos.

#### How Much (¿Cuánto cuesta o qué magnitud tiene el problema?)
El problema tiene un impacto significativo en el sistema de salud, generando pérdidas económicas por medicamentos deteriorados, riesgos para la salud de los pacientes y deficiencias en la atención médica. La magnitud es considerable, ya que afecta a múltiples establecimientos de salud a nivel nacional y evidencia la necesidad de implementar soluciones tecnológicas que mejoren el control y la trazabilidad de los medicamentos.

---

#### Descripción de la Problemática

En el Perú, el almacenamiento inadecuado de medicamentos representa una problemática vigente en el sistema de salud. Según reportes de la Contraloría General de la República, en el Hospital de Tingo María se evidenciaron deficiencias en el almacenamiento, como medicamentos ubicados en pasadizos, expuestos a condiciones no adecuadas y sin control ambiental, lo que compromete su calidad y efectividad.

Asimismo, el diario oficial El Peruano señala que el Estado ha identificado limitaciones en la infraestructura de almacenamiento de medicamentos, lo que ha llevado a la implementación de mejoras y nuevos almacenes especializados. Esto evidencia que previamente no se contaba con condiciones óptimas para la conservación de productos farmacéuticos, especialmente aquellos que requieren control de temperatura y humedad.

Esta situación refleja una problemática estructural caracterizada por la falta de monitoreo en tiempo real, deficiencias en infraestructura y dependencia de procesos manuales, lo que incrementa el riesgo de deterioro de los medicamentos. Como consecuencia, se generan pérdidas económicas, desabastecimiento y, principalmente, riesgos para la salud de los pacientes, evidenciando la necesidad de implementar soluciones tecnológicas que permitan supervisar de manera eficiente las condiciones de almacenamiento.
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
### Dominio y Alcance del Problema
El proyecto se enmarca en el sector salud, específicamente en la gestión y almacenamiento de medicamentos dentro de hospitales, centros de distribución y almacenes farmacéuticos en el Perú. A pesar de la importancia crítica de mantener condiciones adecuadas de conservación, la supervisión de variables como temperatura, humedad y luz aún presenta deficiencias debido a procesos manuales, infraestructura limitada y ausencia de monitoreo en tiempo real.

El problema se presenta a nivel nacional, con énfasis en hospitales públicos y centros de distribución de medicamentos, incluyendo almacenes estratégicos como los de Lurín. Afecta tanto a zonas urbanas como rurales, donde las limitaciones tecnológicas y de infraestructura dificultan el control adecuado de las condiciones de almacenamiento.

---

### Actores Involucrados (Segmentos de Cliente)
- Personal encargado de almacenes farmacéuticos (operarios, técnicos y responsables de control): responsables directos del almacenamiento y conservación de medicamentos.
- Personal de salud (farmacéuticos, administradores hospitalarios): supervisan el uso y disponibilidad de medicamentos.
- Entidades del Estado (MINSA, redes de salud): responsables de la distribución y cumplimiento de normativas.
- Pacientes: usuarios finales afectados por la calidad de los medicamentos.

---

### Problemas, Puntos de Dolor y Causas
**Puntos de dolor**
- Falta de herramientas tecnológicas para monitoreo en tiempo real.
- Dificultad para detectar variaciones de temperatura o humedad.
- Falta de alertas automáticas.
- Baja trazabilidad de los medicamentos.
- Pérdidas económicas por deterioro o vencimiento.

**Causas raíz**
- Infraestructura insuficiente.
- Ausencia de sistemas automatizados.
- Procesos manuales propensos a errores.
- Falta de integración tecnológica.
- Supervisión limitada y no continua.

---

### Brecha, Impactos e Indicadores
**Brecha detectada**  
No existe un sistema digital integrado que permita monitorear en tiempo real las condiciones ambientales de almacenamiento de medicamentos, generando alertas y registros históricos confiables.

**Impactos y riesgos**
- Deterioro de medicamentos.
- Riesgos para la salud.
- Pérdidas económicas.
- Incumplimiento normativo.
- Desabastecimiento.

**Indicadores**
- Número de incidencias.
- Tiempo de detección de fallas.
- % de medicamentos deteriorados.
- Nivel de cumplimiento.
- Tiempo de respuesta.
- Disponibilidad de datos históricos.

#### 1.2.2.2. Lean UX Assumptions
**Sobre usuarios (personal de almacenes, farmacéuticos, administradores de salud)**
- Asumimos que el personal encargado del almacenamiento prioriza mantener condiciones adecuadas de temperatura, humedad y luz para conservar los medicamentos.
- Asumimos que necesitan información en tiempo real sobre las condiciones ambientales para tomar decisiones rápidas.
- Asumimos que valoran sistemas simples y fáciles de usar, debido a la carga operativa diaria.
- Asumimos que toleran poca complejidad en el uso de nuevas tecnologías, por lo que requieren interfaces intuitivas.
- Asumimos que consideran importante recibir alertas inmediatas ante cualquier variación crítica en las condiciones de almacenamiento.
- Asumimos que una parte del personal depende aún de registros manuales, como cuadernos o Excel.
- Asumimos que existe interés en digitalizar procesos si esto reduce errores y facilita su trabajo.
- Asumimos que el personal valora la trazabilidad de los datos para auditorías y cumplimiento de normativas.

**Sobre entidades de salud (hospitales, MINSA, centros de distribución como Lurín)**
- Asumimos que muchas entidades gestionan el almacenamiento de medicamentos con procesos manuales o parcialmente digitalizados.
- Asumimos que carecen de monitoreo continuo y automatizado de condiciones ambientales.
- Asumimos que necesitan garantizar el cumplimiento de normativas sanitarias relacionadas al almacenamiento.
- Asumimos que requieren información histórica para auditorías y toma de decisiones.
- Asumimos que buscan reducir pérdidas económicas por medicamentos deteriorados o vencidos.
- Asumimos que la centralización de información facilitaría la gestión de múltiples almacenes o sedes.
- Asumimos que existe interés en soluciones tecnológicas que mejoren la eficiencia operativa.

**Sobre comportamiento y riesgos**
- Asumimos que la falta de monitoreo en tiempo real incrementa el riesgo de deterioro de medicamentos.
- Asumimos que errores humanos en registros manuales pueden generar información inexacta.
- Asumimos que la ausencia de alertas inmediatas retrasa la respuesta ante condiciones críticas.
- Asumimos que condiciones ambientales inadecuadas pueden pasar desapercibidas durante largos periodos.
- Asumimos que la falta de trazabilidad dificulta identificar responsabilidades ante incidentes.

**Sobre tecnología y datos**
- Asumimos que las entidades están dispuestas a implementar sensores IoT si estos mejoran el control y monitoreo.
- Asumimos que existe disponibilidad de conexión a internet en la mayoría de almacenes principales.
- Asumimos que los datos de temperatura, humedad y luz pueden ser recolectados y procesados en tiempo real.
- Asumimos que la visualización de datos en dashboards facilita la toma de decisiones.
- Asumimos que el registro histórico de datos permitirá análisis y mejora continua del proceso.
- Asumimos que la automatización mediante alertas reducirá la dependencia de la supervisión manual.

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hipótesis 1:**  
  Si ofrecemos una plataforma web que permita el monitoreo en tiempo real de las condiciones ambientales de almacenamiento de medicamentos, entonces el personal encargado podrá tomar decisiones oportunas para evitar el deterioro de los productos farmacéuticos.

- **Hipótesis 2:**  
  Si las entidades de salud cuentan con un sistema que genere alertas automáticas ante variaciones de temperatura, humedad o luz, entonces podrán reducir riesgos asociados al almacenamiento inadecuado y mejorar la seguridad de los medicamentos.

- **Hipótesis 3:**  
  Si los usuarios pueden visualizar datos históricos y reportes sobre las condiciones de almacenamiento, entonces podrán mejorar la trazabilidad y cumplir con las normativas sanitarias de manera más eficiente.

- **Hipótesis 4:**  
  Si se implementa el uso de sensores IoT integrados a una plataforma digital, entonces se reducirá la dependencia de procesos manuales y se minimizarán los errores humanos en el control de condiciones ambientales.

- **Hipótesis 5:**  
  Si las entidades de salud utilizan un sistema centralizado para gestionar múltiples almacenes o sedes, entonces podrán optimizar la gestión de recursos, reducir pérdidas económicas y mejorar la eficiencia operativa.

#### 1.2.2.4. Lean UX Canvas

**1. Business Problem**  
La gestión del almacenamiento de medicamentos en el sistema de salud presenta deficiencias debido a la falta de monitoreo en tiempo real y el uso de procesos manuales. Esto provoca que variables críticas como la temperatura, humedad y exposición a la luz no sean controladas adecuadamente, generando riesgos en la calidad de los medicamentos tanto en almacenes como durante su transporte.

**2. Business Outcomes**
- Reducir la pérdida de medicamentos por condiciones inadecuadas de almacenamiento.
- Mejorar la eficiencia en la gestión de almacenes farmacéuticos.
- Disminuir el tiempo de respuesta ante incidencias relacionadas con condiciones ambientales.
- Asegurar el cumplimiento de normativas sanitarias en almacenamiento de medicamentos.
- Optimizar la trazabilidad y control de los productos farmacéuticos en múltiples sedes.

**3. Users**
- Personal encargado de almacenes farmacéuticos (operarios, técnicos y responsables de control).
- Farmacéuticos y administradores de hospitales.
- Entidades del sector salud como el MINSA y centros de distribución (ej. almacenes de Lurín).

**4. User Benefits**
- Monitoreo en tiempo real de condiciones ambientales.
- Alertas automáticas ante variaciones críticas.
- Acceso a datos históricos para auditorías y toma de decisiones.
- Reducción de procesos manuales y errores humanos.
- Mejora en la seguridad y calidad de los medicamentos.

**5. Solutions**
- Plataforma web con dashboards para visualizar condiciones ambientales en tiempo real.
- Integración con sensores IoT para capturar datos de temperatura, humedad y luz.
- Sistema de alertas automáticas ante condiciones fuera de rango.
- Módulo de reportes y almacenamiento de datos históricos.
- Gestión centralizada para múltiples almacenes o sedes.

**6. Hypotheses**
- Si implementamos un sistema de monitoreo en tiempo real, el personal podrá detectar problemas antes de que afecten los medicamentos.
- Si se automatizan las alertas, se reducirá el riesgo de deterioro por falta de respuesta oportuna.
- Si centralizamos la información de múltiples almacenes, las entidades de salud mejorarán su control y eficiencia operativa.
- Si se digitalizan los registros de almacenamiento, se reducirá el error humano y se mejorará la trazabilidad.
- Si el sistema es fácil de usar, el personal adoptará la tecnología y reemplazará los métodos manuales.

**7. What’s the most important thing we need to learn first?**  
Primero necesitamos entender si el personal encargado de almacenes y las entidades de salud están dispuestos a adoptar una solución tecnológica para el monitoreo en tiempo real, así como sus necesidades específicas y limitaciones en el uso de estas herramientas.

**8. What’s the least amount of work we need to do to learn the next most important thing?**  
Realizar entrevistas con personal de almacenes y profesionales de salud, además de pruebas de prototipos simples (mockups o dashboards básicos) para validar la utilidad del monitoreo en tiempo real y la aceptación del sistema.

---

## 1.3. Segmentos objetivo

### 1.3. Segmentos objetivo

**1. Personal operativo de almacenes farmacéuticos**  
Este segmento agrupa a operarios, técnicos y responsables del almacenamiento de medicamentos en hospitales, clínicas y centros de distribución en el Perú, incluyendo almacenes estratégicos como los de Lurín. Son los encargados directos de supervisar las condiciones en las que se conservan los productos farmacéuticos.

**Características demográficas:**
- Edad: 25 – 50 años
- Ubicación: Lima Metropolitana y principales regiones del país
- Nivel socioeconómico: NSE B y C
- Ocupación: Técnicos en farmacia, operarios logísticos, encargados de almacén

**Necesidad prioritaria:**  
Contar con herramientas tecnológicas simples que permitan monitorear en tiempo real las condiciones ambientales (temperatura, humedad y luz), recibir alertas automáticas y reducir la dependencia de registros manuales.

**Sustento estadístico:**  
Según la Contraloría General de la República, se han identificado deficiencias en el almacenamiento de medicamentos en establecimientos de salud del Perú, incluyendo falta de control ambiental y registros manuales, lo que evidencia la necesidad de mejorar los procesos y herramientas utilizadas por este personal.

---

**2. Entidades de salud y gestores farmacéuticos (MINSA, hospitales y clínicas)**  
Este segmento incluye instituciones públicas y privadas responsables de la gestión, supervisión y distribución de medicamentos a nivel nacional, como el MINSA, hospitales, clínicas y centros de distribución.

**Características demográficas / organizacionales:**
- Tipo de entidad: Instituciones del sector salud (públicas y privadas)
- Cobertura: Local, regional y nacional
- Ubicación: Principalmente zonas urbanas y centros logísticos (ej. Lurín)
- Responsables: Químicos farmacéuticos, administradores, gestores logísticos

**Necesidad prioritaria:**  
Sistemas que permitan monitorear múltiples almacenes en tiempo real, garantizar condiciones adecuadas durante almacenamiento y transporte, cumplir normativas sanitarias y mejorar la trazabilidad de los medicamentos.

**Sustento estadístico:**  
De acuerdo con el diario oficial El Peruano, el Estado peruano ha implementado mejoras en infraestructura de almacenamiento de medicamentos debido a limitaciones identificadas, lo que evidencia brechas en la gestión actual. Asimismo, la Contraloría ha reportado deficiencias en el control de condiciones de almacenamiento en diversos establecimientos de salud.

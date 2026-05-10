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
| U202216240 | **Luis Angel Tufiño Argüelles**<br>Ingeniería de Software<br><br>Elegí la carrera de Ingeniería de Software motivado por mi interés inicial en comprender el funcionamiento de un programa básico como Scratch. Posteriormente, durante la pandemia, comencé a modificar juegos sencillos, lo que representó mis primeros acercamientos al mundo de la programación.<br><br>Cuento con conocimientos en lenguajes como C++, Python y JavaScript. Además, durante el verano reforcé mis habilidades en el desarrollo de páginas web utilizando HTML y CSS, así como en la creación de bots para Discord y Telegram empleando el lenguaje Python.<br><br>Considero que mi capacidad para generar ideas, junto con mi disposición para escuchar y trabajar en equipo, pueden aportar de manera positiva al desarrollo de este proyecto. | ![Foto](../assets/luis-tufino.png)                   |
| U20221587  | **Franco Diego Rioja Nuñez** <br>Ingeniería de Software<br><br>Tengo 21 años y actualmente curso el séptimo ciclo de la carrera. Me considero una persona proactiva y comprometida en el desarrollo de proyectos, además de ser colaborativa y atenta a las necesidades y problemas de mis compañeros de equipo. En paralelo, me encuentro llevando cursos de especialización en Análisis de Datos, con el objetivo de ampliar mis conocimientos y fortalecer mis competencias profesionales.<br>                                                                                                                                                                                                                                                                                                                                    | ![Foto](../assets/Franco-Rioja.png)   |
| U20231e443 | **Mateo Sebastian Urviola Condori** <br>"Soy estudiante del programa para ingeniería en software, tengo 20 años y estoy buscando mi lugar en el mundo de la tecnología. Llevo año y medio estudiando programación y me gustaría seguir mejorando constantemente, creo que tengo potencial para desarrollar sistemas muy buenos.Tengo conocimientos en C++ basico-intermedio, dominio básico en python con el cuál he hecho web scraping y ya he manejado openGL como motor gráfico.<br>                                                                                                                                                                                                                                                                                                                                              | ![Foto](../assets/mateo-urviola.png)  |
| U202419440 | **Dhilsen Armil Mallqui Vilca** <br><br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | ![Foto](../assets/dhilsen-malqui.png) |
| U202319037 | **Diego Fernando Herrera Enriquez** <br>Con creatividad, responsabilidad y con disposición para aprender y crecer junto a mi equipo, pienso en entregar una aportación sobresaliente. Me adapto con facilidad a distintos retos, aportando ideas y soluciones prácticas que buscan mejorar cada proyecto. Valoro las buenas prácticas en esta profesión para servir a las personas con pasión por lo que hacemos. Conocimientos competentes en Frontend (HTML, CSS, JS) y experimentado en el diseño de proyectos a nivel integral. Mi enfoque está orientado a desarrollar soluciones prácticas y efectivas, siempre priorizando la satisfacción del usuario y con visión a seguir mejorando en futuros proyectos<br>                                                                                                               | ![Foto](../assets/diego-herrera.png)  |
---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Who (¿Quiénes son los involucrados?)
Los principales involucrados en esta problemática son los hospitales, clínicas, farmacias, almacenes farmacéuticos, distribuidores de medicamentos y entidades del Estado encargadas de la regulación y distribución de medicamentos en el Perú. Los pacientes son también actores clave, ya que dependen de que los medicamentos sean almacenados y transportados en condiciones óptimas para garantizar su efectividad y seguridad.

#### What (¿Qué se necesita?)
Se necesita un sistema tecnológico que permita monitorear en tiempo real las condiciones de almacenamiento y transporte de los **medicamentos**, específicamente variables críticas como la temperatura, la humedad y la exposición a la luz. Este sistema debe utilizar sensores IoT para asegurar que los medicamentos mantengan sus propiedades y no sufran deterioro debido a condiciones de almacenamiento inadecuadas.

#### Where (¿Dónde ocurre el problema?)
El problema ocurre principalmente en los hospitales, clínicas, almacenes farmacéuticos y centros de distribución de medicamentos a nivel nacional, especialmente en zonas de provincias como Tingo María y en áreas de difícil acceso donde la infraestructura de almacenamiento no es adecuada para garantizar el control de los medicamentos. Este problema también se extiende a los procesos de transporte, donde los medicamentos pueden ser expuestos a condiciones no ideales sin monitoreo efectivo.

#### When (¿Cuándo surge esta necesidad?)
Esta necesidad surge de manera constante durante todo el proceso de almacenamiento y distribución de medicamentos. Desde que los productos son almacenados hasta que son transportados a su destino final, existe la necesidad continua de monitorear las condiciones ambientales para evitar que los medicamentos sufran alteraciones que puedan comprometer su seguridad y efectividad.

#### Why (¿Por qué existe esta necesidad?)
La problemática existe debido a la falta de infraestructura adecuada en muchos almacenes y hospitales, junto con la carencia de sistemas automatizados de monitoreo de condiciones. Esto ha provocado incidentes de almacenamiento inadecuado, como la exposición a temperaturas o humedades fuera de rango, lo que compromete la calidad de los medicamentos. Además, la dependencia de procesos manuales y la ausencia de tecnologías de monitoreo en tiempo real incrementan el riesgo de pérdida de productos y desabastecimiento.

#### How (¿Cómo se manifiesta el problema?)
El problema se manifiesta en el almacenamiento de medicamentos en condiciones no controladas, como la exposición al sol, humedad excesiva, polvo, o el almacenamiento en espacios no adecuados. También se evidencia la falta de un sistema automatizado que controle y ajuste en tiempo real estos parámetros, lo que obliga a depender de procesos manuales y poco confiables. Esto aumenta el riesgo de que los medicamentos se deterioren o pierdan su efectividad, poniendo en peligro la salud de los pacientes.

#### How Much (¿Cuánto cuesta o qué magnitud tiene el problema?)
El impacto económico de este problema es significativo, dado que el almacenamiento inadecuado de medicamentos genera pérdidas debido al deterioro de productos que no pueden ser utilizados. Además, esta situación afecta la salud de los pacientes, ya que los medicamentos deteriorados pueden resultar ineficaces o incluso peligrosos. La magnitud del problema es considerable a nivel nacional, afectando tanto a las entidades públicas como privadas, lo que resalta la urgente necesidad de implementar soluciones tecnológicas que permitan garantizar la trazabilidad y conservación de los medicamentos.

---

### Descripción de la Solución Propuesta

El producto propuesto consiste en un sistema de monitoreo en tiempo real utilizando sensores IoT que permiten controlar y registrar las condiciones ambientales de almacenamiento y transporte de los **medicamentos**. Estos sensores medirán constantemente parámetros como temperatura, humedad y exposición a la luz, proporcionando alertas inmediatas si alguno de estos valores se desvía de los rangos recomendados para la correcta conservación de los medicamentos.

Este sistema automatizado facilitará la gestión de los productos farmacéuticos a lo largo de toda la cadena de suministro, desde el almacenamiento en los almacenes hasta el transporte y distribución. A través de la integración de tecnologías de monitoreo avanzadas, el sistema asegura que los medicamentos se mantengan en condiciones óptimas, evitando el deterioro y mejorando la trazabilidad, lo que reducirá el riesgo de pérdidas económicas y contribuirá a la seguridad de los pacientes.

## 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

### Dominio y Alcance del Problema

El proyecto se enfoca en el sector de la salud, específicamente en la gestión y almacenamiento de **medicamentos** dentro de hospitales, centros de distribución y almacenes farmacéuticos en el Perú. A pesar de la importancia crítica de mantener condiciones adecuadas de conservación, la supervisión de variables como temperatura, humedad y luz sigue siendo deficiente debido a la dependencia de procesos manuales, infraestructura limitada y la falta de monitoreo en tiempo real.

Este problema afecta a nivel nacional, con un énfasis particular en hospitales públicos y centros de distribución de medicamentos, incluyendo almacenes estratégicos como los de Lurín. El problema se presenta tanto en zonas urbanas como rurales, donde las limitaciones tecnológicas y de infraestructura dificultan el control adecuado de las condiciones de almacenamiento. Esto genera un riesgo en la calidad y seguridad de los medicamentos, impactando directamente a los pacientes y la operatividad de las entidades de salud.

Un ejemplo claro de la magnitud de este problema es el caso del **Hospital Santa Rosa de Piura**, donde un informe de Infobae titulado *"Entre cucarachas y medicina vencida fue hallado almacén del hospital Santa Rosa de Piura"* reveló que, debido a la falta de controles adecuados y la inadecuada conservación, se encontraron **medicamentos vencidos** y condiciones insalubres en el área de almacenamiento. Este hallazgo subraya la urgente necesidad de mejorar la infraestructura y los procesos de conservación en los hospitales y almacenes farmacéuticos, ya que los **medicamentos vencidos** representan no solo una **pérdida económica significativa**, sino también un **grave riesgo para la salud** de los pacientes. Este tipo de incidentes pone de manifiesto los peligros que enfrentan los pacientes cuando no se implementan tecnologías adecuadas para monitorear y controlar las condiciones de almacenamiento.

La oportunidad clave que nuestra startup busca aprovechar radica en la creciente necesidad de optimizar el control y monitoreo de los medicamentos a través de soluciones tecnológicas avanzadas, que permitan automatizar los procesos de conservación y garantizar un control más riguroso en tiempo real. Esto no solo resolvería las deficiencias del sistema actual, sino que también contribuiría a la mejora de la trazabilidad, la eficiencia operativa y el cumplimiento de las normativas sanitarias.

---

### Actores Involucrados (Segmentos de Cliente)
- **Personal encargado de almacenes farmacéuticos (operarios, técnicos y responsables de control):** Son los responsables directos del almacenamiento y conservación de medicamentos. Necesitan herramientas que mejoren la gestión de condiciones de almacenamiento y reduzcan el riesgo de errores.
- **Personal de salud (farmacéuticos, administradores hospitalarios):** Supervisan el uso y la disponibilidad de los medicamentos, y deben garantizar que los productos sean administrados con la máxima seguridad.
- **Entidades del Estado (MINSA, redes de salud):** Regulan la distribución de medicamentos y deben asegurarse de que se cumplan las normativas de conservación y control sanitario.
- **Pacientes:** Son los usuarios finales que se ven directamente afectados por la calidad de los medicamentos, y cuya seguridad depende de que se mantengan condiciones adecuadas de conservación.

---

### Problemas, Puntos de Dolor y Causas

#### **Puntos de dolor**
- **Falta de herramientas tecnológicas para monitoreo en tiempo real:** El personal encargado de almacenar medicamentos carece de un sistema automatizado que permita monitorear las condiciones críticas de almacenamiento en tiempo real, lo que genera vulnerabilidades en el proceso.
- **Dificultad para detectar variaciones de temperatura o humedad:** Sin un sistema adecuado, las variaciones de estos factores pueden pasar desapercibidas hasta que los medicamentos se ven afectados.
- **Falta de alertas automáticas:** En el sistema actual, los fallos en las condiciones ambientales no generan alertas inmediatas, lo que retrasa las decisiones correctivas.
- **Baja trazabilidad de los medicamentos:** La falta de un registro digitalizado dificulta el seguimiento histórico de los medicamentos, lo que complica las auditorías y el control normativo.
- **Pérdidas económicas por deterioro o vencimiento:** La gestión inadecuada de las condiciones de almacenamiento lleva a la pérdida de medicamentos, generando pérdidas económicas significativas.

#### **Causas raíz**
- **Infraestructura insuficiente:** Muchos almacenes y hospitales carecen de la infraestructura adecuada para almacenar medicamentos de manera controlada.
- **Ausencia de sistemas automatizados de monitoreo:** La falta de tecnología para monitorear condiciones críticas contribuye a la ineficiencia y los errores en la gestión de los productos farmacéuticos.
- **Dependencia de procesos manuales propensos a errores:** Los registros manuales y el monitoreo visual son procesos lentos y vulnerables a errores.
- **Falta de integración tecnológica:** La ausencia de un sistema centralizado dificulta el intercambio de información entre diferentes niveles de la cadena de suministro de medicamentos.
- **Supervisión limitada y no continua:** El monitoreo de las condiciones de almacenamiento es insuficiente, y no se realiza de manera continua, lo que aumenta los riesgos de deterioro.

---

### Brecha, Impactos e Indicadores

#### **Brecha detectada**
Actualmente, no existe un sistema digital integrado que permita monitorear en tiempo real las condiciones ambientales de almacenamiento de medicamentos. Esta falta de monitoreo eficaz genera riesgos que impactan tanto en la calidad de los medicamentos como en la eficiencia operativa del sistema de salud.

#### **Impactos y riesgos**
- **Deterioro de medicamentos:** Los medicamentos se pueden deteriorar debido a condiciones inadecuadas de almacenamiento, lo que afecta su efectividad y seguridad.
- **Riesgos para la salud:** Los medicamentos deteriorados pueden causar daños a la salud de los pacientes.
- **Pérdidas económicas:** La inadecuada conservación de los medicamentos genera pérdidas económicas considerables debido a productos no aptos para su consumo.
- **Incumplimiento normativo:** La falta de un sistema adecuado de monitoreo puede resultar en el incumplimiento de normativas sanitarias sobre almacenamiento de medicamentos.
- **Desabastecimiento:** La gestión deficiente puede llevar a un desabastecimiento de medicamentos esenciales en hospitales y clínicas.

#### **Indicadores**
- **Número de incidencias:** Casos de medicamentos almacenados fuera de los rangos recomendados.
- **Tiempo de detección de fallas:** El tiempo promedio desde que ocurre una desviación hasta que es detectada.
- **% de medicamentos deteriorados:** Proporción de medicamentos que han sido deteriorados por condiciones inadecuadas.
- **Nivel de cumplimiento normativo:** Porcentaje de almacenes y hospitales que cumplen con las normativas de conservación.
- **Tiempo de respuesta:** Tiempo necesario para tomar medidas correctivas después de una desviación.
- **Disponibilidad de datos históricos:** La cantidad y calidad de los registros históricos disponibles para auditar el cumplimiento de las condiciones de almacenamiento.


#### 1.2.2.2. Lean UX Assumptions

**Sobre usuarios (personal de almacenes, farmacéuticos, administradores de salud)**

- Asumimos que el personal encargado del almacenamiento de medicamentos prioriza la conservación adecuada de las condiciones ambientales (temperatura, humedad, luz) para mantener la efectividad de los medicamentos.  
  Métrica de éxito: El 95% de los medicamentos deben mantenerse dentro de los rangos ideales de conservación (temperatura, humedad, luz) durante todo el ciclo de almacenamiento.  
  Definition of done: El sistema asegura que el 95% de los productos almacenados se mantengan en condiciones adecuadas, con registros automáticos de temperatura, humedad y luz.  
  Objetivos del grupo objetivo: Garantizar la conservación de los medicamentos sin deterioro y asegurar su efectividad al final del proceso de almacenamiento.  
  Características de la solución: La solución debe incluir sensores IoT para monitorear en tiempo real las condiciones de almacenamiento y alertar en caso de desviaciones.

- Asumimos que los operarios necesitan información en tiempo real sobre las condiciones ambientales para tomar decisiones rápidas y garantizar la calidad de los medicamentos.  
  Métrica de éxito: Reducir el tiempo de respuesta a las alertas críticas en un 30%, pasando de 15 a 10 minutos, mediante el uso de alertas automáticas y monitoreo en tiempo real.  
  Definition of done: El sistema permite la recepción de alertas en tiempo real y asegura que los operarios tomen decisiones correctivas inmediatamente después de recibir la alerta.  
  Objetivos del grupo objetivo: Minimizar el impacto de las variaciones ambientales en los medicamentos, asegurando que las decisiones correctivas se tomen rápidamente.  
  Características de la solución: La solución debe permitir la visualización en tiempo real de las condiciones ambientales mediante un dashboard fácil de usar y accesible para los operarios.

- Asumimos que los usuarios valoran soluciones simples y fáciles de usar debido a la carga operativa diaria, lo que implica que la interfaz debe ser intuitiva y fácil de implementar.  
  Métrica de éxito: El 85% de los usuarios deben ser capaces de utilizar la solución de manera efectiva con menos de 30 minutos de formación inicial.  
  Definition of done: La solución se considera implementada cuando al menos el 85% de los usuarios activos logran completar las tareas básicas sin asistencia adicional.  
  Objetivos del grupo objetivo: Mejorar la eficiencia operativa diaria sin agregar complejidad.  
  Características de la solución: Interfaz de usuario intuitiva, diseño simple y accesibilidad desde dispositivos móviles y estaciones de trabajo.

- Asumimos que los usuarios consideran importante recibir alertas inmediatas ante cualquier variación crítica en las condiciones de almacenamiento, para poder mitigar riesgos.  
  Métrica de éxito: El 95% de las alertas deben ser gestionadas de forma efectiva dentro del tiempo estipulado.  
  Definition of done: El sistema estará completo cuando el 95% de las alertas generen una respuesta de acción dentro de un tiempo de 30 minutos desde su emisión.  
  Objetivos del grupo objetivo: Minimizar el riesgo de deterioro de los medicamentos mediante la rápida identificación y solución de problemas.  
  Características de la solución: Sistema de alertas automáticas basado en condiciones predefinidas, con opción de personalización de umbrales.

---

**Sobre entidades de salud (hospitales, MINSA, centros de distribución como Lurín)**

- Asumimos que muchas entidades gestionan el almacenamiento de medicamentos con procesos manuales o parcialmente digitalizados, lo que dificulta el control y la trazabilidad.  
  Métrica de éxito: Implementar el sistema en al menos el 60% de las entidades del sistema de salud dentro de los primeros 12 meses.  
  Definition of done: El sistema se considera implementado cuando el 60% de las entidades cuentan con monitoreo automatizado, registrando datos de temperatura, humedad y luz en tiempo real.  
  Objetivos del grupo objetivo: Mejorar la trazabilidad de los medicamentos y optimizar el control de almacenamiento a nivel nacional.  
  Características de la solución: La solución debe incluir una plataforma centralizada que permita acceder a los datos históricos y actuales de todos los almacenes y entidades conectadas.

- Asumimos que estas entidades carecen de sistemas continuos y automatizados de monitoreo de condiciones ambientales.  
  Métrica de éxito: Automatizar el monitoreo en tiempo real en el 80% de los almacenes en los primeros 6 meses de implementación.  
  Definition of done: El sistema se considera completamente implementado cuando el 80% de los almacenes estén conectados a la plataforma de monitoreo en tiempo real.  
  Objetivos del grupo objetivo: Mejorar la eficiencia operativa, reducir los riesgos de errores humanos y garantizar la calidad de los medicamentos.  
  Características de la solución: Sensores IoT integrados para monitoreo en tiempo real, accesibles desde una plataforma centralizada.

- Asumimos que estas entidades necesitan garantizar el cumplimiento de normativas sanitarias relacionadas con el almacenamiento de medicamentos, para evitar sanciones y mejorar la calidad del servicio.  
  Métrica de éxito: Lograr el 100% de cumplimiento con las normativas sanitarias dentro de los primeros 12 meses.  
  Definition of done: El sistema se considerará exitoso cuando todas las entidades implementen un sistema de monitoreo que cumpla con las normativas locales e internacionales.  
  Objetivos del grupo objetivo: Garantizar que todos los medicamentos almacenados estén en condiciones adecuadas según las regulaciones vigentes.  
  Características de la solución: Reportes automáticos de cumplimiento normativo, con opción de auditorías digitales.

---

**Sobre comportamiento y riesgos**

- Asumimos que la falta de monitoreo en tiempo real incrementa significativamente el riesgo de deterioro de medicamentos, lo que pone en peligro la seguridad de los pacientes.  
  Métrica de éxito: Reducir el riesgo de deterioro de los medicamentos en 90% mediante el monitoreo en tiempo real.  
  Definition of done: El sistema se considerará exitoso cuando el 90% de los incidentes se resuelvan antes de que los medicamentos sufran daños irreparables.  
  Objetivos del grupo objetivo: Asegurar la calidad y seguridad de los medicamentos hasta su distribución final.  
  Características de la solución: Sistema de monitoreo en tiempo real con alertas automáticas que permitan tomar decisiones correctivas antes de que los productos sean afectados.

---

**Sobre tecnología y datos**

- Asumimos que las entidades están dispuestas a implementar sensores IoT si estos mejoran el control y monitoreo de las condiciones de almacenamiento, brindando mayor seguridad en el proceso.  
  Métrica de éxito: Implementar sensores IoT en el 80% de los almacenes dentro del primer año.  
  Definition of done: El sistema se considera completo cuando el 80% de los almacenes han adoptado la tecnología de sensores IoT para monitoreo de condiciones ambientales.  
  Objetivos del grupo objetivo: Aumentar la precisión del monitoreo y mejorar la seguridad en el almacenamiento de los medicamentos.  
  Características de la solución: Sensores IoT para recolección de datos en tiempo real, integrados a una plataforma accesible en todo momento.

- Asumimos que existe disponibilidad de conexión a internet en la mayoría de los almacenes principales, lo que facilita la implementación de soluciones tecnológicas avanzadas.  
  Métrica de éxito: El 95% de los almacenes clave deben contar con conexión a Internet confiable dentro del primer año de implementación.  
  Definition of done: El sistema se considera implementado cuando el 95% de los almacenes clave tienen la capacidad de conectarse a la plataforma para monitorear las condiciones ambientales.  
  Objetivos del grupo objetivo: Facilitar el monitoreo remoto y la centralización de datos en tiempo real.  
  Características de la solución: Solución basada en la nube, con acceso remoto y conexión continua.


#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hipótesis 1:**  
  Si ofrecemos una plataforma web que permita el monitoreo en tiempo real de las condiciones ambientales de almacenamiento de medicamentos, entonces el personal encargado podrá tomar decisiones oportunas para evitar el deterioro de los productos farmacéuticos.  
  Usuarios: Personal encargado de almacenes farmacéuticos, operarios.  
  User Outcome: Mejorar la toma de decisiones en tiempo real y evitar el deterioro de los productos farmacéuticos.  
  Feature: Plataforma web con monitoreo en tiempo real de las condiciones de almacenamiento y alertas automáticas.

- **Hipótesis 2:**  
  Si las entidades de salud cuentan con un sistema que genere alertas automáticas ante variaciones de temperatura, humedad o luz, entonces podrán reducir riesgos asociados al almacenamiento inadecuado y mejorar la seguridad de los medicamentos.  
  Usuarios: Administradores de almacenes, personal de salud.  
  User Outcome: Mejorar la seguridad de los medicamentos mediante alertas automáticas para tomar decisiones rápidas ante variaciones críticas.  
  Feature: Sistema de alertas automáticas basado en sensores para monitoreo de temperatura, humedad y luz.

- **Hipótesis 3:**  
  Si los usuarios pueden visualizar datos históricos y reportes sobre las condiciones de almacenamiento, entonces podrán mejorar la trazabilidad y cumplir con las normativas sanitarias de manera más eficiente.  
  Usuarios: Farmacéuticos, administradores de salud, auditores.  
  User Outcome: Facilitar auditorías y el cumplimiento normativo con acceso a datos históricos y reportes detallados.  
  Feature: Funcionalidad para visualizar datos históricos y generar reportes automáticos sobre las condiciones de almacenamiento.

- **Hipótesis 4:**  
  Si se implementa el uso de sensores IoT integrados a una plataforma digital, entonces se reducirá la dependencia de procesos manuales y se minimizarán los errores humanos en el control de condiciones ambientales.  
  Usuarios: Personal de almacenes, operarios.  
  User Outcome: Mejorar la precisión y eficiencia del monitoreo de las condiciones de almacenamiento, reduciendo la carga operativa.  
  Feature: Sensores IoT integrados para monitoreo continuo de las condiciones ambientales, con registro automático de datos.

- **Hipótesis 5:**  
  Si las entidades de salud utilizan un sistema centralizado para gestionar múltiples almacenes o sedes, entonces podrán optimizar la gestión de recursos, reducir pérdidas económicas y mejorar la eficiencia operativa.  
  Usuarios: Administradores de salud, responsables de la gestión de almacenes.  
  User Outcome: Facilitar la gestión de múltiples almacenes y mejorar la eficiencia operativa mediante un sistema centralizado.  
  Feature: Plataforma centralizada para la gestión de almacenes y distribución de medicamentos, con acceso a datos en tiempo real.


### 1.2.2.4. Lean UX Canvas

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
Realizar entrevistas con personal de almacenes y profesionales de salud, además de pruebas de prototipos simples, como mockups o dashboards básicos, para validar la utilidad del monitoreo en tiempo real y la aceptación del sistema. También se debe crear una landing page para obtener retroalimentación sobre el interés en la solución propuesta.
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

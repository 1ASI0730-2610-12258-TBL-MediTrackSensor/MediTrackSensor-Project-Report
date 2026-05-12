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

### Contexto del mercado y oportunidad

En el Perú, el sector salud enfrenta desafíos en la gestión del almacenamiento de medicamentos, como se evidencia en el caso del Hospital I de Tingo María, donde los medicamentos se encontraron almacenados en condiciones inadecuadas, expuestos al sol y sin control adecuado de temperatura y humedad. Este problema, común en muchas instituciones de salud, compromete la eficacia y seguridad de los medicamentos.
Actualmente, existe una oportunidad de mercado para soluciones tecnológicas que mejoren la eficiencia operativa del sector salud. Aunque algunas herramientas en el mercado abordan aspectos como inventarios o facturación, pocas resuelven el problema central: la falta de visibilidad en tiempo real sobre las condiciones críticas de almacenamiento.
Con la creciente necesidad de digitalización en el sector, especialmente a través de iniciativas como las del Ministerio de Salud, las soluciones basadas en sensores IoT ofrecen una oportunidad única para mejorar el monitoreo y control de las condiciones de conservación de los medicamentos, asegurando su efectividad y reduciendo riesgos operativos.
---
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

### 1.2.2.1. Lean UX Problem Statements

#### **Problem Statement 1 — Personal encargado de almacenes farmacéuticos**

**Contexto:**
En el sector salud en Perú, hospitales y centros de distribución enfrentan el desafío de no contar con un sistema de monitoreo en tiempo real para condiciones críticas como temperatura, humedad y luz. La falta de visibilidad sobre estos parámetros compromete la efectividad de los medicamentos y genera pérdidas económicas debido al deterioro o vencimiento de productos.

**Problema:**
El personal de almacenes farmacéuticos carece de un sistema automatizado que permita monitorear en tiempo real las condiciones críticas de almacenamiento, lo que genera vulnerabilidades en el proceso y aumenta el riesgo de deterioro de los medicamentos.

**Pregunta clave:**
¿Cómo podemos proporcionar a los encargados de almacenes una solución que permita monitorear las condiciones de almacenamiento de los medicamentos en tiempo real, reducir las incidencias operativas no detectadas y mejorar la trazabilidad de los productos en un 30% durante los primeros 6 meses?

---

#### **Problem Statement 2 — Personal de salud y entidades regulatorias**

**Contexto:**
Las entidades de salud, como hospitales y centros de distribución, carecen de un sistema automatizado de monitoreo continuo para asegurar que los medicamentos se conserven en condiciones óptimas. Esto genera incumplimiento de normativas sanitarias y riesgos para la seguridad de los pacientes debido a la dependencia de procesos manuales ineficaces.

**Problema:**
El personal de salud y las entidades regulatorias no cuentan con herramientas automatizadas para monitorear y garantizar el cumplimiento de las normativas de conservación de medicamentos, lo que pone en riesgo la calidad de los medicamentos y la seguridad de los pacientes.

**Pregunta clave:**
¿Cómo podemos diseñar un sistema que permita a las entidades de salud cumplir con las normativas sanitarias de manera más eficiente, garantizando que el 100% de los medicamentos se almacenen en condiciones adecuadas dentro de los primeros 12 meses de uso?

### 1.2.2.2.2. Lean UX Assumptions

#### Supuestos de Negocio
- **Creemos que** el mercado de la salud en Perú necesita una solución tecnológica que permita monitorear en tiempo real las condiciones ambientales (temperatura, humedad, luz) en los almacenes farmacéuticos y hospitales, para garantizar la conservación adecuada de los medicamentos.

- **Creemos que** el valor principal que los clientes buscan obtener de esta solución es la seguridad de los medicamentos, evitando pérdidas económicas debido al deterioro o vencimiento de los productos.

- **Creemos que** el modelo de negocio se basará en un sistema de suscripción mensual escalable según la cantidad de almacenes y sensores IoT conectados, con soporte adicional para instalación y mantenimiento de los sensores.

- **Creemos que** nuestra ventaja competitiva es la combinación de monitoreo IoT en tiempo real con la gestión de condiciones ambientales, específicamente en el sector farmacéutico y de salud.

- **Creemos que** si no se evidencia una reducción de pérdidas operativas en los primeros 3 meses, perderemos la confianza de los clientes y no renovarán la suscripción.

- **Creemos que** la mayoría de los almacenes clave en el sector salud cuentan con conexión a internet suficiente para sincronizar datos operativos en tiempo real desde la plataforma.

---

#### Supuestos de Usuario

- ¿Quién es el usuario?
  - Personal encargado de almacenes farmacéuticos, como operarios, técnicos y responsables de control de medicamentos en hospitales y centros de distribución.

- ¿Dónde encaja nuestro producto en su trabajo o vida?
  - El producto se utilizará en la gestión diaria del almacenamiento de medicamentos, ayudando al personal a monitorear las condiciones ambientales (temperatura, humedad, luz) y asegurarse de que los productos se mantengan en condiciones adecuadas.

- ¿Qué problemas resuelve nuestro producto?
  - La falta de visibilidad en tiempo real sobre las condiciones de almacenamiento de medicamentos, la detección tardía de anomalías y la ausencia de alertas automáticas ante condiciones no ideales.

- ¿Cuándo y cómo se usa nuestro producto?
  - Durante toda la jornada operativa, tanto en dispositivos móviles como en computadoras, con acceso a un dashboard centralizado para visualizar en tiempo real las condiciones de los medicamentos y responder a alertas.

- ¿Qué características son indispensables?
  - Dashboard en tiempo real con datos de los sensores IoT, alertas automáticas ante condiciones fuera de rango, gestión multisede y reportes históricos para auditorías.

- ¿Cómo debe verse y comportarse el producto?
  - Interfaz simple y clara, con codificación por colores (verde, amarillo, rojo) para que el personal entienda rápidamente el estado de los medicamentos, sin necesidad de capacitación técnica extensa.

---

#### Supuestos de Tecnología

- **Creemos que** las entidades de salud están dispuestas a adoptar tecnología avanzada como sensores IoT para mejorar el monitoreo de las condiciones de almacenamiento de medicamentos.

- **Creemos que** los sensores IoT serán integrados fácilmente a una plataforma centralizada que permitirá acceder a datos históricos y en tiempo real desde cualquier dispositivo conectado.

- **Creemos que** los almacenes principales tienen conexión a internet confiable, lo que facilita la implementación de soluciones basadas en la nube.

- **Creemos que** la plataforma será compatible con los sistemas actuales de gestión de inventarios y será fácil de integrar sin interrumpir las operaciones diarias.

- **Creemos que** los sensores IoT podrán funcionar de manera eficiente en diversas condiciones ambientales, como en áreas con temperaturas extremas o humedad elevada, comunes en algunos hospitales y almacenes.

- **Creemos que** la plataforma debe ser escalable para adaptarse al crecimiento de los hospitales o redes de distribución, permitiendo agregar más sensores y almacenes sin dificultad.

---

#### Supuestos del Mercado

- **Creemos que** las entidades de salud (hospitales y centros de distribución) necesitan una solución automatizada para cumplir con las normativas sanitarias relacionadas con el almacenamiento de medicamentos.

- **Creemos que** la adopción de esta tecnología será rápida en el sector debido a la creciente demanda por soluciones tecnológicas para mejorar la seguridad de los pacientes y cumplir con las normativas.

- **Creemos que** las entidades de salud están cada vez más dispuestas a invertir en tecnologías que les permitan optimizar costos y mejorar la eficiencia operativa a largo plazo.

- **Creemos que** la competencia en el mercado de monitoreo IoT para el sector farmacéutico aún está en etapas tempranas, lo que nos ofrece una ventaja para posicionarnos como líderes en este nicho.

- **Creemos que** los clientes en el sector de salud valoran las soluciones personalizables que se adaptan a sus necesidades específicas y que sean fáciles de integrar en sus sistemas operativos existentes.

- **Creemos que** las entidades reguladoras como MINSA y otras agencias de salud están promoviendo iniciativas digitales para mejorar la eficiencia en la gestión de medicamentos, lo que facilita la adopción de soluciones tecnológicas.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1**

**Creemos que lograremos** una mejora significativa en la toma de decisiones del personal encargado de almacenes farmacéuticos para evitar el deterioro de los productos farmacéuticos  
**Si** el personal encargado de almacenes farmacéuticos tiene acceso a una plataforma web con monitoreo en tiempo real de las condiciones de almacenamiento de medicamentos  
**Alcanzan** la capacidad de tomar decisiones oportunas para evitar el deterioro de los productos farmacéuticos  
**Con** el sistema de monitoreo en tiempo real de las condiciones de almacenamiento y alertas automáticas sobre temperatura, humedad y exposición a la luz

> Sabremos que esto es verdad cuando observemos una mejora del 30% en la reducción de incidentes relacionados con el deterioro de medicamentos durante los primeros 3 meses de uso de la plataforma.

---

**Hipótesis 2**

**Creemos que lograremos** una mejora significativa en la seguridad de los medicamentos al reducir los riesgos asociados al almacenamiento inadecuado  
**Si** las entidades de salud cuentan con un sistema que genere alertas automáticas ante variaciones de temperatura, humedad o luz  
**Alcanzan** la capacidad de tomar decisiones rápidas ante variaciones críticas en las condiciones de almacenamiento  
**Con** el sistema de alertas automáticas basado en sensores para monitoreo de temperatura, humedad y luz

> Sabremos que esto es verdad cuando observemos una mejora del 25% en la reducción de incidentes de deterioro de medicamentos durante los primeros 3 meses de uso del sistema de alertas.--

---

**Hipótesis 3**

**Creemos que lograremos** una mejora significativa en la trazabilidad y cumplimiento de las normativas sanitarias  
**Si** los usuarios pueden visualizar datos históricos y reportes sobre las condiciones de almacenamiento  
**Alcanzan** la capacidad de mejorar la trazabilidad y cumplir con las normativas sanitarias de manera más eficiente  
**Con** la funcionalidad para visualizar datos históricos y generar reportes automáticos sobre las condiciones de almacenamiento

> Sabremos que esto es verdad cuando observemos una mejora del 20% en la eficiencia de auditorías y cumplimiento normativo durante los primeros 3 meses de uso del sistema de reportes.

---

**Hipótesis 4**

**Creemos que lograremos** una reducción significativa en la dependencia de procesos manuales y los errores humanos  
**Si** se implementa el uso de sensores IoT integrados a una plataforma digital  
**Alcanzan** la capacidad de reducir la carga operativa y mejorar la precisión del monitoreo de las condiciones ambientales  
**Con** los sensores IoT integrados para monitoreo continuo de las condiciones ambientales, con registro automático de datos

> Sabremos que esto es verdad cuando observemos una mejora del 25% en la precisión del monitoreo y una reducción del 30% en los errores operativos durante los primeros 3 meses de uso del sistema.

---

**Hipótesis 5**

**Creemos que lograremos** una optimización significativa en la gestión de recursos y eficiencia operativa  
**Si** las entidades de salud utilizan un sistema centralizado para gestionar múltiples almacenes o sedes  
**Alcanzan** la capacidad de optimizar la gestión de recursos, reducir pérdidas económicas y mejorar la eficiencia operativa  
**Con** una plataforma centralizada para la gestión de almacenes y distribución de medicamentos, con acceso a datos en tiempo real

> Sabremos que esto es verdad cuando observemos una mejora del 30% en la eficiencia operativa y una reducción del 20% en pérdidas económicas durante los primeros 6 meses de uso del sistema centralizado.

### 1.2.2.4. Lean UX Canvas

**1. Business Problem**

La gestión del almacenamiento de medicamentos en el sistema de salud fue diseñada para conservar los productos farmacéuticos en condiciones seguras y garantizar su calidad durante el almacenamiento y transporte. Sin embargo, hemos observado que la falta de monitoreo en tiempo real y el uso de procesos manuales están afectando la eficacia de este sistema. Variables críticas como temperatura, humedad y exposición a la luz no están siendo controladas adecuadamente, lo que genera riesgos en la calidad de los medicamentos, tanto en los almacenes como durante su transporte.

¿Cómo podríamos mejorar el sistema de gestión de almacenamiento de medicamentos para que las entidades de salud sean más exitosas, evidenciado por una reducción del 30% en incidentes relacionados con el deterioro de los medicamentos, una mejora en la respuesta a desviaciones de condiciones ambientales y un aumento en el cumplimiento de las normativas de conservación?

---
**2. Business Outcomes**

**1.** **Nuestro producto** fue diseñado para lograr **[estos objetivos de negocio/cliente y entregar este valor]**.
- **Contexto**: El sistema fue diseñado para garantizar la conservación y trazabilidad de los medicamentos en condiciones óptimas dentro de los almacenes farmacéuticos, mejorando la eficiencia operativa y asegurando el cumplimiento de las normativas sanitarias.

**2.** **Hemos observado [de estas maneras]** que el producto/servicio no está cumpliendo estos objetivos, lo que está causando **[este efecto/adversidad]** en nuestro negocio.
- **Observación**: Hemos notado que el almacenamiento inadecuado y la falta de monitoreo en tiempo real están llevando a un aumento en las pérdidas económicas por medicamentos deteriorados, incumplimiento de las normativas de conservación y baja eficiencia en la gestión de los almacenes, lo que también afecta la trazabilidad y el control en múltiples sedes.

**3.** **¿Cómo podríamos mejorar [el servicio/producto]** para que nuestros clientes sean más exitosos, según **[estos cambios medibles en su comportamiento]**?
- **Resultado de negocio 1**: **Reducir la pérdida de medicamentos** por condiciones inadecuadas de almacenamiento en un 30%.
- **Resultado de negocio 2**: **Mejorar la eficiencia en la gestión de almacenes farmacéuticos**, alcanzando una reducción del 20% en los tiempos de gestión operativa dentro de los primeros 6 meses.
- **Resultado de negocio 3**: **Disminuir el tiempo de respuesta** ante incidencias relacionadas con condiciones ambientales de 15 a 10 minutos, mejorando la capacidad de reacción ante problemas críticos.
- **Resultado de negocio 4**: **Asegurar el cumplimiento del 100% de las normativas sanitarias** relacionadas con el almacenamiento de medicamentos dentro de los primeros 6 meses de uso.
- **Resultado de negocio 5**: **Optimizar la trazabilidad y control de los productos farmacéuticos** en múltiples sedes, garantizando que el 80% de los almacenes estén conectados y monitorizados en tiempo real.

---
**3. Users**

1. **Personal encargado de almacenes farmacéuticos**
  - **¿Quién compra el producto?**  
    Los **hospitales, clínicas y centros de distribución** que necesitan una solución para optimizar el almacenamiento y monitoreo de medicamentos.
  - **¿Quién usa el producto?**  
    El **personal operativo de los almacenes farmacéuticos**, incluyendo operarios, técnicos y encargados de la gestión de los productos.
  - **¿Quién configura el producto?**  
    Los **administradores** de las entidades de salud y personal de soporte técnico en los almacenes.

2. **Personal de salud (farmacéuticos, administradores hospitalarios)**
  - **¿Quién compra el producto?**  
    **Hospitales, farmacias y clínicas** que necesitan asegurar la conservación de medicamentos en condiciones óptimas.
  - **¿Quién usa el producto?**  
    Los **farmacéuticos** y **administradores hospitalarios** que supervisan la distribución de medicamentos y deben asegurarse de que los productos sean almacenados correctamente.
  - **¿Quién configura el producto?**  
    Los **técnicos y administradores** encargados de configurar el sistema para supervisar y gestionar el almacenamiento.

3. **Entidades regulatorias (MINSA y redes de salud)**
  - **¿Quién compra el producto?**  
    **Instituciones gubernamentales o entidades regulatorias** encargadas de supervisar las normativas sanitarias de almacenamiento y distribución de medicamentos.
  - **¿Quién usa el producto?**  
    Las **entidades gubernamentales** que monitorean el cumplimiento de las normativas en centros de salud y almacenes farmacéuticos.
  - **¿Quién configura el producto?**  
    Los **administradores de las redes de salud** que supervisan y regulan el cumplimiento de las normativas sanitarias a nivel nacional.

---

**4. User Benefits**
1. **Personal encargado de almacenes farmacéuticos**
  - **¿Por qué buscan nuestro producto?**  
    Necesitan una **solución eficiente** para monitorear las condiciones de almacenamiento de medicamentos y evitar la pérdida de productos debido a condiciones inadecuadas.
  - **¿Qué beneficio obtienen de usarlo?**  
    Reducción de la **pérdida de medicamentos** y mejora de la **eficiencia operativa** en la gestión de almacenes.
  - **Cambio de comportamiento observable**:  
    El personal adoptará prácticas más **diligentes y sistemáticas** en el monitoreo de las condiciones ambientales, registrando y respondiendo de manera oportuna ante desviaciones.

2. **Personal de salud (farmacéuticos, administradores hospitalarios)**
  - **¿Por qué buscan nuestro producto?**  
    Buscan una **herramienta confiable** para asegurar que los medicamentos se almacenen correctamente, respetando las normativas sanitarias y evitando riesgos para los pacientes.
  - **¿Qué beneficio obtienen de usarlo?**  
    Aseguran que los medicamentos estén en condiciones óptimas, **cumpliendo con las normativas** y mejorando la **seguridad de los pacientes**.
  - **Cambio de comportamiento observable**:  
    El personal usará el sistema para **verificar condiciones ambientales en tiempo real**, asegurando que los productos farmacéuticos no se deterioren y se mantengan dentro de los parámetros establecidos.

3. **Entidades regulatorias (MINSA y redes de salud)**
  - **¿Por qué buscan nuestro producto?**  
    Necesitan garantizar que las **normativas sanitarias** se sigan de manera efectiva en los centros de salud y almacenes farmacéuticos.
  - **¿Qué beneficio obtienen de usarlo?**  
    Mejora del **cumplimiento normativo** a nivel nacional, con la capacidad de auditar y verificar de manera sencilla si se están cumpliendo las condiciones de almacenamiento.
  - **Cambio de comportamiento observable**:  
    Las entidades podrán **verificar y reportar el cumplimiento de normativas** en tiempo real, evitando sanciones y mejorando la supervisión de los centros de salud.

4. **Pacientes**
  - **¿Por qué buscan nuestro producto?**  
    Aunque no usan el producto directamente, los **pacientes se benefician indirectamente** al recibir medicamentos que han sido almacenados y distribuidos bajo condiciones controladas.
  - **¿Qué beneficio obtienen de usarlo?**  
    Garantía de que los **medicamentos sean efectivos** y **seguros** al ser almacenados adecuadamente.
  - **Cambio de comportamiento observable**:  
    El **impacto indirecto** se verá reflejado en una mayor **confianza en la seguridad de los medicamentos** que los pacientes consumen.

---
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

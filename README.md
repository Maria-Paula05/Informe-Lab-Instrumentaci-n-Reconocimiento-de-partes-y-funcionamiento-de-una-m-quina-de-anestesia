# Informe de Laboratorio   Instrumentación Biomédica y Biosensores 
Jhonatan David Guevara, Juan Pablo Díaz, María Paula Fernández.
### Reconocimiento de partes y funcionamiento de una máquina de anestesia  

---

##  1. Introducción

Las máquinas de anestesia constituyen uno de los equipos más críticos en el entorno quirúrgico moderno, ya que permiten la administración controlada de agentes anestésicos y el mantenimiento de funciones vitales durante procedimientos médicos. Estos sistemas integran múltiples subsistemas, incluyendo el suministro de gases médicos, vaporizadores, ventilación mecánica, circuitos respiratorios, alarmas de seguridad y monitoreo del paciente, con el fin de garantizar una anestesia segura y eficaz (Dorsch & Dorsch, 2014; Miller, 2015).

El principio de funcionamiento de una máquina de anestesia se basa en la mezcla precisa de gases como oxígeno, aire medicinal y, en algunos casos, óxido nitroso, junto con agentes anestésicos volátiles administrados mediante vaporizadores. Estos componentes permiten controlar tanto el flujo como la concentración del anestésico suministrado al paciente. Además, las máquinas incorporan mecanismos de seguridad diseñados para prevenir fallos críticos, como la administración de mezclas hipóxicas, pérdidas de presión, fallos en el suministro de gases o desconexiones del circuito respiratorio (Butterworth et al., 2018; Dorsch & Dorsch, 2014; ECRI Institute, 2021).

En la práctica clínica, el uso seguro de estos equipos requiere una monitorización continua del paciente, especialmente de variables como oxigenación, ventilación, circulación y temperatura. Por esta razón, los estándares de monitoreo anestésico establecen que durante todo procedimiento bajo anestesia debe mantenerse una vigilancia constante de las funciones fisiológicas esenciales del paciente (American Society of Anesthesiologists, 2020). De igual forma, la Organización Mundial de la Salud resalta la importancia de la seguridad quirúrgica y del uso adecuado de tecnologías biomédicas para reducir riesgos durante los procedimientos operatorios (World Health Organization, 2009).

En la actualidad, equipos desarrollados por fabricantes como GE Healthcare y Mindray han evolucionado hacia estaciones de anestesia más automatizadas, integrando ventiladores avanzados, sensores, alarmas inteligentes, pantallas de monitoreo y herramientas de control en tiempo real. Estos avances permiten mejorar la precisión en la administración de gases anestésicos y fortalecer la seguridad del paciente durante el acto quirúrgico (GE Healthcare, n.d.; Mindray, n.d.).

Desde la perspectiva de la ingeniería biomédica, el estudio de las máquinas de anestesia es fundamental, ya que involucra conocimientos de electrónica, neumática, control de sistemas, ventilación mecánica, mantenimiento preventivo y seguridad clínica. Comprender su funcionamiento permite optimizar su uso, identificar posibles fallas, apoyar los procesos de mantenimiento hospitalario y reducir riesgos asociados al uso de equipos críticos en salas de cirugía (Dorsch & Dorsch, 2014; ECRI Institute, 2021).

---

##  2. Objetivos

###  Objetivo general
Familiarizar al estudiante con los componentes, funcionamiento y mantenimiento de una máquina de anestesia.

###  Objetivos específicos
- Identificar las partes principales de la máquina WATO EX-20  
- Comprender su funcionamiento  
- Reconocer la importancia del mantenimiento  

---

##  3. Marco Teórico

Las máquinas de anestesia son sistemas electromédicos avanzados diseñados para administrar mezclas controladas de gases anestésicos y garantizar la ventilación adecuada del paciente durante procedimientos quirúrgicos. Su funcionamiento se basa en la integración de subsistemas neumáticos, electrónicos y de control, los cuales operan de manera coordinada para mantener condiciones fisiológicas estables (Dorsch, J. A. & Dorsch, S. E., 2014).

Desde el punto de vista ingenieril, estos equipos pueden analizarse como sistemas dinámicos de flujo continuo, en los cuales variables como presión, caudal y concentración son reguladas mediante dispositivos de control en lazo cerrado. Esto permite compensar perturbaciones y garantizar la seguridad del paciente durante la administración de anestesia.

 1. Sistema de suministro y regulación de gases

El sistema de suministro constituye la etapa inicial del proceso, donde gases como oxígeno (O₂), aire y óxido nitroso (N₂O) son suministrados desde cilindros o redes hospitalarias a alta presión. Posteriormente, pasan por reguladores que reducen la presión a niveles operativos seguros.

El control del flujo se realiza mediante flujómetros calibrados, los cuales permiten ajustar el caudal de cada gas. La mezcla resultante debe cumplir condiciones específicas de concentración para evitar eventos adversos como hipoxia o hiperoxia, lo cual es fundamental en la práctica clínica (World Health Organization, 2010).

 2. Vaporización de agentes anestésicos

Los vaporizadores son dispositivos diseñados para convertir anestésicos líquidos volátiles en vapor y mezclarlos con el flujo de gases. Su funcionamiento se basa en principios de transferencia de masa y equilibrio térmico, permitiendo mantener una concentración constante del agente anestésico a pesar de variaciones en el flujo o la temperatura.

Este control preciso es crítico, ya que pequeñas variaciones en la concentración pueden generar efectos clínicos significativos, desde una anestesia insuficiente hasta una depresión respiratoria severa (Dorsch & Dorsch, 2014).

 3. Sistema respiratorio y eliminación de CO₂

El sistema respiratorio de la máquina de anestesia permite la entrega de la mezcla gaseosa al paciente y la eliminación del dióxido de carbono producido durante la respiración. Este sistema incluye circuitos cerrados o semicerrados, válvulas unidireccionales y absorbedores de CO₂.

El absorbedor, generalmente basado en cal sodada, realiza reacciones químicas que eliminan el CO₂ del circuito, permitiendo la reutilización de gases y mejorando la eficiencia del sistema. Este proceso es fundamental para evitar la hipercapnia y mantener el equilibrio ácido-base del paciente.

 4. Ventilación mecánica

Las máquinas de anestesia modernas incorporan ventiladores mecánicos que permiten controlar la respiración del paciente. Estos sistemas pueden operar en diferentes modos, tales como ventilación controlada por volumen o presión, dependiendo de las necesidades clínicas.

Desde el punto de vista de control, el ventilador puede modelarse como un sistema dinámico donde se regulan variables como volumen tidal, frecuencia respiratoria y presión inspiratoria. Esto garantiza un intercambio gaseoso adecuado incluso en pacientes con compromiso respiratorio (American Society of Anesthesiologists, 2020).

 5. Sistemas de monitoreo y control

El monitoreo continuo es una característica esencial en las máquinas de anestesia modernas. Sensores especializados permiten medir variables como presión, flujo y concentración de gases en tiempo real, mientras que sistemas electrónicos procesan esta información y activan alarmas en caso de desviaciones.

Equipos desarrollados por Mindray integran interfaces digitales avanzadas que facilitan la supervisión y el ajuste de parámetros, mejorando la interacción entre el usuario y el sistema.

 6. Sistemas de seguridad

Debido al alto riesgo asociado a su uso, las máquinas de anestesia incorporan múltiples mecanismos de seguridad, tales como válvulas de alivio de presión, sistemas de corte automático de gases y alarmas auditivas y visuales.

Estos sistemas están diseñados para prevenir fallos críticos y cumplir con estándares internacionales, garantizando un entorno seguro tanto para el paciente como para el personal médico (ASA, 2020).

 7. Enfoque desde la ingeniería biomédica

Desde la ingeniería biomédica, la máquina de anestesia representa un sistema complejo que integra múltiples disciplinas, incluyendo electrónica, control automático, termodinámica y fisiología. Su análisis permite comprender la interacción entre variables físicas y biológicas, así como desarrollar estrategias de mantenimiento y mejora tecnológica.

El conocimiento detallado de estos sistemas es fundamental para asegurar su correcto funcionamiento, prevenir fallas y contribuir a la seguridad del paciente en entornos clínicos.

---

##  4. Parte A

### a. ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican durante una cirugía? Explique cada uno.


Durante los procedimientos quirúrgicos se emplean principalmente **tres tipos de anestesia**: anestesia general, anestesia regional y anestesia local. 
Cada uno presenta características específicas en cuanto a su mecanismo de acción, alcance fisiológico y aplicaciones en el ámbito clínico.

---

##  1. Anestesia general

La anestesia general es un estado farmacológicamente inducido que produce **pérdida reversible de la conciencia**, junto con analgesia, amnesia y relajación muscular. Este tipo de anestesia actúa sobre el sistema nervioso central mediante agentes inhalatorios o intravenosos.

Desde el punto de vista fisiológico, los anestésicos generales actúan sobre receptores neuronales como los GABA\(_A\), aumentando la inhibición sináptica y reduciendo la excitabilidad neuronal. Esto permite que el paciente no perciba estímulos dolorosos ni tenga respuesta consciente durante la cirugía.

Además, suele requerir ventilación asistida debido a la depresión del sistema respiratorio.

### Aplicaciones clínicas
- Cirugías mayores (abdominales, cardíacas, neurológicas).
- Procedimientos prolongados.
- Intervenciones que requieren inmovilidad total. 

---

##  2. Anestesia regional

La anestesia regional consiste en el **bloqueo reversible de la conducción nerviosa** en una región específica del cuerpo, sin pérdida de la conciencia. 
Esta se logra mediante anestésicos locales aplicados cerca de nervios o plexos nerviosos.

###  Tipos más comunes:
- **Epidural:** anestesia aplicada en el espacio epidural la cual es usada principalmente en obstetricia.
- **Espinal (raquídea):** esta es una técnica anestesica regional que inyecta anestésico local directamente en el líquido cefalorraquídeo (espacio subaracnoideo) para bloquear la sensibilidad y el movimiento en la parte inferior del cuerpo.Usada principalmente en aparatyos reproductores, vias urinarias y en general, parte inferior del cuerpo.
- **Bloqueos periféricos:**:técnicas de anestesia regional que inyectan anestésicos locales cerca de nervios específicos para adormecer extremidades o áreas localizadas, siendo útiles para cirugía y control del dolor postoperatorio. Se clasifican principalmente por la ubicación del nervio (plexos, nervios troncales) y pueden ser únicos o continuos (catéter).
Algunas aplicaciones de este puede ser bloqueo al plexo braquial para cirugía de hombro, brazo , antebrazo o codo según el nervio que se bloquee:
Interescalénico: Hombro y brazo superior.
Supraclavicular:Brazo, codo y mano ("bloqueo espinal del miembro superior").
Infraclavicular/Axilar: Antebrazo y mano.

El mecanismo de acción consiste en el bloqueo de los canales de sodio dependientes de voltaje, impidiendo la propagación del potencial de acción.

### Ventajas
- Menor depresión respiratoria  
- Recuperación más rápida  
- Menor uso de anestésicos sistémicos  

---

##  3. Anestesia local

La anestesia local produce la **pérdida de sensibilidad en una zona específica del cuerpo**, sin afectar la conciencia del paciente. Se administra directamente en el área de intervención.

Su mecanismo de acción es el bloqueo de canales de sodio en las fibras nerviosas, impidiendo la transmisión del dolor.

###  Aplicaciones clínicas
- Suturas  
- Biopsias  
- Procedimientos odontológicos  
- Dermatología  

---

## Comparación general

| Tipo de anestesia | Conciencia | Alcance | Uso principal |
|------------------|-----------|--------|--------------|
| General | No | Todo el cuerpo | Cirugías mayores |
| Regional | Sí | Región específica | Ortopedia, partos |
| Local | Sí | Zona pequeña | Procedimientos menores |

---

### b. ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante sistema de alta presión?

Las máquinas de anestesia utilizan principalmente una combinación de gases médicos que cumplen funciones específicas en la administración de anestesia y en el mantenimiento de las funciones fisiológicas del paciente.

---

##  1. Oxígeno (O₂)

El oxígeno es el gas más importante dentro del sistema, ya que es esencial para el metabolismo celular y la perfusión de los tejidos.

### Función
- Mantener la oxigenación de los tejidos (respiración celular)  
- Prevenir hipoxia durante la anestesia  
- Servir como gas base en la mezcla anestésica  

###  Porcentaje de uso
- En condiciones normales: **21% (aire ambiente)**  
- En anestesia: generalmente entre **30% y 100%**, dependiendo del paciente  
- Nunca debe ser menor a **21%**, ya que se produciría hipoxia  

###  Proceso dentro de la máquina
1. El oxígeno ingresa desde:
   - Cilindro (alta presión ≈ 2000 psi)  
   - Red hospitalaria  

2. Pasa por:
   - Regulador de presión  
   - Flujómetro (control de caudal)  

3. Se mezcla con otros gases (aire, N₂O)  

4. Pasa al vaporizador (si hay anestésico)  

5. Llega al paciente mediante el sistema respiratorio  

### Seguridad
- Sistemas anti-hipoxia garantizan que el O₂ nunca sea inferior al mínimo requerido  
- Alarmas detectan caídas en la concentración  

---

##  2. Óxido nitroso (N₂O)

Es un gas anestésico con propiedades analgésicas.

###  Función
- Disminuir el dolor  
- Reducir la cantidad de anestésico volátil necesario  
- Aumentar el efecto anestésico  

###  Porcentaje de uso
- Usualmente entre **30% y 70%**  
- Siempre combinado con oxígeno (nunca se usa solo)  

### Proceso
- Ingresa desde cilindro (alta presión ≈ 750 psi)  
- Se regula su flujo  
- Se mezcla con oxígeno antes de llegar al paciente  

---

## 3. Aire comprimido

Es una mezcla de gases similar al aire atmosférico.

###  Función
- Ajustar la concentración de oxígeno  
- Evitar toxicidad por oxígeno puro  
- Mantener condiciones fisiológicas normales  

###  Porcentaje
- Contiene aproximadamente:
  - 21% O₂  
  - 78% N₂  

---

##  4. Agentes anestésicos volátiles

Son líquidos que se vaporizan (ej: sevoflurano, isoflurano).

### Función
- Inducir y mantener anestesia general  
- Generar inconsciencia y relajación  

###  Proceso
- El gas pasa por el vaporizador  
- Se mezcla con el flujo de gases  
- Se administra en concentraciones controladas  

---

##  Gases que se incorporan mediante sistema de alta presión

Los gases que ingresan mediante cilindros a alta presión son:

- **Oxígeno (O₂)** → ≈ 2000 psi  
- **Óxido nitroso (N₂O)** → ≈ 750 psi  

Estos requieren reguladores para reducir la presión antes de su uso.

---

### c. ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

El sistema de respiración es el conjunto de componentes de la máquina de anestesia encargado de **transportar la mezcla de gases (oxígeno, aire y anestésicos)** desde la máquina hasta el paciente, y posteriormente permitir la **eliminación del dióxido de carbono (CO₂)** producido durante la respiración.

---

##  ¿Cuál es su función?

Su función principal es garantizar que el paciente:

1. Reciba la mezcla adecuada de gases anestésicos  
2. Pueda realizar el intercambio gaseoso (O₂ entra / CO₂ sale)  
3. Mantenga una ventilación segura durante toda la cirugía  

---

##  Funcionamiento paso a paso

### 1. Entrada de gases
La mezcla de gases (O₂, N₂O, aire y anestésico) sale de la máquina y entra al sistema respiratorio.

---

### 2. Inspiración (entrada al paciente)
- El gas pasa por las **válvulas unidireccionales**  
- Llega al paciente a través del circuito respiratorio  
- El paciente inhala la mezcla  

---

### 3. Espiración (salida del paciente)
- El paciente exhala CO₂  
- El gas regresa por otra válvula unidireccional  
- Se evita que el gas exhalado vuelva directamente sin control  

---

### 4. Eliminación de CO₂
- El gas pasa por el **absorbedor de CO₂ (cal sodada)**  
- Se elimina el dióxido de carbono  
- El gas puede reutilizarse en sistemas cerrados  

---

### 5. Control de presión
- La **válvula APL** regula la presión del sistema  
- Evita sobrepresión en los pulmones  

---

### 6. Bolsa reservorio / ventilador
- Permite almacenar gas  
- Ayuda a la ventilación manual o mecánica  

---

##  Componentes principales del sistema

- Circuito respiratorio (tubos)  
- Válvulas unidireccionales  
- Bolsa reservorio  
- Absorbedor de CO₂  
- Válvula APL  

---

##  Partes que pueden esterilizarse en autoclave

Las partes que están en contacto directo con el paciente o con los gases respirados deben esterilizarse.

### Componentes esterilizables:

- **Mangueras o circuitos respiratorios**  
- **Conectores y piezas plásticas desmontables**  
- **Bolsa reservorio (según material)**  
- **Válvulas desmontables**  

---

### Componentes NO esterilizables en autoclave:

- Sensores electrónicos  
- Partes internas de la máquina  
- Absorbedor de CO₂ (solo se reemplaza el material)  

---

## Importancia del sistema de respiración

Este sistema es crítico porque:

- Garantiza la oxigenación del paciente  
- Evita acumulación de CO₂ (hipercapnia)  
- Permite ventilación controlada  
- Reduce riesgos durante la anestesia  

---

### d. ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

##  1. Submenú de modos de ventilación

En este submenú se define cómo el ventilador entrega el gas al paciente. Los modos principales son:

###  Ventilación controlada por volumen (VCV)
En este modo, el ventilador garantiza que el paciente reciba un **volumen fijo de aire (volumen tidal)** en cada respiración.

- El volumen es constante  
- La presión puede variar dependiendo de la resistencia pulmonar  
- Es útil cuando se necesita asegurar una ventilación estable  

 Ejemplo: si se configuran 500 mL, el paciente recibirá exactamente ese volumen en cada ciclo.

---

###  Ventilación controlada por presión (PCV)
En este modo, el ventilador mantiene una **presión constante** durante la inspiración.

- La presión es fija  
- El volumen varía según la mecánica pulmonar  
- Reduce el riesgo de daño pulmonar por alta presión  

 Ejemplo: si se fija una presión de 20 cmH₂O, el volumen cambiará dependiendo de los pulmones del paciente.

---

###  Ventilación asistida
El ventilador ayuda al paciente cuando este intenta respirar por sí mismo.

- El paciente inicia la respiración  
- El ventilador la apoya con presión o volumen  
- Mejora la comodidad del paciente  

 Se usa cuando el paciente aún tiene capacidad respiratoria parcial.

---

###  Ventilación espontánea
El paciente respira por sí mismo sin intervención activa del ventilador.

- No hay control directo del ventilador  
- Solo se suministra la mezcla de gases  
- Se usa en fases de recuperación  

---

##  2. Submenú de parámetros ventilatorios

Permite ajustar las variables que controlan la respiración:

- **Volumen tidal (VT):** cantidad de aire por respiración  
- **Frecuencia respiratoria (FR):** número de respiraciones por minuto  
- **Relación I:E:** tiempo de inspiración vs espiración  
- **PEEP:** presión que se mantiene al final de la espiración  

 Estos parámetros se ajustan según el estado del paciente.

---

##  3. Submenú de monitoreo

Muestra en tiempo real el estado del sistema:

- Presión en la vía aérea  
- Volumen respiratorio  
- Flujo de aire  
- Curvas (gráficas)  

 Permite detectar problemas como obstrucciones o fugas.

---

##  4. Submenú de alarmas

Configura límites de seguridad:

- Presión alta o baja  
- Bajo volumen  
- Desconexión  
- Apnea  

 Si algo sale de rango, el equipo alerta inmediatamente.

---

##  5. Submenú de funciones avanzadas

Incluye funciones adicionales del ventilador.

###  Pausa inspiratoria
Mantiene el aire dentro de los pulmones por un breve tiempo al final de la inspiración.

####  ¿Para qué sirve?
- Mejora el intercambio de gases  
- Permite medir la presión alveolar (plateau)  
- Evalúa la mecánica pulmonar  

 Se activa en este submenú.

##  5. Parte B

##  Identificación de componentes de la máquina de anestesia

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/d59ece78-c720-4f4e-83bc-cd592111411a" width="350">
</p>
<p align="center"><em>Figura 1. Máquina de anestesia utilizada en el laboratorio.</em></p>

**Función:**  
Permite administrar gases anestésicos y controlar la ventilación del paciente durante procedimientos quirúrgicos.

**Explicación:**  
Integra sistemas de suministro de gases, ventilación, monitoreo y seguridad que trabajan conjuntamente para mantener condiciones fisiológicas estables en el paciente.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/59ae598d-1088-442a-a0f5-e4827f5b46e0" width="300">
</p>
<p align="center"><em>Figura 2. Bolsa de reinhalación del sistema respiratorio.</em></p>

**Función:**  
Almacenar temporalmente la mezcla de gases y permitir la ventilación manual.

**Explicación:**  
La bolsa se infla y desinfla con la respiración del paciente o con la ventilación asistida, facilitando el control del volumen de aire suministrado.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/0aeaef07-3eb3-4aa6-baf8-f40e8b6f4734" width="300">
</p>
<p align="center"><em>Figura 3. Absorbedor de dióxido de carbono (CO₂) con cal sodada.</em></p>

**Función:**  
Eliminar el CO₂ del aire exhalado por el paciente.

**Explicación:**  
Contiene cal sodada que reacciona químicamente con el CO₂, permitiendo reutilizar los gases en sistemas cerrados y evitando la hipercapnia.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/9f5fa3ca-7594-4d73-b239-a64b18432209" width="300">
</p>
<p align="center"><em>Figura 4. Recipiente recolector de condensados del sistema respiratorio.</em></p>

**Función:**  
Recolectar el agua generada por la condensación en el circuito respiratorio.

**Explicación:**  
Evita que la humedad interfiera con el flujo de gases o regrese al paciente, garantizando un funcionamiento adecuado del sistema.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/0f56d2b8-c22c-47cc-a58d-e5f2aea2d4a5" width="300">
</p>
<p align="center"><em>Figura 5. Panel de flujómetros (rotámetros) para control de gases.</em></p>

**Función:**  
Regular y medir el flujo de los gases suministrados al paciente.

**Explicación:**  
Cada flujómetro controla un gas específico (oxígeno, aire o N₂O) y permite ajustar el caudal en litros por minuto para lograr la mezcla adecuada.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/079342e0-53df-4975-9da2-6e67dd4e1136" width="300">
</p>
<p align="center"><em>Figura 6. Mascarilla de anestesia utilizada para la administración de gases.</em></p>

**Función:**  
Suministrar la mezcla de gases al paciente.

**Explicación:**  
Se adapta al rostro del paciente y permite la administración de oxígeno o anestésicos, además de facilitar la ventilación manual.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/c3fd781b-d6ef-46c3-afb1-9b69d0439780" width="300">
</p>
<p align="center"><em>Figura 7. Puertos de entrada de gases médicos (O₂, aire y N₂O).</em></p>

**Función:**  
Permitir el ingreso de gases desde la red hospitalaria o cilindros.

**Explicación:**  
Utilizan conexiones seguras y codificadas para evitar errores, garantizando el suministro correcto de cada gas al sistema.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/9c8448b7-b425-4740-9598-a23a6b2d4edb" width="300">
</p>
<p align="center"><em>Figura 8. Compartimiento para la instalación de vaporizadores anestésicos.</em></p>

**Función:**  
Permitir la incorporación de vaporizadores al sistema.

**Explicación:**  
En este espacio se instalan dispositivos que convierten anestésicos líquidos en vapor, los cuales se mezclan con los gases para inducir anestesia.

---
### Preguntas

### 1. Si el ventilador muestra “batería en uso” y el paciente está conectado, ¿qué hacer?

Cuando aparece el mensaje **“batería en uso”**, significa que la máquina está funcionando con su batería interna debido a una falla o desconexión de la fuente eléctrica principal.

####  Acción a ejecutar:
1. **Verificar inmediatamente la conexión a la red eléctrica**  
2. **Restablecer la alimentación eléctrica lo antes posible**  
3. Confirmar que la batería tenga suficiente carga  
4. Mantener vigilancia continua del paciente  

#### Importancia:
La batería es un sistema de respaldo temporal. Si se agota, el ventilador podría dejar de funcionar, poniendo en riesgo la ventilación del paciente.

---

###  2. ¿Con qué frecuencia debe reemplazarse el absorbedor de CO₂?

El recipiente de cal sodada no se cambia por tiempo fijo, sino por condición de uso.

####  Debe reemplazarse cuando:
- Hay **cambio de color** del indicador químico  
- Se observa **aumento de CO₂ en el paciente**  
- Se ha utilizado durante largos periodos (según fabricante)  

####  Frecuencia aproximada:
- Entre **6 y 12 horas de uso continuo**, dependiendo del flujo y paciente  

####  Importancia:
Un absorbedor saturado no elimina CO₂, lo que puede causar **hipercapnia**.

---

###  3. Procedimiento para verificar fugas en el cilindro de alta presión

####  Pasos:
1. Cerrar el flujo de gases  
2. Abrir el cilindro lentamente  
3. Observar el manómetro (presión)  
4. Cerrar el cilindro  
5. Monitorear si la presión disminuye con el tiempo  

####  Interpretación:
- Si la presión se mantiene →  no hay fuga  
- Si la presión disminuye →  hay fuga  

####  Adicional:
- Aplicar solución jabonosa en conexiones para detectar burbujas  

---

###  4. ¿Influye el sensor de O₂ en la prueba del sistema de flujo?

####  Sí, influye directamente

El sensor de oxígeno mide la **concentración real de O₂ en la mezcla gaseosa**.

####  Con sensor:
- Se verifica que la mezcla sea correcta  
- Se detectan errores en el flujo  
- Mayor seguridad  

####  Sin sensor:
- No se puede confirmar la concentración real  
- Existe riesgo de administrar mezclas hipóxicas  
- La prueba es incompleta  

---

###  5. ¿Para qué se requiere el sistema de presión negativa?

El sistema de presión negativa se utiliza principalmente en la evacuación de gases anestésicos.

####  Función:
- Extraer gases residuales del sistema  
- Evitar que se acumulen en el ambiente  

####  ¿Qué gases elimina?
- Gases anestésicos sobrantes  
- CO₂ residual  

####  Importancia:
- Protege al personal médico  
- Reduce contaminación ambiental  
- Previene exposición crónica a anestésicos  

##  6. Procedimiento

Durante la práctica de laboratorio se llevó a cabo un análisis estructurado de la máquina de anestesia modelo WATO EX-20, con el objetivo de comprender su funcionamiento, identificar sus componentes principales y evaluar su importancia en la seguridad del paciente.

###  Etapas realizadas:

1. **Observación del equipo**
   - Se realizó una inspección visual general de la máquina de anestesia, identificando su estructura, panel de control, sistema respiratorio y conexiones de gases.
   - Se reconocieron los subsistemas principales: suministro de gases, ventilación, vaporización y monitoreo.

2. **Identificación de componentes**
   - Se analizaron elementos clave como flujómetros, absorbedor de CO₂, bolsa de reinhalación, ventilador (fuelle), puertos de gases y mascarilla.
   - Se relacionó cada componente con su función dentro del sistema global.

3. **Revisión del manual técnico**
   - Se consultó el manual del equipo para comprender parámetros de operación, modos de ventilación, alarmas y protocolos de seguridad.
   - Se identificaron configuraciones recomendadas y límites operativos.

4. **Análisis del funcionamiento**
   - Se estudió el flujo de gases desde la entrada hasta el paciente.
   - Se analizó la interacción entre subsistemas (control de flujo, ventilación y eliminación de CO₂).
   - Se evaluaron posibles fallas y mecanismos de seguridad.

---

##  7. Resultados

Durante la práctica de laboratorio se logró reconocer de manera detallada la estructura general y el funcionamiento de la máquina de anestesia WATO EX-20, identificando sus principales componentes y relacionándolos con su función dentro del sistema anestésico.

En primer lugar, se identificaron los módulos principales del equipo, entre ellos el sistema de suministro de gases, los flujómetros, el vaporizador, el sistema respiratorio, la bolsa de reinhalación, el absorbedor de CO₂, los puertos de entrada de gases médicos, el ventilador y los elementos de monitoreo. Esta identificación permitió comprender que la máquina de anestesia funciona como un sistema integrado, en el cual cada componente cumple una función específica para garantizar la administración segura de gases anestésicos y la ventilación adecuada del paciente.

Asimismo, se comprendió el recorrido funcional de los gases dentro del equipo, desde su ingreso por la red hospitalaria o cilindros de alta presión, pasando por los reguladores, flujómetros y vaporizadores, hasta llegar al paciente mediante el circuito respiratorio. También se reconoció la importancia del absorbedor de CO₂, el cual permite eliminar el dióxido de carbono exhalado y favorece la reutilización parcial de gases en sistemas cerrados o semicerrados.

Otro resultado relevante fue el reconocimiento de los modos y parámetros ventilatorios disponibles en el equipo. Se analizaron variables como volumen tidal, frecuencia respiratoria, presión inspiratoria, relación inspiración-espiración y PEEP, evidenciando que estos parámetros deben ajustarse de acuerdo con las condiciones clínicas del paciente. Además, se identificó la función de la pausa inspiratoria como herramienta útil para evaluar la mecánica pulmonar y mejorar el control de la ventilación.

También se reconoció la importancia de los sistemas de alarma y seguridad, los cuales permiten detectar condiciones anormales como fallas en el suministro eléctrico, uso de batería, fugas en el sistema, baja presión de gases, alteraciones en la concentración de oxígeno o problemas en la ventilación. Estos mecanismos son fundamentales para prevenir eventos críticos y garantizar una respuesta oportuna por parte del personal médico o técnico.

Finalmente, se evidenció que la seguridad del paciente depende directamente de la correcta interacción entre los parámetros de flujo, presión, volumen y concentración de gases. Por esta razón, el mantenimiento preventivo, la verificación de fugas, el control del estado del absorbedor de CO₂, la revisión del sensor de oxígeno y la adecuada configuración del ventilador son procedimientos esenciales para asegurar el funcionamiento confiable de la máquina de anestesia.

---

##  8. Análisis de Resultados

El análisis permitió comprender que la máquina de anestesia es un sistema altamente dependiente de la correcta interacción entre sus subsistemas, donde pequeñas fallas pueden comprometer significativamente la seguridad del paciente.

###  Fallas comunes identificadas

- **Fugas de gas:** pueden generar pérdida de presión y mezcla incorrecta de gases, aumentando el riesgo de hipoxia.  
- **Sensores defectuosos:** afectan la medición de variables críticas como concentración de O₂ o presión.  
- **Problemas de ventilación:** fallas en el ventilador o en el circuito pueden comprometer el intercambio gaseoso.  
- **Error humano:** configuraciones incorrectas o mala manipulación del equipo representan una de las principales causas de riesgo.

---

###  Subsistemas críticos

1. **Sistema de gases**
   - Responsable del suministro y mezcla de gases medicinales.
   - Un fallo en este sistema puede generar mezclas peligrosas.

2. **Ventilador**
   - Controla la respiración del paciente.
   - Es fundamental en anestesia general.

3. **Sensores**
   - Permiten el monitoreo en tiempo real.
   - Detectan desviaciones en parámetros críticos.

4. **Sistema de alarmas**
   - Actúa como mecanismo de seguridad.
   - Permite respuesta inmediata ante fallas.

---

##  9. Conclusiones

La práctica permitió comprender de manera integral el funcionamiento de la máquina de anestesia y su importancia dentro del entorno clínico. Se evidenció que este equipo no solo administra gases anestésicos, sino que también cumple funciones críticas de ventilación y monitoreo, siendo un elemento esencial para la seguridad del paciente.

Asimismo, se concluye que la mayoría de los riesgos asociados al uso de este tipo de equipos están relacionados con errores humanos, fallas en el mantenimiento o una incorrecta configuración de parámetros. Por ello, el papel del ingeniero biomédico resulta fundamental, tanto en la gestión tecnológica como en la implementación de protocolos de seguridad que garanticen el correcto funcionamiento del equipo.

---

##  10. Preguntas de Discusión

###  1. Anestésicos más utilizados

- **Sevoflurano:** agente inhalatorio de rápida acción y recuperación, ampliamente utilizado en inducción y mantenimiento de anestesia.  
- **Isoflurano:** anestésico volátil con buena estabilidad, utilizado en procedimientos prolongados.  
- **Propofol:** anestésico intravenoso que produce inducción rápida y controlada de la anestesia.  

---

###  2. Diferencias entre WATO EX-20 y WATO EX-35

- **Nivel de automatización:** el modelo EX-35 presenta mayor automatización en procesos de ventilación y control.  
- **Monitoreo:** el EX-35 incorpora sistemas más avanzados de monitoreo de parámetros respiratorios y de gases.  
- **Interfaz de usuario:** el EX-35 cuenta con una interfaz más moderna, intuitiva y digitalizada.  
- **Capacidades clínicas:** el EX-35 ofrece mayor precisión en el control de ventilación y soporte para modos más avanzados.  

---
###  3. ¿ La máquina de anestesia WATO-EX-20 tiene bomba de infusión?

Normalas máquinas de anestesia normalmente no incorporan una bomba de infusión como componente principal integrado, ya que su función central es administrar gases médicos, agentes anestésicos volátiles y ventilación mecánica. Sin embargo, durante los procedimientos anestésicos suelen utilizarse bombas externas, especialmente bombas de jeringa, para administrar fármacos intravenosos como propofol, remifentanilo, opioides, relajantes neuromusculares o medicamentos vasoactivos. Este tipo de bomba permite una administración precisa y continua de medicamentos, por lo que es común en anestesia total intravenosa y en el soporte farmacológico intraoperatorio (Butterworth et al., 2018; Miller, 2015; Dorsch & Dorsch, 2014).
La bomba más común que se usa junto a una máquina de anestesia es la:

Bomba de jeringa o syringe pump:
	​
<img width="297" height="170" alt="image" src="https://github.com/user-attachments/assets/f1737626-2407-49e8-9c7d-be7d0eaae0dc" />

<p align="center"><em>Figura 9. Bomba de infusión de jeringa.</em></p>

Esta se utiliza para administrar medicamentos como:

Propofol.
Remifentanilo.
Fentanilo.
Dexmedetomidina.
Vasopresores.
Relajantes neuromusculares.

También puede usarse una:

Bomba de infusion volumetrica:
<img width="197" height="256" alt="image" src="https://github.com/user-attachments/assets/5b477d42-2393-48ed-a6f3-01ccf419c8b5" />
	​<p align="center"><em>Figura 10. Bomba de infusión volumétrica.</em></p>
 
Pero esta es más común para líquidos intravenosos, soluciones, mantenimiento de fluidos o medicamentos que requieren mayores volúmenes.

---
##  11. Bibliografía

American Society of Anesthesiologists. (2020). Standards for basic anesthetic monitoring. La página oficial de ASA reúne sus estándares de monitoreo anestésico y parámetros de práctica; la versión oficial actualmente disponible aparece como documento de estándares de monitoreo básico.

Butterworth, J. F., Mackey, D. C., & Wasnick, J. D. (2018). Morgan & Mikhail’s clinical anesthesiology (6th ed.). McGraw-Hill Education.

Dorsch, J. A., & Dorsch, S. E. (2014). Understanding anesthesia equipment (5th ed.). Lippincott Williams & Wilkins.

ECRI Institute. (2021). Anesthesia systems: Safety and maintenance guidelines.

GE Healthcare. (n.d.). Anesthesia systems: User manuals and technical documentation. GE Healthcare cuenta con una biblioteca oficial de documentación técnica, manuales de usuario y documentación de soporte para sus equipos médicos.

Miller, R. D. (2015). Miller’s anesthesia (8th ed.). Elsevier.

Mindray. (n.d.). WATO EX-20 anesthesia machine: Operator’s manual. Mindray dispone de una biblioteca técnica con manuales de operador y servicio para sus equipos médicos, incluyendo documentación de máquinas de anestesia.

World Health Organization. (2009). WHO guidelines for safe surgery. WHO Press. La guía de cirugía segura de la OMS incluye recomendaciones relacionadas con la seguridad anestésica, monitoreo y prevención de eventos adversos durante procedimientos quirúrgicos.

World Health Organization. (2010). Technical specifications for oxygen concentrators. WHO Press.

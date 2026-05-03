# Informe de Laboratorio  
## Instrumentación Biomédica y Biosensores  
### Reconocimiento de partes y funcionamiento de una máquina de anestesia  

---

##  1. Introducción

Las máquinas de anestesia constituyen uno de los equipos más críticos en el entorno quirúrgico moderno, ya que permiten la administración controlada de agentes anestésicos y el mantenimiento de funciones vitales durante procedimientos médicos. Estos sistemas integran múltiples subsistemas, incluyendo el suministro de gases médicos, vaporizadores, ventilación mecánica y monitoreo del paciente, con el fin de garantizar una anestesia segura y eficaz.

El principio de funcionamiento de una máquina de anestesia se basa en la mezcla precisa de gases como oxígeno, aire y agentes anestésicos volátiles, los cuales son regulados mediante dispositivos especializados que controlan tanto la concentración como el flujo. Además, incorporan mecanismos de seguridad diseñados para prevenir fallos críticos, tales como la administración incorrecta de gases o la pérdida de presión en el sistema.

En la actualidad, equipos desarrollados por fabricantes como GE Healthcare y Mindray han evolucionado hacia sistemas altamente automatizados que integran ventiladores avanzados, sensores y alarmas inteligentes, permitiendo una monitorización continua en tiempo real. Esta evolución tecnológica ha incrementado significativamente la precisión y seguridad en la administración de anestesia.

Desde la perspectiva de la ingeniería biomédica, el estudio de estas máquinas es fundamental, ya que involucra conocimientos en electrónica, control de sistemas y seguridad clínica. Comprender su funcionamiento permite optimizar su uso y contribuir al mantenimiento preventivo, reduciendo riesgos en el entorno hospitalario.

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

a) Tipos de anestesia

- **General**: pérdida total de conciencia  
- **Regional**: bloquea una zona del cuerpo  
- **Local**: actúa en una zona específica  

---

### b. ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediantesistema de alta presión?

  Gases utilizados

- Oxígeno (O₂) → función vital  
- Óxido nitroso (N₂O) → analgésico  
- Aire comprimido → mezcla  
- Anestésicos volátiles (isoflurano, sevoflurano)

**Alta presión:** O₂ y N₂O (cilindros)

---

### c. ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

 Sistema de respiración

Permite el transporte de gases y eliminación de CO₂.

**Partes esterilizables:**
- Mangueras  
- Válvulas  
- Bolsa respiratoria  

---

### d. ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

Submenús del ventilador

- Modos de ventilación  
- Configuración de parámetros  
- Alarmas  
- Monitoreo  

---

##  5. Parte B

### ✔ Partes de la máquina

- **Vaporizador:** convierte anestésico líquido en gas  
- **Válvula APL:** regula la presión  
- **Absorbedor de CO₂:** elimina dióxido de carbono  
- **Fuelle:** permite ventilación mecánica  

---

### ✔ Preguntas

**2. Batería en uso:**  
Conectar a la red eléctrica inmediatamente  

**3. Recambio de CO₂:**  
Cuando el indicador de saturación lo indique  

**4. Fugas:**  
Prueba de presión en el cilindro  

**5. Sensor de O₂:**  
Afecta la precisión del flujo  

**6. Presión negativa:**  
Evita contaminación de gases  

---

##  6. Procedimiento

1. Observación de la máquina WATO EX-20  
2. Identificación de componentes  
3. Revisión del manual  
4. Análisis de funcionamiento  

---

##  7. Resultados

- Identificación de módulos principales  
- Comprensión del funcionamiento  
- Reconocimiento de alarmas y fallas  

---

##  8. Análisis de Resultados

### ✔ Fallas comunes

- Fugas de gas  
- Sensores defectuosos  
- Problemas de ventilación  
- Error humano  

### ✔ Subsistemas críticos

1. Sistema de gases  
2. Ventilador  
3. Sensores  
4. Alarmas  

---

## 9. Conclusiones

La práctica permitió comprender la importancia de la máquina de anestesia en procedimientos clínicos. Se evidenció que muchas fallas se deben a errores humanos o falta de mantenimiento, resaltando la importancia del ingeniero biomédico en la seguridad del paciente.

---

##  10. Preguntas de Discusión

**1. Anestésicos más usados:**
- Sevoflurano  
- Isoflurano  
- Propofol  

**2. Diferencias EX-20 vs EX-35:**
- Mayor automatización  
- Mejor monitoreo  
- Interfaz más avanzada  

---

##  11. Bibliografía

- Dosch, *The Anesthesia Machine*  
- Sherwin & Eisenkraft (2020)  
- Dondelinger (2004)  

---


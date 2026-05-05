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

El oxígeno es el gas más importante dentro del sistema, ya que es esencial para el metabolismo celular y la vida.

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
   - cilindro (alta presión ≈ 2000 psi)  
   - red hospitalaria  

2. Pasa por:
   - regulador de presión  
   - flujómetro (control de caudal)  

3. Se mezcla con otros gases (aire, N₂O)  

4. Pasa al vaporizador (si hay anestésico)  

5. Llega al paciente mediante el sistema respiratorio  

### ✔ Seguridad
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

### ✔ Partes de la máquina
<p align="center">
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/d59ece78-c720-4f4e-83bc-cd592111411a" />    
Figura 1: Maquina de anestesia.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/59ae598d-1088-442a-a0f5-e4827f5b46e0" />
Figura 2:Bolsa de reinhalación de maquina de anestesia.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0aeaef07-3eb3-4aa6-baf8-f40e8b6f4734" />
Figura 3:Absorbedor de dióxido de carbono (CO₂
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9f5fa3ca-7594-4d73-b239-a64b18432209" />
Figura 4:Recipiente recolector de condensados
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0f56d2b8-c22c-47cc-a58d-e5f2aea2d4a5" />
Figura 5:Panel de flujómetros (rotámetros)
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/079342e0-53df-4975-9da2-6e67dd4e1136" />
Figura 6:Mascarilla de oxígeno/anestesia colocada en el paciente
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9134407c-f8c6-487d-9038-c5c78d619480" />
Figura 7:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/c3fd781b-d6ef-46c3-afb1-9b69d0439780" />
Figura 8:Puertos de gases médicos.
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9c8448b7-b425-4740-9598-a23a6b2d4edb" />
Figura 9: Lugar donde irian vaporizadores.
</p>
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
## 🔵 Referencias (APA 7)

- :contentReference[oaicite:0]{index=0}, :contentReference[oaicite:1]{index=1}, & :contentReference[oaicite:2]{index=2}. (2018). *Morgan & Mikhail’s clinical anesthesiology* (6th ed.). McGraw-Hill Education.  

- :contentReference[oaicite:3]{index=3}, & :contentReference[oaicite:4]{index=4}. (2014). *Understanding anesthesia equipment* (5th ed.). Lippincott Williams & Wilkins.  

- :contentReference[oaicite:5]{index=5}. (2015). *Miller’s anesthesia* (8th ed.). Elsevier.  

- :contentReference[oaicite:6]{index=6}. (2009). *WHO guidelines for safe surgery*.  

- :contentReference[oaicite:7]{index=7}. (2010). *Technical specifications for oxygen concentrators*. WHO Press.  

- :contentReference[oaicite:8]{index=8}. (2020). *Standards for basic anesthetic monitoring*.  

- :contentReference[oaicite:9]{index=9}. (n.d.). *WATO EX-20 anesthesia machine: Operator’s manual*.  

- :contentReference[oaicite:10]{index=10}. (n.d.). *Anesthesia system user manuals*.  
 

---


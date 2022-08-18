# Informe_Tarea7
Resolución de ejercicios Capítulo 13 y 14 del Libro de Floyd (Octava edición)

### Inductores (Capitulo 13)

### Transformadores (Capitulo 14)

### 1. OBJETIVOS

#### Objetivos Generales

Conocer y estudiar los conceptos de inductores y transformadores en circuitos eléctricos elementales por medio de la implementación de mapas conceptuales para mejorar el entendimiento, para luego desarrollar correctamente los ejercicios respectivos a cada tema.

#### Objetivos Específicos

- Analizar el concepto de inductores y su clasificación

- Describir la construcción y las características básicas de un inductor

- Estudiar inductores dispuestos en serie y en paralelo 

- Analizar el concepto de carga reflejada en un transformador y describir un transformador no ideal

- Describir varios tipos de transformadores

- Describir cómo se construye un transformador y cómo funciona

- Describir cómo los transformadores incrementan y disminuyen el voltaje

### 2. MARCO TEORICO

## Inductores (Capitulo 13)

![image](https://user-images.githubusercontent.com/105259381/185485768-c864dc74-b935-4e3d-9e02-e6f4ad96bc27.png)

![image](https://user-images.githubusercontent.com/105259381/185489799-0cf0e56b-c101-4044-8c79-91a4d054c785.png)
----

![image](https://user-images.githubusercontent.com/105259381/185489517-3c3a1eab-0151-40cb-980e-6d61579e1f54.png)
----

![image](https://user-images.githubusercontent.com/105259381/185492978-9e8f58c8-2c82-45e3-8829-9748e803abe7.png)

#### Potencia en un inductor

Un inductor ideal (suponiendo que no hay resistencia de devanado) no disipa energía, sólo la guarda. Cuando se aplica un voltaje de ca a un inductor ideal, el inductor almacena energía durante una parte del ciclo; en seguida la energía guardada regresa a la fuente durante otra parte del ciclo. En un inductor ideal no se pierde energía neta a causa de la conversión en calor.

Potencia instantánea (p) El producto de v por i proporciona potencia instantánea. En puntos donde v o i son cero, p también es cero. Cuando tanto v como i son positivos, p es igualmente positiva. Si v o i son positivos y la otra variable (v o i) es negativa, p es negativa. Cuando v e i son negativos, p es positiva

Potencia real (Preal) De modo ideal, toda la energía guardada por un inductor durante la parte positiva del ciclo de potencia es regresada a la fuente durante la parte negativa. No se pierde energía neta por la conversión en calor en el inductor, por lo que la potencia real es de cero.

![image](https://user-images.githubusercontent.com/105259381/185496273-e0b8aa47-7227-4d38-a5b3-0607db8facdf.png)

Potencia reactiva (Pr) La rapidez a la cual un inductor guarda o regresa energía se conoce como su potencia reactiva, con la unidad de VAR (volt-ampere reactivo). La potencia reactiva es una cantidad distinta de cero porque en cualquier instante el inductor está tomando energía de la fuente o regresando energía a ella.

![image](https://user-images.githubusercontent.com/105259381/185496416-19bc913c-84ea-4134-9297-efe9d0e4772c.png)

#### Aplicaciones de los inductores

Los inductores no son tan versátiles como los capacitores y tienden a estar más limitados en sus aplicaciones debido en parte a su tamaño, a factores de costos y a su comportamiento no ideal (resistencia interna, etc.)

Supresión de ruido

Una de las aplicaciones más importantes de los inductores tiene que ver con la supresión de ruido eléctrico indeseable. Los inductores utilizados en estas aplicaciones, en general, se enrollan sobre un núcleo cerrado para evitar que el propio inductor se transforme en una fuente de ruido radiado. Dos tipos de ruido son el ruido conductivo y el ruido radiado.

Bobinas de RF (radiofrecuencia)

Los inductores utilizados para bloquear frecuencias muy altas se llaman bobinas de radiofrecuencia (RF). Las bobinas de RF se utilizan para ruido conductivo o radiado. Son inductores especiales diseñados para impedir que las altas frecuencias entren a, o salgan de algunas partes de un sistema al crear una trayectoria de gran impedancia para frecuencias altas. 

Circuitos sintonizados 

Se utilizan inductores junto con capacitores para proporcionar la selección de frecuencia en sistemas de comunicaciones. Estos circuitos sintonizados permiten seleccionar una banda angosta de frecuencias en tanto que otras frecuencias son rechazadas. Los sintonizadores de televisión y los receptores de radio están basados en este principio y permiten seleccionar un canal o una estación de entre muchas disponibles.

## Transformadores (Capitulo 14)







### 3. EXPLICACIÓN O RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

## Resolución de los ejercicios Capítulo 13

#### SECCION 13-1 El inductor básico

2. Convierta los siguientes valores en microhenries:

![image](https://user-images.githubusercontent.com/105259381/185301674-11bbc69b-b446-47bc-bda6-5211c3f49d8e.png)

4. Se inducen 50 volts en una bobina de 25 mH. ¿Con qué rapidez cambia la corriente?

![image](https://user-images.githubusercontent.com/105259381/185301780-9288f722-7e1e-4df2-937d-affa1be0f32d.png)

6. ¿Cuántas vueltas se requieren para producir 30 mH con una bobina enrollada sobre un núcleo cilíndrico cuya área de sección transversal mide 10x10^-5 m2 y tiene longitud de 0.05 m? La permeabilidad del núcleo es de 1.2x10^-6 H/m. 

![image](https://user-images.githubusercontent.com/105259381/185302007-b1f1ddb2-fd5d-4df8-9979-baaa0e40cf4d.png)

8. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 tiene dos veces la cantidad de vueltas del inductor 1.

![image](https://user-images.githubusercontent.com/105259381/185302115-252b9111-9180-47f0-aa4d-0a1484bda68e.png)

10. Un estudiante enrolla 100 vueltas de alambre sobre un lápiz de 7 mm de diámetro como se muestra en la figura 13-43. El lápiz es un núcleo no magnético de tal suerte que su permeabilidad es igual a la de un vacío (4πx10^-6 H/m). Determine la inductancia de la bobina que se formó.

![image](https://user-images.githubusercontent.com/105259381/185302444-7cf82dde-60b7-438a-b7a4-3a4e9f45d9cb.png)

![image](https://user-images.githubusercontent.com/105259381/185302479-39d41bfa-6440-45fe-9d9e-e824c126844e.png)

#### SECCIÓN 13–3 Inductores en serie y en paralelo

12. Usted requiere una inductancia total de 50 mH. Tiene disponibles una bobina de 10 mH y otra de 22 mH. ¿Cuánta inductancia adicional necesita?

![image](https://user-images.githubusercontent.com/105259381/185302697-ec729d27-fb24-4438-b4c0-dd04d6c1c7c6.png)

14. En la figura 13-45, ¿cuál es la inductancia total entre los puntos A y B con cada posición del interruptor?

![image](https://user-images.githubusercontent.com/105259381/185302832-6bc9d81d-a49f-4404-af7d-e2c4286e1d92.png)

![image](https://user-images.githubusercontent.com/105259381/185303016-bc5175ed-84d1-4980-b222-e05a145bb6b9.png)

16. Usted tiene un inductor de 12 mH, y éste es su valor más bajo, pero necesita una inductancia de 8 mH. ¿Qué valor puede utilizar en paralelo con el inductor de 12 mH para obtener 8 mH?

![image](https://user-images.githubusercontent.com/105259381/185303140-3e8c6568-144e-4bcc-9aa4-aedc64c60df3.png)

18. Determine la inductancia total de cada circuito mostrado en la figura 13-47

![image](https://user-images.githubusercontent.com/105259381/185303233-2d7e63ed-e824-4ead-a747-5b9c3ca71239.png)

Para el circuito del literal a

![image](https://user-images.githubusercontent.com/105259381/185303330-11994e6c-1d29-44d5-95e7-15c6c2c6fbda.png)

Para el circuito del literal b

![image](https://user-images.githubusercontent.com/105259381/185303417-9cd8cad3-7d82-4792-a0a8-8a190c60e1aa.png)

Para el circuito del literal c

![image](https://user-images.githubusercontent.com/105259381/185303476-79aabf1e-51b1-4cb3-94b2-78fa27ce98ff.png)

#### SECCIÓN 13–4 Inductores en circuitos de cd

20. En un circuito RL en serie, determine cuánto tiempo se lleva la corriente para incrementarse a su valor total con cada una de las siguientes combinaciones:

![image](https://user-images.githubusercontent.com/105259381/185303861-48741ab3-3837-4a37-8455-681c98c7ac10.png)

![image](https://user-images.githubusercontent.com/105259381/185303919-88e1db81-412b-47e2-b2a1-3de998731a4f.png)

![image](https://user-images.githubusercontent.com/105259381/185303977-be7a44fd-265f-4dd2-9d33-23ac844526b9.png)

22. Para el inductor ideal de la figura 13-49, calcule la corriente en cada uno de los siguientes instantes:

![image](https://user-images.githubusercontent.com/105259381/185304108-13020679-b26a-4c27-abf9-64bf604da0c2.png)

![image](https://user-images.githubusercontent.com/105259381/185304247-bbe18593-c60e-43d3-8d3f-605ce5999f1d.png)

24. Repita el problema 22 para los siguientes instantes:

![image](https://user-images.githubusercontent.com/105259381/185304417-21f5a7b7-0064-454a-99a4-8bf9c61a737f.png)

26. (a) ¿Cuál es la polaridad del voltaje inducido en el inductor de la figura 13-49 cuando la onda cuadrada está creciendo?


![image](https://user-images.githubusercontent.com/105259381/185304556-69987e93-99c8-4ab0-93ee-97fbb78098be.png)

La polaridad será negativa ya que la polaridad del voltaje inducido se opone al cambio de corriente inducido en el circuito

(b) ¿Cuál es la corriente justo antes de que la onda cuadrada se reduzca a cero?

![image](https://user-images.githubusercontent.com/105259381/185304794-2df39f70-4213-4d17-b102-bd3a3b0a8f36.png)

28. (a) ¿Cuál es la corriente en el inductor 1.0 ms después de que se cierra el interruptor en la figura 13-50?

![image](https://user-images.githubusercontent.com/105259381/185304951-b838ae25-aa7b-47ea-a5b8-a159aec64b70.png)

![image](https://user-images.githubusercontent.com/105259381/185305027-5684b156-7670-4761-a9fa-15cf8072210e.png)

(b) ¿Cuál es la corriente después de que transcurren 5t?

![image](https://user-images.githubusercontent.com/105259381/185305121-0627c330-b286-4c93-8519-a31c2cfe2056.png)

#### SECCIÓN 13–5 Inductores en circuitos de ca

30. Determine la resistencia total para cada circuito de la figura 13-46 cuando se aplica voltaje a una frecuencia de 5 kHz entre las termina

![image](https://user-images.githubusercontent.com/105259381/185305348-3b0a2cd9-3c9b-4e38-b4d5-02d2a7c7c47b.png)

Para el circuito del literal a

![image](https://user-images.githubusercontent.com/105259381/185305477-0e6ff6b2-07bf-4e0b-a561-8e1da3215e88.png)

Para el circuito del literal b

![image](https://user-images.githubusercontent.com/105259381/185305569-8c405706-79d7-43c9-91ed-95aa578c4e16.png)

Para el circuito del literal c

![image](https://user-images.githubusercontent.com/105259381/185305640-3fac4de3-8dac-4237-8355-51d0df7bf653.png)

32. En la figura 13-51, determine la corriente rms total. ¿Cuáles son las corrientes a través de L2 y L3?

![image](https://user-images.githubusercontent.com/105259381/185306009-dfd13eb9-9146-4b1f-a878-1e284cf040a8.png)

![image](https://user-images.githubusercontent.com/105259381/185305903-819335b8-4603-40e4-969f-925c819a1dc3.png)

34. En la figura 13-51, determine la potencia reactiva.

![image](https://user-images.githubusercontent.com/105259381/185306009-dfd13eb9-9146-4b1f-a878-1e284cf040a8.png)

![image](https://user-images.githubusercontent.com/105259381/185306131-b318a849-1ba9-45dc-a294-6ef4d4d7e27c.png)

## Resolución de los ejercicios Capítulo 14

#### SECCIÓN 14–1 Inductancia mutua

2. Determine el coeficiente de acoplamiento cuando LM= 1 mH, L1= 8 mH, y L2= 2 mH.

![image](https://user-images.githubusercontent.com/105259381/185416839-4fbd63d0-453c-4276-90fe-82a2d18c6e82.png)

#### SECCIÓN 14–2 El transformador básico

4. Cierto transformador tiene 250 vueltas en su devanado primario. Para duplicar el voltaje, ¿cuántas vueltas debe haber en el devanado secundario?

![image](https://user-images.githubusercontent.com/105259381/185423785-79606d75-4f56-4e33-9924-ff3be38e3d54.png)

#### SECCIÓN 14–3 Transformadores elevadores y reductores

6. Para elevar 240 V de ca a 720 V, ¿cuál debe ser la relación de vueltas?

![image](https://user-images.githubusercontent.com/105259381/185424245-22080167-6105-4e99-9b11-ed2b2be20e02.png)

8. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 10 para obtener un voltaje secundario de 60 V de ca?

![image](https://user-images.githubusercontent.com/105259381/185424449-b2273f59-a86b-4dc1-9282-e8f692d27d34.png)

10. El devanado primario de un transformador tiene 1200 V a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 0.2?

![image](https://user-images.githubusercontent.com/105259381/185424649-7cefe839-9d10-44e0-b2ba-1a152bc22327.png)

12. ¿Cuál es el voltaje a través de la carga en cada uno de los circuitos de la figura 14-43?

![image](https://user-images.githubusercontent.com/105259381/185424807-23b09ec2-5012-4635-83a5-395b4242e091.png)

Para el circuito del literal a

![image](https://user-images.githubusercontent.com/105259381/185425186-42f665a6-1eef-4a95-833b-5fead891a039.png)

Para el circuito del literal b

![image](https://user-images.githubusercontent.com/105259381/185425534-6bfa3204-dce6-49a0-856d-793530006e84.png)

Para el circuito del literal c

![image](https://user-images.githubusercontent.com/105259381/185425867-8e261f3a-b93c-4723-86b5-71ca2fb54e60.png)

#### SECCIÓN 14–4 Carga del devanado secundario

14. Determine Is en la figura 14-45. ¿Cuál es el valor de RL?

![image](https://user-images.githubusercontent.com/105259381/185426089-703cea6a-e39a-4ea1-bd93-2d82f56f5725.png)

![image](https://user-images.githubusercontent.com/105259381/185426299-9385900c-df5c-4258-925f-c5422f89bc79.png)

#### SECCIÓN 14–5 Carga reflejada

16. ¿Cuál es la resistencia en la carga vista por la fuente en la figura 14-47?

![image](https://user-images.githubusercontent.com/105259381/185426505-d4b0f326-a522-4ce6-90df-2954a8f42dd7.png)

![image](https://user-images.githubusercontent.com/105259381/185426604-2a93e87a-9790-4a9a-b785-e7bac975ab19.png)

#### SECCIÓN 14–6 Igualación de impedancia

18. En el circuito de la figura 14-49, encuentre la relación de vueltas requerida para suministrar potencia máxima al altavoz de 4Ω. 

![image](https://user-images.githubusercontent.com/105259381/185427160-a9930fb2-f19c-4492-9e87-64114dc45a9b.png)

![image](https://user-images.githubusercontent.com/105259381/185427470-ce7d4472-1033-41f5-856d-bf51507c1bdd.png)

20. Encuentre la relación de vueltas apropiada en cada una de las posiciones mostradas en la figura 14-50 para transferir potencia máxima a cada carga cuando la resistencia de fuente es de 10Ω. Especifique el número de vueltas requerido para el devanado secundario si el devanado primario tiene 1000 vueltas.

![image](https://user-images.githubusercontent.com/105259381/185427708-e0934b84-1c6c-47fd-9e8d-8a11c65fa5be.png)

Posición 1 

![image](https://user-images.githubusercontent.com/105259381/185427920-01ccae08-9859-488a-9aaa-410bd26567fb.png)

Posición 2 

![image](https://user-images.githubusercontent.com/105259381/185428060-b6822e2f-d217-42b0-9503-b89f8160d550.png)

Posición 3

![image](https://user-images.githubusercontent.com/105259381/185428209-bf6b25b2-06e4-4e61-939e-34b8651a092e.png)

#### SECCIÓN 14–7 Características de un transformador no ideal

22. ¿Cuál es la eficiencia del transformador en el problema 21?

![image](https://user-images.githubusercontent.com/105259381/185428527-34cb2c5a-4767-48cb-8df7-db766b8755cb.png)

24. La potencia nominal de cierto transformador es de 1 kVA. El transformador opera a 60 Hz y 120 V de ca. El voltaje secundario es de 600 V

(a) ¿Cuál es la corriente máxima en la carga?

![image](https://user-images.githubusercontent.com/105259381/185428789-a41690c2-5305-44d1-b6ed-ab2a3891c798.png)

(b) ¿Cuál es el valor RL más pequeño que puede ser excitado?

![image](https://user-images.githubusercontent.com/105259381/185429024-f1ae7588-c68f-405b-8f94-72e0b069bd3f.png)

(c) ¿Cuál es el capacitor más grande que se puede conectar como carga?

![image](https://user-images.githubusercontent.com/105259381/185429145-97f3e018-a59f-453f-8776-6bf8ed96ec3b.png)

26. La potencia nominal de cierto transformador es de 5 kVA, 2400/120 V, a 60 Hz.

(a) ¿Cuál es la relación de vueltas si los 120 V son el voltaje secundario?

![image](https://user-images.githubusercontent.com/105259381/185429454-7aaacc2c-8b79-44a7-88a5-b85f392c6ee0.png)

(b) ¿Cuál es la corriente nominal del secundario si los 2400 V son el voltaje primario?

![image](https://user-images.githubusercontent.com/105259381/185429584-7ccd1e9e-df31-46bb-90a8-f2c310427b21.png)

(c) ¿Cuál es la corriente nominal del devanado primario si los 2400 V son el voltaje primario?

![image](https://user-images.githubusercontent.com/105259381/185429615-22957140-e06d-4564-a70d-c58c8730b565.png)

#### SECCIÓN 14–8 Transformadores con tomas y devanados múltiples

28. Con los voltajes indicados en la figura 14-52, determine la relación de vueltas de cada sección de toma del devanado secundario al devanado primario.

![image](https://user-images.githubusercontent.com/105259381/185430034-1c040e9b-0f49-4e9f-b992-8d959cd9ef25.png)

Secundario 1

![image](https://user-images.githubusercontent.com/105259381/185429943-f048ed5f-12e8-4db8-b1ea-ed6da23ebedb.png)

Secundario 2

![image](https://user-images.githubusercontent.com/105259381/185430161-b2d14610-d594-4de2-9b93-8dc8f10c4c91.png)

Secundario 3

![image](https://user-images.githubusercontent.com/105259381/185430185-b805a5e9-cc02-4fd4-a8d7-49895228978c.png)

30. En la figura 14-54, cada primario puede acomodar 120 V de ca. ¿Cómo se deberán conectar los primarios para que operen con 240 V de ca? Determine cada voltaje secundario para operación con 240 V

![image](https://user-images.githubusercontent.com/105259381/185430885-5f235284-1f52-4c67-9699-f10de5acad6d.png)

Se conecta de la siguiente manera:

![image](https://user-images.githubusercontent.com/105259381/185431281-3ea26822-2cc3-4e0a-a77c-e5906f4d0ae2.png)

100 vueltas

![image](https://user-images.githubusercontent.com/105259381/185431562-9f93b126-412f-4480-99e2-fcee2a2a0f54.png)

200 vueltas

![image](https://user-images.githubusercontent.com/105259381/185431660-66deb1e5-0c91-4188-a7d1-44fe3157538f.png)

500 vueltas

![image](https://user-images.githubusercontent.com/105259381/185431718-43e863fc-337e-4e5c-9ae9-b5d3d1d2ce27.png)

1000 vueltas

![image](https://user-images.githubusercontent.com/105259381/185431769-0f1efd91-512f-4255-85a2-fedb52d218d1.png)

#### SECCIÓN 14–9 Localización de fallas

32. Cuando se aplican 120 V de ca a través del devanado primario de un transformador y se verifica el voltaje en el devanado secundario, se leen 0 V. Una investigación más a fondo muestra que no hay corriente en el primario ni en el secundario. Enumere las posibles fallas. ¿Cuál es el siguiente paso en la investigación del problema?

![image](https://user-images.githubusercontent.com/105259381/185432553-59a76246-01ef-442c-a305-eebf1ede8640.png)

Respuesta:

- El devanado secundario se encuentra en cortocircuito

- Se debe realizar una verificación del devanado secundario con el ohmetro

- El siguiente paso sería reemplazar el transformador

34. Mientras usted revisa un transformador, se da cuenta que el voltaje secundario es menor de lo que debería ser aunque no es de cero. ¿Cuál es la falla más probable?

Respuesta:

El devanado secundario puede que esté en cortocircuito. Es probable que exista una corriente excesiva debido a la baja resistencia reflejada provocada por el corto.

### 4. CONCLUSIONES

Mediante el estudio del inductor se conoce que básicamente una bobina de alambre se basa en el principio de inducción electromagnética, lo cual ya se había estudiado una parte de este tema. Se denota que la inductancia es la propiedad de una bobina de alambre que se opone a un cambio de corriente. La base de la inductancia es el campo electromagnético que rodea cualquier conductor cuando fluye corriente a través de él.

Para la aplicación de inductores en un circuito se determina la inductancia de bobinas midiendo la constante de tiempo de un circuito de prueba por medio de formas de onda de un osciloscopio. 

Al momento de aplicar transformadores en un circuito se aprendió a localizar fallas en un tipo de fuente de potencia de cdque utiliza un transformador para acoplar el voltaje de ca tomado de una toma de corriente eléctrica estándar. Al medir el voltaje en varios puntos, es posible determinar si existe una falla y especificar la parte defectuosa de la fuente de potencia.

Mediante el estudio de transformadores se analizó que la operación del transformador se basa en el principio de inductancia mutua, la cual ocurre si dos o más bobinas están muy cercanas una de otra. En realidad, un transformador simple se compone de dos bobinas que están acopladas de manera electromagnética por su inductancia mutua. Como no existe contacto eléctrico entre dos bobinas magnéticamente acopladas, la transferencia de energía de una bobina a la otra se logra en una situación de completo aislamiento eléctrico.

### 5. VIDEO



### 6. BIBLIOGRAFÍA

Floyd, TL (2007). Principios de circuitos electricos. Monterrey: Pearson Educación.


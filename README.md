# Informe_Tarea_9

1. OBJETIVOS

1.1. OBJETIVO GENERAL

Analizar el comportamiento de los circuitos RLC y de los filtros pasivos, mediante el análisis de los capítulos 17 y 18 del libro "Principios de circuitos eléctricos" de Thomas Floyd, con el fin de desarrollar correctamente los ejercicios planteados en ambos capítulos y aplicar los conocimientos adquiridos en clase.

1.2. OBJETIVOS ESPECÍFICOS

-	Determinar el comportamiento de la impedancia en un circuito en serie, para realizar el análisis correcto del mismo. 
-	Identificar el significado de decibeles, para entender su relación con los diferentes tipos de filtros pasivos.

2. MARCO TEORICO 

- CAPÍTULO 17

2.1. CIRCUITOS EN SERIE

![Copia de Concept map (1)](https://user-images.githubusercontent.com/94008521/155534835-a7b307c8-f5f0-41aa-9f64-40901072d3a8.png)

2.2. CIRCUITOS EN PARALELO

![Copia de Concept map (2)](https://user-images.githubusercontent.com/94008521/155534872-40622359-0177-4819-8923-934ab2bd7a6b.png)

2.3. CIRCUITOS EN SERIE - PARALELO

![Cause and effect (6)](https://user-images.githubusercontent.com/94008521/155534925-922cdb8d-4f8a-40fc-a0c1-0b93e99b286f.png)

2.4. TEMAS ESPECIALES

![Copia de Concept map (3)](https://user-images.githubusercontent.com/94008521/155534960-e1295ed1-6028-4139-8855-a4b56adf1c88.png)

- CAPÍTULO 18

2.5. FILTROS PASABAJAS

![Cause and effect (7)](https://user-images.githubusercontent.com/94008521/155535085-c47d8459-2f97-4f90-98a0-8148988cef26.png)

2.6. FILTROS PASAALTAS

![Copia de Concept map (4)](https://user-images.githubusercontent.com/94008521/155535121-127af4ed-3869-4e02-b5b8-0291867a5238.png)

2.7. FILTROS PASABANDA

![Cause and effect (8)](https://user-images.githubusercontent.com/94008521/155535185-8ad61add-806c-4a7e-a354-7e20ee2120e0.png)

2.8. FILTROS RECHAZABANDA 

![Copia de Concept map (5)](https://user-images.githubusercontent.com/94008521/155535237-3c35b489-55a2-459a-9350-f8cea42231c7.png)

3. EXPLICACION Y RESOLUCION DE EJERCICIOS O PROBLEMAS

        CAPITULO 17 
    
PARTE 1: CIRCUITOS EN SERIE

SECCIÓN 17–1 Impedancia de circuitos RLC en serie

1.Cierto circuito RLC en serie tiene los siguientes valores: R=10Ω, C =0.047 mF, y L= 5 mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

![image](https://user-images.githubusercontent.com/93960809/155445443-cfaab9c4-20a1-4cfb-a6d8-170c3feeb030.png)

Para el desarrollo de este ejercicio, en primer lugar, se halla los valores de reactancia tanto para el capacitor como para el inductor. Luego se determina cuál es el mayor valor de reactancia para identificar si el circuito es predominante capacitivo o predominante inductivo. Se halla el valor de reactancia neta o total y luego se encuentra el valor de la impedancia en su forma polar, como se puede ver el ángulo es positivo debido a que es un circuito inductivo.

3.Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/93960809/155445530-3838267a-2d7f-4941-be38-3f6cf088e5b8.png)

Si se duplica la frecuencia esto quiere decir que dicha frecuencia se va a aumentar por tanto el valor de las reactancias capacitivas al ser inversos a la frecuencia van a disminuir, mientras que el valor de la reactancia inductiva se va a aumentar debido a que esto es proporcional a la frecuencia. Por tanto, la magnitud de la impedancia va a cambiar de modo que se va a disminuir dicha magnitud de impedancia. 

SECCIÓN 17–2 Análisis de circuitos RLC en serie

5.Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/93960809/155445585-7e90db47-6c39-49b4-be83-7ff773acc4cb.png)

![image](https://user-images.githubusercontent.com/93960809/155445617-703f77ce-8b21-42fa-be8d-21cbda10ab38.png)

Para hallar los datos que se solicita de este circuito, primero se halla el valor de la impedancia en polares y luego mediante la ley de ohm se calcula tanto el valor de corriente como de voltajes. 

7.Analice el circuito de la figura 17-60 para determinar lo siguiente (f = 25 kHz): (a) Itot (b) Preal (c) Pr (d) Pa

![image](https://user-images.githubusercontent.com/93960809/155445647-cf76a8d8-3acd-4499-948e-4d5d0cdf3133.png)

![image](https://user-images.githubusercontent.com/93960809/155445772-a974647e-f006-40f1-aac3-a770b840b72d.png)

Para resolver este ejercicio y hallar los respectivos datos solicitados en los literales, primero se calcula el valor de resistencia, inductancia y capacitancia total. Luego se procede a hallar las reactancias mediante lo cual se determina que este es un circuito capacitivo. Se halla el valor de la impedancia y mediante la ley de ohm se encuentra la corriente, finalmente con los datos ya obtenidos se utilizan las fórmulas de potencia.

SECCIÓN 17–3 Resonancia en serie

9.Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/93960809/155448661-ba1b3a54-76f7-4d2a-b1dd-c5487f9808ac.png)

![image](https://user-images.githubusercontent.com/93960809/155448690-3791308d-707b-4b44-a2df-c49631287425.png)

Para hallar el valor del voltaje, teniendo en cuenta que el circuito se encuentra en condición de resonancia, se conoce que la impedancia es puramente resistiva. Luego con el valor de impedancia y aplicando la ley de ohm se encuentra el valor de voltaje a través de la resistencia. 

11.Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

![image](https://user-images.githubusercontent.com/93960809/155448732-f0d625c1-da95-4d8c-8db8-ec4f2414b70f.png)

Mediante los datos que da el enunciado del ejercicio y despejando impedancia y reactancia de las fórmulas de la ley de ohm se obtienen los datos solicitados. Al ser un circuito resonante XL es igual a Xc. 

13.Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/93960809/155452865-114aa48a-d570-46e1-a41d-e30bdc37ed6a.png)

![image](https://user-images.githubusercontent.com/93960809/155452886-65b6b3bc-9eca-43ba-b7d8-a842b06a50fa.png)

Para determinar el valor de la corriente, se halla primero el valor de la impedancia y luego mediante la ley de ohm se procede a encontrar la corriente. 

15.Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador: (a) 500 kHz (b) 1000 kHz (c) 1500 kHz (d) 2000 kHz

![image](https://user-images.githubusercontent.com/93960809/155533843-0eb23bc2-6bae-47f5-b774-881ef6e6a04c.png)

PARTE 2: CIRCUITOS EN PARALELO

SECCIÓN 17–4 Impedancia de circuitos RLC en paralelo *

17.¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta.

![image](https://user-images.githubusercontent.com/93960809/155454514-672a7daf-5b7d-4078-8676-328e3fe19191.png)

![image](https://user-images.githubusercontent.com/93960809/155454535-5725dc9c-f414-47d5-bfa7-1d853d092c35.png)

El circuito es inductivo debido a que el valor de reactancia inductiva es menor al valor de reactancia capacitiva, ya que en circuitos RLC paralelos la cantidad más pequeña tiene el efecto más grande en la corriente total porque su corriente es máxima.

SECCIÓN 17–5 Análisis de circuitos RLC en paralelo

19.Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar.

![image](https://user-images.githubusercontent.com/93960809/155459294-5a614259-c69e-4c36-a933-7a7932c6c523.png)

![image](https://user-images.githubusercontent.com/93960809/155459316-37cf59f4-fc30-481c-9fc9-a1de6ab90f04.png)

Para determinar todas las corrientes y voltajes primero se halla el valor de las reactancias y luego despejando la corriente y el voltaje de la ley de ohm se obtienen cada uno de los valores solicitados.

21.Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19.

![image](https://user-images.githubusercontent.com/93960809/155459330-341b776e-4d09-4a7b-9b51-4e56199208fb.png)

![image](https://user-images.githubusercontent.com/93960809/155459356-787f9fda-ebf3-4e88-adaf-4ec902347236.png)

Para determinar todas las corrientes y voltajes primero se halla el valor de las reactancias y luego despejando la corriente y el voltaje de la ley de ohm se obtienen cada uno de los valores solicitados.

SECCIÓN 17–6 Resonancia en paralelo

23.Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![image](https://user-images.githubusercontent.com/93960809/155531083-cf7bf62f-7d09-4288-900c-9c782fdf8e33.png)

![image](https://user-images.githubusercontent.com/93960809/155533710-6aa1fca4-6eab-45fb-ae81-1969974a6bbc.png)

Para hallar el valor de la frecuencia resonante se usa la fórmula especificada arriba a fin de encontrar el dato solicitado. Y la impedancia la hallamos mediante la sumatoria inversa. 

25.Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![image](https://user-images.githubusercontent.com/93960809/155531162-87b51c7e-024c-4fb8-9786-c18afa317324.png)

![image](https://user-images.githubusercontent.com/93960809/155531202-5a3e2ceb-dcec-4f90-bfde-67016f7d5721.png)

Para resolver este ejercicio y hallar los respectivos datos solicitados en los literales, primero se calcula el valor de la frecuencia resonante. Luego se procede a hallar las reactancias mediante lo cual se determina que este es un circuito capacitivo. Se halla el valor de la impedancia y mediante la ley de ohm se encuentra la corriente, finalmente con los datos ya obtenidos se utilizan las fórmulas de potencia.

PARTE 3: CIRCUITOS EN SERIE-PARALELO

SECCIÓN 17–7 ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

27.Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.

![image](https://user-images.githubusercontent.com/93960809/155531724-57c72e2c-c2d3-4a1c-8c0d-77d8abcfba02.png)

![image](https://user-images.githubusercontent.com/93960809/155544025-c6cdb3e1-0e2b-45f9-a999-1a2572b980cc.png)

Para el circuito a:

![image](https://user-images.githubusercontent.com/93960809/155544076-f0a8f233-dc05-4db0-9b3d-d574e9d805d0.png)

Para el circuito b: 

![image](https://user-images.githubusercontent.com/93960809/155544122-666c3832-d215-4e04-8939-9400a647ffdb.png)

29.Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![image](https://user-images.githubusercontent.com/93960809/155531748-d677c9e1-0dc8-4780-b855-c3e48722b2f7.png)

![image](https://user-images.githubusercontent.com/93960809/155544174-a4c0a7d4-42a3-4f70-a671-64b96f539057.png)

El nuevo circuito tiene como resistencia 49.03k ohmios y un valor de inductancia de 17.44kH. 

31.En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![image](https://user-images.githubusercontent.com/93960809/155531764-82a08534-3220-4c34-b845-85737d3f5fc4.png)

![image](https://user-images.githubusercontent.com/93960809/155544295-8e68f0c3-43d0-42d6-8e9a-fd305ff78a16.png)

Para determinar lo solicitado en este ejercicio primero se halla el valor de las reactancias para así calcular la impedancia y mediante la ley de ohm se halla lo requerido por el enunciado del ejercicio. 

33.Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada componente.

![image](https://user-images.githubusercontent.com/93960809/155531788-82898748-f16b-4327-bdb2-d8e11d7e3538.png)

![image](https://user-images.githubusercontent.com/93960809/155544363-e02c58f4-ce76-4e00-8447-63886667a864.png)

35.Si el valor de C es de 0.22 mF, ¿cuál es la corriente a través de un resistor de 100 Ω conectado de a a b en la figura 17-69?

![image](https://user-images.githubusercontent.com/93960809/155531881-f7e9366a-5b06-45f2-a507-8aef2e98468d.png)

![image](https://user-images.githubusercontent.com/93415377/155535911-9f97f205-892b-48bf-b679-17cb85b07858.png)


37.Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![image](https://user-images.githubusercontent.com/93415377/155426462-39107a04-9228-4cfc-8d77-6dc770ddc900.png)

![image](https://user-images.githubusercontent.com/93415377/155426485-c94ccf94-c746-47d7-a103-cf6374ea9519.png)


PARTE 4: TEMAS ESPECIALES

SECCIÓN 17–8 Ancho de banda de circuitos resonantes

39.En condición de resonancia, XL = 2 kΩ y RW =25Ω en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda.

![image](https://user-images.githubusercontent.com/93415377/155426421-25c32c7f-c9e3-48f5-8fb3-226c5214e9c8.png)


41.En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

![image](https://user-images.githubusercontent.com/93415377/155426367-e33e8f42-fbbb-43e0-9315-1fbf85445f74.png)


43.Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?

![image](https://user-images.githubusercontent.com/93415377/155426334-33fada2a-b1c3-4d47-a04f-3adf5a64e498.png)


     CAPITULO 18

SECCIÓN 18–1 Filtros pasabajas

1.En cierto filtro pasabajas, XC = 500 Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms?

![image](https://user-images.githubusercontent.com/93415377/155426545-a2df192e-efe8-4c8e-8558-49d271abdb14.png)


3.Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent = 10 V.

![image](https://user-images.githubusercontent.com/93415377/155426639-e4fdeb42-c391-44a7-a5fc-a093fde3bdc5.png)

![image](https://user-images.githubusercontent.com/93415377/155426663-4fe7e9f5-e21e-4b74-990c-b44c395fcd53.png)

![image](https://user-images.githubusercontent.com/93415377/155426811-d915375e-36ab-42fe-a869-3ed2c8cab2b4.png)

![image](https://user-images.githubusercontent.com/93415377/155426832-01789b8d-7512-49e1-a869-f8d3d8660e15.png)

5.Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas:
(a) 60 Hz  (b) 500 Hz   (c) 1 kHz  (d) 5 kHz

![image](https://user-images.githubusercontent.com/93415377/155426866-6bbc1918-d835-47bd-ba33-3e3cee8611ac.png)

![image](https://user-images.githubusercontent.com/93415377/155427027-123fb539-f2dc-4197-9313-924c9bd0049d.png)

7.Trace una curva de Bode para cada una de las partes del problema 5.

![image](https://user-images.githubusercontent.com/93415377/155427046-569c0a85-4658-4fc0-a133-4952418a33bf.png)

9.El voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:
(a) -1 dB      (b) -3 dB       (c) -6 dB       (d) -20 dB

![image](https://user-images.githubusercontent.com/93415377/155427140-8e81a924-63f0-439b-a5f3-c8226a9ba793.png)

![image](https://user-images.githubusercontent.com/93415377/155427246-868557aa-20d6-495a-a380-c2bf5841cbeb.png)


SECCIÓN 18–2 Filtros pasaaltas

11.En un filtro pasaaltas, XC = 500Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando Vent =10 V rms?

![image](https://user-images.githubusercontent.com/93415377/155427284-66c9178f-7ca7-475e-8693-a99522c324ee.png)


13.Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent =10 V.

![image](https://user-images.githubusercontent.com/93415377/155427401-24958e2c-2d55-4a52-a686-2b5e13913561.png)

![image](https://user-images.githubusercontent.com/93415377/155427421-2fa567bb-7c63-4f36-a183-b60cc6dc5265.png)

![image](https://user-images.githubusercontent.com/93415377/155427503-1e18861e-0064-47f1-94cf-6ae5dec5d483.png)

![image](https://user-images.githubusercontent.com/93415377/155427534-9e2dcac1-aa9b-4a01-a142-c05d90fbe7e2.png)


15.Trace la curva de Bode para cada filtro mostrado en la figura 18-41.

![image](https://user-images.githubusercontent.com/93415377/155427907-ca34272d-8289-4af5-a21f-f41718db4e30.png)

![image](https://user-images.githubusercontent.com/93415377/155427974-81c9768f-733d-4d79-8ebf-122201611cc1.png)

SECCIÓN 18–3 Filtros pasabanda

17.Determine la frecuencia central para cada filtro de la figura 18-43.

![image](https://user-images.githubusercontent.com/93415377/155428352-48d743a2-48f2-42f9-82b0-f1f23f58fc3e.png)


19.¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0.

![image](https://user-images.githubusercontent.com/93415377/155530871-4305402e-a797-4e0e-a43c-d456d3e09f1f.png)


21.Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent =120 V?

![image](https://user-images.githubusercontent.com/93415377/155429015-59ea19c5-101f-4a8e-a650-09e7573d7096.png)


23.Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB = 500 Hz; Q = 40; e IC(máx) = 20 mA, VC(máx) = 2.5 V.

![image](https://user-images.githubusercontent.com/93415377/155429207-6caa5068-b482-41d6-9cdc-b9c3cea0b5cd.png)

SECCIÓN 18–4 Filtros Rechazabanda

25.Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo.

![image](https://user-images.githubusercontent.com/93415377/155429374-07290180-74ea-485c-b48f-111113e2ee38.png)


27.Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200 kHz y rechazar una señal con frecuencia de 456 kHz.

![image](https://user-images.githubusercontent.com/93415377/155429413-f9a63bfc-f805-45f9-be72-3acae24cb07a.png)

![image](https://user-images.githubusercontent.com/93415377/155429429-f92537ca-8df6-4a76-b54d-f8940f0a00c6.png)

4. VIDEO

https://www.youtube.com/watch?v=KAdeoOMgnkc

5. CONCLUSIONES

-	Como se pudo analizar durante el capítulo 17, en un circuito RLC en serie típico la impedancia total se comporta de la siguiente manera, al momento de comenzar con una frecuencia muy baja, XC es alta, XL es baja, por lo que el circuito es predominantemente capacitivo. 
-	Con respecto al termino decibeles se puede terminar que, este es una unidad que se deriva de la respuesta logarítmica que el oído humano presenta a la intensidad de sonido, así mismo esta unidad posee una relación de una potencia a otra y de un voltaje a otro, dentro de los filtros pasivos se lo utiliza para expresar o explicar la relación de entrada a salida de un filtro.

6. BIBLIOGRAFÍA

-	Irwin, J. David, Análisis básico de circuitos en ingeniería, Prentice Hall Hispanoamericana, 1997, ISBN: 968-880-816-4.
-	Humphries J.T. y Sheets L.P., Electrónica industrial: Dispositivos, Máquinas y Sistemas de potencia industrial, Paraninfo, 1993, ISBN: 84-283-2278-3
-	Purcell, E. M. (1969). Berkeley physics course, volumen 2, Electricidad y Magnetismo. Reverté, Barcelona. 
-	Salvador, G., Rodriguez, R. (2002). Física Re-Creativa. Prentice Hall, Buenos Aires.
-	Floyd, T. (2007). Principios de circuitos eléctricos. Monterrey: Pearson.

# UNIVERSIDAD DE LAS FUERZAS ARMADAS "ESPE"
![image](https://user-images.githubusercontent.com/116772918/200762591-a164d8db-c02e-4269-8bb4-0bc4c810d79f.png)

# INFORME TAREA 7

**Nombre:** Emerson Solano

**Carrera:** Mecatrónica

**Fecha de entrega:** 19/02/2023

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**1. OBJETIVOS**

**1.1  OBJETIVO GENERAL**

* Leer el capitulo 13 y 14 del libro *Principios de circuitos electricos-Floyd* para comprender, analizar e investigar acerca de los inductores y los transformadores.

**1.2  OBJETIVOS ESPECIFICOS**
* Resumir los capítulos trece y catorce del libro de Floyd, para el estudio de los temas relacionados a inductores.
* Aplicar los conocimientos aprendidos de los capítulos 13 y 14 del libro *Principios de circuitos electricos-Floyd* para resolver ejercicios que tengan relación con el tema.
* Identificar los diferentes tipos de inductores y transformadores, sus funciones y características.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. MARCO TEORICO**

# Capítulo 13

![image](https://user-images.githubusercontent.com/93794279/153586600-931f24d3-0ca8-45c7-b9f9-f2a1934f937f.png)

![image](https://user-images.githubusercontent.com/93794279/153588775-82c20d21-1af4-47ed-9747-3b5dd5bc4733.png)

# Capítulo 14

![image](https://user-images.githubusercontent.com/93794279/153590176-edc59369-404f-48b9-ab64-00d15a0bba66.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**

# Capítulo 13

**SECCIÓN 13-1 El inductor básico**
1. Convierta los siguientes valores en milihenries: 

(a) 1 H = 1000 mH 	(b) 250µH = 2,5x10^-4	(c) 10µH = 10^-5 	(d) 0.0005 H = 0.5mH

3. ¿Cuál es el voltaje en una bobina cuando di/dt = 10 mA/µs y L = 5 µH?

Vind=L*di/dt
Vind=5 mH*10 mA/ms
Vind=50 mV

5. La corriente a través de una bobina de 100 mH cambia a razón de 200 mA/s. ¿Cuánto voltaje se induce en la bobina?

Vind=L*di/dt
200 mA/s*(1 s)/(1000 ms)=0.2 mA/ms
Vind=100 mH*0.2 mA/ms
Vind=20 mV

7. ¿Qué cantidad de energía se guarda en un inductor de 4,7 mH cuando la corriente es de 20 mA?

W=1/2LI^2
W=1/24.7 mH[(20 mA)]^2
W=940 mJ

9. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 está enrollado sobre un núcleo de hierro (permeabilidad relativa = 150) y el inductor 1 está enrollado sobre un núcleo de acero al bajo carbono (permeabilidad relativa = 200).

La inductancia del inductor 1 es mayor que la inductancia del inductor 2 ya que L=(N^2μA)/l, siendo L directamente proporcional a μ: la permeabilidad. Si 150/200=3/4, se concluye que la inductancia del inductor 2 es los 3/4 de la inductancia del inductor 1.

**SECCIÓN 13-3 Inductores en serie y paralelo**

11. Se conectan cinco inductores en serie. El valor más bajo es de 5 mH. Si el valor de cada inductor es el doble del valor precedente, y si los inductores se conectan en orden de valores ascendentes, ¿cuál es la inductancia total?

L_T = L_1+L_2+L_3+⋯+L_n
L_T = (5+10+20+40+80) μH
L_T = 155 μH

13. Determine la inductancia total en la figura 13-44

![axel_imagen13](https://user-images.githubusercontent.com/99141342/152921264-a2b83e7a-8dd1-41fd-8e4b-dbf0af4b5fb6.png)


L_T=L_1+L_2+L_3+⋯+L_n
500 μH*(1 mH)/(1000 μH)=0.5 mH
L_T= (50+0.5+0.01) mH
L_T=50.51 mH

15. Determine la inductancia total en paralelo para las siguientes bobinas dispuestas en paralelo: 75 µH, 50 µH, 25 µH, y 15 µH.

1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n
1/L_T =1/75 μH+1/50 μH+1/25 μH+1/15 μH
1/L_T =7/50 μH
L_T=50/7 μH=7.14 μH

17. Determine la inductancia total de cada circuito mostrado en la figura 13-46.

![axel_imagen17](https://user-images.githubusercontent.com/99141342/152921335-1675d590-cc8f-4180-802b-1ee4b5cb0c06.png)

(a)
1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n
1/L_T =1/10 H+1/5 H
1/L_T =3/10 H
1/L_T =10/3 H=3.33 H
L_T=L_1+L_2+L_3+⋯+L_n
L_T=(3.33+1)H
L_T=4.33 H
(b)
L_T=L_1+L_2+L_3+⋯+L_n
L_T=(50+50) mH
L_T=100 mH
1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n
1/L_T =1/100 mH+1/100 mH
1/L_T =2/100 mH
L_T =100/2 mH=50 mH
(c)
1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n
1/L_T =1/200 μH+1/100 μH+1/400 μH
1/L_T =7/400 μH
L_T =400/7 μH=57.14 μH

**SECCIÓN 13-4 Inductores en circuitos de cd**

19. Determine la constante de tiempo para cada una de las siguientes combinaciones RL dispuestas en serie:
(a) R= 100 Ω, L= 100µH
T=L/R
100μH*1mH/(1000 μH)*1H/(1000 mH)=0.0001 H
T=(0.0001 H)/(100 Ω)
T=0.000001 s=1 μs

(b) R= 4,7 kΩ, L=10mH

T=L/R
10mH*1H/(1000 mH)=0.01 H
4.7 kΩ*1000Ω/(1 kΩ )=4700 Ω
T=(0.01 H)/(4700 Ω)
T=0.000002128 s=2.13 μs


(c) R= 1.5MΩ, L=3H
T=L/R
1.5 MΩ*1000000Ω/(1 MΩ)=1500000 Ω
T=(3 H)/(1500000 Ω)
T=0.000002 s=2 μs


25. En la figura 13-48, ¿en qué momento luego de que se cierra el interruptor el voltaje llega a 5 V?

![FIGURA 1](https://user-images.githubusercontent.com/99141342/152904702-c8b68ecc-0b63-4224-a7c8-73cf899afe43.PNG)

![FIGURA 2](https://user-images.githubusercontent.com/99141342/152904716-a40ec62c-2581-4030-a7af-f5f8fc2bd823.PNG)

27. Determine la constante de tiempo para el circuito de la figura 13-50.

![FIGURA 3](https://user-images.githubusercontent.com/99141342/152904758-7f0ab640-edad-412f-95c0-7e9d9383819f.PNG)

![FIGURA 4](https://user-images.githubusercontent.com/99141342/152904766-66157791-1062-478c-8d41-0ca168051c7e.PNG)

*29. Para el circuito de la figura 13-50, suponga que el interruptor estuvo cerrado por más de 5t y se abre
¿Cuál es la corriente en el inductor 1.0 ms después de que se abre el interruptor?

![FIGURA 5](https://user-images.githubusercontent.com/99141342/152904833-2965725a-5cfe-4a54-9993-a283441744e6.PNG)

**SECCIÓN 13-5 Inductores de circuitos en ca**

31. Determine la reactancia total para cada circuito de la figura 13-47 cuando se aplica voltaje a una frecuencia
de 400 Hz.

![FIGURA 6](https://user-images.githubusercontent.com/99141342/152905027-4ce98853-a41b-4a48-9c8c-72a669c315e4.PNG)

![FIGURA 7](https://user-images.githubusercontent.com/99141342/152905032-0f2884cc-e693-42c6-a972-0669cc9af5e4.PNG)

33. ¿Qué frecuencia producirá una corriente rms total de 500 mA en cada circuito de la figura 13-47 con
un voltaje de entrada rms de 10 V?

![FIGURA 8](https://user-images.githubusercontent.com/99141342/152905076-780c9ed3-ab3d-4724-b649-1a6dfd35f387.PNG)

35. Determine IL2 en la figura 13-52.

![FIGURA 9](https://user-images.githubusercontent.com/99141342/152905112-936d9def-76d4-4a6f-b6d7-ab48b6b0c6fc.PNG)

![FIGURA 10](https://user-images.githubusercontent.com/99141342/152905118-a0a5a530-d4b2-420c-b8d9-3703cd48ccf4.PNG)


# Capítulo 14

**SECCIÓN 14–1 Inductancia mutua**
  
1. ¿Cuál es la inductancia mutua cuando k=0.75, L1=1 uH, y L2=4 uH?

![p1](https://user-images.githubusercontent.com/94129932/153522826-c75affdd-c1dc-4b39-a8f8-3bca2c1a4132.png)

**SECCIÓN 14–2 El transformador básico**
  
3. ¿Cuál es la relación de vueltas de un transformador con 250 vueltas en el primario y 1000 en el secundario? ¿Cuál es la relación de vueltas cuando el devanado primario tiene 400 vueltas y el secundario 100?
Respondiendo la primera pregunta:

![image](https://user-images.githubusercontent.com/94129932/153532973-aa15cfaf-7439-4dc7-a33a-af484d994500.png)

Respondiendo la segunda pregunta:

![image](https://user-images.githubusercontent.com/94129932/153532937-e21fb70c-a6dd-4469-85ab-394d26074256.png)

5. Para cada transformador de la figura 14-42, trace el voltaje secundario que muestre su relación con el
voltaje primario. Indique también la amplitud.

![image](https://user-images.githubusercontent.com/94129932/153528940-4f855839-d183-4af2-8b45-1030790bfa35.png)

a) Se puede apreciar en el tranformador que las bobinas tienen la misma dirección, por lo tanto los voltajes primario y secundario están en la fase. La relación de vueltas es 10 por lo tanto el voltaje secundario es 10 veces mayor que el voltaje de entrada 100v.

![image](https://user-images.githubusercontent.com/94129932/153530652-2e69a41e-813e-42ea-a050-435ee36883ca.png)

b)Se puede apreciar en el tranformador que las bobinas estan enrolladas, por lo tanto los voltajes primario y secundario están desfasados 180 grados. La relación de vueltas es 2 por lo tanto el voltaje secundario es el doble que el voltaje de entrada 20v.

![image](https://user-images.githubusercontent.com/94129932/153531417-ef6bea5f-7bb2-4fd6-95ba-d86ba4739ecd.png)

c)Se puede apreciar en el tranformador que las bobinas estan enrolladas en dirección opuesta, por lo tanto los voltajes primario y secundario están desfasados 180 grados. La relación de vueltas es un quinto por lo tanto el voltaje secundario es un quinto del voltaje de entrada 20v.

![image](https://user-images.githubusercontent.com/94129932/153531362-a6aaef96-4593-4607-8af7-b56aa72d86b9.png)

**SECCIÓN 14–3 Transformadores elevadores y reductores**

7. El devanado primario de un transformador tiene 120 V de ca a través de él. ¿Cuál es el voltaje secundario
si la relación de vueltas es de 5?

![image](https://user-images.githubusercontent.com/94129932/153533341-5370e49b-348f-4f82-9ec8-2470360c1d8f.png)

9. Para reducir 120 V a 30 V, ¿cuál debe ser la relación de vueltas?

![image](https://user-images.githubusercontent.com/94129932/153534096-c19f8ee4-ec36-4e00-aafc-899cb41e6007.png)

11. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 0.1 para
obtener un voltaje secundario de 6 V de ca?

![image](https://user-images.githubusercontent.com/94129932/153534435-10c7948d-51dd-4154-8fd0-20dea3f10597.png)

13. Determine las lecturas de medidor no especificadas en la figura 14-44.

![image](https://user-images.githubusercontent.com/94129932/153534495-f7a3545e-29dd-4e7a-8c5e-62c8917f159a.png)

a)
![image](https://user-images.githubusercontent.com/94129932/153602111-218bd7ba-db22-4c82-9e5c-c3d8f1ed606e.png)

b)
![image](https://user-images.githubusercontent.com/94129932/153602515-5259443e-d1f2-4daa-a6e9-61420b769a8f.png)

**SECCIÓN 14–4 Carga del devanado secundario**

15. Determine las siguientes cantidades en la figura 14-46.

![image](https://user-images.githubusercontent.com/94129932/153535152-911ad7f0-57d0-4087-a737-6382e4aa8939.png)

a)
![image](https://user-images.githubusercontent.com/94129932/153536706-3c2f4a65-8727-4fdc-bad4-244e32b6fa62.png)

b)
![image](https://user-images.githubusercontent.com/94129932/153536884-4788da41-abc5-4df7-b4db-e2084002faf0.png)

c)
![image](https://user-images.githubusercontent.com/94129932/153536747-89af8ef7-ad36-4535-97e0-00710aa09f5a.png)

d)
![image](https://user-images.githubusercontent.com/94129932/153536762-8e902cb6-0c97-46dc-a1ea-ad6b94191130.png)

**SECCIÓN 14–5 Carga reflejada**

17. ¿Cuál debe ser la relación de vueltas en la figura 14-48 para reflejar 300 Æ en el circuito primario?

![image](https://user-images.githubusercontent.com/94129932/153537819-297978a2-9f34-459c-a983-edef70a9f99c.png)

![image](https://user-images.githubusercontent.com/94129932/153537774-2f0480af-6ecb-48ef-ab7a-587aa18f0f57.png)

**SECCIÓN 14–6 Igualación de impedancia **

19. En la figura 14-49, ¿cuál es la potencia máxima que puede ser suministrada al altavoz de 4 Æ?

![image](https://user-images.githubusercontent.com/94129932/153539732-4455744d-cf68-4d5e-9849-ac7a5f17b4f3.png)

![image](https://user-images.githubusercontent.com/94129932/153539685-05fa273d-d695-483c-867b-310b0800b4ed.png)

**SECCIÓN 14–7 Características de un transformador no ideal**

21. En cierto transformador, la potencia de entrada al primario es de 100 W, Si se pierden 5.5 W en las resistencias
de devanado, ¿cuál es la potencia de salida hacia la carga, omitiendo cualesquiera otras pérdidas?

![image](https://user-images.githubusercontent.com/94129932/153603266-d24e970a-bf6a-438c-ad59-e2d5648cddc9.png)

23. Determine el coeficiente de acoplamiento de un transformador en el cual un 2% del flujo total generado
en el primario no pasa a través del secundario.

![image](https://user-images.githubusercontent.com/94129932/153604599-f4ac8fdc-6235-4306-9065-633ff763394d.png)

25. ¿Qué potencia nominal en kVA se requiere para un transformador que debe manejar una corriente máxima
de 10 A a través de la carga con un voltaje secundario de 2.5 kV?

![image](https://user-images.githubusercontent.com/94129932/153598140-6c472df0-ee72-487c-ab75-f17a2a6d80af.png)


**SECCIÓN 14–8 Transformadores con tomas y devanados múltiples**

27. Determine cada uno de los voltajes desconocidos indicados en la figura 14-51.

![image](https://user-images.githubusercontent.com/94129932/153540742-47d147ac-f842-4892-b400-8ab74f0b1708.png)

![image](https://user-images.githubusercontent.com/94129932/153600024-b1ad108d-fd3f-4b57-b40b-68ac22be5fb3.png)

29. Encuentre el voltaje secundario para cada uno de los autotransformadores mostrados en la figura 14-53.

![image](https://user-images.githubusercontent.com/94129932/153540762-9b8cc074-3385-46ec-bdc8-7aa3e4c14665.png)

a)
![image](https://user-images.githubusercontent.com/94129932/153605049-1a582139-1760-4b94-9b62-f06d89c7be79.png)

b)
![image](https://user-images.githubusercontent.com/94129932/153605243-bf9ee837-cf70-4db7-a924-f5f2600975ce.png)

*31. Para el transformador cargado con tomas que muestra la figura 14-55, determine lo siguiente:

![image](https://user-images.githubusercontent.com/94129932/153540796-a6d363f1-2ef2-422b-9207-04a6cb2fe4f1.png)

a)
![image](https://user-images.githubusercontent.com/94129932/153607128-2d5529ea-9a3c-4d4b-81c2-c0f49901ef79.png)

b)
![image](https://user-images.githubusercontent.com/94129932/153606859-87612279-dfc7-4465-9edc-8699f07bc53e.png)

**SECCIÓN 14–9 Localización de fallas**

33. ¿Qué es probable que suceda si el devanado primario de un transformador se pone en cortocircuito?

Se extrae corriente primaria en exceso, lo que causaría que potencialmente se queme la fuente y/o el transformador a menos que se proteja el primario con un fusible o resistencia.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**4. VIDEO**

https://youtu.be/rjMv_GqmLkA

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**5. CONCLUSIONES**
* Un inductor guarda energía en su campo magnético cuando a través de él fluye corriente
* La interacción entre inductores da lugar a los transformadores, que producen un campo electromagnético útil para determinar diferentes características existentes entre  inductores, como son voltaje y corriente.
* Los transformadores de potencial son los utilizados en lo que es transmisión ya que estos convierten voltajes altos en bajos voltajes estos transformadores son los que trabajan para sistemas trifásicos.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**7. BIBLIOGRAFÍA**
1. Qué es un inductor y cómo funciona. (2018, February 9). Plantas eléctricas. https://www.luzplantas.com/que-es-un-inductor-y-como-funciona/
2. Banerjee, K. (2021, June 15). Inductores en serie y paralelo. Lambda Geeks. https://es.lambdageeks.com/inductors-in-series-and-parallel/
3.Electromecánicos, A. (n.d.). UNIDAD 2: Transformadores. Edu.Ar. Retrieved February 11, 2022, from https://rephip.unr.edu.ar/bitstream/handle/2133/16745/21503-19%20ACCIONAMIENTOS%20ELECTROMEC%C3%81NICOS%20Transformadores.pdf?sequence=3&isAllowed=y
4. Ryff, P. F., & etc. (1986). Electrical machines and transformers: Principles and applications. Prentice Hall.
5. Floyd, Thomas.L. (2007). Floyd Octava Edición principios de circuitos electricos (8va edición, Vol.11 y 12). Prentice Hall

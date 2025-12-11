<p align="center">
  <img src="https://img.shields.io/badge/ENTROPÍA-TERMODINÁMICA%20%7C%20INFORMACIÓN%20%7C%20CUÁNTICA-blueviolet?style=for-the-badge&logo=python&logoColor=white" />
</p>

<h1 align="center">📘 Proyecto: ENTROPÍA</h1>

<p align="center">
  <b>Dispersión de la energía • Microestados • Shannon • Entrelazamiento • Dimensionalidad</b>
</p>

<hr>


# Definiciones-Alternativas-de-Entropia
Entropía – Repositorio
Definición de la entropía como la dispersión de la energía

Para tener una definición más moderna de la entropía, la definen Atkins y De Paula (2008) como la medida del grado de disipación de la energía en un sistema y alrededores,

En palabras textuales:

“Una interpretación más satisfactoria de la entropía, es como medida de la disipación de la energía. Cuando ocurre un cambio, la energía se disipa más y la entropía aumenta. así la segunda ley de la termodinámica es, por lo tanto, la afirmación de que la energía tiene a disiparse y que existe una dirección natural del cambio en la que la energía queda cada vez más disipada.”
(Atkins y De Paula, 2008, pág. 77-78)

También incluyen el criterio universal del cambio espontaneo:

“Hemos encontrado la señal indicadora del cambio espontaneo: buscamos la dirección del cambio que conduce la disipación de energía total del sistema aislado”
(Atkins & de Paula, 2008, p. 78)

Podemos definir la entropía S como la función de estado que cuantifica el grado en el que la energía de un proceso se ha disipado o distribuido entre todos los microestados accesibles del sistema y sus alrededores.

Un proceso espontáneo ocurre siempre en la dirección en la que la energía total se disipa más, es decir, aquella en la que la variación de la entropía total del universo es mayor que cero:

Δ
𝑆
tot
=
𝑆
sistema
+
𝑆
alrededores
>
0
ΔS
tot
	​

=S
sistema
	​

+S
alrededores
	​

>0

Resumiendo, así la segunda ley como:

Δ
𝑆
tot
>
0
ΔS
tot
	​

>0
EJERCICIOS PRÁCTICOS
Enunciado 1: Un cubito de hielo a 0 °C se pone en agua a 25 °C

La energía térmica del agua tibia se reparte hacia el hielo (lo derrite) y queda distribuida entre muchas más moléculas en forma líquida.
→ La energía total se disipa más que antes
→ ΔS_tot > 0
→ Proceso espontáneo.

El proceso inverso (el agua líquida se congela sola sacando calor al ambiente más caliente) nunca ocurre porque disminuiría la disipación total de energía.

Enunciado 2: Mezcla de gases

Un recipiente dividido en dos partes: una con helio y otra con neón (misma T y P). Se quita la pared divisoria.

Las moléculas de cada gas, que antes estaban confinadas en la mitad del volumen, ahora ocupan todo el recipiente.
→ La energía cinética de traslación se reparte en un volumen mayor número de posiciones posibles
→ La energía se disipa más
→ ΔS_tot > 0
→ La mezcla es espontánea.

Nunca se ve que los gases se separen solos, porque eso concentraría la energía en menos microestados.

Entropía como distribución de microestados

En la termodinámica estadística, la entropía cuantifica la multiplicidad de microestados accesibles a un macroestado especificado por variables extensivas como energía, volumen y número de partículas. Esta formulación, propuesta por Ludwig Boltzmann, fundamenta la irreversibilidad termodinámica en el principio de máxima probabilidad, donde los macroestados de alta entropía dominan debido a su superior degeneración microscópica (Reif, 1965).

Microestados y Macroestados

Un microestado es como una “foto instantánea completa” de todo lo que pasa dentro del sistema: la posición exacta (q) y la velocidad (p) de cada una de las N partículas.

El macroestado es una “región grande” en el espacio fase (ΔΓ), que agrupa muchos microestados parecidos.

Entonces, Ω (el número de microestados) se calcula como el tamaño de esa región dividido por:

ℎ
3
𝑁
𝑁
!
h
3N
N!

Finalmente:

𝑆
=
𝑘
𝐵
ln
⁡
Ω
S=k
B
	​

lnΩ

Cuando N es muy grande, esta S se comporta como una propiedad extensiva (que suma al juntar sistemas).

La Segunda Ley, al Natural

La segunda ley dice que la entropía nunca baja (ΔS ≥ 0) en un sistema aislado.
¿Por qué? Porque Ω (número de microestados) solo puede aumentar o quedarse igual.

Ejemplos prácticos
Ejemplo 1: Entropía de 20 monedas

Estado: 10 caras y 10 cruces.

Ω
=
(
20
10
)
Ω=(
10
20
	​

)
𝑆
=
𝑘
𝐵
ln
⁡
Ω
S=k
B
	​

lnΩ

Máxima entropía:

𝑆
max
=
20
𝑘
𝐵
ln
⁡
2
S
max
	​

=20k
B
	​

ln2

Conclusión: Es el macroestado más probable.

Ejemplo 2: Gas ideal expandiéndose

4 partículas, 2 compartimentos.

Estado inicial: todas a la izquierda → Ω = 1
Estado final: distribución libre → Ω ≈ 16
ΔS > 0 → espontáneo

Entropía como calidad de información (Shannon)

Shannon (1948) define la entropía como incertidumbre promedio:

𝐻
=
−
∑
𝑝
𝑖
log
⁡
2
𝑝
𝑖
H=−∑p
i
	​

log
2
	​

p
i
	​


Propiedades:

Máxima cuando todos los eventos son equiprobables.

Cero cuando un evento es seguro.

Concavidad: mezclar aumenta la entropía.

Conexión con física

Jaynes (1957) mostró que si todos los microestados tienen probabilidad igual, Shannon y Boltzmann se vuelven equivalentes:

𝑆
=
𝑘
𝐵
ln
⁡
Ω
S=k
B
	​

lnΩ
Ejemplos de Shannon
Ejemplo 1: Moneda sesgada

P(cara)=0.9, P(cruz)=0.1.

H < 1 bit → más predecible.

Ejemplo 2: Compresión de texto con Huffman

Ejemplo trabajado:
Frecuencias de letras (e, t, a, o, i, n, r, s)
Construcción del árbol Huffman
Códigos óptimos
Tasa promedio ≈ 3.05 bits
ASCII = 8 bits
→ Compresión ~62%

Entropía como entrelazamiento cuántico

La entropía cuántica de von Neumann:

𝑆
(
𝜌
)
=
−
Tr
(
𝜌
ln
⁡
𝜌
)
S(ρ)=−Tr(ρlnρ)

Propiedades:

Estado puro: S = 0

Estado totalmente mezclado: S máxima

Subaditividad

Mide el grado de entrelazamiento

Ejemplo 1: Par de Bell

Sistema total: S = 0
Cada qubit individual: S = 1
→ máximo entrelazamiento.

Ejemplo 2: Qubits con magnetización parcial

Se muestran valores comparativos de entropía:

Estado	S_total	S_A	S_B	Entrelazamiento
Bell	0	1	1	Máximo
Separado	0.32	0.50	0.50	Bajo
Producto	0.32	0.11	0.32	Ninguno
Entropía como función de la dimensionalidad

En espacios de alta dimensión:

El volumen se concentra en la superficie.

La entropía crece extremadamente rápido.

Ejemplo:
Hipercubo en D dimensiones
Volumen efectivo en superficie para D > 10
H ∝ D × 2^D

Relación con el Principio Holográfico

En gravedad cuántica:

𝑆
∝
𝐴
S∝A

(área, no volumen)

Maldacena (1998): AdS/CFT
’t Hooft (1993): Reducción dimensional
Susskind (1995): Mundos holográficos

Definición y ecuación de la segunda ley de la termodinámica

La segunda ley indica que la entropía total del universo aumenta en procesos espontáneos.

Según Chemistry (Flowers et al., 2015):

Definiciones:
Δ
𝑆
=
𝑆
final
−
𝑆
inicial
ΔS=S
final
	​

−S
inicial
	​

Δ
𝑆
univ
=
Δ
𝑆
sis
+
Δ
𝑆
alr
ΔS
univ
	​

=ΔS
sis
	​

+ΔS
alr
	​

Δ
𝑆
alr
=
−
Δ
𝐻
sis
𝑇
ΔS
alr
	​

=
T
−ΔH
sis
	​

	​


Criterios:

ΔS_univ > 0 → espontáneo

ΔS_univ < 0 → no espontáneo

ΔS_univ = 0 → reversible

Ejemplo: Congelación del agua
Parámetro	Cálculo	Resultado
ΔS_alr	(-ΔH_sis)/T = -(-6000 J)/263.15 K	+22.80 J/K
ΔS_univ	ΔS_sis + ΔS_alr = -22.1 + 22.80	+0.70 J/K

→ Espontáneo a -10°C

Parámetro	Cálculo	Resultado
ΔS_alr	-(-6000)/273.16	+21.97 J/K
ΔS_univ	-22.1 + 21.97	-0.13 J/K

→ No espontáneo a +10°C

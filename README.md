<p align="center">
  <img src="https://img.shields.io/badge/ENTROPÍA-TERMODINÁMICA%20%7C%20INFORMACIÓN%20%7C%20CUÁNTICA-blueviolet?style=for-the-badge&logo=python&logoColor=white" />
</p>

<h1 align="center">📘 Proyecto: ENTROPÍA</h1>

<p align="center">
  <b>Dispersión de la energía • Microestados • Shannon • Entrelazamiento • Dimensionalidad</b>
</p>

<hr>


# 📑 Índice

1. [Definición de la entropía como dispersión de la energía](#definición-de-la-entropía-como-la-dispersión-de-la-energía)
2. [Ejercicios prácticos](#ejercicios-practicos)
3. [Entropía como distribución de microestados](#entropía-como-distribución-de-microestados)
    - [Microestados y Microestados](#microestados-y-microestados)
    - [La Segunda Ley, al Natural](#la-segunda-ley-al-natural)
4. [Ejemplos prácticos](#ejemplos-prácticos)
5. [Entropía como calidad de información](#entropía-como-calidad-de-información)
6. [Entropía como entrelazamiento de información](#entropía-como-entrelazamiento-de-información)
7. [Entropía como función de la dimensionalidad](#entropía-como-función-de-la-dimensionalidad)
8. [Segunda ley de la termodinámica](#definición-y-ecuación-de-la-segunda-ley-de-la-termodinámica)
9. [Ejemplo: Congelación del agua](#ejemplo-congelación-del-agua)
10. [Referencias](#referencias)


Definición de la entropía como la dispersión de la energía

Para tener una definición más moderna de la entropía, la definen Atkins y De Paula (2008) como la medida del grado de disipación de la energía en un sistema y alrededores,
En palabras textuales: 
“Una interpretación más satisfactoria de la entropía, es como medida de la disipación de la energía. Cuando ocurre un cambio, la energía se disipa más y la entropía aumenta. así la segunda ley de la termodinámica es, por lo tanto, la afirmación de que la energía tiene a disiparse y que existe una dirección natural del cambio en la que la energía queda cada vez más disipada.” (Atkins y De Paula, 2008, pág. 77-78)
También incluyen el criterio universal del cambio espontaneo:
“Hemos encontrado la señal indicadora del cambio espontaneo: buscamos la dirección del cambio que conduce la disipación de energía total del sistema aislado” (Atkins & de Paula, 2008, p. 78)

Podemos definir la entropía S como la función de estado que cuantifica el grado en el que la energía de un proceso se ha disipado o distribuido entre todos los microestados accesibles del sistema y sus alrededores.
Un proceso espontáneo ocurre siempre en la dirección en la que la energía total se disipa más, es decir, aquella en la que la variación de la entropía total del universo es mayor que cero:
ΔSₜₒₜ = S sistema +S Alrededores> 0 
Resumiendo, así la segunda ley como: 
ΔStot > 0
(Atkins & de Paula, 2008, pp. 78–79)
EJERCICIOS PRACTICOS:
Enunciado Un cubito de hielo a 0 °C se pone en agua a 25 °C.
La energía térmica del agua tibia se reparte hacia el hielo (lo derrite) y queda distribuida entre muchas más moléculas en forma líquida. → La energía total se disipa más que antes → ΔS_tot > 0 → proceso espontáneo. El proceso inverso (el agua líquida se congela sola sacando calor al ambiente más caliente) nunca ocurre porque disminuiría la disipación total de energía.
Enunciado Un recipiente dividido en dos partes: una con helio y otra con neón (misma T y P). Se quita la pared divisoria.
Las moléculas de cada gas, que antes estaban confinadas en la mitad del volumen, ahora ocupan todo el recipiente. → La energía cinética de traslación se reparte en un volumen mayor número de posiciones posibles → la energía se disipa más → ΔS_tot > 0 → la mezcla es espontánea. Nunca se ve que los gases se separen solos, porque eso concentraría la energía en menos microestados.
Entropía como distribución de microestados

En la termodinámica estadística, la entropía S cuantifica la multiplicidad de microestados Ω accesibles a un macroestado especificado por variables extensivas como energía E, volumen V y número de partículas N. Esta formulación, propuesta por Ludwig Boltzmann, fundamenta la irreversibilidad termodinámica en el principio de máxima probabilidad, donde los macroestados de alta entropía dominan debido a su superior degeneración microscópica (Reif, 1965).
Microestados y Microestados
Un microestado es como una "foto instantánea completa" de todo lo que pasa dentro del sistema: la posición exacta (q) y la velocidad (p) de cada una de las N partículas. Imagina el "espacio de fase" como un mapa gigante en 6 dimensiones por partícula (3 para posición + 3 para velocidad), así que para N partículas son 6N dimensiones en total.
El macroestado es una "región grande" en ese mapa (ΔΓ), que agrupa muchos microestados parecidos. Por ejemplo, todos los microestados donde el gas tiene energía E, volumen V y N moléculas.
Entonces, Ω (el número de microestados) se calcula como el tamaño de esa región dividido por h^{3N} N! (h es la constante de Planck para corregir unidades cuánticas, y N! porque las partículas son idénticas y no distinguimos cuál es cuál).
Finalmente, la entropía sale como S = k_B ln Ω. Y cuando N es muy grande (límite termodinámico), esta S se comporta como una propiedad "normal" que suma si juntas sistemas (Reif, 1965).

La Segunda Ley, al Natural
La segunda ley dice que la entropía nunca baja (ΔS ≥ 0) en un sistema aislado. ¿Por qué? Porque Ω (número de microestados) solo puede aumentar o quedarse igual. Las trayectorias en el espacio de fase conservan Ω (como billar), pero que el sistema "vaya hacia atrás" a un Ω menor es como que todas las moléculas se junten solas de nuevo: la probabilidad es e^{-N}, ridículamente pequeña cuando N es grande (tipo Avogadro).
Esto explica paradojas como el demonio de Maxwell: un ser que "mide" moléculas para separar rápidas de lentas. Parece violar la segunda ley, pero medir genera entropía extra (información = correlación = desorden oculto), así que al final todo suma (Reif, 1965).
Ejemplos prácticos:
Ejemplo 1: Entropía de 20 monedas (Sistema simple de dos estados)
Situación: Imagina 20 monedas justas (cara o cruz). Calcula la entropía del macroestado con exactamente 10 caras y 10 cruces.
Paso 1: Identifica Ω (número de microestados).
Es el número de formas de elegir 10 caras de 20 monedas:
Ω=(20¦10)=20!/(10!⋅10!)=184756
Paso 2: Calcula la entropía.
S=k_B ln⁡Ω=k_B ln⁡(184756)≈k_B⋅12.43
(Aquí k_B es la constante de Boltzmann; numéricamente ~1.38×10^{-23} J/K, pero para sistemas macro se usa en unidades arbitrarias).
Paso 3: Compara con máximo.
Máxima Ω total = 2^{20} = 1,048,576 (todos los estados posibles).
S_máx = k_B ln(2^{20}) = 20 k_B ln 2 ≈ 13.86 k_B.
Conclusión: Este macroestado tiene ~90% de la entropía máxima, por eso es el más probable.
Ejemplo 2: Gas ideal expandiéndose (4 partículas en 2 compartimentos)
Situación: 4 partículas indistinguibles en un recipiente con 2 compartimentos iguales (izquierdo/derecho). Inicialmente todas a la izquierda; luego se libera la partición.
Paso 1 (Inicial): Todas 4 a la izquierda.
Ω_inicial = 1 (solo una forma, partículas idénticas).
S_inicial = k_B ln 1 = 0.
Paso 2 (Final, equilibrio): Partículas distribuidas libremente (cada una tiene 2 choices).
Ω_final = 2^4 / 4! = 16 / 24 = 2/3? Espera, mejor: total microestados = \binom{4+2-1}{4} = 15 (distribución Bose para idénticas), pero simple: Ω = 2^4 = 16 sin dividir por N! para distinguishable approx.
(Aprox. distinguishable para claridad): Ω_final = 16.
S_final = k_B ln 16 ≈ 2.77 k_B.
Paso 3: Cambio de entropía.
ΔS = S_final - S_inicial = 2.77 k_B > 0.
Conclusión: La expansión aumenta S porque hay 16 veces más formas de estar distribuidas que concentradas. Probabilidad de volver al inicial: 1/16 (Reif, 1965).
Entropía como calidad de información 

La entropía de Shannon, desarrollada en 1948, redefine la entropía como una medida de incertidumbre o información promedio en un mensaje o fuente de datos. No es "desorden físico", sino cuántos bits necesitas en promedio para describir un evento aleatorio. Para una fuente con eventos de probabilidad p_i, la entropía mide la "sorpresa media" necesaria para codificar la información (Shannon, 1948).
Definición Matemática
Para una variable aleatoria discreta X con N posibles outcomes de probabilidades {p_1ⓜ,p_2ⓜ,...ⓜ,p_N }:
H(X)=-∑_(i=1)^N▒p_i  〖log⁡〗_2 p_i
Unidades: bits (log base 2). Si usas ln, son nats.
Propiedades clave:
	H máxima cuando todos p_i=1/N: H_max=〖log⁡〗_2 N
	H=0 si un evento es cierto (p=1)
	Concava: mezcla probabilidades no reduce información
Conexión con la Entropía Física
Edwin Jaynes (1957) demostró que la fórmula de Boltzmann S=k_B ln⁡Ω es idéntica a la entropía de Shannon cuando todos los microestados son equiprobables (p_i=1/Ω):
S=-k_B∑p_i ln⁡p_i=k_B ln⁡Ω
La termodinámica emerge como inferencia bayesiana máxima de entropía bajo restricciones macroscópicas conocidas (Jaynes, 1957).
Ejemplos prácticos: 
Ejemplo 1: Cara/Cruz sesgada
Moneda con P(cara)=0.9, P(cruz)=0.1.
H=-[0.9〖log⁡〗_2 0.9+0.1〖log⁡〗_2 0.1]=-[0.9(-0.152)+0.1(-3.322)]=0.469" bits" 
Comparación: Moneda justa (0.5/0.5): H=1 bit.
Interpretación: La moneda sesgada da menos información por tiro (más predecible), requiere menos bits para comprimir secuencias largas.
Ejemplo 2: Texto de inglés básico (Compresión real)
Fuente: Texto simple con letras frecuentes en inglés básico:
e(0.30), t(0.20), a(0.15), o(0.10), i(0.08), n(0.07), r(0.05), s(0.05)
Paso 1: Construye el árbol Huffman (proceso simplificado):
	Une los menos frecuentes: r+s = 0.10 → nuevo nodo "rs"
	Une i+n = 0.15 → nuevo nodo "in"
	Une "rs"(0.10) + o(0.10) = 0.20 → nodo "rso"
	Ahora tienes: e(0.30), t(0.20), a(0.15), "in"(0.15), "rso"(0.20)
	Une a+"in" = 0.30 → nodo "ain"
	Une t+"rso" = 0.40 → nodo "trso"
	Final: e(0.30) vs "trso"(0.40) → raíz
Tabla de códigos resultantes:
Letra	Prob	Código	Longitud
e	0.30	0	1
t	0.20	100	3
a	0.15	110	3
o	0.10	1010	4
i	0.08	1110	4
n	0.07	1111	4
r	0.05	10110	5
s	0.05	10111	5
Paso 2: Calcula tasa promedio de bits
L=0.30⋅1+0.20⋅3+0.15⋅3+0.10⋅4+0.08⋅4+0.07⋅4+0.05⋅5+0.05⋅5=3.05" bits/letra" 
Paso 3: Entropía teórica H
H=-∑p_i 〖log⁡〗_2 p_i≈2.95" bits/letra"
(Códigos muy cercanos al óptimo)
Comparación práctica:
	Codificación fija (8 bits/letra, ASCII) = 8 bits
	Huffman = 3.05 bits → 62% de compresión
	Ejemplo texto: "the" → t(100)+h(?)+e(0) = ~7 bits vs 24 bits fijos
Conclusión: En textos reales, Huffman ahorra ~60% espacio. ZIP/JPG lo usan combinado con otros métodos (Shannon, 1948).

Entropía como entrelazamiento de información 
Introducción
En mecánica cuántica, la entropía de von Neumann generaliza la entropía de Shannon al mundo cuántico, midiendo la "mezcla" o pureza de un estado cuántico. Para sistemas entrelazados, captura la correlación cuántica no clásica que no se puede describir por estados separados. Cuando dos partículas están entrelazadas, su entropía conjunta es baja (estado puro), pero cada subsistema por separado tiene entropía máxima (totalmente mezclada), cuantificando así el grado de entrelazamiento (Nielsen & Chuang, 2000).
Definición Matemática
Para un sistema cuántico con matriz densidad ρ:
S(ρ)=-"Tr"(ρ〖log⁡〗_2 ρ)
Propiedades clave:
	Estado puro: ρ=∣ψ⟩⟨ψ∣, eigenvalues=1,0 → S=0
	Estado máximo mezclado (qubit): ρ=I/2, S=1 bit
	Subaditividad: S(AB)≤S(A)+S(B), igualdad si no entrelazados
Diferencia con Shannon
Shannon asume observables conmutativos (clásicos). Von Neumann maneja no-conmutatividad:
S(ρ_AB)+S(ρ_A)+S(ρ_B)≥S(ρ_A⊗ρ_B)
La discordancia cuántica mide exceso de correlación cuántica sobre clásica.
Ejemplo 1: Par de Bell (Máximo entrelazamiento)
Estado: ∣Φ^+⟩=(∣00⟩+∣11⟩)/√2
Paso 1: Sistema total (puro): ρ_AB=∣Φ^+⟩⟨Φ^+∣, S(ρ_AB)=0
Paso 2: Subistema A (traza parcial): ρ_A=〖"Tr" 〗_B (ρ_AB)=I/2, eigenvalues=[0.5,0.5]
S(ρ_A)=-2⋅(0.5〖log⁡〗_2 0.5)=1" bit"
Igual para ρ_B.
Interpretación: Sistema total "sabe todo" (S=0), pero cada mitad está completamente incierta (S=1). El entrelazamiento es la "información compartida cuánticamente".
Ejemplo 2: Dos qubits con magnetización parcial
Estado: √0.8∣00⟩+√0.2∣11⟩
Tabla de entropías:
Estado	S(ρ_AB)	S(ρ_A)	S(ρ_B)	Entrelazamiento
Bell	0	1	1	Máximo (1 bit)
Separado	0.32	0.50	0.50	Bajo (0.18 bit)
Producto	0.32	0.11	0.32	Ninguno (0)
Cálculo detallado: ρ_A=(■(0.8&0@0&0.2))
S(ρ_A)=-[0.8〖log⁡〗_2 0.8+0.2〖log⁡〗_2 0.2]≈0.50" bits"
Entrelazamiento cuantificado: E=S(ρ_A)=0.50 bits (para estados puros).
Aplicaciones Prácticas
	Criptografía cuántica: Protocolo BB84 usa entropía para detectar espionaje (Eve introduce entropía).
	Computación cuántica: Estados con S(ρ_A)≈1 para cada qubit son ideales para qubits lógicos.
	Teletransportación: Requiere entropía máxima en pares EPR precompartidos.
Conexión con Termodinámica
La entropía de von Neumann reduce a Shannon para bases comunes, y para muchos partículas no interactuantes reproduce Boltzmann. El principio de máxima entropía cuántico de Jaynes da distribuciones térmicas desde restricciones de energía (Vedral et al., 1997).
Entropía como función de la dimensionalidad 

Introducción
En teoría de la información y aprendizaje automático, la entropía crece explosivamente con la dimensionalidad D del espacio de datos ("maldición de la dimensionalidad"). En D→∞, el volumen se concentra en la cáscara superficial, haciendo H∝D×2ᴰ. El principio holográfico resuelve esto: toda información D-dimensional se codifica eficientemente en (D-1)-dimensional, como en AdS/CFT donde gravedad 5D=teoría de campos 4D en frontera (Bellman, 1961; Maldacena, 1998).
Fórmula clave: Entropía volumétrica
Datos uniformes en hipercubo ^D:
H_D=D〖log⁡〗_2 L+〖log⁡〗_2 ("volumen efectivo")
Volumen accesible: ~99.999% en superficie R^{D-1} para D>10.
Entropía superficial: S∝D⋅R^(D-1) (¡como agujeros negros!).
Ejemplo 1: Dado en D dimensiones
Dimensión	Estados	Entropía (bits)	% en superficie
1D	6	2.58	100%
3D	216	7.76	85%
10D	60M	25.9	99.999%
100D	6^100	259	~100%
Interpretación: En alta D, puntos "viven" en la cáscara. H explota exponencialmente (Bellman, 1961).
Ejemplo 2: MNIST (784 dims → manifold real)
	Teórica: 784×8=6272 bits
	Efectiva: ~120 bits (datos en manifold ~10D)
	PCA: 154 dims (95% varianza) → H≈154 bits
	Autoencoder: 32 dims → H≈32 bits (holografía computacional)
Relación con Principio Holográfico
Paralelismo perfecto:
Maldición Dimensionalidad	Principio Holográfico
H ∝ D × 2ᴰ (volumen)	S ∝ R² (área)
Datos diluidos en D↑	Info codificada en D-1
Sampling imposible (D>50)	Límite: 1 bit/4lₚ²
ML: PCA, autoencoders	Física: AdS/CFT
Conexión matemática: En espacios de alta D, volumen efectivo → superficie:
〖lim⁡〗_(D→∞)  V_"interior" /V_"total"  →0
H_"efectiva" ≈H_"superficie" ∝(D-1)log⁡R (Maldacena, 1998).
AdS/CFT como "holografía de datos":
	Bulk (5D gravedad): Datos "volumétricos"
	Boundary (4D CFT): Compresión lossless en frontera
	Entropía igual: S_"bulk" =S_"boundary"  ('t Hooft, 1993).
Ejemplo 3: Holografía en ML práctica
python
# Imagen 512×512 = 262k dims → bottleneck 512 dims
entropia_raw = 2M bits      # Pixel-wise
entropia_holo = 512 bits    # Manifold superficie
compresion = 99.97%         # Como S= A/4lₚ²
Implicaciones unificadas
	Universo computacional: ¿Nuestro 3D emerge de 2D informacional?
	Límite físico-ML: Autoencoders = duality holográfica
	Big Data: Nunca proceses D>1000 sin reducción dimensional (Bellman, 1961).
Conclusión: La maldición dimensionalidad + holografía = teorema universal: toda información compleja vive en su "frontera", sea física o datos.





 
Definición y ecuación de la segunda ley de la termodinámica
La segunda ley de la termodinámica se basa en definir la dirección de los procesos naturales en un sistema aislado aumenta espontáneamente. Esto se representa como entropía total o entropía del universo [ΔSuniv]. A su vez esta ley complementa a la primera ley de la termodinámica la cual establece que la energía se conserva, pero no predice la dirección de cambio.
Entropía (S) y Cambio de Entropía (ΔS):
A partir del libro Chemistry (Flowers, Theopold, Langley Richard, & Robinson, 2015, págs. 891-893) podemos tomar entropía(S) como desorden o aleatoriedad de un sistema en un estado especifico. Ahora bien, el cambio de la entropía lo podemos calcular con: 
ΔS = S_final – S_inicial
Otra cosa para tener en cuenta es que ΔS_univ se puede calcular de la forma:
ΔS_univ = ΔS_sis + ΔS_alr
Siendo ΔS_sis el cambio de entropía del sistema y ΔS_alr el cambio de entropía de los alrededores. En caso de necesitar calcular ΔS_alr podemos tomar la formula ΔS_alr = (-ΔH_sis) / T. 
Como un extra podríamos tener en cuenta la energía libre de Gibbs (ΔG = ΔH - T * ΔS_sis) pero para este repositorio no profundizaremos sobre esta misma.
Partiendo es estos cálculos podríamos tomar criterios claves para determinar si el proceso es espontaneo o no espontaneo. Los criterios para esto son:
Si ΔS_univ > 0, el proceso es Espontáneo.
Si ΔS_univ < 0, el proceso es No espontáneo.
Si ΔS_univ = 0, el proceso es Reversible
Ejemplos:
¿Se derretirá el hielo espontáneamente?
La variación de entropía del proceso H₂O(s) ⟶ H₂O(l) es de 22,1 J/K y requiere que el entorno transfiera 6,00 kJ de calor al sistema. ¿Es el proceso espontáneo a −10,00 °C? ¿Es espontáneo a +10,00 °C?
Parámetro	Cálculo	Resultado
ΔS_alr	(-ΔH_sis) / T = -(-6000 J) / 263.15 K	+22.80 J/K
ΔS_univ	ΔS_sis + ΔS_alr = -22.1 J/K + 22.80 J/K	+0.70 J/K

RTA: La congelación es espontánea a -10 °C al ΔS_univ ser positivo
Parámetro	Cálculo	Resultado
ΔS_alr	(-ΔH_sis) / T = -(-6000 J) / 273.16 K	+21.97 J/K
ΔS_univ	ΔS_sis + ΔS_alr = -22.1 J/K + 21.97 J/K	-0.13 J/K

La congelación es no espontánea a 10 °C al ΔS_univ ser negativo
Referencias
Referencias Completas en Formato APA (7ma edición)
Física Estadística (Boltzmann/Microestados)
Reif, F. (1965). Fundamentals of statistical and thermal physics. McGraw-Hill.
Teoría de la Información
Shannon, C. E. (1948). A mathematical theory of communication. The Bell System Technical Journal, 27(3), 379-423. https://doi.org/10.1002/j.1538-7305.1948.tb01338.x
Información Cuántica
Nielsen, M. A., & Chuang, I. L. (2000). Quantum computation and quantum information. Cambridge University Press. https://doi.org/10.1017/CBO9780511976667
Vedral, V., Plenio, M. B., Rippin, M. A., & Knight, P. L. (1997). Rigorous conditions for pure-state convertibility and their application to entanglement. Physical Review Letters, 78(17), 3217-3220. https://doi.org/10.1103/PhysRevLett.78.3217
Principio Holográfico
't Hooft, G. (1993). Dimensional reduction in quantum gravity. arXiv:gr-qc/9310026. https://arxiv.org/abs/gr-qc/9310026
Susskind, L. (1995). The world as a hologram. Journal of Mathematical Physics, 36(11), 6377-6396. https://doi.org/10.1063/1.531249
Maldacena, J. (1998). The large N limit of superconformal field theories and supergravity. Advances in Theoretical and Mathematical Physics, 2, 231-252. https://doi.org/10.4310/ATMP.1998.v2.n2.a1
Dimensionalidad y Machine Learning
Bellman, R. (1961). Adaptive control processes: A guided tour. Princeton University Press.
Jaynes (Puente termodinámica-información)
Jaynes, E. T. (1957). Information theory and statistical mechanics. Physical Review, 106(4), 620-630. https://doi.org/10.1103/PhysRev.106.620
Jaynes, E. T. (1957). Information theory and statistical mechanics II. Physical Review, 108(2), 171-190. https://doi.org/10.1103/PhysRev.108.171
Flowers, P., Theopold, K., Langley Richard, & Robinson, W.R. (2015). Chemistry. Houston: OpenStax.

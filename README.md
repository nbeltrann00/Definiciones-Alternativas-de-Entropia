
# Entropía y Segunda Ley de la Termodinámica  
## Índice

- [1. Entropía como dispersión de la energía](#1-entropía-como-dispersión-de-la-energía)
- [2. Ejemplos prácticos de dispersión](#2-ejemplos-prácticos-de-dispersión)
- [3. Entropía estadística: microestados y fórmula de Boltzmann](#3-entropía-estadística-microestados-y-fórmula-de-boltzmann)
- [4. Entropía y alta dimensionalidad (maldición + holografía)](#4-entropía-y-alta-dimensionalidad-maldición--holografía)
- [5. Segunda Ley de la Termodinámica y criterio de espontaneidad](#5-segunda-ley-de-la-termodinámica-y-criterio-de-espontaneidad)
- [6. Referencias](#referencias)

---
## Definición de la entropía como la dispersión de la energía
Para tener una definiciónmás moderna de la entropía, la definen Atkins y De Paula (2008) como la medida del grado de disipación de la energía en un sistema y alrededores,
En palabras textuales:
“Una interpretaciónmás satisfactoria de la entropía, es como medida de la disipación de la energía. Cuando ocurre un cambio, la energía se disipa más y la entropía aumenta.así lasegunda ley de latermodinámicaes, por lo tanto, la afirmación de que la energía tiene a disiparse y que existe una dirección natural del cambioen la que la energía queda cada vezmás disipada.” (Atkins y De Paula, 2008,pág. 77-78)
También incluyen el criterio universal del cambio espontaneo:
“Hemos encontrado la señal indicadora del cambio espontaneo: buscamos la dirección del cambio que conduce la disipaciónde energía total del sistema aislado”(Atkins & de Paula, 2008, p. 78)
Podemos definir laentropía S como la función de estado quecuantifica el grado en el que la energía de un proceso se ha disipado o distribuido entre todos los microestados accesibles del sistema y sus alrededores.
Un proceso espontáneo ocurre siempre en la dirección en la que la energía total se disipa más, es decir, aquella en la que la variación de la entropía total del universo es mayor que cero:
ΔSₜₒₜ =S sistema +SAlrededores> 0
Resumiendo, así la segunda ley como:
ΔStot > 0
(Atkins & de Paula, 2008, pp. 78–79)

## EJERCICIOS PRACTICOS:
Enunciado Un cubito de hielo a 0 °C se pone en agua a 25 °C.
La energía térmica del agua tibia se reparte hacia el hielo (lo derrite) y queda distribuida entre muchas más moléculas en forma líquida. → La energía total sedisipa más que antes →ΔS_tot > 0 → proceso espontáneo. El proceso inverso (el agua líquida se congela sola sacando calor al ambiente más caliente) nunca ocurre porque disminuiría la disipación total de energía.
Enunciado Un recipiente dividido en dos partes: una con helio y otra con neón (misma T y P). Se quita la pared divisoria.
Las moléculas de cada gas, que antes estaban confinadas en la mitad del volumen, ahora ocupan todo el recipiente. → La energía cinética de traslación se reparte en un volumen mayor número de posiciones posibles → la energía sedisipa más →ΔS_tot > 0 → la mezcla es espontánea. Nunca se ve que los gases se separen solos, porque eso concentraría la energía en menos microestados.

## Entropía como distribución de microestados
En la termodinámica estadística, la entropía cuantifica la multiplicidad de microestados accesibles a un macroestado especificado por variables extensivas como energía, volumen y número de partículas. Esta formulación, propuesta por Ludwig Boltzmann, fundamenta la irreversibilidad termodinámica en el principio de máxima probabilidad, donde los macroestados de alta entropía dominan debido a su superior degeneración microscópica (Reif, 1965).
## Microestados y Microestados
Un microestado es como una "foto instantánea completa" de todo lo que pasa dentro del sistema: la posición exacta (q) y la velocidad (p) de cada una de las N partículas. Imagina el "espacio de fase" como un mapa gigante en 6 dimensiones por partícula (3 para posición + 3 para velocidad), así que para N partículas son 6N dimensiones en total.
El macroestado es una "región grande" en ese mapa (ΔΓ), que agrupa muchos microestados parecidos. Por ejemplo, todos los microestados donde el gas tiene energía E, volumen V y N moléculas.
Entonces, Ω (el número de microestados) se calcula como el tamaño de esa región dividido por h^{3N} N! (h es la constante de Planck para corregir unidades cuánticas, y N! porque las partículas son idénticas y no distinguimos cuál es cuál).
Finalmente, la entropía sale como S =k_Bln Ω. Y cuando N es muy grande (límite termodinámico), esta S se comporta como una propiedad "normal" que suma sijuntas sistemas (Reif, 1965).
La Segunda Ley, al NaturalLa segunda ley dice que la entropía nunca baja (ΔS ≥ 0) en un sistema aislado. ¿Por qué? Porque Ω (número de microestados) solo puede aumentar o quedarse igual. Las trayectorias en el espacio de fase conservan Ω (como billar), pero que el sistema "vaya hacia atrás" a un Ω menor es como que todas las moléculas se junten solas de nuevo: la probabilidad es e^{-N}, ridículamente pequeña cuando Nes grande (tipo Avogadro).
Esto explica paradojas como eldemonio de Maxwell: un ser que "mide" moléculas para separar rápidas de lentas. Parece violar la segunda ley, pero medir genera entropía extra (información = correlación = desorden oculto), así que al final todo suma (Reif, 1965).
## Ejemplos prácticos:
Ejemplo 1: Entropía de 20 monedas (Sistema simple de dos estados)
Situación: Imagina 20 monedas justas justas (cara o cruz). Calcula la entropía delmacroestado con exactamente 10 caras y 10 cruces.
Paso 1: Identifica Ω (número de microestados).Es el número de formas de elegir 10 caras de 20 monedas:
Paso 2: Calcula la entropía.(Aquí es la constante de Boltzmann; numéricamente ~1.38×10^{-23} J/K, pero para sistemas macro se usa en unidades arbitrarias).
Paso 3: Compara con máximo.Máxima Ω total = 2^{20} = 1,048,576 (todos los estados posibles).S_máx =k_Bln(2^{20}) = 20k_Bln 2 ≈ 13.86k_B.Conclusión: Estemacroestado tiene ...(truncated 5066 characters)...nn. El principio de máxima entropía cuántico de Jaynes da distribuciones térmicas desde restricciones de energía (Vedral et al., 1997).
## Entropía como calidad de información 
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

## Ejemplos prácticos: 

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
Letra	Prob	Código	    Longitud
- e	   0.30	      0	           1
- t	   0.20	     100	       3
- a	   0.15	     110	       3
- o	   0.10	     1010	       4
- i	   0.08	     1110	       4
- n	   0.07	     1111	       4
- r	   0.05	     10110	       5
- s	   0.05	     10111	       5
Paso 2: Calcula tasa promedio de bits
-L=0.30⋅1+0.20⋅3+0.15⋅3+0.10⋅4+0.08⋅4+0.07⋅4+0.05⋅5+0.05⋅5=3.05" bits/letra" 
Paso 3: Entropía teórica H
-H=-∑p_i 〖log⁡〗_2 p_i≈2.95" bits/letra"
(Códigos muy cercanos al óptimo)
## Comparación práctica:
	
-Codificación fija (8 bits/letra, ASCII) = 8 bits
-Huffman = 3.05 bits → 62% de compresión
-Ejemplo texto: "the" → t(100)+h(?)+e(0) = ~7 bits vs 24 bits fijos

Conclusión: En textos reales, Huffman ahorra ~60% espacio. ZIP/JPG lo usan combinado con otros métodos (Shannon, 1948).

## Entropía como función de la dimensionalidad

> Introducción
En teoría de la información y aprendizaje automático, laentropía crece explosivamente con la dimensionalidad D del espacio de datos ("maldición de la dimensionalidad"). En D→∞, el volumen se concentra en la cáscara superficial, haciendo H∝D×2ᴰ. Elprincipio holográfico resuelve esto: toda información D-dimensional se codifica eficientemente en (D-1)-dimensional, como enAdS/CFT donde gravedad 5D=teoría de campos 4D en frontera (Bellman, 1961;Maldacena, 1998).
Fórmula clave: Entropía volumétricaDatos uniformes en hipercubo ^D:Volumen accesible: ~99.999% en superficie R^{D-1} para D>10.Entropía superficial: (¡como agujeros negros!).
Ejemplo 1: Dado en D dimensiones
Interpretación: En alta D, puntos "viven" en la cáscara. H explota exponencialmente (Bellman, 1961).
Ejemplo 2: MNIST (784dims →manifold real)
Teórica: 784×8=6272 bits
Efectiva: ~120 bits (datos enmanifold ~10D)
PCA: 154dims (95% varianza) → H≈154 bits
Autoencoder: 32dims → H≈32 bits (holografía computacional)
Relación con Principio HolográficoParalelismo perfecto:
Conexión matemática: En espacios de alta D, volumen efectivo → superficie: (Maldacena, 1998).
AdS/CFT como "holografía de datos":
Bulk (5D gravedad): Datos "volumétricos"
Boundary (4D CFT): Compresiónlossless en frontera
Entropíaigual: ('t Hooft, 1993).
Ejemplo 3: Holografía en ML práctica
# Imagen 512×512 = 262k dims → bottleneck 512dims
entropia_raw = 2M bits# Pixel-wise
entropia_holo = 512 bits# Manifold superficie
compresion = 99.97%# Como S= A/4lₚ²
Implicaciones unificadas
Universo computacional: ¿Nuestro 3D emerge de 2D informacional?
Límite físico-ML:Autoencoders =duality holográfica
Big Data: Nunca proceses D>1000 sin reducción dimensional (Bellman, 1961).
Conclusión: La maldición dimensionalidad + holografía =teorema universal: toda información compleja vive en su "frontera", sea física o datos.

## Definición ecuaciónde segunda ley de latermodinámica
La segunda ley de la termodinámica se basa en definir la dirección de los procesos naturalesen un sistema aislado aumenta espontáneamente. Esto serepresenta comoentropía total oentropía del universo[].A su vez esta ley complementa a la primera ley de la termodinámicala cualestablece que la energía seconserva,pero no predice la dirección de cambio.
## Entropía (S) y Cambio de Entropía (ΔS):
Apartir del libroChemistry(Flowers, Theopold, Langley Richard, & Robinson, 2015, págs.891-893)podemos tomar entropía(S) como desorden o aleatoriedadde un sistema en un estado especifico. Ahorabien, el cambio de la entropía lo podemos calcular con:
ΔS =S_final –S_inicial
Otra cosa para tener en cuenta es queΔS_univ se puede calcular de la forma:
ΔS_univ =ΔS_sis +ΔS_alr
Siendo ΔS_sisel cambio de entropía del sistema y ΔS_alrel cambio de entropía de los alrededores. En caso de necesitar calcular ΔS_alr podemos tomar la formulaΔS_alr = (-ΔH_sis) / T.
Como un extra podríamos tener en cuenta la energía libre de Gibbs (ΔG = ΔH - T *ΔS_sis) pero para este repositorio no profundizaremos sobre esta misma.
Partiendo es estos cálculospodríamos tomar criterios claves para determinar si el proceso es espontaneo o no espontaneo. Los criterios para esto son:
SiΔS_univ > 0, el proceso es Espontáneo.
SiΔS_univ < 0, el proceso es No espontáneo.
SiΔS_univ = 0, el proceso es Reversible
## Ejemplos:
¿Se derretirá el hielo espontáneamente?
La variación de entropía del proceso H₂O(s)⟶ H₂O(l) es de 22,1 J/K y requiere que el entorno transfiera 6,00 kJ de calor al sistema. ¿Es el proceso espontáneo a −10,00 °C? ¿Es espontáneo a +10,00 °C?
RTA: La congelación esespontánea a -10 °C alΔS_univ ser positivo
La congelación esnoespontánea a 10 °C alΔS_univ sernegativo

## Referencias
- Física Estadística (Boltzmann/Microestados) 
Reif, F. (1965). Fundamentals of statistical and thermal physics. McGraw-Hill.
- Shannon, C. E. (1948). A mathematical theory of communication. The Bell System Technical Journal, 27(3), 379-423. https://doi.org/10.1002/j.1538-7305.1948.tb01338.x
- Nielsen, M. A., & Chuang, I. L. (2000). Quantum computation and quantum information. Cambridge University Press. https://doi.org/10.1017/CBO9780511976667
- Vedral, V., Plenio, M. B., Rippin, M. A., & Knight, P. L. (1997). Rigorous conditions for pure-state convertibility and their application to entanglement. Physical Review Letters, 78(17), 3217-3220. https://doi.org/10.1103/PhysRevLett.78.3217
- Principio Holográfico
't Hooft, G. (1993). Dimensional reduction in quantum gravity. arXiv:gr-qc/9310026. https://arxiv.org/abs/gr-qc/9310026
- Susskind, L. (1995). The world as a hologram. Journal of Mathematical Physics, 36(11), 6377-6396. https://doi.org/10.1063/1.531249
- Maldacena, J. (1998). The large N limit of superconformal field theories and supergravity. Advances in Theoretical and Mathematical Physics, 2, 231-252. https://doi.org/10.4310/ATMP.1998.v2.n2.a1
- Bellman, R. (1961). Adaptive control processes: A guided tour. Princeton University Press.
- Jaynes, E. T. (1957). Information theory and statistical mechanics. Physical Review, 106(4), 620-630. https://doi.org/10.1103/PhysRev.106.620
- Jaynes, E. T. (1957). Information theory and statistical mechanics II. Physical Review, 108(2), 171-190. https://doi.org/10.1103/PhysRev.108.171
- Flowers, P., Theopold, K., Langley Richard, & Robinson, W.R. (2015). Chemistry. Houston: OpenStax.
### AUTORES:
> Nhoe Gabrhiel Beltran Nova, 1052840863, nbeltrann@unal.edu.co
> Heilerth Jesus Gonzalez Bracho, 6046140, hgonzalezbr@unal.edu.co
---

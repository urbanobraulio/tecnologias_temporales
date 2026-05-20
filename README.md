# tecnologias_temporales
Catalogo de herramientas digitales gratuitas, de código abierto o de desarrolladorxs independientes, para manipular sonido orientado a la práctica musical. Parte del proyecto de investigación: "Temporalidades discursivas en la música contemporánea argentina del siglo XXI. Una breve cartografía sonora local." que se inscribe en el programa SEAS (Sistemas y Espacialidad en el Arte Sonoro) - Universidad Nacional de Quilmes.

Indice de procesos:
1. Time Stretching
2. Síntesis granular
3. Samplers
4. Filtros resonantes
5. Filtros espectrales
6. Sistemas de reverberación



1. Time Stretching: Time stretching proceso de manipulación digital del audio que permite modificar su duración o velocidad sin alterar su altura. Se utiliza para expandir o comprimir el tiempo sonoro, y puede aplicarse en contextos de procesamiento en tiempo real o diferido. 



Existen diferentes maneras de implementar este proceso en la manipulación digital de audio. Algunos ejemplos: 

PaulXStretch - basado en Paul's Extreme Sound Stretch, disponible en VST y como software standalone ; https://sonosaurus.com/paulxstretch/ 



2. Síntesis Granular:

La síntesis granular es una técnica que construye objetos sonoros complejos mediante la combinación de miles de granos de sonido, definidos como eventos microacústicos breves de entre 1 y 100 ms. Curtis Roads la describe como un sistema que permite manipular el sonido como un medio fluido, integrando dimensiones temporales y espectrales en una sola unidad. Dada la altísima densidad de datos que requiere, el proceso se organiza habitualmente a través de nubes o masas controladas globalmente por algoritmos, permitiendo al compositor crear texturas que van desde pulsaciones rítmicas hasta masas de ruido continuo o timbres vocales


EmissionControl 2 - Software standalone ; https://www.curtisroads.net/software

ys.granular - patchs de pure data / pd vanilla ; https://github.com/yannseznec/ys.granular

nuPG — The New Pulsar Generator, para Supercollider ; https://www.marcinpietruszewski.com/research-nupg


3. Samplers (Samplers): Son dispositivos o programas diseñados para grabar y reproducir fragmentos de sonido real ("muestras" o samples). Actúan como precursores de la síntesis moderna y se utilizan en contextos de síntesis granular para segmentar y reorganizar sonidos grabados, permitiendo variaciones extraordinarias de la fuente original.


4. Filtros Resonantes (Resonance Filters): Son filtros, generalmente de paso de banda, que se utilizan para enfatizar formantes o regiones específicas de energía en el espectro. Históricamente, se han empleado para dar a pulsaciones eléctricas una "resonancia aguda" que genera tonos musicales o para simular la resonancia física de instrumentos, como la caja de una maraca.


5. Filtros Espectrales (Spectral Filters): Procesos que operan directamente en el dominio de la frecuencia, re-escalando las amplitudes de bins (bandas) o pistas espectrales individuales. Pueden controlarse mediante interfaces gráficas que permiten "pintar" o borrar regiones específicas de un sonograma para esculpir el sonido de manera precisa antes de su resíntesis.

6. Sistemas de reverberación: Son herramientas que simulan la respuesta acústica de un espacio mediante la adición de una "halo" de ecos densos y cercanos. Técnicamente se consideran filtros con una respuesta de impulso (IR) larga; se pueden implementar mediante métodos clásicos (como placas de metal) o técnicas avanzadas de convolución, donde el sonido se "cruza" con la firma acústica de una sala real


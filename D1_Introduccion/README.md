# Día 1. Introducción al modelamiento de sistemas biológicos

**Enlace al Jupyter notebook:** https://colab.research.google.com/drive/1KtumhVvZYXp9Z790SFXG1pnjVb1IYnNa?usp=sharing

En esta sesión, veremos los siguientes módulos:
* **Intuición detrás del modelamiento de sistemas biológicos**. El objetivo de este módulo es presentar el flujo de trabajo para modelar un circuito genético: entender el proceso biológico --> plantear las ecuaciones (bio)químicas --> plantear un sistema de ecuaciones diferenciales ordinarias (EDOs). Como caso de estudio, analizaremos el sistema biológico más simple (expresión de proteínas), entendiendo de por medio la ley de acción de masas. Además, nos familiarizaremos con el código para resolver las ODEs mediante ```scipy.integrate.odeint``` y la visualización de resultados utilizando ```bokeh```.
* **Regulación en la expresión de genes: ultrasensitivity y funciones de Hill**. El objetivo de este módulo es presentar el modelamiento de la regulación de expresión génica por medio de factores de transcripción por medio de las funciones de Hill.
* **Sistemas biestables**. En este módulo, aplicaremos los conceptos aprendidos hasta el momento para modelar un sistema con dos genes que se reprimen mutuamente: el *toggle switch*. Además, nos introduciremos al análisis en estado estacionario, que incluye el cálculo de las ecuaciones de *nullclines* y cómo hallar los puntos de equilibrio mediante ```intersect```.
* **Introducción a las simulaciones estocásticas**. Por último, nos introduciremos a las simulaciones estocásticas por medio del algoritmo de Gillespie, y las variables que debemos definir para resolver este tipo de sistemas.

Como material bibliográfico, se recomiendan revisar los siguientes artículos:
* Gardner, T., Cantor, C. & Collins, J. Construction of a genetic toggle switch in Escherichia coli. Nature 403, 339–342 (2000). https://doi.org/10.1038/35002131
* Alon, U. (2007). Network motifs: theory and experimental approaches. Nature Reviews. Genetics, 8(6), 450–461. https://doi.org/10.1038/nrg2102
* Del Vecchio, D., Dy, A. J., & Qian, Y. (2016). Control theory meets synthetic biology. Journal of the Royal Society Interface, 13(120), 20160380. https://doi.org/10.1098/rsif.2016.0380
* Ferrell, J. E., & Ha, S. H. (2014). Ultrasensitivity part I: Michaelian responses and zero-order ultrasensitivity. Trends in Biochemical Sciences, 39(10), 496–503. https://doi.org/10.1016/j.tibs.2014.08.003
* Elowitz, M. B., Levine, A. J., Siggia, E. D., & Swain, P. S. (2002). Stochastic gene expression in a single cell. Science, 297(5584), 1183–1186. https://doi.org/10.1126/science.1070919
* Zheng, Y., & Sriram, G. (2010). Mathematical Modeling: Bridging the Gap between Concept and Realization in Synthetic Biology. Journal of Biomedicine and Biotechnology, 2010, 1–16. https://doi.org/10.1155/2010/541609


# Water Potability DataSet

El presente proyecto consta en determinar un modelo de clasificación para determinar de acuerdo a 9 características presentes en los cuerpos de agua (extensiones de agua que se encuentran por la superficie terrestre o en el subsuelo (acuíferos, ríos subterráneos), tanto en estado líquido como sólido -hielo- (glaciares, campos de hielo, casquete glaciar, inlandsis, casquetes polares), tanto naturales como artificiales (embalses) y tanto de agua salada (océanos, mares), salobre (estuarios, algunos lagos, etc.) como dulce (lagos, ríos, etc.), si el agua es apta para el consumo humano (potable) o si no lo es.

El set de datos a analizar contiene métricas de las características presentes en 3276 cuerpos de agua diferentes

Los campos presentes en el set de datos son los siguientes:

1. pH:

El pH es un parámetro importante para evaluar el balance acído-base en el agua. También indica la condición alcalina o ácida del agua. La OMS ha recomendado que el limite máximo permisible para el pH es de 6.5 a 8.5. Los datos presentados están en el rango de 6.52 a 6.83, por lo cual se encuentran dentro de lo indicado por la OMS.

2. Dureza (Hardness):

La dureza es causada principalemente por sales de calcio y magnecio, las cuales son liberadas en el agua durante el movimiento de esta a traves de despósitos geológicos. Se mide en mg/L.


3. Solidos (Total dissolved solids - TDS):

El agua tiene la propiedad de disolver un amplio rango de material inorgánico y orgánico, como potasio, calcio, sodio, bicarbonatos, cloruros, magnesio, sulfato, etc. Estos minareles producen un gusto indeseado y diluye el color del agua. Este es una característica importante para el uso del agua. El agua con altos niveles de TDS indica que el agua posee una gran cantidad de minerales. Los límites deseables para el TDS es de 500 mg/L y un límite máximo de 1000 mg/L para consumo humano.

4. Cloraminas:

El cloro y la cloramina son los mayores desinfectantes usados en los sistemas públicos de aguas. Las cloraminas son comumnetoe formadas cuando amoniaco es añadido al cloro, para tratar el agua potable. Los niveles de cloro de hasta 4 miligramos por litro (mg/L o 4 partes por millón (ppm)) se consideran seguros en el agua potable.

5. Sulfato:

Los sulfatos son sustancias naturales que se encuentran en los minerales, el suelo y las rocas. Están presentes en el aire, las aguas subterráneas, las plantas y los alimentos. El principal uso comercial del sulfato es en la industria química. La concentración de sulfato en el agua de mar es de aproximadamente 2700 miligramos por litro (mg/L). Varía de 3 a 30 mg/L en la mayoría de los suministros de agua dulce, aunque se encuentran concentraciones mucho más altas (1000 mg/L) en algunas ubicaciones geográficas.

El nivel máximo de sulfato sugerido por la OMS es de 500 mg/l. Las normas de la UE son más completas y estrictas que la OMS, lo que sugiere un máximo de 250 mg/l de sulfato en el agua destinada al consumo humano.

6. Conductividad:

El agua pura no es un buen conductor de la corriente eléctrica sino un buen aislante. El aumento de la concentración de iones mejora la conductividad eléctrica del agua. Generalmente, la cantidad de sólidos disueltos en el agua determina la conductividad eléctrica. La conductividad eléctrica (CE) en realidad mide el proceso iónico de una solución que le permite transmitir corriente. De acuerdo con los estándares de la OMS, el valor de CE no debe exceder los 400 μS/cm.

7. Carbono Orgánico:

El carbono orgánico total (TOC) en las fuentes de agua proviene de la materia orgánica natural en descomposición (NOM), así como de fuentes sintéticas. TOC es una medida de la cantidad total de carbono en compuestos orgánicos en agua pura. Según US EPA < 2 mg/L como TOC en agua tratada/bebible, y < 4 mg/Lt en agua de fuente que se usa para tratamiento.

8. Trihalometanos:

Los THM son sustancias químicas que se pueden encontrar en el agua tratada con cloro. La concentración de THM en el agua potable varía según el nivel de materia orgánica en el agua, la cantidad de cloro requerida para tratar el agua y la temperatura del agua que se está tratando. Los niveles de THM de hasta 80 ppm se consideran seguros en el agua potable.

9. Turbidez:

La turbidez del agua depende de la cantidad de materia sólida presente en estado de suspensión. Es una medida de las propiedades emisoras de luz del agua y la prueba se utiliza para indicar la calidad de la descarga de desechos con respecto a la materia coloidal. El valor medio de turbidez obtenido para Wondo Genet Campus (0,98 NTU) es inferior al valor recomendado por la OMS de 5,00 NTU.

10. Potabilidad:

Indica si el agua es segura para el consumo humano, donde 1 significa que es potable y 0 significa que no es potable.
---
layout: page
title: Monadología en TEI
---

# La Monadología marcada en TEI

## Por Patricio Garrido

En esta ocasión, decidí trabajar con la *Monadología* de Leibniz, porque en una parte del curso estudiamos lo que era un fragmento y con la ayuda del profesor
**Ernesto Priani**, descubrimos que la definición de una `mónada` era muy similar a la definición del `fragmento`. 

Decidí marcar ciertos fragmentos de la *Monadología* que a mi parecer, podían usarse para hacer la analogía con la idea de `fragmento` que trabajamos. 
Uno de mis objetivos con esta propuesta, es didáctico, pues busco que al hacer la relación entre *fragmentos y mónadas*, se puede entender mejor lo que es una 
**mónada**. Es por esto que una de mis prioridades en la selección de marcas fue la mejor comprensión del texto, ofreciendo claves de lectura.

Y ahora sí, sin hacerla más de emoción, los fragmentos de la *Monadología*:

  `<teiHeader>`
      `<fileDesc>`
         `<titleStmt>`
            `<title>`Fragmentos de la Monadología de Leibniz: Una edición digital`</title>`
         `</titleStmt>`
         `<publicationStmt>`
            `<publisher>`Patricio Garrido`</publisher>`
						`<pubPlace>`México`</pubPlace>`
						`<date when="2021">`2021`</date>`
				 `</publicationStmt>`
         `<sourceDesc>`
            `<bibl>`LEIBNIZ, Gottfried Wilhem, Monadología. Trad., pról. y notas de Manuel Fuentes Benot.
							Editor digital: Titivillus. epub libre.`</bibl>`
						`<p>`Título original: La Monadologie. Gottfried Wilhem Leibniz. 1714`</p>`
         `</sourceDesc>`
      `</fileDesc>`
  `</teiHeader>`
  `<text>`
      `<body>`
         `<div type="primera parte" xml:id="primera_parte" org="(§§ 1-30)">`

					 `<head type="primera parte">`Teoría de la `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">``<hi rend="italic">`sustancia`</hi>` simple`</interp>``</term>` (§§ 1-30)`</head>`

					 `<head type="subtítulo">`La `<term type="concepto filosófico" xml:id="mencion_monada">``<hi rend="italic">` mónada`</hi>``</term>` en general (§§ 1-7)`</head>`

					 `<head type="Número de fragmento">`§ 1`</head>`
					 `<p type="fragmento" xml:id="fragmento_1">``<q>`La `<term type="concepto filosófico" xml:id="mencion_monada_2">``<hi rend="italic">`mónada`</hi>``</term>` de que hablaremos aquí, no es otra cosa que una `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">` substancia simple`</interp>``</term>`, que forma parte de los
					 `<term type="concepto físico" xml:id="comp">`compuestos `</term>`; `<term type="concepto físico" xml:id="simpl">``<distinct type="concepto técnico">`simple`</term>``</distinct>`, es decir, sin partes.
					 (`<ref>``<name type="libro">``<hi rend="italic">`Teodicea`</hi>``</name>`, § 10)`</ref>``</q>``<note type="nota al margen">`La Mónada se parece mucho a la definición de fragmento que trabajamos en clase. El fragmento también es una sustancia simple, que forma parte de un compuesto: el texto. Nótese también la importancia de la relación forma y fondo que tiene el texto, pues Leibniz nos está hablando de una sustancia simple, que forma parte de los compuestos; y eso es justamente lo que hace en este texto. Pues al presentarlo como fragmentos, está haciendo un compuesto (La Monadología) a partir de sus partes (las mónadas), que son los fragmentos`</note>``</p>`

					 `<head type="Número de fragmento">`§ 3`</head>`
					 `<p type="fragmento" xml:id="fragmento_2">`Allí donde no hay partes no hay, por consecuencia, ni `<term type="concepto físico" xml:id="ext">`extensión`</term>`, ni `<term type="concepto físico" xml:id="fig">`figura`</term>`, ni divisibilidad posibles. Y a estas `<term type="concepto filosófico" xml:id="mencion_monada_3">`mónadas`</term>` son los verdaderos
					 `<term type="concepto físico" xml:id="atom">``<hi rend="italic">`átomos`</hi>``</term>` de la naturaleza y, en una palabra, los `<term type="concepto físico" xml:id="atom">``<hi rend="italic">`elementos`</hi>``</term>` de las cosas.`</p>`

					 `<head type="Número de fragmento">`§ 6`</head>`
     			 `<p type="fragmento" xml:id="fragmento_3">`Por tanto, se puede decir que las `<term type="concepto filosófico" xml:id="mencion_monada_4">`mónadas`</term>` no podrían comenzar ni terminar de una vez, es decir, no podrían comenzar más que por `<interp type="cualidad de la mónada">`creación`</interp>`, y terminar más que por `<interp type="cualidad de la mónada">`aniquilación`</interp>`; por el contrario, aquello que está `<term type="concepto físico" xml:id="comp">`compuesto`</term>` comienza y termina por partes.`</p>`

					 `<head type="Número de fragmento">`§ 7`</head>`
					 `<p type="fragmento" xml:id="fragmento_4">`No hay medio tampoco de explicar cómo una `<term type="concepto filosófico" xml:id="mencion_monada_5">`mónada`</term>` pudiera ser alterada, o cambiada en su interior por alguna otra `<term type="concepto filosófico">``<interp type="alusión a una sustancia metafísica">`criatura`</interp>``</term>`; pues no se le puede transponer nada, ni concebir en ella ningún movimiento interno que pueda ser excitado, dirigido, aumentado o disminuido dentro de ella, como ocurre en los `<term type="concepto físico" xml:id="comp">`compuestos`</term>`, donde hay cambio entre las partes. Las
					 `<term type="concepto filosófico" xml:id="mencion_monada_6">``<emph>``<hi rend="italic">`mónadas`</term>` no tienen ventanas`</emph>``</hi>` por las cuales alguna cosa pueda entrar o salir en ellas. Los `<interp type="cualidad metafísica de las mónadas">`accidentes`</interp>` no pueden separarse, ni salir fuera de las `<term type="concepto filosófico" xml:id="subs">`substancias`</term>`, como hacían en otros tiempos las `<term type="concepto filosófico">`especies sensibles`</term>` de los `<name type="corriente filosófica">`escolásticos`</name>`.
					 Por tanto, ni una `<term type="concepto filosófico" xml:id="subs">`substancia`</term>`, ni un `<interp type="cualidad metafísica de las mónadas">`accidente`</interp>` puede entrar desde fuera en una `<term type="concepto filosófico" xml:id="mencion_monada_6">`mónada`</term>`.`</p>`

					 `<head type="subtítulo">`El `<emph>``<hi rend="italic">`principio de los indiscernibles`</hi>``</emph>` y las cualidades de las `<term type="concepto filosófico" xml:id="mencion_monada_7">`mónadas`</term>`: `<emph>``<hi rend="italic">`percepción, apercepción y apetición`</hi>``</emph>`. (§§ 8-17)`</head>`

					 `<head type="Número de fragmento">`§ 8`</head>`
					 `<p type="fragmento" xml:id="fragmento_5">`Es necesario, sin embargo, que las `<term type="concepto filosófico" xml:id="mencion_monada_8">`mónadas`</term>` posean algunas cualidades; en otro caso no serían ni siquiera `<term type="concepto filosófico">`seres`</term>`. Y si las `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">`substancias simples`</interp>``</term>` no difirieran por sus cualidades, no habría medio de darse cuenta de ningún cambio en las cosas; puesto que
					 lo que hay en lo `<term type="concepto físico" xml:id="comp">`compuesto`</term>` no puede venir sino de los ingredientes `<term type="concepto físico" xml:id="simpl">``<distinct type="concepto técnico">`simples`</distinct>``</term>`; y las `<term type="concepto filosófico" xml:id="mencion_monada_9">`mónadas`</term>`, no teniendo cualidades, serían indistinguibles las unas de las otras, puesto que tampoco difieren en cantidad. Y por consecuencia, supuesto lo `<interp type="postura metafísica del autor">`lleno`</interp>` cada lugar no recibiría nunca en el movimiento más que el equivalente de lo que había tenido, y un estado de cosas sería indistinguible de otro.`</p>`

					 `<head type="Número de fragmento">`§ 9`</head>`
					 `<p type="fragmento" xml:id="fragmento_6">`Es necesario también que cada una de las `<term type="concepto filosófico" xml:id="mencion_monada_9">`mónadas`</term>` sea diferente de toda otra. Porque no hay en la naturaleza dos seres que sean perfectamente el uno como el otro, y donde no sea posible encontrar una diferencia interna, o fundamentada en una denominación intrínseca.`</p>`

					 `<head type="Número de fragmento">`§ 11`</head>`
					 `<p type="fragmento" xml:id="fragmento_7">``<q>`Se sigue de lo que acabamos de decir que los cambios naturales de las `<term type="concepto filosófico" xml:id="mencion_monada_9">`mónadas`</term>` vienen de un `<interp type="cualidad metafísica de las mónadas">`principio interno`</interp>`, puesto que una causa externa no puede influir en su interior.
					 (`<ref>``<name type="libro">``<hi rend="italic">`Teodicea`</hi>``</name>`, §§ 396, 400)`</ref>``</q>``</p>`

					 `<head type="subtítulo">`Tres especies de `<term type="concepto filosófico" xml:id="mencion_monada_10">`mónadas`</term>`: `<emph>``<hi rend="italic">`entelequias, almas y espíritus.`</hi>``</emph>` (§§ 18-30)`</head>`

					 `<head type="Número de fragmento">`§ 18`</head>`
					 `<p type="fragmento" xml:id="fragmento_8">``<q>`Se podría dar el nombre de `<term type="concepto filosófico" xml:id="entel" xml:lang="Griego">``<emph>``<hi rend="italic">`entelequias`</hi>``</emph>``</term>` a todas las
					 `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">`substancias simples`</interp>``</term>`, o `<distinct type="tipo específico de mónadas">``<term type="concepto filosófico" xml:id="mencion_monada_10">`mónadas`</term>` creadas`</distinct>`, porque tienen en sí mismas una cierta perfección (`<foreign xml:lang="Griego">`ἔχουσι τὸ ἐντελὲς`</foreign>`), hay en ellas una
					 `<term type="concepto filosófico" xml:id="sufic">`suficiencia (`<foreign xml:lang="Griego">`αὐταρκεια`</foreign>`) que las convierte en fuentes de sus acciones internas y, por decirlo así, en `<distinct type="analogía">``<emph>``<hi rend="italic">`autómatas incorpóreos`</hi>``</emph>``</distinct>`.
					 (`<ref>``<name type="libro">``<hi rend="italic">`Teodicea`</hi>``</name>`, § 87)`</ref>``</q>``</p>`

					 `<head type="Número de fragmento">`§ 22`</head>`
			  	 `<p type="fragmento" xml:id="fragmento_9">``<q>`Y como todo estado presente de una `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">`substancia simple`</interp>``</term>` es naturalmente una consecuencia de su estado precedente, de este modo su `<distinct type="metáfora">`presente está preñado del porvenir`</distinct>`.
					 (`<ref>``<name type="libro">``<hi rend="italic">`Teodicea`</hi>``</name>`, § 360)`</ref>``</q>``</p>`

				 `</div>`

				 `<div type="tercera parte" xml:id="tercera_parte" org="(§§ 47-90)">`

					 `<head type="tercera parte">``<name type="deidad">`Dios`</name>` y la `<distinct type="concepto técnico">``<emph>``<hi rend="italic">`armonía preestablecida.`</hi>``</emph>``</distinct>` (§§ 47-90)`</head>`

					 `<head type="subtítulo">`La creación del universo de acuerdo al `<distinct type="concepto técnico">``<emph>``<hi rend="italic">`principio de conveniencia.`</hi>``</emph>``</distinct>` (§§ 47-55)`</head>`

					 `<head type="Número de fragmento">`§ 51`</head>`
					 `<p type="fragmento" xml:id="fragmento_10">`Pero en las `<term type="concepto filosófico" xml:id="subs_simpl">``<interp type="intercambiable por mónada">`substancias simples`</interp>``</term>` no hay sino una influencia ideal de una `<term type="concepto filosófico" xml:id="mencion_monada_11">`mónada`</term>` sobre otra, la cual no puede tener su efecto más que por la intervención de `<name type="deidad">`Dios`</name>`, en tanto que en las ideas de `<name type="deidad">`Dios`</name>` una
					 `<term type="concepto filosófico" xml:id="mencion_monada_12">`mónada`</term>` pide con razón, que `<name type="deidad">`Dios`</name>`, al regular las otras desde el comienzo de las cosas, la tenga en cuenta. Porque, como una `<distinct type="tipo específico de mónadas">``<term type="concepto filosófico" xml:id="mencion_monada_13">`mónada`</term>` creada`</distinct>` no puede tener una influencia física sobre el interior de otra, sólo por este medio una puede ser dependiente de otra.`</p>`

				 `</div>`
      `</body>`
  `</text>`
`</TEI>`

Crea un archivo de texto llamado textos.txt:
<h1>Texto grande</h1>
<h3>Texto pequeño</h3>
Ábrelo con un navegador. Cámbialo de nombre por textos.html. Vuélvelo a abrir con el navegador.
¿Qué conclusiones sacas de tu observación?
Que el lenguaje html está diseñado para poder utiizarse en archivos de texto plano sin problemas.

2. Observa el siguiente fragmento de un texto:
<dam>
 <modulo><titulo>Lenguaje de Marcas</titulo>
 <contenido>
<unidad>Introducción</unidad>
<unidad>HTML</unidad>
<unidad>CSS</unidad>
…
 </contenido>
 </modulo>
…
</dam>
Lo que vemos es una manera de estructurar la información sobre los módulos de DAM. Podemos
distinguir:
Vocabulario: dam, modulo, titulo, contenido, unidad
Reglas: dam contiene varios modulos, un modulo tiene un titulo y un contenido, contenido tiene
varias unidades, todas las unidades están en un contenido, las unidades son texto simple, detrás de
una unidad solo puede ir otra unidad o fin contenido, detrás de uno modulo solo puede ir otro
modulo o fin de dam
Completa con al menos tres de los módulos de DAM en este archivo. Llámale DAM.sgml
<dam>
 <modulo><titulo>Lenguaje de Marcas</titulo>
 <contenido>
<unidad>Introducción</unidad>
<unidad>HTML</unidad>
<unidad>CSS</unidad>
 </contenido>
 </modulo>
  <modulo><titulo>Fundamentos del hadrware</titulo>
 <contenido>
<unidad>Historia de los sistemas informáticos</unidad>
<unidad>Componentes básicos de los sistemas</unidad>
<unidad>Sistemas embedidos</unidad>
 </contenido>
 </modulo>
 <modulo><titulo>Implementación de sistemas en red</titulo>
 <contenido>
<unidad>Bases de los sistemas operativos</unidad>
<unidad>Sistemas operativos en monopuestos</unidad>
<unidad>Sistemas operativos en red</unidad>
</contenido>
 </modulo>
  <modulo><titulo>IPE</titulo>
 <contenido>
<unidad>Derechos laborales</unidad>
<unidad>Prevención de riesgos laborales</unidad>
<unidad>Convenios laborales</unidad>
</contenido>
 </modulo>
</dam>

3. Crea tu propio documento SGML indicando vocabulario y reglas. Implementa los
datos para PAISES DEL MUNDO
vocabulario:mundo,  continente, nombre, paises
Mundo contiene barios continentes, cada uno con su propio nombre, luego se habre la sección de paises que contiene cada continente y se listan los nombres de los paises
<mundo>
 <continente><titulo>Lenguaje de Marcas</titulo>
 <contenido>
<unidad>Introducción</unidad>
<unidad>HTML</unidad>
<unidad>CSS</unidad>
 </contenido>
 </mundo>
…

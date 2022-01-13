
## Ej1. Práctica de selectores CSS  (**2 pts**)

Crea un documento ****HTML**** cunha páxina web en ****HTML5**** que reproduza en contido e aspecto o que se mostra na seguinte imaxe, empregando unha folla de estilos ****CSS externa****. 

![Captura_do_horario](../imgs/img_task_selectors.png)

O texto está dispoñible sen formato no [ficheiro adxunto](../recursos/Texto_tarefa_selectors.txt)

Emprega a seguinte regra de estilos para a táboa:
`table, tr, th, td {border:1px solid #000; border-collapse:collapse; padding:5px;}`

Escolle as cores do xeito máis semellante entre os seguintes: 

![paleta_cores](../imgs/paleta_cores.png)

Entrega o ficheiro HTML e mais o ficheiro CSS

## Ej2. MAQUETAR UN CURRICULUM  (**3 pts**)

Cree un documento HTML chamado **curriculum.html** cunha folla de estilo asociada almacenada nun ficheiro externo chamado **curriculum.css**.
O navegador debería mostrar un resultado igual ao que se mostra na captura de pantalla contida na imaxe
![curriculum_con_css](../imgs/curriculum_con_css.png)
Estas son as reglas de estilo que tes que aplicar:
1. A tipografía será da familia xenérica sans serif.
2. A cor de fondo da páxina será #EEEEEE
3. O resto das cores a utilizar son as seguintes:
   * Título principal: #333333 (cor de texto)
   * Títulos de seccións: #7FFF00 (cor de texto) e #888888 (cor de fondo)
   * Cor de fondo de contenido de seccióons: #CCCCCC
   * Cor de texto de tipos de datos personais (nome, DNI, dirección) e idiomas (inglés, francés): #20B2AA
   * Cor de texto de datas de formación académica: #A52A2A
   * Cor de fondo do elemento que contén o texto co nome do autor e a data da última modificación: branco

NOTA 1: Como axuda para estruturar o documento mediante HTML, adxuntase unha captura de pantalla da mesma páxina sen aplicar ningún estilo (só os aplicados por defecto polo navegador). Esta captura está contida na imaxe ![curriculum_sin_css](../imgs/curriculum_sin_css.png)
NOTA 2: Achégase no arquivo [curriculum_sin_marcar](../recursos/curriculum_sin_marcar.html) o texto da páxina (sen marcar).

A entrega desta tarefa farase mediante **2 ficheiros, un HTML e outro CSS**.


## Ej3. APLICAR ESTILOS A FORMULARIO HTML5 (**4 pts**)

A partir do código HTML proporcionado no adxunto [formulario de alta](../recursos/form_alta.html)

1) Aplicar as reglas CSS necesarias para que o formulario HTML5 teña o seguinte aspecto:

![img_form_alta](../imgs/img_form_alta.png)

tendo en conta que:
- Os campos do formulario agruparanse por apartados: Nome e Apelidos, Enderezo, Correo electrónico, Teléfono
- Crea unha nova sección chamada Outros Datos cos campos:
  - Data de Nacemento co formato dd/mm/aaaa visible
  - Idade: se fixará facendo uso dun campo tipo rango de 0 a 100 
  - Campo de texto libre para comentarios de 4 filas de alto e 30 columnas de ancho

2) Cando o usuario pase o rato sobre cada grupo de elementos do formulario (é dicir, sobre cada `<li>`) debe modificarse a súa cor de fondo (suxestión: amarelo claro # FF9).
3) Cando o usuario está situado nunha caixa de texto, debe modificarse o seu bordo para resaltar o campo que está activo en cada momento (suxestión: cor amarela # E6B700) tal e como se ve na seguinte imaxe:

![Exemplo](../imgs/exemplo_aptdo3.png)

## Ej4. UNIDADES DE MEDIDA (**1 pts**)

A folla de estilo styles.css da carpeta [ej4](../recursos/ej4) establece unha marxe de 1 em para os parágrafos do documento html anexo.

1. Añade a declaración "font-size: 16px" á regla de estilo dos elementos p. Que sucede? Cal é es a anchura do marxen?

2. Modifica o atributo font-size a 32px. Cal é agora a anchura do marxen?

3. Modifica a regla para reducir a anchura do marxen a 16px pero mantendo o tamaño de letra dos párrafos en 32px. Que sucede?
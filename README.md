# mat-unab
Paquetes LaTeX del Dpto Matemáticas UNAB

1) Se requiere instalar la clase exam, disponible en https://www.ctan.org/tex-archive/macros/latex/contrib/exam

2) Opciones

<código de curso> =  debe ser ingresado en minúsculas, por ejemplo fms171. No hay opción predefinida.

<código de campus> = debe ser ingresado para definir el campus. La opción predefinida es República, por lo que no es necesario ingresar un código para este campus. Posibilidades son: repu,caso,avar,conc,vina,leon,bell

borrador = es una opción que puede ser usada para agregar marca de agua a la izquierda de cada pagina, para evitar que se envíe una version preliminar a impresión. Basta deshabilitarla para tener la version final. No es anulada por la opción "final".

pauta = opcion para agregar "Pauta" al título y activar \printanswers de clase exam.cls

3) Algunos paquetes no muy comunes que están cargados son:

	- draftwatermark https://www.ctan.org/pkg/draftwatermark
	- booktabs https://www.ctan.org/pkg/booktabs
	- bigstrut https://www.ctan.org/pkg/bigstrut
	- fixltx2e https://www.ctan.org/pkg/fixltx2e
	- pstricks https://www.ctan.org/pkg/pstricks (Se debe compilar con latex > dvips >ps2pdf si usa este paquete)
	- pst-func https://www.ctan.org/pkg/pst-func (Se debe compilar con latex > dvips >ps2pdf si usa este paquete)
	- pstricks-add https://www.ctan.org/pkg/pstricks-add (Se debe compilar con latex > dvips >ps2pdf si usa este paquete)
	- ps-plot https://www.ctan.org/pkg/pst-plot (Se debe compilar con latex > dvips >ps2pdf si usa este paquete)
	- longtable https://www.ctan.org/pkg/longtable
	- ragged2e https://www.ctan.org/pkg/ragged2e
	
4) Cambios recientes

 - Es posible compilar con pdflatex además de latex.


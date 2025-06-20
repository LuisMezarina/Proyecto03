# Proyecto03

## Justificacion:

Las historias de usuarfio implementadasd fueron la posibilidad de exportar la vista previa en pdf y el modo claro oscuro.
Ambas fueron implementadas con la intención de facilitar el uso al usuario final ya que algunas personas prefieren el modo oscuro cuando trabajan prolongadamente en computadoras, en el caso de exportar a pdf se implemento en caso el usuario final requiera una copia impresa del dpcumento generado. 

## Desiciones tecnicas: 

En el caso de modo oscuro se aplicó modificando el codigo Tailwind al agregar o quitar clases de acuerdo al valor booleano aplicado dark, este valor booleano cambia de true a false al aplicar el boton. 

En el caso de exportar el pdf se logro utiliznado la bilioteca "html2pdf.js", la cual junto a la funcion renderiza la vista previa y exporta el pedf. 
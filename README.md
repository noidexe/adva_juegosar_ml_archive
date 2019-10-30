# Backup de listas de correo JuegosAR y ADVA

Este repo contiene un backup de las listas de correo ADVA y JuegosAR vinculadas a la historia del desarrollo de videojuegos en la Republica Argentina. Lo pongo a disposición para cualquiera que le interese junto con las herramientas utilizadas.

## Contenido de las carpetas

### adva, JuegosAR

Mensajes individuales en formato .json

### adva_binaries, JuegosAR_binaries

Fotos, Archivos y Adjuntos (descargados a mano ya que no lo cubría el script).

### adva_archive, JuegosAR_archive

Un archivo compilatorio por año en formato legible. HTML y TXT

## Nota
Los scripts de conversion a txt y html no contemplaban que el json fuera de error 500 y no tuviera las keys yDdata para obtener el timestamp del mensaje y demas. Como fix simple en ese caso hice que devuelva 0.0 por lo que si genera un .html o .txt correspondiente a 1969 vacio pueden eliminarlo.

## Creditos
Scripts forkeados de https://github.com/andrewferguson/YahooGroups-Archiver
Gracias a Federico "Master of the Scrapeo" por conseguirme los scripts. (@fcingolani)
Gracias a Francisco "Panchi" Demartino (@franciscod) por la ayuda con algunos errores de python. No tiene soundcloud pero hace un tracker con el primo que esta muy piola: http://deflemask.com/

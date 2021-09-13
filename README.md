Probé la original que era kayceesrk/cs3100_iitm
Muy buena, pero había que colocar manualmente el comando para inicialr jupyter.
Además solo funcionaba con token...paja.

Después de darme un montón de vueltas tratando de armar una imagen casi desde 0 tomando como BASE la imagen ocaml/opam
logré arrancar todo bien, pero al cargar un notebook con prolog se caía por incompatibilidad de versiones de la librería.

Al final (lo más simple) lo más efectivo fue tomar como BASE kayceesrk/cs3100_iitm e incorporar los cambios que necesitaba.
Esto quedó en el Dockerfile Dockerfile_custom_mini

Jz. Sept. 2021

# PyE1
Repositorio para el proyecto final de probabilidad y estadística 1 del año 2021-1


para poder visualizar la base de datos del DANE debe de seguir estos pasos
1. inicialmente debe de ir al apartado File > Import Dataset > From SAS...
2. copiar la dirección del archivo en su computador 
3. importar
4. le saldrá el siguiente código en la parte inferior
  library(haven)
  juanfer <- read_sas("URL del archivo/juanfer.sas7bdat", 
      NULL)
  View(juanfer)
5. ejecute el código del código en R

# Métodos para arrancar un Sistema Operativo

Hay 3 métodos los cuales puedes emplear para arrancar un SO, estos son: 
Arranque por PEN, por DD y por red (PXE). En nuestro ciclo de grado 
medio, empleamos el arranque por red para instalar el Fedora 27.
 
Si nuestro SO es reciente, activaremos la opción AHCI, ya que, si 
tenemos un DD SATA, haremos que se comporte como tal e irá más rápido. 
Pero en este parámetro de compatibilidad, hay la opción IDE también, 
que hace que tu disco SATA se comporte como los DD IDE con las antiguas 
reglas llamadas "_Legacy_" (Reglas de Windows). Debo remarcar que 
_Leacy_/UEFI son opciones del Boot Menu que podemos activar o 
desactivar, o activar ambas a voluntad. En caso de activar las dos, 
permitimos a nuestro DD reconocer caulquier Sistema Operativo. Y si 
queremos instalar un SO por red (PXE) debemos activar la opción LAN 
Boot desde la BIOS para realizar la instalación.

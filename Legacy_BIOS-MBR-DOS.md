# Antiguo Sistema de partición del Disco Duro (DD)

La BIOS MBR DOS, tiene ciertas limitaciones para particionar el Disco Duro, sobretodo en Windows. En el Sistema Operativo Windows, hay una serie de normas, conocidas como Legacy, que son las siguientes:

- Máximo 4 particiones primarias
- 1 primaria puede se _Extend_ (Extendida)
- Dentro de la extendida, puede haber _n_ lógicas. (Dónde _n_ és un número entero y finito)
- 1 primaria debe ser _Active_ (Activa)

Linux nunca ha tenido reglas de partición del Disco Duro.

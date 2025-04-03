# Siwa Dual Core Notes

Hola este es una página web de notas para el Siwa Dual Core. La idea es que utilice este espacio para compartir información que tuve que buscar y entender. No se compartirá código del SIWA, sino simplemente información útil para comprender mejor el código del SIWA.

## Cargar 2 programas a Memoria RAM

Lo primero que hay que hacer cambios en la máquinas de estados del SPI que es quien carga los programas desde la memoria externa a la memoria RAM. Entonces primero esencial entender los [protocolos](./protocols.md) de comunicación del SIWA.

## Modificar MCB

El Memory Controller Bus se tiene que modificar ya que se tiene que duplicar el módulo del core de SIWA.

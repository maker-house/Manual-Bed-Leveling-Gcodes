# BedLevelingGcodes
Rutina en Gcode para nivelar la cama en 5 puntos (centro y 4 esquinas), con el clásico método del papel, compatible con impresoras 3D y máquinas que acepten el estandar gcode de impresoras 3D / reprap. 
Este método te dará buen resultado a medida que la superficie de impresión esté limpia


# Uso

## Materiales
- Impresora 3D
- Tarjeta SD
- Hoja de papel

1. Descargar el repositorio o el archivo correspondiente a tu máquina segun las dimensiones de tu cama. 

- Superficies de 230 x 230 mm (Ender 3 - 5, CR10) : bedlevel2323.gcode
- Superficies de 220 x 220 mm (Anet A8) : bedlevel2222.gcode
- Superficies de 230 x 150 mm (Flashforge, Makerbot) : bedlevel2315.gcode

2. Copiar el archivo en la tarjeta SD de la impresora
3. Colocar el papel en la superficie de impresión 
4. Cerciorarse que el endstop del eje Z está funcionando correctamente y a una altura adecuada.  
5. Precalentar la impresora (recomendado)
6. Seleccionar el archivo tal como si fuera un archivo para imprimir. 
7. La maquina primero realizará un homing, para luego levantar el Z a 10mm
8. Luego la maquina se posicionará en el siguiente punto de nivelacion y bajara hasta Z0, 
9. Ajustar el perno de la cama correspondiente a la posición actual de la boquilla, tal que el papel quede semi atrapado entre la boquilla y la superficie (que se pueda mover pero con cierto roce). 
10. Una vez listo presionar el boton para continuar al siguiente punto
11. Repetir 8-10 para los 5 puntos de nivelación
12. Si es necesario repetir todo el proceso desde 6 para confirmar la correcta nivelacion

13. Se recomienda imprimir un archivo para comprobar que la nivelación quedó bien ajustada: https://www.thingiverse.com/thing:4362091


# Licencia
Este código está protegido bajo una licencia GPLv3. Eres libre de usarlo y modificarlo dando el crédito a sus creadores y respetando los terminos de la licencia. 


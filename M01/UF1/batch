@echo off
::Script Que Dice Hola Mundo
cls
echo Hola Mundo
pause
exit

@echo off
cls
SET /P miNombre=Introduce tu Nombre:
echo Hola %miNombre%
pause
exit

@echo off
:: Script de copia de ficheros
echo Bienvenido al programa de copia de ficheros
pause
IF EXIST "archivo1.txt" (
  copy /-Y archivo1.txt .\carpeta1\
) ELSE (
  ECHO copy archivo1.txt .\carpeta1\
)
IF '%ERRORLEVEL%'=='0' echo Todo ha ido bien
IF '%ERRORLEVEL%'=='1' echo Algo ha fallado
pause
exit

@echo off
:: Script de copia de ficheros
echo Bienvenido al programa de copia de ficheros
pause
IF EXIST "archivo2.txt" (
  move /-Y archivo2.txt .\carpeta1\
) ELSE (
  ECHO move archivo2.txt .\carpeta1\
)




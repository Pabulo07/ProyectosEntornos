# Practica 4 - GIT 
### Deshacer cambios

1. Entra en el directorio de la práctica2 (practica2git) y a partir de ahí realizaremos esta práctica. Debes tener en cuenta que la práctica 3 debe estar realizada para hacer esta.

2. Elimina la linea - Mac del fichero contenido.txt
3. Comprueba el estado del repositorio
![](4_3.png)
4. Deshaz los cambios realizados en el fichero contenido.txt y vuelve a la versión anterkior del fichero.
  
   ```
   Para deshacer los cambios se usa la opción chechout:
   $git checkout -- contenido.txt
   (se le pasa como argumento el fichero ... por ahora ...)
   ```

![](4_4.png)

5. Comprobar el estado del repositorio y el contenido del fichero modificado.
![](4_5.png)
6. Eliminar la última línea del fichero contenido.txt y guardarlo.
7. Añadir los cambios a la zona de preparado.
![](4_67.png)
8. Comprobar de nuevo el estado del repositorio.
![](4_8.png)
9. Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.
![](4_9.png)
10. Comprobar de nuevo el estado del repositorio.
![](4_10.png)
11. Deshacer los cambios realizados en el fichero contenido.txt para volver a la versión anterior del fichero.
![](4_11.png)
12. Volver a comprobar el estado del repositorio.
![](4_12.png)
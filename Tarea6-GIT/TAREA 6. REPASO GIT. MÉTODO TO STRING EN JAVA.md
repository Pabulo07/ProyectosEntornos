# TAREA 6. REPASO GIT. MÉTODO TO STRING EN JAVA
0. Inicializad bien vuestro repositorio de Entornos si lo tenéis o bien la carpeta Tarea6-GIT
1. Cread un fichero test.java con la clase test como sigue:
2. Pasad a preparado el fichero.

![](img/Captura%20de%20pantalla%202021-02-02%20085134.png)

3. Cread el fichero Principal.java
4. Pasad a preparado el fichero

![](img/Captura%20de%20pantalla%202021-02-02%20085611.png)

5. Haced un commit con el comentario “Inicial clases test y principal”

![](img/3.png)

6. Comprobad la salida del programa. (debéis compilar los .java y probar el Principal)

    ![](img/4.png)

7. Modificad el fichero test eliminando el método toString()

    ![](img/5.png)

8. Pasad a preparado el fichero

![](img/6.png)

9. Realizad un segundo commit “Eliminada ToString()”

![](img/7.png)

10. Comprobad de nuevo la salida del programa.

    ![](img/8.png)

11. Volved atrás viendo los “log” y haciendo “checkout” necesarios para que la salida del programa sea la
del paso 6. Responded a las preguntas en el markdown: ¿Qué creéis que hace el método toString? Y ¿Qué
conseguimos con el @Override?
    
##### $git log --oneline
    
##### $git checkout ..

> @Override se utiliza, para forzar al compilador a comprobar que estás sobrescribiendo correctamente un método, y de este modo evitar errores.
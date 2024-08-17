# PARTE I (Trabajo Individual).
1.	Crea un repositorio localmente.
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/inicializar%20repositorio.png)
2.	Agrega un archivo de ejemplo al repositorio, el **README.md** puede ser una gran opción.
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/agregar%20readme.png)
3.	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**
- git add: añade los cambios realizados en el repositorio local a la zona de "staging". Para ello, notifica a git que queremos realizer cambios/actualizaciones a un(os) archivo(s) en particular para el siguiente commit. Hay que aclarar que esto no afecta el repositorio del servidor aún, solo guarda el estado actual de los archivos seleccionados (en staging), pero aún no los sube.
- git commit -m "mensaje": confirma los cambios realizados después de realizer un "git add". Todos estos cambios quedan guardados, como realizer una captura de pantalla al repositorio en el estado actual.
4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
   [Como enlazar correos en GitHub](https://docs.github.com/es/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/adding-an-email-address-to-your-github-account)
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/enlazar%20correo.png)
   
5.	Crea un repositorio en blanco (vacío) e GitHub.
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/crear%20repositorio.png)

   
6.	Configura el repositorio local con el repositorio remoto.

      [Como subir un proyecto local a github.](https://gist.github.com/cgonzalezdai/cc33db72a6fe5178637aabb562eae35c)
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/enlazar%20repositiorio1.png)
![image](https://github.com/santiagoAvellaR/CVDS-lab01/blob/master/images/enlazar%20repositorio2.png)

7.	Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3
    Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:
   	```bash
      git add .
    ```

    ```bash
      git commit -m "mensaje, lo que hiciste con el archivo"
    ```

    ```bash
      git push "url repositorio"
    ```
    ![image]()
    ![image]()
8.	Configura el correo en git local de manera correcta
![image](URL)
9.	Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).
![image](URL)

Bibliografía:


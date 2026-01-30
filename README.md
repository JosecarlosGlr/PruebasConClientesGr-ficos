# Pruebas con clientes gráficos

### Uso de Cliente Gráfico (FileZilla Client)

Para facilitar la gestión de archivos, he configurado una conexión persistente en el **Gestor de Sitios**. He definido un sitio llamado **"Prueba Local"** utilizando el protocolo FTP con cifrado explícito sobre TLS, apuntando a la dirección `127.0.0.1` con el usuario `tester`.

![](https://raw.githubusercontent.com/JosecarlosGlr/PruebasConClientesGr-ficos/refs/heads/main/1.png)

**Operaciones realizadas:**

* **Conexión y Autenticación:** He establecido la sesión validando el certificado del servidor. En el panel de mensajes se observa la correcta inicialización de TLS y el registro del usuario.
* **Transferencia Bidireccional:** He realizado con éxito el intercambio de archivos entre el sitio local (`/home/user/`) y el sitio remoto (`/`).
    * **Descarga:** Se transfirió el archivo `archivo_del_servidor.txt` al equipo local.
    * **Subida:** Se subió el archivo `prueba.txt` al servidor.
* **Verificación de estado:** En la consola de mensajes se confirma que ambas transferencias finalizaron correctamente ("Transferencia correcta"), y en la parte inferior se listan en la pestaña de **"Transferencias satisfactorias"**.

![](https://raw.githubusercontent.com/JosecarlosGlr/PruebasConClientesGr-ficos/refs/heads/main/2.png)

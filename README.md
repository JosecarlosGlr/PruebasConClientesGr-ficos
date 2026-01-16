# Pruebas con clientes gráficos

### Uso de Cliente Gráfico (FileZilla Client)

Se configuró una conexión persistente en el Gestor de Sitios utilizando el protocolo FTP con cifrado explícito sobre TLS (usuario `tester`).

**Operaciones realizadas:**
* Se estableció la conexión validando el certificado del servidor.
* Se realizó una **transferencia bidireccional**: descarga del archivo `archivo_del_servidor.txt` y subida de archivos locales mediante la interfaz de arrastrar y soltar.
* Se verificó en el panel de "Mensajes de estado" que las transferencias finalizaron con el código "226 Transfer OK".

!()[https://raw.githubusercontent.com/JosecarlosGlr/PruebasConClientesGr-ficos/refs/heads/main/1.png]
!()[https://raw.githubusercontent.com/JosecarlosGlr/PruebasConClientesGr-ficos/refs/heads/main/2.png]

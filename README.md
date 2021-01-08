## Instalar Pentaho (Kettle)
1. Instalar JDK **sudo apt install openjdk-8-jdk**  (se requiere Java 8.0)
```
En caso de tener más de una version de Java instalado es necesario seleccionarlo como default 
con sudo update-alternatives --config java
```
2. Descargar PDI de pentaho [LINK ](https://sourceforge.net/projects/pentaho/files/latest/download)

3. Descomprimir el .zip 
4. Si se tiene **Ubuntu 18** Ejecutar apt-get install libwebkitgtk-1.0. 

    Para **versiones posteriores** debe descargar lo siguiente e instalarlo:

    * [libjavascriptcoregtk ](http://archive.ubuntu.com/ubuntu/pool/universe/w/webkitgtk/libjavascriptcoregtk-1.0-0_2.4.11-3ubuntu3_amd64.deb)

    * [libwebkitgtk ](https://launchpadlibrarian.net/344880892/libwebkitgtk-1.0-0_2.4.11-3ubuntu3_amd64.deb)

5. Descargar [mysql-connector](https://cdn.mysql.com//Downloads/Connector-J/mysql-connector-java-5.1.49.tar.gz)

6. Mover el archivo  **mysql-connector-java-5.1.49-bin.jar**  a la carpeta data-integration/bin

## TEST DISPONIBLES
**Movies**:
 * db : db-test(BETWEEN DB and CSV).sql
 
* file: TEST MOVIES (BETWEEN DB and CSV).ktr



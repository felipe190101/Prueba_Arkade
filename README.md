Se encuentra el codigo para la ejecucion de la prueba tecnica, se encuentran dos archivos relevantes ademas de los archivos fuente:

1. Un archivo llamado Formato_Carga_Archivo_Excel_Arkade en el cual se muestra el formato que debe contener dicho archivo para realizar la carga masiva de equipos a una prealerta, dicho formato se encuentra en la ruta Prueba_Arkade/resources/
2. Un archivo llamado SQLQueryDatabasePruebaArkade el cual es el script de la creacion de la base de datos en SQL Server para la ejecucion del programa, este se encuentra en PruebaTecnicaArkade/resources/, para realizar dicha
conexion desde el codigo, se deben cambiar los valores de usuario y contraseña definidos como variables en la clase ConexionBD la cual se encuentra en PruebaTecnicaArkade/src/dao.
3. Para realizar una conexion exitosa con la base de datos se debe activar la conecion TPC/IP desde el administrador de configuracion de SQL Server, esto desde Configuracion de red de SQL Server -> protocolos de MSSQLSERVER y habilitar la opcion llamada TCP/IP y verificar que el puerto de conexion TCP sea el 1433

# Unidad 1

**Sistemas Gestores de BD (SGBD):**
- Almacenamiento eficiente
- Acceso rápido de datos
- Seguridad
- Integridad de datos
- Concurrencia y Control de transacciones
- Escalabilidad y disponibilidad

SGBD mas usados
- Mysql
- PostgreSQL
- Oracle Database
- SQL Server
- SQLite
- MongoDB


|Base de datos|   
|------------|
|Selección|   
|Preprocesado|
|Selección de caracteristicas|
|Extracción de conocimiento|
|Evolución|
|Modelo clasificador de conocimientos|


# Unidad 2.- Instalación de un Gestor de BD

1. SGBD
    - Estructura de memoria
        - SGA (Area global del sistema)
            - Cache de los buffers
            - Buffer del registro del rado (Insert, Update, Delete, Create)
            - El pool compartido
            - Large Pool: Procesamiento de entrada y salida, memoria de la seción, copias de seguridad y copias de recuperación
            - Java Pool
            - Streams Pool
            - Cache de Diccionario (Tablas y listas de la BD que contiene información, junto el como se comoponen y sus usuarios)
    - Estructura de procesos
        - Usuario: Conexión del usuario y el servidor
        - De segundo plano: Enlace entre la estructura fisica y de memoria
            - LCK
            - SMON (Monutior del sistema)
            - PMON (Monitor de procesos)
            - DBWR (Escritor de DB)
            - LGWR (Escritor de registro)
            - CKPT (Punto de control)
            - ARCH (Archivador)
            - RECO (Recuperación)
    - Archivos
        - completar con los tipos de archivos de un gestor de BD
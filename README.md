# ApiMinitBits Backend

Este es el backend para el proyecto ApiMinitBits.

## Descripción

[Añade una breve descripción de tu proyecto aquí]

## Tecnologías

*   Go
*   GORM (ORM para Go)
*   PostgreSQL (Neon)

## Configuración

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/RobertoSuarez/ApiMiniBits.git
    cd ApiMiniBits
    ```
2.  **Instalar dependencias:**
    ```bash
    go mod tidy
    ```
3.  **Configurar variables de entorno:**
    Crea un archivo `.env` en la raíz del proyecto y añade tu cadena de conexión a la base de datos Neon:
    ```
    DATABASE_URL="tu_cadena_de_conexion_aqui"
    ```
    El archivo `main.go` está configurado para leer esta variable.

4.  **Ejecutar la aplicación:**
    ```bash
    go run main.go
    ```

## Próximos Pasos

*   Definir modelos de datos.
*   Implementar endpoints de la API.
*   Añadir autenticación.

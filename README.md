# Neurolap

## Instalación

1. **Descargar PocketBase**:

   Visita la [página de descargas de PocketBase](https://pocketbase.io/docs/) y descarga la versión adecuada para tu sistema operativo.

2. **Extraer el archivo**:

   Descomprime el archivo descargado en el directorio de tu elección.

3. **Iniciar PocketBase**:

   Abre una terminal, navega al directorio donde extrajiste PocketBase y ejecuta:

   ```bash
   ./pocketbase serve
   ```

   Esto iniciará el servidor en `http://127.0.0.1:8090`.

## Importar Colecciones

Para importar las colecciones definidas en el archivo `pb_schema_v1.json` ubicado en la carpeta `Schemas`, sigue estos pasos:

1. **Acceder al panel de administración**:

   Abre `http://127.0.0.1:8090/_/` en tu navegador y crea una cuenta de administrador si es la primera vez que accedes.

2. **Importar el esquema**:

   En el panel de administración, ve a la sección de "Settings" y selecciona "Import Collections".

3. **Seleccionar el archivo**:

   Haz clic en "Load from JSON file" y selecciona `pb_schema_v1.json` desde la carpeta `Schemas`.

4. **Importar**:

   Haz clic en "Import" para cargar las colecciones en PocketBase.

## Uso de PocketBase como Gestor de Archivos

PocketBase permite almacenar y gestionar archivos de manera eficiente.

1. **Subir archivos**:

   Puedes subir archivos a través del panel de administración o mediante la API REST.

2. **Acceder a archivos**:

   Los archivos subidos se pueden acceder mediante URLs públicas o privadas, según la configuración de permisos.

Para más información, revisa la [documentación sobre manejo de archivos](https://pocketbase.io/docs/files-handling/).

## Endpoints y Autenticación

PocketBase ofrece una API REST para interactuar con los datos y gestionar la autenticación.

- **Autenticación de usuarios**:

   Puedes autenticar usuarios mediante correo electrónico y contraseña, o utilizando proveedores OAuth2 como Google, Facebook, GitHub, entre otros.

   Consulta la [documentación sobre autenticación](https://pocketbase.io/docs/authentication/) para más detalles.

- **Gestión de registros**:

   Utiliza la API REST para crear, leer, actualizar y eliminar registros en tus colecciones.

   Revisa la [documentación sobre la API REST](https://pocketbase.io/docs/api-records/) para conocer los endpoints disponibles.

Para una integración más sencilla, puedes utilizar los SDKs oficiales:

- [Client-side SDKs](https://pocketbase.io/docs/client-side-sdks/)


Para más información y ejemplos, visita la [documentación oficial de PocketBase](https://pocketbase.io/docs/).
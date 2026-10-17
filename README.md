# //. The Omnicorp Launcher

Launcher de escritorio para **Minecraft Java Edition en Windows**, con instancias independientes, gestión de mods.

## Descarga e instalación

1. Abre **Releases** en este repositorio y entra en la última versión estable.
2. En **Assets**, descarga el instalador de Windows terminado en `-setup.exe` o `-Setup.exe`.
3. Ejecuta el instalador y sigue sus instrucciones.
4. Abre **The Omnicorp Launcher** y selecciona **Conectar Microsoft**.
5. Copia el código temporal, abre la página oficial de Microsoft y autoriza tu cuenta. La conexión se completará automáticamente en el launcher.
6. Crea una instancia o selecciona uno de los perfiles PRO y pulsa **Jugar**.

Los archivos **Source code (zip)** y **Source code (tar.gz)** que genera GitHub contienen la documentación de este repositorio; no son el instalador.

## Requisitos

- Windows 10 u 11 de 64 bits, con arquitectura x64.
- Microsoft Edge WebView2 Runtime. Si falta, puedes obtenerlo desde la [página oficial de Microsoft](https://developer.microsoft.com/microsoft-edge/webview2/).
- Una cuenta Microsoft con acceso vigente a Minecraft Java Edition.
- Conexión a Internet para iniciar sesión y descargar el juego y su contenido.
- Memoria y almacenamiento suficientes para la versión de Minecraft y los mods elegidos.

No necesitas instalar Java previamente: el launcher permite descargar OpenJDK Temurin y seleccionar un runtime compatible con cada instancia.

## Funciones

- **Instancias independientes:** versión, icono, cuenta, Java y servidor propios.
- **Vanilla, Fabric y Forge**, con instalación del loader al preparar el juego.
- **Modrinth integrado:** búsqueda e importación de modpacks y descarga de mods compatibles.
- **Gestores de mods, shaders y resource packs:** añadir archivos locales, habilitar, deshabilitar y retirar contenido.
- **Java configurable:** descarga integrada de OpenJDK Temurin 8, 17, 21 y 25, selección manual y argumentos personalizados.
- **Memoria mínima y máxima** mediante controles deslizantes o valores numéricos, con avisos de RAM.
- **Omnicorp PRO:** tres perfiles incluidos para Minecraft 1.8.9, 1.12.2 y 1.21, con packs propios y Omnicorp HUD configurable.

Los shaders requieren un mod de renderizado compatible. Los shaders y resource packs se seleccionan dentro de Minecraft una vez descargados.

## Actualizaciones

Descarga el instalador de la nueva versión desde **Releases** e instálalo. Allí encontrarás también las notas de cada versión.

Antes de cambiar la versión de Minecraft o los mods de una instancia, haz una copia de seguridad de sus mundos.

## Soporte

Para comunicar un problema, abre un **Issue** e incluye:

- Versión del launcher y de Windows.
- Versión de Minecraft y loader utilizado.
- Pasos para reproducir el fallo y mensaje de error.
- Registro del juego, si está disponible y resulta relevante.

Revisa los registros antes de publicarlos y elimina códigos de acceso, tokens u otros datos personales.

## Créditos

Proyecto independiente, sin afiliación con Mojang Studios, Microsoft, Modrinth ni los desarrolladores de Fabric, Forge o Eclipse Temurin.

Minecraft y sus recursos pertenecen a sus respectivos titulares. Los mods, shaders y resource packs conservan las licencias y condiciones de sus autores.

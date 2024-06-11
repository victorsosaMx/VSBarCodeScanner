# VSBarCodeScanner

VSBarCodeScanner es un proyecto simple de lector de códigos de barras utilizando JavaScript y la biblioteca QuaggaJS. Este proyecto permite escanear códigos de barras utilizando la cámara de un dispositivo, agregar los códigos escaneados a una lista y emitir un sonido de "BEEP" cada vez que se agrega un nuevo código.

## Funcionalidades

- **Escaneo de Códigos de Barras**: Utiliza la cámara del dispositivo para escanear diferentes tipos de códigos de barras.
- **Lista de Códigos Escaneados**: Los códigos escaneados se agregan a una lista para su referencia.
- **Sonido de Confirmación**: Emite un sonido de "BEEP" cada vez que se agrega un nuevo código a la lista.
- **Precisión Mejorada**: Implementa un sistema para evitar la adición de códigos duplicados y mejorar la precisión del escaneo.

## Instrucciones de Uso

1. **Abrir el Proyecto**: Abre el archivo `VSBarCodeScanner.html` en tu navegador web. Asegúrate de que el navegador soporte `getUserMedia` para el acceso a la cámara.
2. **Permitir Acceso a la Cámara**: Permite que el navegador acceda a la cámara de tu dispositivo cuando se te solicite.
3. **Escanear Códigos de Barras**: Coloca un código de barras frente a la cámara para escanearlo. Los códigos válidos se agregarán automáticamente a la lista.
4. **Ver Lista de Códigos**: La lista de códigos escaneados se mostrará en la parte inferior de la página.
5. **Sonido de Confirmación**: Escucharás un sonido de "BEEP" cada vez que se agrega un nuevo código a la lista.

## Requisitos

- Un navegador web moderno que soporte `getUserMedia` para el acceso a la cámara.
- Conexión a Internet para cargar la biblioteca QuaggaJS desde el CDN.
- Un archivo de sonido `beep.mp3` ubicado en el mismo directorio que el archivo HTML.

## Contratiempos 

- Utilice la extencion de live server de VSCODE para ejecutar el código en HTTPS (vease archivo createssl.txt)


## Archivo de Sonido

Asegúrate de tener un archivo de sonido llamado `beep.mp3` en el mismo directorio que tu archivo `VSBarCodeScanner.html`, o ajusta la ruta del archivo de sonido en el elemento `<audio>` dentro del archivo HTML.

## Créditos

Este proyecto utiliza la biblioteca [QuaggaJS](https://serratus.github.io/quaggaJS/) para el escaneo de códigos de barras.

## Licencia

Este proyecto está licenciado bajo la MIT License.

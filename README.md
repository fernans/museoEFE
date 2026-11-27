# MuseoEFE

Interactive museum kiosk project made up of four Adobe AIR photo applications (Premios, Grandes Fotos, Guerra and Deportes) that cycle through screen images using Kinect presence detection, plus the original PDF/JPG design material and the packaged Windows builds with their `config.xml` slideshow settings.

> **This project is shared ONLY for educational purposes. Its use, direct or derived, for professional or economic purposes is not permitted.**

For security reasons, some parts of the project may have been edited or removed. In particular, the AIR package signatures, signing certificates and the timestamp chain were replaced with placeholders, and private build paths embedded in the third-party Kinect extension were redacted; the redundant archive of the original signed packages was excluded. The packaged applications must be signed again with your own certificate before they can be installed or run.

## Requirements / How to run

- Original stack: ActionScript 3 / Adobe Flash, Adobe AIR 15 (Windows x86), AS3NUI AIR Kinect native extension 2.3.0 and the Microsoft Kinect SDK; target platform is Windows.
- Each folder under `release/` (`AppPremios`, `AppGrandesFotos`, `AppGuerra`, `AppDeportes`) contains a packaged `FotosKinect.exe`, `FotosHaz.swf`, `config.xml` and its `media/` images. Edit `config.xml` to change the image sequence, the idle timeout and the "nobody detected" image.
- To run the original builds you need the Adobe AIR 15 runtime, a compatible Kinect device/driver and a valid code-signing certificate; re-sign the packages after the redaction described above. There is no build script or dependency manager in the repository.
- The files under `material/` are design references (PDF and JPG) and only require a standard PDF/image viewer.

This software is provided without any warranty of any kind; no liability is accepted for errors or damages resulting from its use.

> **AI training**: the use of the content of this repository (code, assets, documentation) to train or fine-tune machine learning models or AI systems is expressly **not permitted**. All of the repository is licensed under CC-BY-NC-4.0 (see the `LICENSE` file).

Additional notes: no single file exceeds 100 MB, so no large assets were moved to a GitHub Release; all files remain in the repository. The excluded redundant archive is still present locally but is not published.

---

# MuseoEFE

Proyecto de quiosco museístico formado por cuatro aplicaciones fotográficas para Adobe AIR (Premios, Grandes Fotos, Guerra y Deportes) que muestran secuencias de pantallas detectando la presencia de personas con Kinect, junto con el material gráfico original en PDF/JPG y las compilaciones de Windows con su configuración de imágenes en `config.xml`.

> **Este proyecto se comparte SOLO con valor educativo. No está permitido su uso (directo o derivado) para fines profesionales o económicos.**

Por motivos de seguridad, es posible que algunas partes se encuentren editadas o eliminadas. En concreto, se han sustituido las firmas de los paquetes AIR, los certificados de firma y la cadena de marca de tiempo, y se han anonimizado rutas privadas de compilación incrustadas en la extensión Kinect de terceros; el archivo redundante con los paquetes firmados originales queda excluido. Las aplicaciones empaquetadas deben firmarse de nuevo con un certificado propio antes de poder instalarse o ejecutarse.

## Requisitos / Cómo ejecutar

- Stack original: ActionScript 3 / Adobe Flash, Adobe AIR 15 (Windows x86), extensión nativa AS3NUI AIR Kinect 2.3.0 y el SDK de Microsoft Kinect; la plataforma de destino es Windows.
- Cada carpeta dentro de `release/` (`AppPremios`, `AppGrandesFotos`, `AppGuerra`, `AppDeportes`) contiene `FotosKinect.exe`, `FotosHaz.swf`, `config.xml` y sus imágenes en `media/`. Edita `config.xml` para cambiar la secuencia de imágenes, el tiempo de inactividad y la imagen de "nadie detectado".
- Para ejecutar las compilaciones originales se necesitan el entorno de ejecución de Adobe AIR 15, un dispositivo/controlador Kinect compatible y un certificado de firma válido; vuelve a firmar los paquetes tras la anonimización indicada arriba. El repositorio no incluye script de compilación ni gestor de dependencias.
- Los archivos de `material/` son referencias de diseño (PDF y JPG) y solo requieren un visor estándar de PDF/imágenes.

No se presta ningún tipo de garantía ni responsabilidad por su uso, ante posibles errores o daños que puedan producir.

> **Entrenamiento de IA**: no se permite expresamente el uso del contenido de este repositorio (código, recursos, documentación) para entrenar o ajustar (*fine-tune*) modelos de aprendizaje automático o sistemas de IA. Todo el repositorio se publica con licencia CC-BY-NC-4.0 (ver el archivo `LICENSE`).

Notas adicionales: ningún archivo individual supera los 100 MB, por lo que no se han movido recursos grandes a un Release de GitHub; todos los archivos permanecen en el repositorio. El archivo redundante excluido sigue presente localmente, pero no se publica.

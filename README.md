# Enlaces verificados de Nexo

Este repositorio publica `/.well-known/assetlinks.json` para asociar enlaces
HTTPS de `marco04git.github.io` con las apps Android de Nexo. No contiene
credenciales: las huellas SHA-256 de los certificados son públicas.

La asociación actual incluye la app de desarrollo `com.example.nexo` firmada
con la clave debug de este ordenador y la APK local `io.nexo.mobile` firmada
con la clave de subida. Al distribuir desde Google Play habrá que añadir la
huella **de firma de aplicaciones de Play**, que puede ser distinta. iOS
necesitará Team ID, Bundle ID definitivo y `apple-app-site-association` antes
de activar Universal Links.

El enlace de recuperación se limita al camino
`/nexo-confirmacion/recuperar.html`; otros enlaces del dominio no se manejan
desde la aplicación.

# ZG ZoneMenu — releases / entregas

## 1.0.3 protected candidate / candidato protegido

- Minecraft 1.20.1, Forge 47.x, Java 17. **One universal JAR on client and server**; use matching 1.0.3 on both sides. Internal network protocol remains `4`. No other ZG mod is a mandatory dependency.
- `zonemenu-1.0.3-protected.jar` SHA-256 `471ACDA4A1142DED196E6DA38036E9B596E73A7154696E52B898C3EAF8D9A3E8`.
- New release metadata: Elgochogms, All Rights Reserved, `LICENSE.txt` packaged. Earlier MIT grants persist for older versions. Gameplay behavior and packet protocol remain from 1.0.2.
- Gradle clean build and ProGuard passed. The **unprotected build** passed 13 isolated Forge fixture checks: automatic pickup blocked, chosen stacks transferred, self-dropped items recoverable, distant/delayed/protected items rejected, and bulk pickup deduplicated. The **exact protected JAR** started and shut down cleanly on isolated Forge 47.4.10. No Java source or private mapping is embedded.
- The 13 checks are not a direct functional test of the protected JAR because the fixture links to original class names. Graphical client, actual client-server packet exchange, full modpack and production hosting remain untested with the protected JAR. CurseForge upload/review remains pending.

## Español

Un JAR 1.0.3 para ambos lados. Pasó compilación y 13 comprobaciones de recogida con el JAR sin proteger; el JAR protegido arrancó en Forge aislado. Faltan prueba gráfica y transferencia de paquetes con ese JAR exacto, modpack completo y hosting. Verifica el SHA-256 antes de instalar.


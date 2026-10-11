# ZG ZoneMenu

## Español

Interfaz RPG ZG para recoger manualmente objetos del suelo en Minecraft 1.20.1 / Forge 47.x. **Instala el mismo JAR universal 1.0.3 en servidor y clientes**. El servidor cancela la recogida automática y valida cada clic o `RECOGER TODO`: espectador, entidad existente, distancia máxima de 2 bloques, demora de recogida, veto de otros mods e inventario disponible. Las solicitudes de recogida masiva admiten como máximo 128 identificadores por paquete.

La lista compacta aparece al acercarse a un objeto; puedes elegir una pila o recoger todo. El cursor queda libre y puedes seguir caminando con WASD. Clic derecho cierra la lista. Los objetos recién soltados por el jugador no abren la lista inmediatamente hasta alejarse y volver. Los objetos no recogidos permanecen como entidades normales.

En **Opciones > Controles**, el botón `ZoneMenu: Automático / Con tecla` cambia el modo local. En **Controles > Teclas** puedes asignar `Abrir lista de objetos del suelo`. La preferencia se guarda en `config/zonemenu-client.toml`; véase [CONFIGURATION.md](CONFIGURATION.md). [RELEASES.md](RELEASES.md) incluye hash y pruebas. No se requieren mods ZG adicionales; la protección de otros mods se respeta mediante el evento de recogida de Forge.

## English

Original ZG RPG interface for manual ground item pickup on Minecraft 1.20.1 / Forge 47.x. **Install the same universal 1.0.3 JAR on server and clients**. The server blocks automatic pickup and checks each click or `COLLECT ALL`: spectator state, item existence, distance up to 2 blocks, pickup delay, protection hooks from other mods, and inventory space. Bulk requests accept at most 128 entity IDs per packet.

The compact list appears near ground items, allowing one stack or all nearby stacks to be collected. The cursor is free while WASD movement remains available; right-click closes the list. Newly dropped items do not open the list immediately until the player moves away and returns. Unselected items remain normal item entities.

In **Options > Controls**, switch automatic or key mode; set the `Open ground item list` key under key bindings. The local preference is saved in `config/zonemenu-client.toml`; see [CONFIGURATION.md](CONFIGURATION.md). [RELEASES.md](RELEASES.md) has the checksum and test limits. No other ZG mods are mandatory; Forge pickup events let other mods veto a transfer.

## Ownership / Titularidad

Original ZG assets and documentation © Elgochogms. This public repo contains documentation and an avatar only; source and private obfuscation mapping remain private. The new 1.0.3 JAR declares All Rights Reserved; earlier MIT grants remain in effect for older versions.


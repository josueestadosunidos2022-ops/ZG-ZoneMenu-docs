# ZG ZoneMenu 1.0.3 — TOML / configuración

`config/zonemenu-client.toml` is a **per-client** Forge config, not a server policy file. / Es configuración de **cada cliente**, no una política del servidor.

| Key / Clave | Default / Predeterminado | Effect / Efecto |
|---|---|---|
| `automaticOpen` | `true` | `true`: automatically open the nearby ground-item list. `false`: require the player-assigned key. / `true`: abre la lista al acercarse a un objeto. `false`: exige la tecla asignada por el jugador. |

The in-game button under Minecraft **Options > Controls** changes this setting; the key binding is under **Controls > Keys**. / El botón en **Opciones > Controles** cambia este ajuste; la tecla se asigna en **Controles > Teclas**.

There is no server TOML in this release. Server-side pickup validation is always active when the JAR is installed: distance, pickup delay, inventory space and protection event veto cannot be disabled by this client setting. / No hay TOML de servidor en esta entrega. La validación del servidor permanece activa sin importar el ajuste del cliente.


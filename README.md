# Project Gielinor Rust showcase

Project Gielinor Rust is an in-progress Rust server and native OSRS 239.1 client project. GPT Astra is the primary AI development contributor, working under human direction and review. The screenshots show selected development checkpoints, not full functional parity. Live captures here use the isolated Kotlin Project Gielinor reference server; they do not establish Rust-client-to-Rust-server acceptance.

This repository contains only development showcase screenshots and their manifest. Captures are individually labeled as live native client, offline rendering test, or UI test. No executable, source, cache, model archive, music or private test resource is included.

Credits: Project Gielinor / Slashx124 and RS Mod contributors (ISC; Copyright 2025 RS Mod); RSProt / Z-Kris (MIT; Copyright 2024 Z-Kris); RuneLite and RSProx contributors for reference/tooling; Project Gielinor Rust contributors. Jagex owns RuneScape/Old School RuneScape and the depicted game assets. Third-party libraries retain their respective licenses. This unofficial project is unaffiliated with and not endorsed by Jagex. No screenshot or Jagex-asset license is granted by the software licenses.

## Gallery

23 reviewed screenshots, led by full logged-in native client views. Live captures use the isolated Kotlin reference server. Historical offline scenes and UI tests are individually labeled. Full HUD composition does not imply complete functional parity.

### Live native client: Full native client with actors, populated inventory, chat, HUD and minimap during the widget-drag acceptance run.

![Full native client with actors, populated inventory, chat, HUD and minimap during the widget-drag acceptance run.](images/21-live-inventory.png)

### Live native client: World, actors, minimap and spellbook in the native client.

![World, actors, minimap and spellbook in the native client.](images/01-native-world.png)

### Live native client: Floating world map in the native client.

![Floating world map in the native client.](images/02-native-world-map.png)

### Live native client: Full native client showing the hub, actors, inventory, chat and minimap during preference verification.

![Full native client showing the hub, actors, inventory, chat and minimap during preference verification.](images/22-live-hub.png)

### Offline rendering test: Lumbridge castle and surrounding terrain.

![Lumbridge castle and surrounding terrain.](images/11-lumbridge-castle.png)

### Offline rendering test: Falador castle, towers and rooftops.

![Falador castle, towers and rooftops.](images/13-falador-castle.png)

### Offline rendering test: Draynor village buildings and waterfront.

![Draynor village buildings and waterfront.](images/14-draynor-village.png)

### Offline rendering test: Varrock market square and fountain.

![Varrock market square and fountain.](images/12-varrock-square.png)

### Offline rendering test: Al Kharid palace and desert scenery.

![Al Kharid palace and desert scenery.](images/15-al-kharid-palace.png)

### Offline rendering test: Lumbridge castle upper-floor interior.

![Lumbridge castle upper-floor interior.](images/16-castle-interior.png)

### Offline rendering test: Windmill animation test captured at tick 60.

![Windmill animation test captured at tick 60.](images/19-windmill-frame.png)

### Live native client: Native client during a ranged encounter against the isolated Kotlin reference server.

![Native client during a ranged encounter against the isolated Kotlin reference server.](images/03-ranged-encounter.png)

### Live native client: Native client during a Wind Strike encounter against the isolated Kotlin reference server.

![Native client during a Wind Strike encounter against the isolated Kotlin reference server.](images/04-magic-encounter.png)

### Offline rendering test: Assembled rune equipment meshes; no player base model.

![Assembled rune equipment meshes; no player base model.](images/17-rune-equipment.png)

### Offline rendering test: Assembled dragon equipment meshes; no player base model.

![Assembled dragon equipment meshes; no player base model.](images/18-dragon-equipment.png)

### Offline rendering test: Green dragon model in the native animation/rendering harness.

![Green dragon model in the native animation/rendering harness.](images/20-green-dragon.png)

### Offline rendering test: Goblin model in the isolated Rust animation and rendering harness.

![Goblin model in the isolated Rust animation and rendering harness.](images/09-goblin-model.png)

### Offline rendering test: World-map overview rendered by Rust.

![World-map overview rendered by Rust.](images/08-map-overview.png)

### Offline rendering test: Item icons rendered by Rust.

![Item icons rendered by Rust.](images/07-item-icons.png)

### UI test: Textured item models rendered inside native widgets.

![Textured item models rendered inside native widgets.](images/10-widget-models.png)

### UI test: Bank interface rendered by the isolated Rust UI harness.

![Bank interface rendered by the isolated Rust UI harness.](images/05-bank-interface.png)

### UI test: Equipment interface rendered by the isolated Rust UI harness.

![Equipment interface rendered by the isolated Rust UI harness.](images/06-equipment-interface.png)

### UI test in live session: Temporary text-editor acceptance widget inside the logged-in native client; not a standard gameplay dialogue.

![Temporary text-editor acceptance widget inside the logged-in native client; not a standard gameplay dialogue.](images/23-live-editor.png)



## Server project thread

The [ready-to-post main server thread](threads/server-project.bbcode) has a separate [server gallery and image links](threads/server-project-images.md). It includes actual Rust-server integration captures, prepared test setups, historical live views and explicitly labelled Kotlin-reference comparison images. See the [scope and evidence notes](threads/server-project-evidence.md). The original gallery above and its image manifest are preserved.

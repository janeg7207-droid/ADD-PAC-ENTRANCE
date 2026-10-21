# ADD-PAC-ENTRANCE

PAC All Out entrances for WWE 2K26, packaged for the **same Entrance Installer Free 1.7 included with MJF**. The installer executable, UI, and supporting Tools executable are unchanged; load a PAC `.entrance` file instead of MJF's.

[Download the full PAC installer ZIP](packages/PAC-All-Out-Discovery-Installer.zip)

1. Extract the complete ZIP. Close WWE 2K26.
2. Open `WWE 2K26 Entrance Installer Free.exe`, select **Discovery**, and confirm your game and mod data folders.
3. Click **Load New Entrance** and choose a PAC file from `Entrances`.
4. Check the slot status, keep backups enabled, and click **Install Entrance**. Cancel if it would replace another entrance you want to keep.
5. In Discovery, bake **both `discovery_data` and `_entrances`**, then assign the PAC entrance in-game.

| Entrance | Authored slot | Intended arenas |
| --- | --- | --- |
| PAC All Out SummerSlam 2025 | 979 | SummerSlam 2025 |
| PAC All Out WrestleMania 41 SmackDown | 981 | WrestleMania 41 / SmackDown |

You can install both variants. The supplied Free installer uses the authored slots; it cannot automatically relocate an occupied slot or uninstall entrances. Keep backups. The original author reports a lighting-pillar collision in SummerSlam, and placement in other arenas may not line up. The PAC wrestler model is not included.

If you already have MJF's Installer 1.7, the PAC files are also available separately in [entrances](entrances). These are real `.entrance` imports, not `.dsco` files.

Both files passed the supplied installer's package loader, extraction checks, registration validation, and install-preparation checks, including ADEF/CLIPS links. Corrupted checksums were rejected. Animation records are preserved; assembly metadata and animation-bank container layout were adapted for this installer. See [validation details](packages/PAC-Discovery-Validation.json).

**Windows UI execution, Discovery baking, and in-game playback have not been tested here.**

Credits: PAC entrance by Mr Creeper HD / Gorilla Modding Tools. Installer supplied with the TranquilKraken MJF archive. Original documentation is included in the ZIP. This is a repackaged PAC import, not an official installer update.

The earlier PAC manual ZIP and MJF ZIP remain in [packages](packages).

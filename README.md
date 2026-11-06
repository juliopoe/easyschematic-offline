# easyschematic-offline

Baut [EasySchematic](https://github.com/duremovich/EasySchematic) (AGPL-3.0) unverändert als statische Seite für den Unterpfad `/schematic/`
und veröffentlicht sie als Release-ZIP. Das VideoToolkit lädt das ZIP über die Downloads-Kachel und liefert die Seite lokal aus.

Der Ablauf (`.github/workflows/bauen.yml`) läuft täglich und baut nur, wenn es die neueste EasySchematic-Version hier noch nicht gibt.
Von Hand: Actions → Bauen → Run workflow.

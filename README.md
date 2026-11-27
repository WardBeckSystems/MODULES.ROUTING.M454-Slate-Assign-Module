# M454 · Routing

Ward-Beck Systems M454, 1974|7. Wiki page: [M454 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M454.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 40 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 3 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 15 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2VaY3NKR2ZkWnM/view?resourcekey=0-2IKYvdGmcA_Sj-2Tmf4dsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2VaY3NKR2ZkWnM&resourcekey=0-2IKYvdGmcA_Sj-2Tmf4dsg" width="240" alt="1974 - M454 - Slate Module.jpg"></a><br><sub>1974|7 · Slate Module</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1974|7 · wbsps - module - m454 - slate module_small](https://drive.google.com/file/d/0B0yR0b5T78SKMzdEaWdvZnBUaGs/view?resourcekey=0-_kdewuJt2RrRbl-zSGa2Vg)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc05ZR2NUYnBEeGs/view?resourcekey=0-OmeafGu8SUv52v2Y3rPfag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc05ZR2NUYnBEeGs&resourcekey=0-OmeafGu8SUv52v2Y3rPfag" width="240" alt="1974 - M454 - 454-04-001 - PSSMOO CKO USD.jpg"></a><br><sub>1974|7 · 454-04-001 - PSSMOO CKO USD · <a href="MECHANICAL/1974%20-%20M454%20-%20454-04-001%20-%20PSSMOO%20CKO%20USD%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWo1QWhNT3dJNEE/view?resourcekey=0-OzuAu5ZKNH5QJZroE5weOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWo1QWhNT3dJNEE&resourcekey=0-OzuAu5ZKNH5QJZroE5weOA" width="240" alt="1974 - M454 - 454-04-003 - SLATE ASS IGNMENT MODULE.jpg"></a><br><sub>1974|7 · 454-04-003 - SLATE ASS IGNMENT MODULE · <a href="MECHANICAL/1974%20-%20M454%20-%20454-04-003%20-%20SLATE%20ASS%20IGNMENT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbG54Wm1YZVhzQlU/view?resourcekey=0-EVl1lZrJVEouuEjCBJg9YA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbG54Wm1YZVhzQlU&resourcekey=0-EVl1lZrJVEouuEjCBJg9YA" width="240" alt="1974 - M454 - 454-02-001 - DRAWN ENE.jpg"></a><br><sub>1974|7 · 454-02-001 - DRAWN ENE · <a href="SCHEMATICS/1974%20-%20M454%20-%20454-02-001%20-%20DRAWN%20ENE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1982 - 454-02-001 - SLATE ASSIGN MODULE - DRN D.N. NOV-82 - ISS 2.png`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M454 - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 18 | COMMON | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| Y | +24 V | power |  | high |

**Straps:** CH ON LAMP: JMP.Z.W · CH ON GND : JMP.X.18 · 24V Jumper: JMP.Y.21 · CH ON GND : JMP.20.18 · Insert +: JMP.22.21 · Insert -: JMP.Z.Y · Fader +: JMP.20.19 · Fader - : JMP.X.W

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3ZURHJlc2RnMFU/view?resourcekey=0-UImMswSkOMiLiWO85NHzww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3ZURHJlc2RnMFU&resourcekey=0-UImMswSkOMiLiWO85NHzww" width="240" alt="1974 - M454 - P001 - Title Page.jpg"></a><br><sub>1974|7 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZFBrLUd4elFWVVU/view?resourcekey=0-o6-13lZ_oQrWA0tb1OYJmg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZFBrLUd4elFWVVU&resourcekey=0-o6-13lZ_oQrWA0tb1OYJmg" width="240" alt="1974 - M454 - P002 - 1-1.jpg"></a><br><sub>1974|7 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUEZyR0JIbTRPaEE/view?resourcekey=0-j0ptBaZNk7EcpyaBggaX9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUEZyR0JIbTRPaEE&resourcekey=0-j0ptBaZNk7EcpyaBggaX9g" width="240" alt="1974 - M454 - P003 - 1-2.jpg"></a><br><sub>1974|7 · P003 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVF9TVkt6Y0I5MEk/view?resourcekey=0-wdBL5qdDBPM0p3tOOvxTMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVF9TVkt6Y0I5MEk&resourcekey=0-wdBL5qdDBPM0p3tOOvxTMg" width="240" alt="1974 - M454 - Slate Assign Module (2).pdf"></a><br><sub>1974|7 · Slate Assign Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemV6YU1feUwyZ2M/view?resourcekey=0-NbZtTVFNliGdvCWRGTRfYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemV6YU1feUwyZ2M&resourcekey=0-NbZtTVFNliGdvCWRGTRfYw" width="240" alt="1974 - M454 - Slate Assign Module.pdf"></a><br><sub>1974|7 · Slate Assign Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa2QxamlnTXd4bVk/view?resourcekey=0-X_dT4KrraRJj-DCNQpqkmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa2QxamlnTXd4bVk&resourcekey=0-X_dT4KrraRJj-DCNQpqkmA" width="240" alt="1974 - M454 - vint P1.jpg"></a><br><sub>1974|7 · vint P1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLThXRm1yTExNX3c/view?resourcekey=0-O1qDQxLqb1BR2x8exKLD0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLThXRm1yTExNX3c&resourcekey=0-O1qDQxLqb1BR2x8exKLD0Q" width="240" alt="1974 - M454 - vint P2.jpg"></a><br><sub>1974|7 · vint P2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSFhScFV4cWRMajg/view?resourcekey=0-DZKA6obnhefWL8OJtI66zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSFhScFV4cWRMajg&resourcekey=0-DZKA6obnhefWL8OJtI66zg" width="240" alt="1974 - M454 - vint P3.jpg"></a><br><sub>1974|7 · vint P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1JVDuvdMj6koYIX0ilm-dbVBLlhU6XAIo/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1JVDuvdMj6koYIX0ilm-dbVBLlhU6XAIo" width="240" alt="19xx - M454 - DOC - SLATE ASSIGN MODULE.png"></a><br><sub>19xx - M454 - DOC - SLATE ASSIGN MODULE</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - M454 - 454-02-001 - DRAWN ENE.kicad_sch](KICAD/1974%20-%20M454%20-%20454-02-001%20-%20DRAWN%20ENE.kicad_sch)
- [1982 - 454-02-001 - SLATE ASSIGN MODULE - DRN D.N. NOV-82 - ISS 2.kicad_sch](KICAD/1982%20-%20454-02-001%20-%20SLATE%20ASSIGN%20MODULE%20-%20DRN%20D.N.%20NOV-82%20-%20ISS%202.kicad_sch)
- [M454.kicad_sym](KICAD/M454.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

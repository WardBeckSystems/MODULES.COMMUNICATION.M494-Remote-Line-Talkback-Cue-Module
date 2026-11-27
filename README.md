# M494 · Communication

Ward-Beck Systems M494, 1978|11. Wiki page: [M494 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M494.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 39 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 7 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 94 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 10 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 22 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Circuit description

From [19xx - M494 - Remote Line Tb Module (2).pdf](MANUALS/19xx%20-%20M494%20-%20Remote%20Line%20Tb%20Module%20(2).pdf) pages 2-4 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

&quot;'494 REMOTE LINEn / CUE MODULE

The H494 Module is designed to be uud fn conjunction with u M4S1 hlkback Module ud an H453A Cue AMpllffe r t o provide facilities fort alk back, l f s ten, and prograM cue along a h oway remote line.

The eo d ul e permits connection with up to eight remote l fnes. Any one H ne /lIa y be selected with the Ifd oft he fnterloc ke d push ·button assembly SWI t o SWg. Resistors Rl through R16 pro v fde a balanced, center tapped 600 ohm terMination for uch line.

The &quot; 49 4 lilly be operated in anyone of four distinct modes as described below.

These l e c ted remote line is routed t hrou9 h the closed conhcts o f relays 1&lt;2 and 1&lt; ] t o the LI STEN/ CUE switch SWI0. When In its r e l used position. 5'111 0 connects the !f net o pins I1 /U of the Module connector. This point is externally wired to the Input of In H453A Cue AMplifier, thus per mltt i n9 listen i n9 to there mote line feed.

A p rog rUl feed originating from a console output o r alternatively frOM an off·afr d fs tr l but ion ulplfffe r, i s connected top ins 16/ T of the module connect o r. W1th SWI0 depressed, thfs sfgnll i s fed back Into these l e cte d line and serves IS a cue feed. The g r et n LEO DS3 w111 be illuM f nl ted with SWI0 depressed. TAlKBACK The cut put of an 1'1451 hlkb ack Amplifier enters the 1Il0d\l leon pins IS/V. Similarly, one oft he four control outputs associated with the 1'1 451 outputs elector switches 1$ wired to pfn 21 oft he H494. When it is desired to co tlJa\lnlc ate with the

r eec tel ocatf on, thea ppropriat e O\ltpu t butt nn of the H451 1s

pressed, resulting In I(J oft he &quot;494 being energized and connecting the hlkbl ck feed t o these le c ted lfne. SiMul ta

neo us l y, they ell ow LED DS2 is f ll umf nate d. When operating tn

the TALKBACK..od e, CUE as well as LISTEN r ee t t t t tes are disabled.

**ON-AI R LOCKOUT**

Once the CHANNEl ON button o f the Me90 Input &quot; od uI ere late d tot he selected r e e ere l t ne Is.ctuued, the control feed fro. the 1'490, which is wired top fn X oft he &quot;4 94, will energIze K1. nd de -ene r gf ze 1(.2. As ares ult, all TALKBAC!:, CUE, and LISTEN h c f11t f es are disabled and there e e t e 11ne Is t er. lnated into 600 ohlll. There d LEO OSl f n di c a test his p.rt lc uhr co nd1t ion.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGh6ekFDamNpN2c/view?resourcekey=0-fiTLige95Il0oTE-C_mZeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGh6ekFDamNpN2c&resourcekey=0-fiTLige95Il0oTE-C_mZeA" width="240" alt="19xx - M494 - 494-04-003 - CONNECTED ACROSS BRCHEEM REMOTE INE AND THE GREEN.jpg"></a><br><sub>19xx - M494 - 494-04-003 - CONNECTED ACROSS BRCHEEM REMOTE INE AND THE GREEN · <a href="MECHANICAL/19xx%20-%20M494%20-%20494-04-003%20-%20CONNECTED%20ACROSS%20BRCHEEM%20REMOTE%20INE%20AND%20THE%20GREEN%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLTRVN3VOZi1ZMGc/view?resourcekey=0-hhYif236_AGq6rWmD3Vy2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLTRVN3VOZi1ZMGc&resourcekey=0-hhYif236_AGq6rWmD3Vy2Q" width="240" alt="19xx - M494 - 494-01-001 - AIR CONTROL ASSIGN INPUTS LINE TALK.jpg"></a><br><sub>19xx - M494 - 494-01-001 - AIR CONTROL ASSIGN INPUTS LINE TALK · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-01-001%20-%20AIR%20CONTROL%20ASSIGN%20INPUTS%20LINE%20TALK%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXpHSHJMVWNHVjQ/view?resourcekey=0-6QpP3sqW-4AMr21b8wAfjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXpHSHJMVWNHVjQ&resourcekey=0-6QpP3sqW-4AMr21b8wAfjg" width="240" alt="19xx - M494 - 494-01-001 - ELL- REMOTE LINE TB-CUE MODULE FUNCTIONAL.jpg"></a><br><sub>19xx - M494 - 494-01-001 - ELL- REMOTE LINE TB-CUE MODULE FUNCTIONAL · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-01-001%20-%20ELL-%20REMOTE%20LINE%20TB-CUE%20MODULE%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQzI2bUpJMThoak0/view?resourcekey=0--8Cqn37i96DQNW2oxh7_xg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQzI2bUpJMThoak0&resourcekey=0--8Cqn37i96DQNW2oxh7_xg" width="240" alt="19xx - M494 - 494-02-001 - AND ALL CAPACITORS.jpg"></a><br><sub>19xx - M494 - 494-02-001 - AND ALL CAPACITORS · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-02-001%20-%20AND%20ALL%20CAPACITORS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDdYUVEwOU11dEE/view?resourcekey=0-Sxn6GRLdgYDhWpZNv8Lvtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDdYUVEwOU11dEE&resourcekey=0-Sxn6GRLdgYDhWpZNv8Lvtw" width="240" alt="19xx - M494 - 494-02-001 - IOK AIR RZO.jpg"></a><br><sub>19xx - M494 - 494-02-001 - IOK AIR RZO · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-02-001%20-%20IOK%20AIR%20RZO%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2VPOVVUa294RFk/view?resourcekey=0-ra6p4-teKIGNpJnFZt3YxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2VPOVVUa294RFk&resourcekey=0-ra6p4-teKIGNpJnFZt3YxA" width="240" alt="19xx - M494 - 494-06-001 - REMOTE LINE.jpg"></a><br><sub>19xx - M494 - 494-06-001 - REMOTE LINE · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-06-001%20-%20REMOTE%20LINE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2NRZWRjLVdOcE0/view?resourcekey=0-HGL-gak2dT_S8soVaDULdA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2NRZWRjLVdOcE0&resourcekey=0-HGL-gak2dT_S8soVaDULdA" width="240" alt="19xx - M494 - 494-06-001 - RZI IOO.jpg"></a><br><sub>19xx - M494 - 494-06-001 - RZI IOO · <a href="SCHEMATICS/19xx%20-%20M494%20-%20494-06-001%20-%20RZI%20IOO%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/10PBucS_YumpUAe4MKcrfMnhyC717PCOB/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=10PBucS_YumpUAe4MKcrfMnhyC717PCOB" width="240" alt="19xx - M494 - DOC - 494-02-001 - REMOTE LINE TB-CUE MODULE.jpg"></a><br><sub>19xx - M494 - DOC - 494-02-001 - REMOTE LINE TB-CUE MODULE</sub></td></tr>
</table>

Not on Google Drive yet: `1978 - 494-02-001 - REMOTE LINE TB CUE MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 2 (2).jpg`, `1978 - 494-02-001 - REMOTE LINE TB CUE MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 2.jpg`, `19xx - 494-06-001.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYWc1aWNsYUV5SlU/view?resourcekey=0-QZy1_66TbJvIJ996FjjQTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYWc1aWNsYUV5SlU&resourcekey=0-QZy1_66TbJvIJ996FjjQTw" width="240" alt="19xx - M494 - 494-04-002 - RSLKY CONNECTOR REAR VIEW ALE.jpg"></a><br><sub>19xx - M494 - 494-04-002 - RSLKY CONNECTOR REAR VIEW ALE · <a href="PINOUTS/19xx%20-%20M494%20-%20494-04-002%20-%20RSLKY%20CONNECTOR%20REAR%20VIEW%20ALE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M494 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | LINE INPUT 8 | in | LINE INPUT 8 | high |
| 2 | N/C | nc |  | high |
| 3 | LINE INPUT 7 | in | LINE INPUT 7 | high |
| 4 | N/C | nc |  | high |
| 5 | LINE INPUT 6 | in | LINE INPUT 6 | high |
| 6 | N/C | nc |  | high |
| 7 | LINE INPUT 5 | in | LINE INPUT 5 | high |
| 8 | N/C | nc |  | high |
| 9 | LINE INPUT 4 | in | LINE INPUT 4 | high |
| 10 | N/C | nc |  | high |
| 11 | LINE INPUT 3 | in | LINE INPUT 3 | high |
| 12 | N/C | nc |  | high |
| 13 | LINE INPUT 2 | in | LINE INPUT 2 | high |
| 14 | N/C | nc |  | high |
| 15 | LINE INPUT 1 | in | LINE INPUT 1 | high |
| 16 | CUE IN | in | CUE IN | high |
| 17 | LISTEN OUT | out | LISTEN OUT | high |
| 18 | TB IN | in | TB IN | high |
| 19 | ASSIGN CTL | control_in | ASSIGN CTL | high |
| 20 | GROUND | ground |  | high |
| 21 | TALKBACK CTL | control_in | TALKBACK CTL | high |
| 22 | CHASSIS | ground |  | high |
| A | LINE INPUT 8 | in | LINE INPUT 8 | high |
| B | N/C | nc |  | high |
| C | LINE INPUT 7 | in | LINE INPUT 7 | high |
| D | N/C | nc |  | high |
| E | LINE INPUT 6 | in | LINE INPUT 6 | high |
| F | N/C | nc |  | high |
| H | LINE INPUT 5 | in | LINE INPUT 5 | high |
| J | N/C | nc |  | high |
| K | LINE INPUT 4 | in | LINE INPUT 4 | high |
| L | N/C | nc |  | high |
| M | LINE INPUT 3 | in | LINE INPUT 3 | high |
| N | N/C | nc |  | high |
| P | LINE INPUT 2 | in | LINE INPUT 2 | high |
| R | N/C | nc |  | high |
| S | LINE INPUT 1 | in | LINE INPUT 1 | high |
| T | CUE IN | in | CUE IN | high |
| U | LISTEN OUT | out | LISTEN OUT | high |
| V | TB IN | in | TB IN | high |
| W | N/C | nc |  | high |
| X | ON-AIR CTL | control_in | ON-AIR CTL | high |
| Y | +25 V | power |  | high |
| Z | CONTROL COMMON | ground |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M494 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M494 - DOC - R1400-R2400 - 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZUpROVNjZ0ZOS28/view?resourcekey=0-ivj9AckQj0vaolSvgA-jMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZUpROVNjZ0ZOS28&resourcekey=0-ivj9AckQj0vaolSvgA-jMg" width="240" alt="19xx - M494 - DOC - R1400-R2400 - 016.jpg"></a><br><sub>19xx - M494 - DOC - R1400-R2400 - 016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2xMWFJfajJ4X0U/view?resourcekey=0-8xsK6ObYPgtyzytPpuPbJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2xMWFJfajJ4X0U&resourcekey=0-8xsK6ObYPgtyzytPpuPbJw" width="240" alt="19xx - M494 - P001 - Title Page.jpg"></a><br><sub>19xx - M494 - P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDdDTUpDbmhlUTA/view?resourcekey=0-P_r-zyS25C0UbgEoQkmFzQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDdDTUpDbmhlUTA&resourcekey=0-P_r-zyS25C0UbgEoQkmFzQ" width="240" alt="19xx - M494 - P002 - 1-1.jpg"></a><br><sub>19xx - M494 - P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeDZVUXlGVlJOc00/view?resourcekey=0-vKvaqV2BEww0wrhRC-aYyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeDZVUXlGVlJOc00&resourcekey=0-vKvaqV2BEww0wrhRC-aYyA" width="240" alt="19xx - M494 - P003 - 1-2.jpg"></a><br><sub>19xx - M494 - P003 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXZtc0RGcDdEMGs/view?resourcekey=0-vyE0UY8C42waLN1R3Fdpqg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXZtc0RGcDdEMGs&resourcekey=0-vyE0UY8C42waLN1R3Fdpqg" width="240" alt="19xx - M494 - P004 - 2-1.jpg"></a><br><sub>19xx - M494 - P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkVBTUdhZkw2U1U/view?resourcekey=0-ueH8BmPMrz6imYhj3-TrNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkVBTUdhZkw2U1U&resourcekey=0-ueH8BmPMrz6imYhj3-TrNw" width="240" alt="19xx - M494 - P005 - 2-2.jpg"></a><br><sub>19xx - M494 - P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDVuejhDeTgxQ1k/view?resourcekey=0-OdYZ05pu3Ucyfy1HuA-EYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDVuejhDeTgxQ1k&resourcekey=0-OdYZ05pu3Ucyfy1HuA-EYA" width="240" alt="19xx - M494 - P006 - 2-3.jpg"></a><br><sub>19xx - M494 - P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHQ2Wk9lVFEtUkU/view?resourcekey=0-xA3KAvgdwEqsn5TZE1KgaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHQ2Wk9lVFEtUkU&resourcekey=0-xA3KAvgdwEqsn5TZE1KgaQ" width="240" alt="19xx - M494 - Remote Line Tb Module (2).pdf"></a><br><sub>19xx - M494 - Remote Line Tb Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnYyVTJQVWcwVTQ/view?resourcekey=0-WIMvQXfAgtMBYIeVxEUgKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnYyVTJQVWcwVTQ&resourcekey=0-WIMvQXfAgtMBYIeVxEUgKg" width="240" alt="19xx - M494 - Remote Line Tb Module.pdf"></a><br><sub>19xx - M494 - Remote Line Tb Module</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - 494-02-001 - REMOTE LINE TB CUE MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 2 (2).kicad_sch](KICAD/1978%20-%20494-02-001%20-%20REMOTE%20LINE%20TB%20CUE%20MODULE%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%202%20(2).kicad_sch)
- [1978 - 494-02-001 - REMOTE LINE TB CUE MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 2.kicad_sch](KICAD/1978%20-%20494-02-001%20-%20REMOTE%20LINE%20TB%20CUE%20MODULE%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%202.kicad_sch)
- [19xx - M494 - 494-01-001 - AIR CONTROL ASSIGN INPUTS LINE TALK.kicad_sch](KICAD/19xx%20-%20M494%20-%20494-01-001%20-%20AIR%20CONTROL%20ASSIGN%20INPUTS%20LINE%20TALK.kicad_sch)
- [19xx - M494 - 494-01-001 - ELL- REMOTE LINE TB-CUE MODULE FUNCTIONAL.kicad_sch](KICAD/19xx%20-%20M494%20-%20494-01-001%20-%20ELL-%20REMOTE%20LINE%20TB-CUE%20MODULE%20FUNCTIONAL.kicad_sch)
- [19xx - M494 - 494-02-001 - AND ALL CAPACITORS.kicad_sch](KICAD/19xx%20-%20M494%20-%20494-02-001%20-%20AND%20ALL%20CAPACITORS.kicad_sch)
- [19xx - M494 - 494-02-001 - IOK AIR RZO.kicad_sch](KICAD/19xx%20-%20M494%20-%20494-02-001%20-%20IOK%20AIR%20RZO.kicad_sch)
- [19xx - M494 - Remote Line Tb Module (2) p9.kicad_sch](KICAD/19xx%20-%20M494%20-%20Remote%20Line%20Tb%20Module%20(2)%20p9.kicad_sch)
- [19xx - M494 - Remote Line Tb Module p11.kicad_sch](KICAD/19xx%20-%20M494%20-%20Remote%20Line%20Tb%20Module%20p11.kicad_sch)
- [19xx - M494 - Remote Line Tb Module p9.kicad_sch](KICAD/19xx%20-%20M494%20-%20Remote%20Line%20Tb%20Module%20p9.kicad_sch)
- [M494.kicad_sym](KICAD/M494.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

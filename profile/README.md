# CadCraft Studio

Draft, model and build — with tools you already know.

**[Website](https://getcadcraft.com) | [CadCraft Studio](https://getcadcraft.com/studio) | [Download](https://getcadcraft.com/download#studio) | [Use in the browser](https://getcadcraft.com/use) | [Tutorials](https://getcadcraft.com/tutorials) | [Roadmap](https://getcadcraft.com/roadmap) | [News](https://getcadcraft.com/news)**

## CadCraft Studio: every app, one install

<a href="https://getcadcraft.com/studio"><img src="https://getcadcraft.com/assets/img/studio/hub-paper.png" alt="CadCraft Studio: the home screen with the eight apps"></a>

**[CadCraft Studio](https://github.com/getcadcraft/studio)** is the center of CadCraft: all eight apps in one install, with one home screen to open them from, the same files and one license. It is not another app; it is the eight apps, together.

**[Download CadCraft Studio 0.5](https://getcadcraft.com/download#studio)** for Windows, macOS, Linux and Android. Studio is the one desktop download; each app also runs in the browser.

- **One home screen.** Open any app, your recent drawings and the tutorials from one place.
- **Work together, live.** Host a drawing from Studio and edit it with others on the same network (invite links over the internet open soon).
- **Free for any work.** Every app and every feature, commercial work included. A Studio license adds the cloud.

Studio is built from [studio](https://github.com/getcadcraft/studio) (the home screen and the suite packer) and [desktop-shell](https://github.com/getcadcraft/desktop-shell) (the shell it runs in on every platform).

## The eight apps inside Studio

<table>
<tr><td width="25%" align="center"><a href="https://github.com/getcadcraft/cadcraft"><img src="https://github.com/getcadcraft/cadcraft/raw/main/screenshots/paper.png" alt="CadCraft"></a><br><b>CadCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/bimcraft"><img src="https://github.com/getcadcraft/bimcraft/raw/main/screenshots/paper.png" alt="BimCraft"></a><br><b>BimCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/modelcraft"><img src="https://github.com/getcadcraft/modelcraft/raw/main/screenshots/paper.png" alt="ModelCraft"></a><br><b>ModelCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/markupcraft"><img src="https://github.com/getcadcraft/markupcraft/raw/main/screenshots/paper.png" alt="MarkupCraft"></a><br><b>MarkupCraft</b></td></tr>
<tr><td width="25%" align="center"><a href="https://github.com/getcadcraft/takeoffcraft"><img src="https://github.com/getcadcraft/takeoffcraft/raw/main/screenshots/paper.png" alt="TakeoffCraft"></a><br><b>TakeoffCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/civilcraft"><img src="https://github.com/getcadcraft/civilcraft/raw/main/screenshots/paper.png" alt="CivilCraft"></a><br><b>CivilCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/detailcraft"><img src="https://github.com/getcadcraft/detailcraft/raw/main/screenshots/paper.png" alt="DetailCraft"></a><br><b>DetailCraft</b></td><td width="25%" align="center"><a href="https://github.com/getcadcraft/partcraft"><img src="https://github.com/getcadcraft/partcraft/raw/main/screenshots/paper.png" alt="PartCraft"></a><br><b>PartCraft</b></td></tr>
</table>

| App | What it does | Description | Get it |
|---|---|---|---|
| [**CadCraft**](https://github.com/getcadcraft/cadcraft) | 2D drafting & documentation | Command-line drafting with layers, blocks, dimensions and layouts that plot. Opens and saves DWG and DXF. | In Studio \| [Use in the browser](https://getcadcraft.com/use/cadcraft) |
| [**BimCraft**](https://github.com/getcadcraft/bimcraft) | BIM authoring | Parametric walls, doors and windows on levels and grids, with views, schedules, sheets and clash checks from one model. | In Studio \| [Use in the browser](https://getcadcraft.com/use/bimcraft) |
| [**ModelCraft**](https://github.com/getcadcraft/modelcraft) | 3D modeling for design | Fast push/pull modeling with groups, components, guides and inference snapping, for massing and early design. | In Studio \| [Use in the browser](https://getcadcraft.com/use/modelcraft) |
| [**MarkupCraft**](https://github.com/getcadcraft/markupcraft) | Drawing review & markup | Open a PDF plan set, mark it up from a saved tool chest, compare revisions and run punch lists with the whole team. | In Studio \| [Use in the browser](https://getcadcraft.com/use/markupcraft) |
| [**TakeoffCraft**](https://github.com/getcadcraft/takeoffcraft) | Quantity takeoff & estimating | Calibrated linear, area and count takeoff from PDF plans, with assemblies, cost columns and quantities that export. | In Studio \| [Use in the browser](https://getcadcraft.com/use/takeoffcraft) |
| [**CivilCraft**](https://github.com/getcadcraft/civilcraft) | Civil & site design | Surfaces from points and breaklines, alignments, profiles, corridors, grading and pipe networks. LandXML in and out. | In Studio \| [Use in the browser](https://getcadcraft.com/use/civilcraft) |
| [**DetailCraft**](https://github.com/getcadcraft/detailcraft) | Steel & rebar detailing | Structural steel members and connections, rebar placement and bending schedules, shop drawings and NC files from one model. | In Studio \| [Use in the browser](https://getcadcraft.com/use/detailcraft) |
| [**PartCraft**](https://github.com/getcadcraft/partcraft) | Parametric parts & assemblies | Constrained sketches, feature history, assemblies with joints and drawings with GD&T. STEP in and out. | In Studio \| [Use in the browser](https://getcadcraft.com/use/partcraft) |

Each app's repository follows development: its `main` is the code we work on, so a pull request lands on today's app.

Coming next: **SuperCadCraft**, one app that will rule them all: the eight apps in one window, on the same files.

## Shared repositories

| Repository | What it is |
|---|---|
| [**studio**](https://github.com/getcadcraft/studio) | **CadCraft Studio: the home screen and the packer that puts the eight apps into one install** |
| [desktop-shell](https://github.com/getcadcraft/desktop-shell) | The shell Studio runs in on Windows, macOS, Linux and Android (iPad next) |
| [library](https://github.com/getcadcraft/library) | Openly licensed items for [LibraryCraft](https://getcadcraft.com/library), each credited to its maker |
| [addons](https://github.com/getcadcraft/addons) | Add-ons for the apps, and the template to write your own |

## Rules every app follows

- **Open formats first.** DWG, DXF, IFC, STEP, PDF and LandXML in and out. Your drawings never need us to open them.
- **Works offline.** Local files on your own disk, with no forced cloud. No sign-in and no license check to open a drawing or plot it.
- **Your muscle memory works.** The commands, aliases, layouts and shortcuts you already use do what your hands expect.
- **Scriptable to the command line.** A command-line interface, a JSON control channel and an MCP server, so scripts and AI assistants can draft, check and plot alongside you.
- **Open source.** Apache License 2.0. Read it, build it, change it.

## Get involved

Bugs and feature requests go in the app's own repository (Studio's own in [studio](https://github.com/getcadcraft/studio)). Ideas for what to rebuild next: [getcadcraft.com/suggest](https://getcadcraft.com/suggest). Build news by email: [getcadcraft.com/updates](https://getcadcraft.com/updates).

<sub>CadCraft and the CadCraft logo are trademarks of The Data Design Group, Inc.</sub>

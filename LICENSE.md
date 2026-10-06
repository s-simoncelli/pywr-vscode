# Licence

Copyright (c) 2026 Stefano Simoncelli. All rights reserved.

Pywr for VS Code ("the Software") is proprietary software.

## What you may do

You may install and use the Software, as distributed by the copyright holder, to build,
edit, run and review your own models.

## What you may not do

Without the prior written permission of the copyright holder, you may not:

- copy, modify, merge or create derivative works of the Software;
- publish, distribute, sublicense, rent, lease or sell the Software, in whole or in part;
- reverse engineer, decompile or disassemble the Software, except where the law allows it
  despite this restriction;
- remove or alter any copyright or licence notice in the Software.

## Third-party software


The extension includes third-party software, each under its own licence. The main
components are listed below; [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) has the
full list and the licence texts.

| Component                                                             | Used for                              | Licence            |
| --------------------------------------------------------------------- | ------------------------------------- | ------------------ |
| [pywr-next](https://github.com/pywr/pywr-next)                        | Running and validating Pywr v2 models | MIT or Apache-2.0  |
| [COIN-OR CLP](https://github.com/coin-or/Clp)                         | Linear programming solver             | EPL-2.0            |
| [HDF5](https://github.com/HDFGroup/hdf5) and `hdf5-metno`             | Reading and writing HDF5 files        | BSD-3-Clause, MIT or Apache-2.0 |
| [napi-rs](https://napi.rs)                                            | Native modules                        | MIT                |
| [React](https://react.dev)                                            | Forms, schematic and results viewer   | MIT                |
| [React Flow](https://reactflow.dev)                                   | Schematic                             | MIT                |
| [uPlot](https://github.com/leeoniya/uPlot)                            | Charts                                | MIT                |
| [Zustand](https://github.com/pmndrs/zustand)                          | Schematic state                       | MIT                |
| [Lucide](https://lucide.dev)                                          | Icons                                 | ISC                |
| [Codicons](https://github.com/microsoft/vscode-codicons)              | Icons                                 | CC-BY-4.0          |
| [Tailwind CSS](https://tailwindcss.com)                               | Styles                                | MIT                |
| [jsonc-parser](https://github.com/microsoft/node-jsonc-parser) and [vscode-json-languageservice](https://github.com/microsoft/vscode-json-languageservice) | Reading and validating JSON | MIT |
| [JSON Schema $Ref Parser](https://github.com/APIDevTools/json-schema-ref-parser) | Reading the model schemas  | MIT                |
| [Bootstrap Icons](https://icons.getbootstrap.com)                     | Pywr v1 node icons                    | MIT                |
| [Material Icons](https://fonts.google.com/icons)                      | Pywr v1 node icon                     | Apache-2.0         |

The map behind the schematic is drawn with [Leaflet](https://leafletjs.com)
(BSD-2-Clause), loaded when the map is shown, and uses map data ©
[OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.

## No warranty

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR ITS USE.

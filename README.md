# Solid Connections

Solid Connections is a mechatronics project that combines mechanical CAD, custom PCB design in Altium, and embedded-system prototyping.

## Quick Start (Altium)

1. Open `Electronics/Altium_Project/Solid Connections/Solid Connections.PrjPcb`.
2. Top-level schematic entry: `Electronics/Altium_Project/Solid Connections/Top Level.SchDoc`.
3. Main PCB revisions: `Electronics/Altium_Project/Solid Connections/PBC2A.PcbDoc`, `Electronics/Altium_Project/Solid Connections/PBC2Asave.PcbDoc`, `Electronics/Altium_Project/Solid Connections/PCB2.PcbDoc`.
4. Output job configuration: `Electronics/Altium_Project/Solid Connections/Solid Connections.OutJob`.

## Repository Layout

```text
Solid-Connections/
├── README.md
├── LICENSE
├── CAD/
│   ├── Assemblies/                            # Assembly models (.SLDASM/.STEP)
│   ├── Components/                            # Part models and exports
│   ├── Hardware/                              # Purchased component CAD
│   └── Print_Exports/                         # 3D print outputs (.3mf/.stl)
├── Electronics/
│   ├── Altium_Project/
│   │   └── Solid Connections/                 # Main Altium workspace
│   ├── BOM/                                   # Bill of materials exports
│   └── Reference_Models/                      # PCB/display/MCU reference models
├── Firmware/
│   ├── Archives/                              # Firmware zip bundles
│   └── Vendor/                                # Third-party ESP32 references/examples
├── Documentation/
│   ├── Branding/
│   ├── Diagrams/
│   ├── Reports/
│   └── Images/
├── Assets/
│   └── Fonts/
└── Archive/
    ├── Packages/                              # Legacy packaged iterations
    └── Assets/
```

## Organization Rules

- Put new CAD files in `CAD/` instead of repository root.
- Keep Altium source in `Electronics/Altium_Project/Solid Connections/`.
- Put generated reports/logs under Altium-generated folders (ignored by `.gitignore`).
- Use `Documentation/` for project images/reports and `Archive/` for zip snapshots.

## License

This project is distributed under the license in `LICENSE`.

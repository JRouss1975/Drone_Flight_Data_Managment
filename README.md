# Drone Flight Data Management

Windows desktop application that keeps a library of drone flights and their
logs, shows flight positions on a map and computes flight statistics.

---

## At a glance

| | |
| --- | --- |
| **Type** | Windows desktop app (WPF) |
| **Built with** | C# · .NET Framework 4.6.1 |
| **Status** | Stable: no recent changes (published May 2022) |

---

## Features

- **Flight library:** flight records with their logs and positions.
- **Map view** of flight positions (GMap.NET).
- **Statistics** over the recorded flights, with charts (OxyPlot).
- **Data grids** for browsing and editing records (Xceed).
- Unit conversion, import and export helpers.

---

## Requirements

| | |
| --- | --- |
| Operating system | Windows 10 or 11 |
| Runtime | .NET Framework **4.6.1** or newer |
| Build | Visual Studio 2019 or 2022 with the **.NET desktop development** workload |
| Internet | For map tiles |

---

## Building and running

1. Open `DroneFlightDataManagment.sln` in Visual Studio.
2. Build and run with **F5**. Third-party assemblies are included in `Dlls/`.
3. Extract `Flights.7z` or `Mataranga.7z` to try the app with sample data.

---

## Project structure

```
DroneFlightDataManagment.sln
DroneFlightDataManagment/
├─ Model/                   Flight, Log, Statistics, StatisticsData, Enums
├─ Helpers/                 converters, file and unit helpers
├─ Dlls/                    third-party assemblies
├─ Resources/               icons
└─ MainWindow.xaml(.cs)     main window, map and charts
Flights.7z, Mataranga.7z    sample flight data
```

---

## Dependencies

| Package | Used for |
| --- | --- |
| GMap.NET (Core, WindowsPresentation) | Map |
| OxyPlot.Wpf | Charts |
| Xceed.Wpf.Toolkit / DataGrid | Data grids |

---

## License

Copyright © JRouss1975. All rights reserved.

No license is granted to use, copy, modify or distribute this code without written permission.

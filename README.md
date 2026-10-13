# Drone Flight Data Management

Desktop application to manage drone flight records, map flight positions and
analyse flight statistics.

## Overview

Keeps a library of drone flights and their logs, shows flight positions on a
map and computes statistics over the recorded data.

## Features

- Flight and log records with positions
- Map view of flight positions (GMap.NET)
- Statistics and statistics data model
- Charts (OxyPlot) and data grids (Xceed WPF)
- Unit conversion and object copying helpers
- Import/export helpers

## Tech stack

- WPF, .NET Framework 4.6.1
- GMap.NET, OxyPlot, MathNet.Numerics, Xceed WPF Toolkit/DataGrid

## Repository layout

```
DroneFlightDataManagment/
  Model/     Enums.cs, Flight.cs, Log.cs, Statistics.cs, StatisticsData.cs
  Helpers/   converters and file/unit helpers
  Resources/ icons
  Dlls/      third-party assemblies
DroneFlightDataManagment.sln
Flights.7z / Mataranga.7z   sample data
```

## Notes

Sample flight data is provided in the `Flights.7z` and `Mataranga.7z` archives.

# Strategy Engineer Assistance Tool (SEAT)

## Overview
Strategy Engineer Assistance Tool (SEAT) for rFactor 2 is designed to efficiently summarise timing and telemetry data provided by the rFactor 2 simulator. It allows for easy analysis of session results, summaries of performance indices, lap and sector performance, and race strategy planning and management. The software is configurable for data display and analysis tailored to specific needs. Only rFactor 2 XML logs for the Race, Warmup, Qualifying, Practice and Test Day sessions are supported.

SEAT for rFactor 2 is free to use for non-commercial purposes.

## Installation
- Download the latest release.
- Install .exe file from the archive as any other software.
- [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html) version 24.1 or later is required to run the software. SEAT installer will automatically check if MATLAB Runtime is installed on the PC and, if needed, will download the most recent version and install it with the software.
- After you launch SEAT, use “File -> Load XML log” to load logs. Your local rFactor 2 XML logs are located in ..Steam\steamapps\common\rFactor 2\UserData\Log\Results folder.

Visual C++ Redistributable for Visual Studio 2015 must be installed on PC to launch the installer itself. These components should be on most PCs by default, but if you get an error about missing DLL, install C++ runtime library from [Microsoft website](https://www.microsoft.com/en-gb/download/details.aspx?id=48145).

## Features

### Database

**Multiple session log manager**
- Store as many session logs as you need in a single database
- Quickly load any session log into the program in one click
- Summary statistics for all session logs in the database on one page
​
### Reports

**Session summary**
- Total race/session time, gaps to the leader
- Fastest laps, laps completed, number of pit stops for every driver
- Session classification overall and for every class
- Position changes relative to starting positions

**Drivers**
- Fastest laps, theoretical best times, best sector times, number of laps completed for every driver
- Average pace and consistency
- Average fuel consumption for every driver

**Stints**
- Summary statistics for every stint completed by every driver in the session, including tyre compound, average tyre wear, number of laps, stint time, average pace (excluding pit in/out laps and outliers), consistency, average fuel consumption and fuel load, fastest lap, theoretical best and fastest sector times.

**Timecards**
- Detailed data for every driver and completed lap, including lap number, track position, notes (traffic, pit entry/exit, etc.), lap time, sector times, session time, gap to leader, gap ahead, gap behind, tyre compound, tyre wear for every wheel, fuel consumption.

**Pit stop analysis**
- Tyre compound in and tyre compound out of the pits
- Fuel added (estimation)
- Time lost in pit stop (2 estimates using lap times and sector times)

All reports can be saved as .csv files for further analysis.

### Graphs
​
**Gaps (race session only)**
- Gaps on track to race leader or any car in the session

**Laps**
- Lap times, with or without outliers

**Sectors**
- Sector times (S1/S2/S3)

**Positions**
- Position on track

**Pace**
- Box plots and sorted lap time visualisations for race pace analysis

**Fuel**
- Remaining fuel

**Wear**
- Tyre remaining for all wheels

**​Pits (race session only)**
- Estimated pit stop lengths in seconds for selected cars and median pit stop time for relevant classes.

For most graphs, traffic, tyre compounds, fuel remaining, fuel added, overtakes and driver names markers can be plotted as overlays on the main chart.

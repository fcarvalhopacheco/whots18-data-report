# Description of WHOTS-18 Mooring

The WHOTS-18 mooring, deployed on July 24, 2022, from R/V Oscar Elton Settle,
was outfitted with two complete sets of Air-Sea Interaction Meteorological
(ASIMET) sensors on the buoy and underneath subsurface instruments from 7 to
155 m depth, and near the bottom. See {cite}`Santiago-Mandujano2022, Santiago-Mandujano2024`
for a complete description of the buoy. The WHOTS-18 was recovered on June
19-20 2023.

The buoy used during the WHOTS-18 deployment cruise was equipped with a variety
of surface and subsurface instruments to ensure comprehensive data collection
across multiple environmental parameters.

## Surface Components

- **Two Loggers** (System 1 and System 2) with IDs 7 and 8.
- **Two Iridium Satellite Systems** for communication, with IMEI numbers 30023406326740 and 300234063345500.
- **Two Relative Humidity and Air Temperature (HRH) Sensors**, IDs 704 and 749, mounted at 230 cm and 233 cm above the deck.
- **Two Barometric Pressure Recorders (BPR)**, IDs 211 and 501, mounted at heights of 237 cm and 238 cm.
- **Two Wind Sensors (WND)**, IDs 221 and 343, mounted at 265 cm and 264 cm, respectively, from RM Young.
- **Two Precipitation Sensors (PRC)**, IDs 215 and 216, mounted at 253 cm and 254 cm.
- **Longwave Radiation Sensors (LWR)**, IDs 209 and 210, mounted at 280 cm.
- **Shortwave Radiation Sensors (SWR)**, IDs 504 and 209, also mounted at 280 cm.
- **Sea Surface Temperature (SST) Sensors**, IDs 1834 and 1841, located at -155 cm.
- **A Xeos Melo GPS** with IMEI 300034012129060.
- **Two Xeos Rover GPS Units** with IDs 787 and 859, and IMEI numbers 300434063359170 and 300434063297420.
- **A Vaisala WXT-530 Multi-variable Sensor** (ID 201) measuring temperature, humidity, pressure, wind, and precipitation, mounted at 267 cm.
- **A Sea-Bird SBE39AT Temperature Sensor** (ID 5272), mounted at 233 cm.
- **A Lascar Sensor** (ID 18), mounted at 197 cm.

## Subsurface Instrumentation

- **A pCO2 System** (ID 23), employing an equilibration tube, by Battelle MAPCO2, mounted at 155 cm.
- **A CTD Sensor** (ID 7202), mounted at 155 cm, using an SBE-16.
- **An Oxygen Sensor** (ID 1780), mounted at 155 cm.
- **A Fluorometer** (ID 2676), mounted at 155 cm.
- **A SAMI-2 pH Sensor** (ID 82), mounted at 155 cm.
- **A Xeos Kilo Transmitter** at 160 cm, with IMEI 300234067205440.
- **An Airmar Stand-alone Sensor** (ID 274), mounted at 233 cm.

Five internally logging Sea-Bird SBE-56 temperature sensors were bolted to the
buoy hull's underside, measuring sea surface temperature (SST). The SBE-56
sensors measured SST every 60 seconds at different depths ranging between 80-110cm
below the buoy deck. Two SBE-37 MicroCATs were at 1.55m measuring
at every 300s (See {numref}`table-7`).

```{table} WHOTS-18 MicroCAT and SBE-56 Temperature Sensor Information.
:name: table-7
:widths: auto
:align: center

| **Instrument** | **SN** | **Depth (m)** | **Sample Interval (sec)** |
| :------------: | :----: | :-----------: | :-----------------------: |
|     SBE-56     |  6411  |     0.80      |            60             |
|     SBE-56     |  7413  |     0.80      |            60             |
|     SBE-56     |  7414  |     0.95      |            60             |
|     SBE-56     |  7415  |     0.80      |            60             |
|     SBE-56     |  7412  |     0.80      |            60             |
|    MicroCAT    |  1834  |     1.55      |            300            |
|    MicroCAT    |  1841  |     1.50      |            300            |

```

Instrumentation provided by UH for the WHOTS-18 mooring included 18 SBE-37
Microcats, and two upward-looking RDI Workhorse ADCPs, transmitting in 300 kHz
and 600 kHz,respectively. The Microcats all measured temperature and
conductivity, with eight of them measuring pressure. All MicroCATs were
deployed with antifoulant capsules. In addition to the buoy instrumentation,
WHOI provided two Vector Measuring Current Meters (VMCMs), two deep Microcats (
SBE-37) installed near the bottom of the mooring, and all required subsurface
mooring hardware. In addition, a 69 kHz Vemco acoustic receiver was included
in the mooring to detect the presence of sharks tagged with acoustic
transmitters

The {numref}`mooring_subsurface` provides a listing of the WHOTS-18 subsurface
instrumentation at their nominal depths on the mooring, along with serial
numbers, sampling rates, and other pertinent information. A cold water spike
was induced to the UH MicroCATs before deployment
({numref}`mooring_subsurface`) and after recovery {numref}`table-8` by placing
an ice pack in contact with their temperature sensor to check for any drift in
their internal clock. To produce a spike in the ADCP data, each instrument’s
transducer was rubbed gently by hand for 20 seconds ({numref}`table-9` , and
{numref}`table-10`).

```{figure} figures/tables/WHOTS18_Instrument_Deployment_Info.png
:width: 1000%
:align: center
:name: mooring_subsurface

WHOTS-18 mooring subsurface instrument deployment information. All times
are in UTC
```


```{table} WHOTS-18 mooring C-T and ADCP Instruments recovery information. All times are in UTC (mm/dd/yy hh:mm:ss). Sea-Bird 37 Serial Number (SN).
:name: table-8
:widths: auto
:align: center


| **Depth (m)** | **Sea-Bird Serial #** | **Time out of water** | **Time of Spike** | **Time of End Spike** | **Time Logging Stopped** | **Samples Logged** |      **Data Quality**      |
| :-----------: | :-------------------: | :-------------------: | :---------------: | :-------------------: | :----------------------: | :----------------: | :------------------------: |
|       7       |         3617          |   06/20/23 03:54:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 15:10:40     |       72872        |            Good            |
|      15       |         6893          |   06/20/23 03:58:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 18:36:00     |       358223       |            Good            |
|      25       |         6894          |   06/20/23 04:02:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 19:18:00     |       358181       |            Good            |
|      35       |         6895          |   06/20/23 04:27:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |           N/A            |         0          |          No data           |
|      40       |         6896          |   06/20/23 04:25:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 20:52:30     |       358087       |            Good            |
|      45       |         6887          |   06/20/23 02:20:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 20:32:00     |       174638       |            Good            |
|     47.5      |       ADCP 1825       |   06/16/23 02:16:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |         02/10/23         |       28858        |     Failed on 02/10/23     |
|      50       |         6897          |   06/20/23 02:20:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 16:33:00     |       358346       |            Good            |
|      55       |         6898          |   06/20/23 02:14:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 18:53:10     |       479208       |            Good            |
|      65       |         6899          |   06/20/23 02:10:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 18:54:10     |       358346       |            Good            |
|      75       |         3618          |   06/20/23 02:11:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 22:24:30     |       159809       |            Good            |
|      85       |         3634          |   06/20/23 02:10:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 05:21:20     |       159951       |            Good            |
|      95       |         3670          |   06/20/23 02:08:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 19:31:50     |       119813       |            Good            |
|      105      |         6889          |   06/20/23 02:07:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 02:59:20     |       383760       |            Good            |
|      120      |         6890          |   06/20/23 02:04:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/20/23 22:58:30     |       383567       |            Good            |
|      125      |       ADCP 4891       |   06/20/23 02:00:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |         01/24/23         |       26654        |     Failed on 01/24/23     |
|      135      |         6888          |   06/20/23 02:03:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 06:05:40     |       383945       |            Good            |
|      155      |         6891          |   06/20/23 01:56:00   | 06/20/23 06:08:00 |   06/20/23 06:43:00   |    06/21/23 08:44:20     |       175204       | Large C-offset on 11/15/22 |
|    39 mab     |         12241         |   06/19/23 21:35:00   | 06/20/23 06:08:00 |   06/20/23 06:40:00   |    06/21/23 16:42:00     |       96129        |            Good            |
|    39 mab     |         11391         |   06/19/23 21:35:00   | 06/20/23 06:08:00 |   06/20/23 06:40:00   |    06/21/23 18:33:45     |       96127        |            Good            |

```

```{table} WHOTS-18 mooring ADCP deployment and configuration information. All times are in UTC (mm/dd/yy hh:mm:ss).
:name: table-9
:widths: auto
:align: center
|            **-**            | **ADCP S/N 1825**  | **ADCP S/N 4891**  |
|:---------------------------:|:------------------:|:------------------:|
|     **Frequency (kHz)**     |        600         |        300         |
|  **Number of Depth Cells**  |         25         |         30         |
|   **Depth Cell Size (m)**   |        2 m         |        4 m         |
|   **Pings per Ensemble**    |         80         |         40         |
| **Time per Ensemble (min)** |       10 min       |       10 min       |
|   **Time per Ping (sec)**   |       2 sec        |       4 sec        |
|   **Time of First Ping**    | 07/23/22, 00:40:00 | 07/22/22, 23:59:30 |
| **Transducer 1 Spike Time** | 07/23/22, 00:41:00 | 07/23/22, 00:20:00 |
| **Transducer 2 Spike Time** | 07/23/22, 00:41:15 | 07/23/22, 00:20:15 |
| **Transducer 3 Spike Time** | 07/23/22, 00:41:30 | 07/23/22, 00:20:30 |
| **Transducer 4 Spike Time** | 07/23/22, 00:41:45 | 07/23/22, 00:20:45 |
|   **Ice Spike Time Begin**  | 07/23/22, 00:50:00 | 07/23/22, 00:50:00 |
|    **Ice Spike Time End**   | 07/23/22, 01:20:00 | 07/23/22, 01:20:00 |
|      **Time in Water**      | 07/23/22, 20:13:00 | 07/23/22, 20:23:00 |
|        **Depth (m)**        |       47.5 m       |       125 m        |
```

```{table} WHOTS-18 mooring ADCP recovery information. All times are in UTC (mm/dd/yy hh:mm:ss).
:name: table-10
:widths: auto
:align: center

|            **-**            | **ADCP S/N 1825**  | **ADCP S/N 4891**  |
| :-------------------------: | :----------------: | :----------------: |
|     **Frequency (kHz)**     |        600         |        300         |
|  **Number of Depth Cells**  |         25         |         30         |
|   **Depth Cell Size (m)**   |        2 m         |        4 m         |
|   **Pings per Ensemble**    |         80         |         40         |
| **Time per Ensemble (min)** |       10 min       |       10 min       |
|      **Time in Water**      | 07/23/22, 20:13:00 | 07/23/22, 21:33:00 |
|    **Time out of Water**    | 06/20/23, 02:16:00 | 06/20/23, 02:00:00 |
|        **Depth (m)**        |       47.5 m       |       125 m        |

```

Both the 300 kHz ADCP at 125 m and the 600 kHz ADCP at 47.5 m were found not
pinging upon recovery, with data indicating they stopped recording on January
24, 2023, and February 10, 2023, respectively. In both cases, the likely cause
of failure was power loss due to corrosion of the bulkhead connectors. The data
recorded before the failures were of good quality, although the 600 kHz ADCP
had some near-surface side-lobe interference.

The RDI 300 kHz Workhorse Sentinel ADCP, SN 4891, was deployed at 125 m with
transducers facing upwards with an additional external battery pack. This
instrument was set to ping at 4-second intervals for 160 seconds every 10
minutes, and the burst sampling was designed to minimize aliasing by occasional
large ocean swell orbital motions. The bin size was set for 4 m. The first
ensemble was on 07/22/2012 at 23:45:49,and the last was on 02/10/2023 at
10:33:12 (see more {numref}`table-9`, {numref}`table-10`, and
{ref}`/appendices.md#whots-18-300-khz-serial-4891` for more configuration). This
instrument also measured temperature.

The RDI 600 kHz Workhorse Sentinel ADCP, SN 1825, was deployed at 47.5 m with
transducers facing upwards with an additional external battery pack. The
instrument was set to ping at 2-second intervals for 160 seconds every 10
minutes, and the burst sampling was designed to minimize aliasing by occasional
large ocean swell orbital motions. The bin size was set for 2 m. The first
ensemble was on 07/22/2022 at 23:48:56, and the last was on 01/24/2022 at
16:16:39 (see {numref}`table-9` , {numref}`table-10`, and
{ref}`/appendices.md#whots-18-600-khz-serial-1825` for more configuration). This
instrument also measured temperature.

The two VMCMs, SN 2042 and 2032, were deployed at 30 m and 10 m depth,
respectively. The instruments were prepared for deployment by the WHOI/UOP
group and set to sample at 1-minute interval. These instruments also
measured temperature.

All WHOTS-18 instruments were successfully recovered; recovery information for
the C-T instruments is shown in {numref}`table-8`. Most of the instruments had
some degree of biofouling, with the most substantial fouling near the surface.
The fouling extended down to the ADCP at 125 m, although it was minor at that
level.

All MicroCATs except one were in good condition and had their
antifoulant capsules. The MicroCAT SN 3617 at 7 m was recovered with a bent
conductivity sensor guard

After recovery and before stopping recording, a bag of ice was placed in
contact with each MicroCAT temperature sensor, to produce a spike in the data
as a reference point to check the instrument’s clock. The data from all
instruments were downloaded at UH. {numref}`table-8` has an initial
evaluation of the data quality; more details are in
{ref}`/5_section.md#microcat-data-processing-procedures`, and
{ref}`/6_section.md#microcat-data`.

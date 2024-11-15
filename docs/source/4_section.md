# WHOTS (18-19) Cruise Shipboard Observations

The hydrographic profile observations made during the WHOTS cruises were
obtained with a Sea-Bird CTD package with dual temperature, salinity, and
oxygen sensors. This CTD was installed on a rosette-sampler with 5 L Niskin
sampling bottles for calibration water samples. Furthermore, the ship Oscar
Sette came equipped with a thermosalinograph system that provided a continuous
depiction of the near-surface layer's temperature and salinity. Horizontal
currents over the depth range of 30-700 m were measured from the shipboard 75
kHz Ocean Surveyor (OS75) ADCP (narrowband) with a vertical resolution of 16m
for the WHOTS-18 and WHOTS-19 cruises. Broadband mode for the OS75 provided
additional current data over the range upper 200 m with a vertical resolution
of 8m.

Data gaps occurred when the system was shut down temporarily during
communications with the acoustic releases used for the moorings during both
cruises. Periods of missing data between 300 and 450 m in the broadband ADCP
were apparent due to the lack of scattering material in the water.

## Conductivity, Temperature, and Depth (CTD) Profiling

Continuous measurements of temperature, conductivity, dissolved oxygen, and
pressure were made with the UH Sea-Bird SBE-9/11Plus CTD underwater units
#1487 and #1506 during WHOTS-18 and WHOTS-19 cruises respectively. The CTD was
equipped with an internal Digiquartz pressure sensor and pairs of external
temperature, conductivity, and oxygen sensors.

Each temperature-conductivity sensor pair used a Sea-Bird TC duct, which
circulated seawater through independent pump and plumbing installations. The
CTD configuration also included two oxygen sensors, installed in the plumbing
for each sensor set. In both cruises, the CTD was mounted in a vertical
position in the lower part of a rosette sampler, with the sensors' water
intakes located at the bottom of the rosette.

The package was deployed on a conducting cable, which allowed for real-time
data acquisition and display. The deployment procedure consisted of lowering
the package to approximately 10 dbar and waiting until the CTD pumps started
operating. The CTD was then raised until the sensors were close to the surface
to begin the CTD cast. The time and position of each cast were obtained via a
GPS connection to the CTD deck box. Four salinity samples were taken on each
cast for calibration of the conductivity sensors.

### Data Acquisition and Processing

CTD data were acquired at the instrument's highest sampling rate of 24 samples
per second. Digital data were stored on a laptop computer, and, for redundancy,
the analog signal was recorded on a separate computer using a sound card and
Audacity (TM) software. Backups of CTD data were made onto USB storage cards.

The raw CTD data were quality controlled and screened for spikes described in
the WHOTS Data Report 1 {cite}`Santiago-Mandujano2007`. Data alignment,
averaging, correction, and reporting were done as described in
{cite}`Tupas1993`. Spikes in the data occur when the CTD samples the disturbed
water of its wake. Therefore, the downcast samples were rejected when the CTD
was moving upward or when its acceleration exceeded 0.5 m s-2 in magnitude. The
data were subsequently averaged into 2-dbar pressure bins after calibrating the
CTD conductivity with the bottle salinities.

The data were additionally screened by comparing the T-C sensor pairs. These
differences permitted the identification of problems with the sensors. The data
from only one T-C pair, whichever was deemed most reliable, is reported here.
Only data from the downcast are reported, as wake effects from the rosette
commonly contaminate upcast data.

Temperature is reported on the ITS-90 scale. Salinity and all derived units
were calculated using the UNESCO (1981) routines; salinity is reported in the
Practical Salinity(SA) scale (PSS-78). Oxygen is reported in umol/kg.

### CTD Sensor Calibration and Corrections

#### Pressure

The pressure calibration strategy for CTD pressure transducers #153702 and #154451
used during WHOTS-18 and WHOTS-19 cruises respectively employed a high-quality
quartz pressure transducer as a transfer standard. Periodic recalibrations of
this lab standard were performed with a primary pressure standard. The only
corrections applied to the CTD pressures were a constant offset determined when
the CTD first enters the water on each cast. Also, a span correction determined
from bench tests on the sensor against the transfer standard was applied. These
procedures and corrections are thoroughly documented in the HOT-2022 data
report {cite}`Fukieki2024`.

#### Temperature/Conductivity

Sea-Bird SBE-3-Plus temperature and SBE 4C conductivity transducers were used
during WHOTS-18 and -19 cruises. These sensors' history and performance have
been monitored during HOT cruises, and calibrations and drift corrections
applied during WHOTS cruises are thoroughly documented in the HOT-2022 data
report {cite}`Fukieki2024`.

#### Dissolved Oxygen

Sea-Bird SBE-43 oxygen sensors were used during the WHOTS-18 and -19 cruises.
There were no oxygen samples taken during the cruise to calibrate the CTD sensors.
The WHOTS-18 oxygen data were calibrated using calibration coefficients
obtained during the HOT-305 cruise, as this was the only available option since
these sensors had not been used previously. The HOT cruise CTD empirical calibration was
performed using oxygen water samples and the procedure from {cite}`Owens1985`.
See {cite}`Tupas1996` for details on these calibrations procedures. The oxygen
data from WHOTS-19 were calibrated using calibration coefficients obtained
during the HOT-343 cruise conducted on 15-22 August 2023, after the WHOTS-19
cruise, which used the same oxygen sensor.

## Water Sampling and Analysis

### Salinity

Salinity samples were collected by a rosette sampler during CTD casts at
selected depths during WHOTS-18 and -19, and then sub-sampled in 250 ml glass
bottles. The top of each bottle and thimble were thoroughly dried before being
tightly capped to prevent water from being trapped between the cap or thimble
and the bottle’s mouth. It has been observed that residual water trapped in
this way increases its salinity due to evaporation, and it can leak into the
sample when the bottle is opened for measuring. Samples from each cruise were
measured after the cruise in the UH laboratory using a Guildline Autosal 8400B
SN 73647 for WHOTS-18 and WHOTS-19. International Association for
Physical Sciences of the Ocean (IAPSO) standard seawater samples were measured
to standardize the Autosal, and samples from a large batch of “secondary
standard” (substandard) seawater were measured after every 24-48 samples to
detect drift in the Autosal. Standard deviations of the secondary standard
measurements were less than ± 0.001 for WHOTS-18 and -19 cruises
{numref}`table-11`.

The substandard water was collected by a rosette sampler from 1020 m at station
ALOHA during HOT cruises and drained into a 50-liter Nalgene plastic carboy. In
the laboratory, the water was then thoroughly mixed in a glass carboy for 20
minutes by manually shaking, rolling, and tilting the carboy vigorously, after
which a 2-inch protective layer of white oil was added on top to deter
evaporation. The substandard water was allowed to stand for approximately three
days before it was used and was stored in the same temperature-controlled room
as the Autosal, protecting it from the light with black plastic bags to inhibit
biological growth. Substandard seawater batch #72 was prepared on April 11-13,
2022, and it was used for WHOTS-18. The batch #74 was prepared on July 17-19,
2023, and it was used for WHOTS-19.

Samples from WHOTS-18 were measured on August 4, 2022, while samples from
WHOTS-19 were measured on August 29, 2023. {numref}`table-11` presents the
precision measurements of the secondary sub-standards. For more details about
the salinity measurements, please refer to [WHOTS-18 Salinity Measurements](https://www.soest.hawaii.edu/whots/proc_reports/wh18_salt_report.pdf)
and [WHOTS-19 Salinity Measurements](https://www.soest.hawaii.edu/whots/proc_reports/wh19_salt_report.pdf).

```{table} The precision of salinity measurements of secondary lab standards.
:class: sd-m-auto
:align: center
:name: table-11
|  **Cruise**  | **Mean Salinity +/- SD** | **# Samples** | **Substandard Batch** | **IAPSO Batch** |
| :----------: | :----------------------: | :-----------: | :-------------------: | :-------------: |
| **WHOTS-18** |     34.4930 ± 0.0005     |       3       |          72           |      P164       |
| **WHOTS-19** |     34.4954 ± 0.0004     |       5       |          74           |      P166       |
```

## Thermosalinograph Data Acquisition and Processing

### WHOTS-18 Cruise

Near-surface temperature and salinity data during the WHOTS-18 cruise were
acquired from the thermosalinograph (TSG) system installed on the NOAA Ship
Oscar Sette. The sensors were sampling water from the continuous seawater
system running through the ship. They comprised one thermosalinograph
model SBE-21 (SN 3168) and a micro-thermosalinograph model SBE-45 (SN 0290),
both with (internal) temperature and conductivity sensors located in the ship’s
chemistry lab, about 70 m from the hull intake; and an SBE-38 (SN 266) external
temperature sensor located at the entrance of the water intake. All instruments
recorded data every second. The water intake is located at the ship's bow,
forward from the starboard side bow thruster at a depth of 3 m. The system has
a flow meter in the chemistry lab, showing a flow rate of about 1.1
liters/minute during the cruise. Only the SBE-45 has a debubbler. Salinity
water samples were taken every 8 hours from the exhaust in the Chemistry lab
using 0.25-liter glass bottles, to be measured in the UH lab to correct any
drift in the thermosalinograph conductivities.

#### Temperature Calibration

External temperature data from the SBE-38 sensor (last calibrated at Sea-Bird
on December 7, 2020) were used to measure the seawater temperature. These
data were compared to the data collected during CTD casts.

#### Nominal Conductivity Calibration

Data from the SBE-45 conductivity and temperature sensors were used to
calculate the intake seawater salinity. These sensors were last calibrated at
Sea-Bird on December 7, 2020. All conductivity data from the thermosalinograph
were nominally calibrated with coefficients from this calibration. However, all
the final salinity data reported here were calibrated against bottle data, as
explained below.

#### Data Processing

Daily files containing navigation data recorded every second were concatenated
with the thermosalinograph data. The thermosalinograph data were then screened
for gross errors, with upper and lower bounds of 18°C and 35°C for
temperature and 3 and 6 Siemens/m for conductivity. There were 28 points
outside the valid temperature range and no points outside the valid
conductivity range.

A 5-point running median filter was used to detect one- or two-point
temperature and conductivity glitches in the thermosalinograph data. Glitches
in temperature and conductivity detected by the 5-point median filter were
immediately replaced by the median. Threshold values of 0.3°C for temperature
and 0.1 Siemens/m for conductivity were used for the median filter. After
running the filter, there were 332 internal temperature, 391 external
temperature, and 40 conductivity points replaced with the median.

A 3-point triangular running mean filter was used to smooth the temperature and
conductivity data after passing the glitch detection.

The thermosalinograph aboard the Ship Oscar Sette was set to record data every
second. Data were visually scanned to flag spikes likely caused by contamination due to
the introduction of bubbles to the flow-through system during transits or rough
conditions. Of 456,895 data points, 86,670 conductivity data points were
flagged as bad.

#### Bottle salinity and CTD Salinity Comparisons

The thermosalinograph salinity was calibrated by comparing it to bottle
salinity samples drawn from a water intake next to the thermosalinograph every
8 hours throughout the cruise. Of the twenty thermosalinograph bottles sampled,
bottle #8 was identified as a conductivity outlier and was discarded from the
analysis. Samples were analyzed as described in
{ref}`/4_section.md#water-sampling-and-analysis`. The comparison was made in
conductivity to eliminate the effects of temperature. The conductivity of each
bottle sample was computed using the salinity of the bottle, thermosalinograph
temperature, and a pressure of 10 dbar, which includes the pressure of the
flow-through system’s pump.

Salinity samples were drawn from the flow-through system, located less than 0.5
m from the SBE-45. Consequently, there should be virtually no delay between
when the water passes through the thermosalinograph and sampled. A 90-second
average centered on the sample draw time was chosen for processing purposes.

In order to make the comparison in conductivity units, the CTD conductivity was
calculated using the 4 dbar downcast CTD salinity, the internal
thermosalinograph temperature, and a pump pressure of 10 dbar. There were nine
CTD casts conducted during WHOTS-18 while the thermosalinograph was running.
Casts 4 and 8 were removed from the analysis as temperature and conductivity
outliers.

A cubic spline was fit to the time series of the differences between the bottle
and TSG conductivity, and a correction was obtained for the TSG conductivities.
Salinity was calculated using these corrected conductivities, the
thermosalinograph temperatures, and 10 dbar pressure. After applying
corrections, the mean difference between the bottle and thermosalinograph
salinities was -0.0001 psu with a standard deviation of 0.0033 psu. The mean
CTD - thermosalinograph difference was -0.0011 psu with a standard deviation
of 0.0040 psu.

#### CTD Temperature Comparisons

There were 9 CTD casts conducted during WHOTS-18, one of which was a test cast
offshore Honolulu (Station 20) and four at Station 52 (WHOTS-18), and four at
Station 50 (WHOTS-17), respectively.
The 3 dbar downcast CTD temperature data from those casts were used to compare
with the thermosalinograph data at the time of the casts. This comparison gives
an estimate of the quality of the thermosalinograph measurements.

Of the nine casts, casts #4 and 8 were identified as temperature outliers after
comparing them against the thermosalinograph data and removed from the
analysis. The mean difference between the CTD and the internal temperature
sensor was -0.1274°C, with a standard deviation of ± 0.0448°C.

### WHOTS-19 Cruise

Near-surface temperature and salinity data during the WHOTS-19 cruise were
acquired from the thermosalinograph (TSG) system installed on the NOAA Ship
Oscar Sette. The sensors were sampling water from the continuous seawater
system running through the ship, and comprised one thermosalinograph model
SBE-21 (SN 3168) and a micro-thermosalinograph model SBE-45 (SN 0290), both
with (internal) temperature and conductivity sensors located in the ship’s
chemistry lab, about 70 m from the hull intake; and an SBE-38 (SN 212)
external temperature sensor located at the entrance of the water intake. All
instruments recorded data every second. The water intake is located at the bow
of the ship, forward from the starboard side bow thruster at a depth of 3 m.
The system has a flow meter in the chemistry lab, showing a flow rate of about
1.1 liter/minute during the cruise. Only the SBE-45 has a debubbler. Salinity
water samples were taken every 8 hours from the exhaust in the Chemistry lab
using 0.25 litter glass bottles, to be measured in the UH lab to correct for
any drift in the thermosalinograph conductivities.

#### Temperature Calibration

External temperature data from the SBE-38 sensor (last calibrated at Sea-Bird
on December 8, 2022) were used to measure the seawater temperature. These
data were compared to the data collected during CTD casts.

#### Nominal Conductivity Calibration

Data from the SBE-45 conductivity and temperature sensors were used to
calculate the intake seawater salinity. These sensors were last calibrated at
Sea-Bird on November 11, 2020. All conductivity data from the thermosalinograph
were nominally calibrated with coefficients from this calibration. However, all
the final salinity data reported here were calibrated against bottle data, as
explained below.

#### Data Processing

Daily files containing navigation data recorded every second were concatenated
with the thermosalinograph data. The thermosalinograph data were then screened
for gross errors, with upper and lower bounds of 18°C and 35°C for
temperature and 3 and 6 Siemens m -1 for conductivity. There were 0 points
outside the valid temperature range and no points outside the valid
conductivity range.

A 5-point running median filter was used to detect one- or two-point
temperature and conductivity glitches in the thermosalinograph data. Glitches
in temperature and conductivity detected by the 5-point median filter were
immediately replaced by the median. Threshold values of 0.3°C for temperature
and 0.1 Siemens m-1 for conductivity were used for the median filter. After
running the filter, there were 0 internal temperature, 0 external
temperature, and 5 conductivity points replaced by the median. A 3-point
triangular running mean filter was used to smooth the temperature and
conductivity data after passing the glitch detection.

The thermosalinograph aboard the Ship Oscar Sette was set to record data every
second. Both thermosalinographs exhibited a number of conductivity and
temperature glitches due to air going into the plumbing.

Data were visually scanned to flag spikes likely caused by contamination due to
the introduction of bubbles to the flow-through system during transits or rough
conditions. Of 534647 data points, 11014 conductivity data points were
flagged as bad.

#### Bottle salinity and CTD Salinity Comparisons

The thermosalinograph salinity was calibrated by comparing it to bottle
salinity samples drawn from a water intake next to the thermosalinograph every
8 hours throughout the cruise. Of the twenty thermosalinograph bottles sampled,
no bottles were identified as a conductivity outlier. Samples were analyzed as
described in {ref}`/4_section.md#water-sampling-and-analysis`. The comparison
was made in conductivity to eliminate the effects of temperature. The
conductivity of each bottle sample was computed using the salinity of the
bottle, thermosalinograph temperature, and a pressure of 10 dbar, which
includes the pressure of the flow-through system’s pump.

Salinity samples were drawn from the flow-through system, located less than 0.5
m from the SBE-45. Consequently, there should be virtually no delay between
when the water passes through the thermosalinograph and sampled. A 90-second
average centered on the sample draw time was chosen for processing purposes.

In order to make the comparison in conductivity units, the CTD conductivity was
calculated using the 4 dbar downcast CTD salinity, the internal
thermosalinograph temperature, and a pump pressure of 10 dbar. There were five
CTD casts conducted during WHOTS-19 while the thermosalinograph was running. No
casts were removed from the analysis as temperature and conductivity outliers.

A cubic spline was fit to the time series of the differences between the bottle
and TSG conductivity, and a correction was obtained for the TSG conductivities.
Salinity was calculated using these corrected conductivities, the
thermosalinograph temperatures, and ten dbar pressure. After applying
corrections, the mean difference between the bottle and thermosalinograph
salinities was less than 1 mpsu with a standard deviation of 0.0044 psu. The
mean CTD - thermosalinograph difference was 0.0077 psu with a standard
deviation of 0.0150 psu.

#### CTD Temperature Comparisons

There were five CTD casts conducted during WHOTS-19, one of which was a test
cast offshore Honolulu (Station 20), and four at Station 52 (WHOTS-19). The 3
dbar downcast CTD temperature data from those casts were used to compare with
the thermosalinograph data at the time of the casts. This comparison gives an
estimate of the quality of the thermosalinograph measurements. Of the five
casts, none was identified as temperature outliers after comparing it against
the thermosalinograph data and removed from the analysis. The mean difference
between the CTD and the internal temperature sensor was -0.2114 °C, with a
standard deviation of ± 0.0183 °C.

## Shipboard ADCP

### WHOTS-18 Deployment Cruise

Currents were measured for the cruise duration over the depth range of 30-700 m
with a 75 kHz RDI Ocean Surveyor (OS75) ADCP working in narrowband mode with a
vertical resolution of 16 m and broadband mode with a vertical resolution of 8
m. The system yielded good data {cite}`Santiago-Mandujano2022`
during operations near the WHOTS-17 and WHOTS-18 moorings. The broadband system
only recorded good data in the upper 200 m. The times of the datasets from the
OS75 kHz are shown in {numref}`table-12`.

```{table} ADCP record times (UTC mm/dd/yy hh:mm:ss) for the Narrow Band 75 kHz ADCP during the WHOTS-18 cruise
:class: sd-m-auto
:align: center
:name: table-12
|    **WHOTS-18**    |    **OS75nb**     |    **OS75bb**     |
| :----------------: | :---------------: | :---------------: |
| File starting time | 07/22/22 23:24:47 | 07/22/22 23:24:47 |
|  File ending time  | 07/27/22 20:59:44 | 07/27/22 29:59:44 |

```

### WHOTS-19 Deployment Cruise

Currents were measured for the duration of the cruise over the depth range of
30-700 m with a 75 kHz RDI Ocean Surveyor (OS75) ADCP working in narrowband
mode with a vertical resolution of 16 m, and in broadband mode with vertical
resolution of 8 m. The system yielded good data (see
{cite}`Santiago-Mandujano2024`) during operations near the WHOTS-18 and
WHOTS-19 moorings. The broadband system only recorded good data in the upper
200 m. The times of the datasets from the OS75 kHz are shown in
{numref}`table-13`.

```{table} ADCP record times (UTC mm/dd/yy hh:mm:ss) for the Narrow Band 75 kHz ADCP during the WHOTS-19 cruise
:class: sd-m-auto
:align: center
:name: table-13
|    **WHOTS-19**    |    **OS75nb**     |    **OS75bb**     |
| :----------------: | :---------------: | :---------------: |
| File starting time | 06/16/23 02:12:16 | 06/16/23 02:12:16 |
|  File ending time  | 06/22/23 18:17:13 | 06/22/23 18:17:13 |
```

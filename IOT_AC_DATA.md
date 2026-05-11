# IoT-AC: calibration and fieldwork data

The results of a laboratory test and fieldwork on the Nea Kameni volcano (Santorini) for a fully operational [IoT-AC](https://github.com/giancarlotamburello/IoT-AC/tree/main) system are available [here](https://github.com/giancarlotamburello/IoT-AC/blob/main/iot_ac_calibration_fieldwork.xlsx).
The spreadsheet file contains three sheets (`Calibration_data`, `Calibration_raw_data`, `Nea_Kameni_data`):
* Sheet 1 (`Calibration_data`) contains calibration data, including simulated fluxes, the measured rate of CO<sub>2</sub> concentration change observed by the accumulation chamber, and the resulting recalculated measured fluxes.
* Sheet 2 (`Calibration_raw_data`) contains the raw CO<sub>2</sub> concentration time-series data for each individual measurement trial conducted during the calibration process.
* Sheet 3 (`Nea_Kameni_data`) contains diffuse flux data and geographic coordinates from fieldwork carried out at the Nea Kameni volcano in Santorini.

with the following fields:

* `Calibration_data`
  * CO<sub>2</sub> concentration	(% mol) -	CO<sub>2</sub> concentration of gas standard used for simulating the diffuse flux
  * Flux reading 1 (mL·min<sup>-1</sup>) -	Gas flux reading 1
  * Flux reading 2 (mL·min<sup>-1</sup>) -	Gas flux reading 2
  * Flux reading 3 (mL·min<sup>-1</sup>) -	Gas flux reading 3
  * Slope 1	(ppm·s<sup>-1</sup>) -	Measurement 1 of CO<sub>2</sub> concentration rate
  * Slope 2	(ppm·s<sup>-1</sup>) -	Measurement 2 of CO<sub>2</sub> concentration rate
  * Slope 3	(ppm·s<sup>-1</sup>) -	Measurement 3 of CO<sub>2</sub> concentration rate
  * Slope 4	(ppm·s<sup>-1</sup>) -	Measurement 4 of CO<sub>2</sub> concentration rate
  * Mean slope	(ppm·s<sup>-1</sup>) -	Average of the 4 measured CO<sub>2</sub> concentration rate
  * Diffuse flux	(g·m<sup>-2</sup>·d<sup>-1</sup>) -	Simulated diffuse flux calculated from concentration and average gas flux reading
  * Equation 1	(g·m<sup>-2</sup>·d<sup>-1</sup>) -	Recalculated diffuse flux using Equation 1
  * Equation 2	(g·m<sup>-2</sup>·d<sup>-1</sup>) -	Recalculated diffuse flux using Equation 2
* `Calibration_raw_data`
  * Timestamp	Number - Integer	-	Timestamp in milliseconds inside the AC during measurement
  * Date	-	Timestring inside the AC during measurement
  * CO<sub>2</sub> (ppm)	Number - CO<sub>2</sub> concentration inside the AC during measurement
  * Temperature (°C)	Boolean	-	Temperature inside the AC during measurement
  * Humidity (%)	- Relative humidity inside the AC during measurement
* `Nea_Kameni_data`
  * time	-	Timestring at the beginning of the measurement
  * longitude	-	Longitude in decimal degree WGS84 of the measurement
  * latitude	-	Latitude in decimal degree WGS84 of the measurement
  * elevation	(m) -	Elevation above sea level of the measurement
  * WS CO<sub>2</sub> rate	(ppm·s<sup>-1</sup>) -	Measurement of CO<sub>2</sub> concentration rate of the West System AC
  * WS CO<sub>2</sub> flux	(g·m<sup>-2</sup>·d<sup>-1</sup>) -	Calculated CO<sub>2</sub> diffuse flux using equation 2 for the West System AC
  * IoT-AC CO<sub>2</sub> rate	(ppm·s<sup>-1</sup>) -	Measurement of CO<sub>2</sub> concentration rate of the IoT-AC
  * IoT-AC CO<sub>2</sub> flux	(g·m<sup>-2</sup>·d<sup>-1</sup>) -	Calculated CO<sub>2</sub> diffuse flux using equation 2 for the IoT-AC

---

### 📥 [Download Dataset (xlsx)](https://github.com/giancarlotamburello/IoT-AC/raw/refs/heads/main/iot_ac_calibration_fieldwork.xlsx)

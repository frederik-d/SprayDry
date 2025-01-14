# SprayDry

<!-- Graphical Abstract -->
<br />
<p align="center">
  <a href="https://github.com/frederik-d/SprayDry">
    <img src="SprayDry_Graphical_Abstract.jpg" alt="Logo" width="707" height="272">
  </a>
</p>

<!-- About The Project -->
## About The Project

This repository was created to share code for the B290 Büchi Mini-Spray Dryer data acquisition framework employed in Doerr et al (2020).

⚠️ **Warning:** The introduction of micro-electronics inside the spray drying process might require special considerations regarding process safety. Working with aerosolized fine powders or organic solvents can create highly explosive atmospheres. The system has to be purged with an inert gas to reduce the oxygen concentration below the limiting oxygen concentration (LOC) to prevent ignition/combustion. Please conduct a full risk assessment for your application and carefully read the LICENSE agreement.

BME680 technical details: [https://www.bosch-sensortec.com/products/environmental-sensors/gas-sensors-bme680](https://www.bosch-sensortec.com/products/environmental-sensors/gas-sensors-bme680)

Code written by Frederik Doerr (@frederik-d), Sep-Nov 2018 (Python 2.7)  
Contact: frederik.doerr(at)strath.ac.uk / CMAC ([http://www.cmac.ac.uk/](http://www.cmac.ac.uk/))  

<!-- Reference-->
## Reference (open access):
Doerr, F., Burns, L., Lee, B., Hinds, J., Davis-Harrison, R., Frank, S., & Florence, A. (2020). *Peptide isolation via spray drying : particle formation, process design and implementation for the production of spray dried glucagon.* Pharmaceutical Research, 1–19. [https://doi.org/10.1007/s11095-020-02942-5](https://doi.org/10.1007/s11095-020-02942-5)

Data repository: [https://doi.org/10.15129/dcb859db-fe0d-4a56-b001-3f3d7ac6c44a](https://doi.org/10.15129/dcb859db-fe0d-4a56-b001-3f3d7ac6c44a)  

<!-- Files -->
## Files:
* BME680_SensorMount (folder) with BME680_SensorMount_S1 (design file for 3D printing BME680 Exhaust Gas Sensor Mount)  
* bme680_SprayDry (folder) with Arduino files for SPI communication. See wiring diagram in SprayDry_BME680_Fig. Additional details on Adafruit BME680 Breakout: https://www.adafruit.com/product/3660
* SprayDry_BME680_DataLogger.py: data collection from Arduino nano with connected Adafruit BME680 Breakout (Exhaust Gas Sensor, Publication Fig. 3 P9).
* SprayDry_RS232_DataLogger.py: data collection for B-290 Mini-Spray Dryer (Büchi Labortechnik, Switzerland, Publication Fig. 3 P3/P5).
* XS_RS232_DataLogger.py: data collection for XS60002S balance (Mettler Toledo, Switzerland, Publication Fig. 3 P11).  

### Note to viewers ###
The Python notebook files in this repo may be too large to view within github in a browser. Cloning this repo may be required for viewing the programming itself. Some example visualisations are shown below regardless.

### Example Data Visualisations ###
<details>
  <summary>Radial View of exoplanet position + size at 5000 Parsecs</summary>
  <br>
  ![5k Parsecs view](/img/5000ParsecsSize.png)
 </details>
 
 <details>
  <summary>Radial View of exoplanet position + size at 2000 Parsecs</summary>
  <br>
  ![2k Parsecs View](/img/2000ParsecsSize.png)
 </details>
 
 <details>
  <summary>View of exoplanets from surface of the Earth</summary>
  <br>
  ![Earth-view Location Projection](/LocationProjection.png)
  Notice the dense clump to the left of center. This is the data from the Keplar Mission, which we will isolate below.
 </details>
 
 <details>
  <summary>Zoom in on the Keplar Mission data</summary>
  <br>
  ![Keplar Mission Only](/img/KeplarZoomIn.png)
 </details>
 
 <details>
  <summary>One of many comparison we conducted to find correlations between features</summary>
  <br>
  ![PeriodVsOrbit + Planet Radius](/img/PeriodVsOrbit.png)
 </details>
 
 <details>
  <summary>Comparing discovered planets per system vs distance from Earth (sol)</summary>
  <br>
  ![PlanetCount per solar system vs Distance from Sol](/img/planetCountVsDistance.png)
 </details>
 
 <details>
  <summary>Multiple Linear Regression vs Deep Neural Network models</summary>
  <br>
  ![MLR vs DNN models](/img/MlrVsDnn.png)
 </details>








### Column Abbreviations ###
* sy_snum:        Number of Stars
* sy_pnum:        Number of Planets
* sy_mnum:        Number of Moons
* cb_flag:        Circumbinary Flag
* pl_orbper:      Orbital Period [days]
* pl_orbsmax:     Orbit Semi-Major Axis [au])
* pl_rade:        Planet Radius [Earth Radius]
* pl_bmasse:      Planet Mass or Mass*sin(i) [Earth Mass]
* pl_dens:        Planet Density [g/cm**3]
* pl_orbeccen:    Eccentricity
* pl_insol:       Insolation Flux [Earth Flux]
* pl_eqt:         Equilibrium Temperature [K]
* ttv_flag:       Data show Transit Timing Variations
* st_spectype:    Spectral Type
* st_teff:        Stellar Effective Temperature [K]
* st_rad:         Stellar Radius [Solar Radius]
* st_mass:        Stellar Mass [Solar mass]
* st_metratio:    Stellar Metallicity Ratio
* st_lum:         Stellar Luminosity [log(Solar)]
* st_logg:        Stellar Surface Gravity [log10(cm/s**2)]
* st_age:         Stellar Age [Gyr]
* st_rotp:        Stellar Rotational Period [days]
* glat:           Galactic Latitude [deg]
* glon:           Galactic Longitude [deg]
* sy_pmdec:       Proper Motion (Dec) [mas/yr]
* sy_dist:        Distance [pc]
* sy_plx:         Parallax [mas]
### 🔬 Aim
To Discover the features of our dataset that have influence over exoplanet discoverability.
### Credits
The dataset was produced by the NASA Exoplanet Archive http://exoplanetarchive.ipac.caltech.edu

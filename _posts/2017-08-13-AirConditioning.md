---
layout: post
title:  "Mech4880 Refregeration & Air Conditioning"
date:   2017-08-13
categories: Mechanical
---

This is based on thermodynamics.

## Air conditioning

Creation and mainteneouse of the following simulteneously:

- Temperature
- Humidity
- Air circulation
- Air purity

## Refrigeration

Industrilal process, 0℃ ~ -100℃ 

- Cryogenics 低温学

	temperature below -120℃ such as:
	
	- medical
	- LPG
	- LNG

---
# Psychrometry 空气线图，焓湿图
Psychrometry is the study of a mixture of air and fluid vapour. usually atmospheric. So, air is treated as a binary mixture.

- dry air
- water vapour

Assumptions:

- Vapour contains no dissolved gases
- The gaseous phases can be treated as a mixture of ideal gases.
- There is no interaction between the components and all components are at the mixture temperature.

### Psychrometric Properties

- V: volume of moist air
- p: pressure, taken as barometric usually, 101.325kPa
- T: temperature
- ma: mass of dry air
- mv: mass of water vapour

### Gibbs phase rule

How many components needs to define the systme:

> F=  n + 2 – p

> F = degrees of freedom

> n = number of components 

> p = number of phases

### Moisture Content

Also called: humidity ratio/ specific humidity/ absolute humidity:

The ratio of the mass of water vapour to the mass of dry air in a given volume of the mixture.

<img src='/images/moistureContent1.png'>

<img src='/images/moistureContent2.png'>

mass fraction: g = w/(1+w)

### Dew Point Temperature

saturation temperature at constant pressure. 饱和温度

<img src='/images/dewPointTemperature.png'>

According to [steam table](/resources/SteamTables.pdf), the partial pressure of water vapour under a certain temperature could be found.

### Percentage Saturation 饱和度
Degree of saturation, percetage humidity, μ

‘the ratio of the mass of water actually held per kilogram of dry air to the mass of saturated water vapour per kilogram of dry air at the same mixture temperature and pressure’.

<img src='/images/percentageSaturation.png'>

<img src='/images/percentageSaturation2.png'>

### Relative Humidity

RH, φ，

‘the ratio of the density of the water vapour at a given temperature
to the density of saturated water vapour at the same temperature’.

<img src='/images/relativeHumidity.png'>

<img src='/images/relativeHumidity2.png'>

### Specific Enthalpy

We are interested in the enthalpy per kilogram of dry air.

<img src='/images/specificEnthalpy.png'>

<img src='/images/specificEnthalpy1.png'>

<img src='/images/specificEnthalpy2.png'>

<img src='/images/specificEnthalpy3.png'>

<img src='/images/specificEnthalpy4.png'>

### Specific Volume

v: ‘the number of cubic metres of mixture per kilogram of dry air’.

<img src='/images/specificVolume.png'>

<img src='/images/specificVolume1.png'>

### Wet Bulb Temperature

Moist air is put through an adiabatic chamber, where heat is only transferred between spray water and air, the outlet air is saturated and the temperature is wet bulb temperature

<img src='/images/wetBulb.png'>

---
---
# Graphical Calculation of Properties of Moist Air

Two type of psychrometric chart: AIRAH and ASHRAE

The AIRAH chart is shown [here](/resources/airahpsychro.pdf)

---
# Psychrometric Processes

## Sensible Heating and Cooling

A sensible process is one where the state of moist air is altered along a constant moisture content line.

<img src='/images/sensibleHeatProcess.png'>

<img src='/images/sensibleHeatProcess1.png'>

## Latent Heat Process
Humidification and Dehumidification

This a a process of moist air altering along constant temperature line.

<img src='/images/latentHeatProcess.png'>

<img src='/images/latentHeatProcess1.png'>

## Adiabatic Saturation Process

During this process the thermodynamic wet bulb temperature (and for all practical purposes the web bulb temperature) remains constant.

The enthalpy also remains almost the same.

<img src='/images/adiabaticSaturationProcess.png'>

## Adiabatic Mixing Process

The process of mixing air streams under adiabatic condithions and steady flow.

<img src='/images/adiabaticMixingProcess.png'>

<img src='/images/adiabaticMixingProcess1.png'>

## Total Heating

This process contains both sensible and latent heating component.

<img src='/images/totalHeatProcess.PNG'>

**SHF**: Sensible Heat Factor

<img src='/images/SHF.PNG'>

<img src='/images/SHF1.PNG'>

The room load line is commonly get by using the SHF scale provided.

---
---
# Cooling Coil

## Process in the coil

<img src='/images/coolingCoil.PNG'>

## Apparatus Dew Point

## Coil contact factor and By-pass factor

Not all the air passing through the coil is cooled to the apparatus dew point temperature. So the outlet air condition is between the inlet point and ADP point.

<img src='/images/coilContactFactor.PNG'>

---
---
# Application









---
---
# Refrigerants

Absorb heat while undergoing phase change.

Ideal refregerant
- Moderately low condensing pressure
- Positive evaporating pressure
- Relatively high critical temperature
- Low freezing point
- High latent heat of evaporation
- Non falamable
- Non toxic
- Action of refregerant with water
- Action of refregerant with oil
- non-corrosive
- High dielectric strength
- High thermal conductivity
- Low viscosity
- Easily leak detection
- Cost

---
---
# Vapour Compression Refrigeration

## 1. The ideal cycle

## 2. Theoretical or standard vapour compression cycle

### work of compression

### expansion process

<img src='/images/theoreticalCycle.PNG'>






















---
---










































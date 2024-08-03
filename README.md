![Version](https://img.shields.io/static/v1?label=doe-emofat&message=0.3&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# Excel workbook to compute recipes for a series of cryo-solutions for the cryopreservation of protein crystals

## Purpose: 

This workbook removes the stress and hassle of computing the recipes for a series of cryo solutions with increasing concentrations of a cryo-agent.
These solutions are usually prepared when time is already limited, such as days or even hours before shipping the crystals to a synchrotron radiation lab.

## Scope:

- Useful for vapor diffusion, dialysis, batch, and serial dehydration experiments. 
- Supports solutions with 2 to 8 components other than water.
- Supports series up to 12 solutions in length.

## Background:

Some protein crystallization solutions are cryogenic, so crystals grown from these solutions can be transferred directly from the crystallization drop to the cold stream or liquid nitrogen.
The remaining crystallization solutions have to be displaced from the surface of the crystal with either oil or replaced with a solution containing a cryogenic agent.
In the case of the former, the crystals have to be mechanically strong enough to withstand the shear forces that the crystals experience during the displacement of the aqueous solution from their surfaces.
In the case of the latter, crystals can be quickly passed through this solution and then supercooled.
This technique often requires much trial and error and one may need to shoot 100 crystals before finding one that was successfully cryoprotected in this *dip and freeze* method.
The alternative to the *dip and freeze* method is to  expose the crystal to increasing concentrations of cryo agent.

This technique works when a favorable cryo agent is utilized.
The discovery of the favorable cryo agent requires testing 4 or more alternatives.
Each cryoagent requires its own concentration series.
The labor of planning and making these concentration series inhibits their use.
The workbook in this repository supports the generation of the series of trial solutions required for this last technique by dramatically speeding up the planning of the solutions.
The workbook reduces the labor from a few hours to a few minutes.

## Features:

- Grayscale highlights the cells that require entry of metadata and parameter names and values. A worksheet can be completed in less than 5 minutes.
- Generates twelve recipes in a series of increasing cryoagent concentrations.
- Vertical format eases taping into a laboratory notebook.
- No use of color below grayscale to minimize printing cost

## Comming soon:

A variant to support use with liquid handling robot.

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)

## Update history

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |   Added badges, funding, and update table.                                                                                                 | 2024 August 2         |
| Version 0.3 |   Expanded the explanation of the project in the README.md                                                                                 | 2024 August 3         |

# Supply Chain Greenhouse Gas Emission Factors v1.3 by NAICS-6
## Overview
This dataset provides comprehensive greenhouse gas (GHG) emission factors for 1,016 U.S. commodities classified according to the 2017 North American Industry Classification System (NAICS) at the 6-digit level. The emission factors are based on data from the year 2022.

## Dataset Description
- Commodities Covered: All NAICS 6-digit level commodities except electricity, government, and households.
- Emission Factors Types:
    - Supply Chain Emissions without Margins (SEF): Emissions attributable to the supply chain excluding margin effects.
    - Margins of Supply Chain Emissions (MEF): Emissions associated with supply chain margins.
    - Supply Chain Emissions with Margins (SEF+MEF): Combined emissions including both supply chain and margins

## Units and Calculations
- Emission factors are expressed as kilograms of carbon dioxide equivalents (kg CO2e) per 2022 U.S. dollar (USD) spent, using purchaser prices.
- CO2e values are calculated based on all GHGs combined, applying the 100-year global warming potentials from the IPCC Fifth Assessment Report (AR5).
- In addition to CO2e factors, the dataset includes kg of each individual GHG emitted per 2022 USD per commodity, without aggregating to CO2e.

## Data Structure
Each record corresponds to a unique commodity identified by its 6-digit NAICS code and contains the following factor types:
| Factor Type | Description                              |
| ----------- | ---------------------------------------- |
| SEF         | Supply Chain Emissions without Margins   |
| MEF         | Margins of Supply Chain Emissions        |
| SEF + MEF   | Supply Chain Emissions including Margins |

## Additional Information
- The dollar amounts used in the denominator represent purchaser prices for the respective commodities.
- The dataset excludes electricity, government, and household sectors due to data constraints.

## Citation
Supply Chain Greenhouse Gas Emission Factors v1.3 by NAICS-6, Metadata Updated July 10, 2024.

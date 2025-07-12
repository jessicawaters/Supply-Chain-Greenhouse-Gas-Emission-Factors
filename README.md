# Supply Chain Greenhouse Gas Emission Factors v1.3 by NAICS-6
## Overview
This dataset shows how much greenhouse gas (GHG) pollution is created when people spend money on different products and services in the U.S. It’s organized using 6-digit industry codes from the 2017 NAICS (North American Industry Classification System).

The data is based on emissions from the year 2022 and includes 1,016 commodities (except for electricity, government, and household services, which are not included).

## Dataset Description
Each row represents a product or service and shows how much pollution is generated for every $1 spent on it. The pollution is measured in kilograms of CO₂-equivalent (kg CO₂e) — this combines all greenhouse gases into one number so they’re easier to compare.

You’ll see three types of emission values for each product:
| Factor Type                                      | Description                                                              |
| ------------------------------------------------ | ------------------------------------------------------------------------ |
| **SEF** (Supply Chain Emissions without Margins) | Pollution from producing and transporting the product only               |
| **MEF** (Margins of Emissions)                   | Pollution from additional costs like **retail, wholesale, and delivery** |
| **SEF + MEF**                                    | The total pollution: production **plus** margin emissions                |

## Units and Calculations
- All emissions are reported as kg of CO₂e per $1 (2022 USD) spent.

- The emissions use purchaser prices — what buyers actually pay.

- CO₂e values are calculated using global warming potentials from the IPCC’s 5th report (AR5), looking at impact over 100 years.

## Data Structure
| Column Name        | What It Means                                   |
| ------------------ | ----------------------------------------------- |
| `2017 NAICS Code`  | Unique 6-digit code for each product or service |
| `2017 NAICS Title` | Name of the product or service                  |
| `SEF`              | Emissions from the supply chain only            |
| `MEF`              | Emissions from retail/wholesale/delivery        |
| `SEF + MEF`        | Total emissions (SEF + MEF)                     |

## Additional Information
- The dataset excludes electricity, government, and household sectors due to data constraints.

## Citation
Supply Chain Greenhouse Gas Emission Factors v1.3 by NAICS-6, Metadata Updated July 10, 2024.

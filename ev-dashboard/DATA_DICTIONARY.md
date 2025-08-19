# EV Dataset Data Dictionary

This document describes the fields available in the EV dataset.

---

## Table of Columns

| Column Name | Description |
|-------------|-------------|
| **VIN (1-10)** | First 10 characters of the Vehicle Identification Number (VIN), a unique vehicle identifier. |
| **County** | County where the vehicle is registered. |
| **City** | City where the vehicle is registered. |
| **State** | U.S. state where the vehicle is registered. |
| **Postal Code** | ZIP code of the registration address. |
| **Model Year** | Year the vehicle model was manufactured. |
| **Make** | Vehicle manufacturer/brand (e.g., Tesla, Nissan, Ford). |
| **Model** | Vehicle model name (e.g., Leaf, Model 3, Mustang Mach-E). |
| **Electric Vehicle Type** | Battery Electric Vehicle (BEV) or Plug-in Hybrid Electric Vehicle (PHEV). |
| **Clean Alternative Fuel Vehicle (CAFV) Eligibility** | Whether the vehicle qualifies as a Clean Alternative Fuel Vehicle under state/federal programs. |
| **Electric Range** | EPA-rated all-electric range (in miles) for a full charge. |
| **Base MSRP** | Manufacturer’s Suggested Retail Price (USD) for the base trim level. |
| **Legislative District** | State legislative district where the vehicle is registered. |
| **DOL Vehicle ID** | Unique identifier assigned by the Department of Licensing (DOL). |
| **Vehicle Location** | Geographic location (latitude/longitude or mapped address) of registration. |
| **Electric Utility** | Utility company providing electricity to the registered address. |
| **2020 Census Tract** | Census tract number (from the 2020 Census) for the registration address, useful for demographic analysis. |

---

## Notes
- Some fields may contain missing values depending on availability. 

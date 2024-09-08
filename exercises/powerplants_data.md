# Life Cycle Assessment (LCA) Exercise: Modeling the Life Cycle of Electricity Generation

## Objective

In this exercise, you will model the life cycle impacts of five different 
power plants to represent, in a simplified way, the supply of grid electricity.
The power plants considered are:

1. Wind Turbine Power Plant (Onshore)
2. Solar PV Power Plant
3. Coal Power Plant
4. Natural Gas Power Plant
5. Hydropower Plant

For this, you will consider the following phases:
- Manufacture of the power plant
- Operation over the lifetime of the power plant

You will be given the necessary inputs and outputs for each power plant 
based on its total capacity, annual production, and expected lifetime.

---

## Power Plant Data – Manufacture and Direct Emissions During Operation

### 1. Wind Turbine Power Plant (Onshore)
- **Total Capacity:** 300 MW (100 turbines of 3 MW each)
- **Lifetime:** 25 years
- **Annual Production:** 900,000,000 kWh/year (Capacity factor: 30%)

#### Manufacture Inputs
- Steel: 24,000 tons
- Concrete: 120,000 tons
- Copper: 1,500 tons
- Fiberglass (blades): 3,000 tons
- Rare earth metals (neodymium): 30 tons
- Electricity consumption for manufacturing: 4,500 MWh

#### Manufacture Outputs
- Waste material (concrete): 120,000 tons
- Waste material (fiberglass): 3,000 tons

#### Operation Inputs
- Maintenance: 0.1% of total turbine mass annually

#### Operation Outputs (Direct Emissions)
- CO2 emissions: 0 g/kWh (no direct emissions during operation)

---

### 2. Solar PV Power Plant
- **Total Capacity:** 100 MW
- **Lifetime:** 25 years
- **Annual Production:** 150,000,000 kWh/year (Capacity factor: 17%)

#### Manufacture Inputs
- Silicon: 5,000 tons
- Glass: 10,000 tons
- Aluminum: 2,000 tons
- Silver: 100 tons
- Electricity consumption for manufacturing: 50,000 MWh

#### Operation Inputs
- Cleaning water: 0.001 L/kWh

#### Operation Outputs (Direct Emissions)
- CO2 emissions: 0 g/kWh (no direct emissions during operation)
- Waste (maintenance): negligible

---

### 3. Coal Power Plant
- **Total Capacity:** 500 MW
- **Lifetime:** 40 years
- **Annual Production:** 3,500,000,000 kWh/year (Capacity factor: 80%)

#### Manufacture Inputs
- Steel: 100,000 tons
- Concrete: 250,000 tons
- Copper: 1,000 tons
- Electricity consumption for manufacturing: 10,000 MWh

#### Manufacture Outputs
- Waste material (concrete): 250,000 tons

#### Operation Inputs
- Coal consumption: 0.3 kg/kWh
- Water consumption: 2.5 L/kWh

#### Operation Outputs (Direct Emissions)
- CO2 emissions: 820 g/kWh (from coal combustion)

---

### 4. Natural Gas Power Plant
- **Total Capacity:** 500 MW
- **Lifetime:** 30 years
- **Annual Production:** 3,500,000,000 kWh/year (Capacity factor: 80%)

#### Manufacture Inputs
- Steel: 50,000 tons
- Concrete: 200,000 tons
- Copper: 1,500 tons
- Electricity consumption for manufacturing: 10,000 MWh

#### Manufacture Outputs
- Waste material (Concrete): 200,000 tons

#### Operation Inputs
- Natural gas consumption: 0.15 m³/kWh
- Water consumption: 1.2 L/kWh

#### Operation Outputs (Direct Emissions)
- CO2 emissions: 450 g/kWh (from natural gas combustion)

---

### 5. Hydropower Plant
- **Total Capacity:** 1,000 MW
- **Lifetime:** 50 years
- **Annual Production:** 4,380,000,000 kWh/year (Capacity factor: 50%)

#### Manufacture Inputs
- Steel: 300,000 tons
- Concrete: 1,000,000 tons
- Copper: 10,000 tons
- Electricity consumption for manufacturing: 30,000 MWh

#### Manufacture Outputs
- Waste material (Concrete): 1,000,000 tons

#### Operation Inputs
- Maintenance: 0.01% of total dam material annually
- Water for turbine operation: continuous
- Land use: 500 hectares (due to reservoir)

#### Operation Outputs (Direct Emissions)
- CH4 emissions: 2 g/kWh (due to methane emissions from reservoir)
- Water evaporation: 2 L/kWh

---

## Summary: Direct Emissions for Each Power Plant During Operation

| Power Plant Type | CO2 Emissions (g/kWh) | SOx & NOx (g/kWh) | Other Emissions |
|------------------|------------------------|--------------------|-----------------|
| Wind Turbine      | 0                      | 0                  | Waste: 0.5 g/kWh |
| Solar PV          | 0                      | 0                  | Negligible      |
| Coal              | 820                    | 0.05               | Ash: 0.03 kg/kWh |
| Natural Gas       | 450                    | 0.03               | Water vapor: 0.9 L/kWh |
| Hydropower        | 2                      | 0                  | Water evaporation: 2 L/kWh |

---

## Current grid electricity mix

- Coal: 40%
- Natural Gas: 30%
- Hydropower: 20%
- Wind: 5%
- Solar: 5%

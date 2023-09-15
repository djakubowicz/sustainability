# sustainability

Here is the order to deploy sustainabilityV2 dashboards : 

Create Custom Groups-> Group Types

    One for Applications, named “Application”
    One for Business Units, named “Business Unit”
Create Custom Groups

    One for each App
    One for each Business_Unit
    One for each group of Datacenters with the same PUE/CarbonIntensityFactor, named “DatacenterCarbonIntensity” and “DatacenterPUE”
      Will Add the PUE/CI as custom properties on the datacenters
  Note : Don’t forget to check the “keep group membership up to date” option

Add Supermetrics in this order to avoid naming issue : 

    VMPowerUsageCorrected
    ESXiPowerUsageAlone
    VMESXiPowerUsageAlone
    VMTotalPowerUsage
    PowerForVMs
    Scope2VMCO2
    Scope3VMCO2
    VMTotalCO2
    CO2EmissionsForVMs

Add Views
Add Dashboards

Enjoy and give feedback :)

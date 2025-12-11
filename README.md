# Elderly population projections in South-West Finland

**This webmap was created as MAAN7771 course work by Anna Dust, Minna Palm, Emil Taskinen and Tuomo Kähärä.**

The map depicts how demographic change will affect access to health care services across municipalities. By comparing the elderly population in 2024 with projected changes in 2045, users can identify regions where health care demand may exceed capacity and where service gaps or pressure areas are likely to emerge. The solution responded to challenge provided by Lounaistieto.

Eplore the map: [https://utu-geospatial-labs.github.io/2025-webmap-archipelagis/](https://utu-geospatial-labs.github.io/2025-webmap-archipelagis/)


## Additional information

This web map visualizes how demographic change will affect access to health care services across municipalities. By comparing the elderly population in 2024 with projected changes in 2045, users can identify regions where health care demand may exceed capacity and where service gaps or pressure areas are likely to emerge. The map supports evidence-based planning for resilient health systems by helping to locate underserved areas, visualize demographic pressure, and anticipate future mismatches between an aging population and health care capacity.

The map supports planners and policymakers in integrating demographic forecasts into long-term urban and health infrastructure strategies.

Two main layers enable comparison over time:

- 2024 Layer: Shows the current share of elderly people in each municipality - helping urban planners understand today’s spatial distribution of aging populations and existing health care access.
- 2045 Layer: Displays the percentage increase or decrease of elderly residents, highlighting future hotspots of demographic pressure and areas where demand for care services is expected to grow most.



Another dataset shows the location of health care services, divided into:
- Hospitals
- Municipal Health Centers
- Private Medical Services


Together, these layers allow users to:
- Locate underserved areas or regions where population aging will likely outpace current health care capacity,
- Support planning for new facilities or service expansions,
- Prioritize mobility and infrastructure improvements for older adults, and
- Monitor spatial equity in access to health care across municipalities.



**"paavo_2024"**
Folder includes the "paavo_sw_f_2024.shp" file.
Attribute description:

- area = total area of the municipality
- mun_code = municipality code
- 65_69 = 65-69 years old population (the rest of the age groups have similar logic)
- elderly = paavo pt_elakel attribute renamed, refers to pensioners (those who receive pension)
- mun = municipality name



**"paavo_2045"**
Folder includes the "paavo_sw_f_2045.shp" file.
- area = total area of the municipality
- mun_code = municipality code
- 65_69 = 65-69 years old population (the rest of the age groups have similar logic)
- elderly = paavo pt_elakel attribute renamed, refers to pensioners (those who receive pension)
- mun = municipality name
- 2045_total = total population (all age groups)
- 2045_65-74 = estimated population of 65-74 years old in 2045
- 2045_75- = estimated population of over 75 years old in 2045 

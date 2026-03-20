# Mexico Crime Map Analysis

Geospatial analysis of crime incidents across major roads in Mexico using Python.

## Objective

To visualize and analyze the distribution of crimes across main transportation routes in Mexico.

## 📊 Data

The dataset contains crime records associated with major roads.


## Tools & Libraries

- Python
- Pandas
- Geopandas
- Plotly
- Matplotlib

## Methodology

1. Data cleaning and preprocessing
2. Filtering relevant incidents
3. Geospatial mapping
4. Visualization of crime density

## Results

![Crime distribution map showing assault incidents across major Mexican highways with density heat mapping and geographical markers indicating hotspot locations along transportation routes](Images/Mapa%20Mexico%20asaltos.png)

Interactive version: 
[Open interactive map](Interactive/mexico_2025.html)


## Conclusions

### Implications

- This analysis provides a practical tool for decision-making in logistics and transportation, enabling companies to evaluate safer routing alternatives.
- It supports trade-offs between cost (time and fuel) and risk exposure, allowing for more informed route planning.
- The dataset focuses specifically on highway-related incidents, making it particularly relevant for logistics, delivery operations, and supply chain security.
- The insights can be used to assess risk levels when transporting high-value goods, helping organizations design safer distribution strategies.

### Limitations

- This geospatial analysis does not include time series modeling, although it aggregates incidents throughout 2025.
- Seasonal patterns (daily, weekly, or monthly variations) are not considered.
- The analysis is limited to major highways due to data density and processing constraints, potentially excluding secondary or rural routes.

### Future Work

- Incorporate temporal analysis to identify patterns by time of day, day of the week, or seasonality, enabling more precise risk assessment.
- Integrate near real-time or periodically updated datasets to maintain current risk evaluations.
- Expand coverage to include secondary roads and additional geographic layers for a more comprehensive analysis.

## Sources

- Roads of México
https://www.inegi.org.mx/temas/viascomunicacion/

- Crime incidence of México
https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva

## Author

Omar Sanvicente
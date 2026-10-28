# FIT3179 Data Visualisation 2
**Author:** Nicole Tan 
**Date:** October 2026  

---

## 1. Domain, Why, and Who
* **Domain:**  Australian agricultural productivity, focusing on productivity growth across farming sectors, regional differences, technological innovation, climate variability and economies of scale.
* **Who:** The target audience is the general Australian public, particularly people interested in food production, the economy and environmental sustainability. 
* **Why:** Agriculture is important to Australia's economy, food supply and export industry. However, increased agricultural production does not necessarily mean improved productivity, as it may also result from greater resource use. This visualisation investigates how efficiently Australian farms convert inputs such as land, labour, machinery and fertiliser into agricultural outputs. It aims to explain why productivity growth differs between farming sectors and how innovation, climate conditions, research and development (R&D), and farm size contribute to long-term efficiency improvements.

## 2. What: The Data Sources
DFAT (Agricultural Trade and the WTO): Authored by the Australian Government Department of Foreign Affairs and Trade. Supplies bilateral export shipment volumes, trade values, and tariff concessions across primary Indo-Pacific, North American, European, and Middle Eastern corridors, grounding Australia's trade-exposed commercial model.

ABARES (2025) (Australian Farm Productivity: Broadacre and Dairy Estimates): Authored by the Australian Bureau of Agricultural and Resource Economics and Sciences. Provides the macroeconomic productivity wedge, showing that Australian agricultural output expanded by over 80% while aggregate inputs remained essentially flat.

ABARES (Productivity Drivers, Climate-Adjusted TFP & Rural R&D Investment): Establishes the empirical link between high-return R&D adoption (benefit-cost ratios up to 11:1) and underlying productivity growth, separating climatic drag from technological advancement.

ABARES (Disaggregating Farm Performance Statistics by Size): Underpins the microeconomic scale analysis, detailing how top commercial farm tiers (>$1M–$5M+) produce the majority of national output at ~55% cost-to-output ratios compared to ~96% for small holdings.

ABS (Value of Agricultural Commodities Produced): Authored by the Australian Bureau of Statistics. Supplies high-resolution spatial and sectoral financial data across beef, wheat, dairy, sheep, and horticulture across Australian states and territories.

USDA ERS & OECD (2025) (International Agricultural Productivity & Policy Monitoring): Standardises international productivity comparisons, proving that Australia's 1.52% p.a. TFP growth was achieved with the OECD's second-lowest subsidy level (PSE 2.4%).

## 3. How: Rationale for the Idioms
1. Choropleth Map: Uses colour to encode state-level Gross Value of Agricultural Production (GVAP, A$ billion) or annual Total Factor Productivity (TFP) growth (%). An interactive metric selector allows users to switch between economic output and productivity efficiency, revealing how the states with the highest production value differ from those with the fastest productivity growth.

2. Proportional Symbol Map: Displays 15 major regional agricultural production hubs using circles whose area represents production value and whose colour identifies the dominant farming sector. An interactive sector filter helps users locate major production centres and compare the geographical distribution of different agricultural industries.

3. Choropleth Map: Uses an equal-area projection to compare cumulative agricultural TFP growth with government subsidy levels across countries. Hover-based tooltips reveal country-level values, helping users understand Australia's productivity performance in an international context and compare its relatively low agricultural support with that of other countries.

4. Connected Dot Plot (Dumbbell Chart): Compares 2024 input and output volume indices across six farming sectors. Contrasting coloured endpoints and a connecting line make the gap between resource use and production immediately visible, helping users identify sectors that produce more output relative to their inputs.

5. Streamgraph: Displays changes in the real gross value of six major commodity groups from 1985 to 2025. The flowing, stacked areas reveal long-term growth and shifts in the composition of agricultural production, allowing users to see how the relative contributions of grains, livestock, horticulture and oilseeds have changed over four decades.

6. Bump Chart: Tracks changes in the national production-value rankings of agricultural commodities from 1985 to 2025. Connected ranking lines make changes in relative position easy to follow, highlighting the decline of wool and sheepmeat and the rise of commodities such as wheat, beef and canola.

7. Annotated Multi-Line Chart with Drought Shock Bands: Contrasts observed broadacre TFP with climate-adjusted TFP from 1980 to 2024. Shaded bands identify major drought periods, while separate lines distinguish short-term fluctuations from the underlying productivity trend. This helps users understand how climatic variability affects observed performance and why productivity trends should be interpreted alongside weather conditions.

8. Heatmap: Uses a state-by-year matrix to encode climate-related TFP deviations through a diverging red–yellow–green colour scale. This enables users to scan across states within a single drought year and identify systemic eastern-state synchronicity versus Western Australia’s counter-cyclical winter-rainfall regime and Tasmania’s low climatic exposure.

9. Lollipop Chart: Represents annual TFP growth by horizontal stem length and R&D intensity by circle size. The combination allows users to compare productivity growth with research investment and its reported returns, highlighting differences between agricultural sectors and the potential contribution of research and development to long-term efficiency.

10. Slope Chart: Compares national agricultural output shares across four farm-size tiers between the 1990s and 2020s. The two endpoints and connecting lines emphasise changes over time, particularly the increase in the largest 10% of farms' share from 44% to 69.5%. This helps users understand the growing concentration of agricultural output among larger farms.

11. Butterfly Chart (Diverging Bar Chart): Places cost-to-output ratios on the left and rates of return on capital on the right for six farm-turnover classes. The mirrored layout facilitates direct comparisons between operating costs and financial returns, helping users examine economies of scale and understand how farm size relates to cost efficiency and profitability.

12. Flow Map: Uses radial flows to connect Australia with eight primary international agricultural trading hubs on an Equal-Earth Pacific-centred projection. Line thickness represents export value, while colour distinguishes destination trade corridors. Hover interactions reveal details about individual destinations. This map connects domestic productivity with international markets, showing how Australia's agricultural production supports exports and where its major trading relationships are concentrated.

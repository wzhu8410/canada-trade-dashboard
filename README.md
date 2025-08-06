# Canada Trade Dashboard (Power BI)

This Power BI dashboard explores Canadian imports and exports with the U.S. by **province**, **year**, and **goods/services**, from 2014–2024. It includes interactive features like:

- **Dynamic slicers** for Province, Year, Goods Type, and Trade Type
- A filled map of Canada with hover tooltips
- Custom cards showing **net trade values** with color-coding

## Preview

![Dashboard Demo](demo.gif)

## Files
- `trade.pbix`: Power BI file
- `trade.pdf`: Exported PDF version
- `demo.jif`: Gif demo of the dashboard

## Tools Used
- Power BI Desktop
- DAX for custom measures

## Key Insights
- Certain provinces like Alberta show consistent trade surpluses, while others like Ontario have trade deficits. 
- British Columbia exports forestry products and imports consumer goods heavily, which may be impacted the most by tariffs. 
- Net trade value trends highlight economic events (e.g., noticeable shifts around 2020).
- Alberta leads in energy product export, and imports mostly industrial products as well.
- Canada has overall trade surplus with the U.S., and a unilateral tariff from the U.S. is likely to impact the energy export of Canada the most. 

## Questions Answered
- How has net trade evolved by province and year?
- Which provinces contribute most to Canada’s total exports and imports?
- How is trade distributed between goods and services?
- Which years or regions experienced the largest trade shifts?
- What is the current net trade value for a selected province?

## Limitations
- Map cannot zoom out to full Canada view when "Canada" is selected.
- Dataset may not include the most recent trade year (e.g., post-2024 data).

## License
This project is for educational and demonstration purposes only. Data is from Statistics Canada.

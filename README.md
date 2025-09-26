# Pizza Place Sales Analysis

This project analyzes one year of sales data from a fictitious pizza place.  
The dataset comes from the file **Pizza+Place+Sales.zip**, which contains four CSV files:  
- `orders.csv`  
- `order_details.csv`  
- `pizzas.csv`  
- `pizza_types.csv`  
- `data_dictionary.csv` (describes the schema)

## Key Insights

- **Total revenue:** $817,860.05  
- **Total quantity sold:** 49,574  
- **Total orders:** 21,350  
- **Number of pizza types:** 32  
- **Average pizza price:** $16.49  
- **Peak sales hour:** 12:00 (noon)  
- **Best day of the week (by revenue):** Friday  

### Top 5 Bestselling Pizzas (by quantity sold)
1. The Classic Deluxe Pizza — 2,453  
2. The Barbecue Chicken Pizza — 2,432  
3. The Hawaiian Pizza — 2,422  
4. The Pepperoni Pizza — 2,418  
5. The Thai Chicken Pizza — 2,371  

## Visualizations
The analysis notebook generates plots stored in the `pizza_plots/` folder:
- Revenue by hour  
- Revenue by weekday  
- Revenue by month  
- Top 5 pizzas  

## Repository Structure
```
├── Pizza_Place_Sales_analysis.ipynb   # Main Jupyter notebook with analysis
├── pizza_plots/                       # Visualizations (PNG)
├── data/                              # Original CSV datasets
├── README.md                          # Project overview and results summary
```

## How to Run
1. Clone this repository.  
2. Open `Pizza_Place_Sales_analysis.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.  
3. Run the cells to reproduce the analysis.  

## Next Steps
- Explore daily/weekly trends further.  
- Build a dashboard for interactive sales analysis.  
- Identify underperforming pizza types to optimize the menu.  

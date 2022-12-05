# Python Homework
Unit 2 Assignment by Juil Yoon

## PyBank

Take file of PNLs, calculate and output PNL, average PNL change, biggest increase in PNL, and biggest decrease in PNL.

**Python JupyterLab File:** [PyBank/main.ipynb](PyBank/main.ipynb)

**Data File:** [PyBank/resources/budget_data.csv](PyBank/resources/budget_data.csv)

### Expected Output

	Financial Analysis
	----------------------------
	Total Months: 86
	Total: $38382578
	Average  Change: $-2315.12
	Greatest Increase in Profits: Feb-2012 ($1926159)
	Greatest Decrease in Profits: Sep-2013 ($-2196167)

### Final Output

	Financial Analysis
	------------------------------
	Total Months: 86
	Total: $38,382,578.00
	Average Change: $-2,315.12
	Greatest Increase in Profits: Feb-2012 ($1,926,159.00)
	Greatest Decrease in Profits: Sep-2013 ($-2,196,167.00)

[analysis.txt](PyBank/analysis.txt)

### Notes

- Added commas and 2 decimal places for currency display

## PyRamen

Take menu and sales data and calculate overall profit frome sales.

**Python JupyterLab File:** [PyRamen/main.ipynb](PyRamen/main.ipynb)

**Data File:** 
- [PyRamen/resources/menu_data.csv](PyRamen/resources/menu_data.csv)
- [PyRamen/resources/sales_data.csv](PyRamen/resources/sales_data.csv)

### Expected Output

```
spicy miso ramen {'01-count': 9238, '02-revenue': 110856.0, '03-cogs': 46190.0, '04-profit': 64666.0}
tori paitan ramen {'01-count': 9156, '02-revenue': 119028.0, '03-cogs': 54936.0, '04-profit': 64092.0}
truffle butter ramen {'01-count': 8982, '02-revenue': 125748.0, '03-cogs': 62874.0, '04-profit': 62874.0}
tonkotsu ramen {'01-count': 9288, '02-revenue': 120744.0, '03-cogs': 55728.0, '04-profit': 65016.0}
vegetarian spicy miso {'01-count': 9216, '02-revenue': 110592.0, '03-cogs': 46080.0, '04-profit': 64512.0}
shio ramen {'01-count': 9180, '02-revenue': 100980.0, '03-cogs': 45900.0, '04-profit': 55080.0}
miso crab ramen {'01-count': 8890, '02-revenue': 106680.0, '03-cogs': 53340.0, '04-profit': 53340.0}
nagomi shoyu {'01-count': 9132, '02-revenue': 100452.0, '03-cogs': 45660.0, '04-profit': 54792.0}
soft-shell miso crab ramen {'01-count': 9130, '02-revenue': 127820.0, '03-cogs': 63910.0, '04-profit': 63910.0}
burnt garlic tonkotsu ramen {'01-count': 9070, '02-revenue': 126980.0, '03-cogs': 54420.0, '04-profit': 72560.0}
vegetarian curry + king trumpet mushroom ramen {'01-count': 8824, '02-revenue': 114712.0, '03-cogs': 61768.0, '04-profit': 52944.0}
```

### Final Output

```
spicy miso ramen {'01-count': 9240, '02-revenue': 110880.0, '03-cogs': 46200.0, '04-profit': 64680.0}
tori paitan ramen {'01-count': 9157, '02-revenue': 119041.0, '03-cogs': 54942.0, '04-profit': 64099.0}
truffle butter ramen {'01-count': 8983, '02-revenue': 125762.0, '03-cogs': 62881.0, '04-profit': 62881.0}
tonkotsu ramen {'01-count': 9292, '02-revenue': 120796.0, '03-cogs': 55752.0, '04-profit': 65044.0}
vegetarian spicy miso {'01-count': 9217, '02-revenue': 110604.0, '03-cogs': 46085.0, '04-profit': 64519.0}
shio ramen {'01-count': 9181, '02-revenue': 100991.0, '03-cogs': 45905.0, '04-profit': 55086.0}
miso crab ramen {'01-count': 8892, '02-revenue': 106704.0, '03-cogs': 53352.0, '04-profit': 53352.0}
nagomi shoyu {'01-count': 9133, '02-revenue': 100463.0, '03-cogs': 45665.0, '04-profit': 54798.0}
soft-shell miso crab ramen {'01-count': 9131, '02-revenue': 127834.0, '03-cogs': 63917.0, '04-profit': 63917.0}
burnt garlic tonkotsu ramen {'01-count': 9071, '02-revenue': 126994.0, '03-cogs': 54426.0, '04-profit': 72568.0}
vegetarian curry + king trumpet mushroom ramen {'01-count': 8825, '02-revenue': 114725.0, '03-cogs': 61775.0, '04-profit': 52950.0}
```

[report.txt](PyRamen/report.txt)

### Notes

- Menu item count is adding 1 or 2 in final report (01-count). Didn't have time to figure out what was wrong with calculation.
	- Doesn't seem to be affecting any of the other calculations

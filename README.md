📊 Dataset Description — WFP Food Prices Database
This dataset, sourced from the World Food Programme, contains historical food price data collected across various countries, regions, and markets. It is used to analyze and forecast demand trends for essential commodities.

🧾 Column Descriptions

Column Name	Description
adm0_id	Unique identifier for the country (Admin Level 0).
adm0_name	Name of the country (e.g., Kenya, Bangladesh).
adm1_id	Unique identifier for the region/province/state within the country (Admin Level 1).
adm1_name	Name of the region/province/state (e.g., Nairobi, Punjab). Some values may be missing.
mkt_id	Unique identifier for the market where the price was recorded.
mkt_name	Name of the specific market (e.g., Accra Central, Lusaka Main).
cm_id	Unique identifier for the food commodity.
cm_name	Name of the food commodity (e.g., Maize, Rice, Beans).
cur_id	Unique identifier for the currency used.
cur_name	Name of the currency (e.g., Kenyan Shilling, USD).
pt_id	Unique identifier for the price type.
pt_name	Type of price — e.g., Retail, Wholesale, or Consumer Price.
um_id	Unique identifier for the unit of measurement.
um_name	The measurement unit used (e.g., kg, litre, dozen).
mp_month	Month the price was recorded (1 = January, 12 = December).
mp_year	Year the price was recorded (e.g., 2022).
mp_price	Price of the commodity in the local currency.
mp_commoditysource	Intended to be the data source for the commodity, but this column is empty in the dataset

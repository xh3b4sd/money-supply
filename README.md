# money-supply

Public data collector for money supply based on the https://api.stlouisfed.org
API. A Github Action is scheduled to update the `supply.csv` file once a day.
That CSV file can be integrated via Github's Raw Data endpoint in various ways.
One way to use the raw data is to define a Grafana CSV Data Source using the
plugin https://grafana.com/grafana/plugins/marcusolsson-csv-datasource.

![Grafana](/asset/grafana.png)

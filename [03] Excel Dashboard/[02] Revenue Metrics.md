### Revenue Metrics

- Total Sales Revenue
```
=SUM(Dataset[revenue])
```
Custom Formatting -> $0.00,,"M"

- Total Orders
```
=COUNTA(UNIQUE(Dataset[order_number]))
```

- Average Order Value (AOV)
```
=SUM(Dataset[revenue])/COUNTA(UNIQUE(Dataset[order_number]))
```
Custom Formatting -> $

- Sales Growth Rate
```
=(B15-B10)/B10

[=(Sales in 2021−Sales in 2016) / Sales in 2016]
```
Custom Formatting -> %

- Total Units Sold
```
=SUM(Dataset[quantity])
```

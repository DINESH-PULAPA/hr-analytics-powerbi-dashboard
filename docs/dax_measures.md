# DAX Measures Used

These are the DAX measures used in the Power BI dashboard:

```dax
Active Employee = [Total Employees] - [Total Attrition]

Attrition Rate = DIVIDE([Total Attrition], [Total Employees])

Total Attrition = SUM('HR data'[Attrition Count])

Total Employees = COUNT('HR data'[Employee Number])
```

Notes:
- `DIVIDE` is used to avoid division-by-zero errors.
- Replace `'HR data'` with the actual table name if different.
- These measures drive the KPI cards (Total Employees, Total Attrition, Attrition Rate) and filtered visuals in the dashboard.

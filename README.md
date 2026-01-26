# Dataflow Gen2 in Microsoft Fabric

Dataflow Gen2 is a Power Query–based ETL tool inside Microsoft Fabric that lets you extract, transform, and load data into OneLake using a no‑code or low‑code interface.

It’s basically Power Query + Fabric compute + Delta Lake output.

## 🚀 Dataflow Gen2 — Quick Summary

| Feature                | Description |
|------------------------|-------------|
| Purpose                | No‑code/low‑code ETL using Power Query |
| Runs On                | Fabric compute (capacity-based) |
| Output Format          | Delta tables, SQL tables, CSV (limited), Power BI tables |
| Output Storage         | Lakehouse, Warehouse, SQL database, Azure SQL database, Azure Data Explorer (Kusto), Power BI Datamart |
| Best For               | Data preparation, cleansing, lightweight ETL |
| Integration            | Lakehouse, Warehouse, Pipelines, Power BI |
| Refresh Options        | Manual, Scheduled, Pipeline-triggered |
| Incremental Refresh    | Supported |
| RLS Support            | Not supported in Dataflow Gen2 (apply RLS in Power BI semantic model) |

# Pipeline in MicroSoft_Fabric

A pipeline in Microsoft Fabric is a tool that helps you automate and schedule data tasks like copying data, running notebooks, refreshing Power BI, or loading data into a Lakehouse.

It works similar to ADF pipelines but is built inside Fabric and tightly connected to OneLake.

A pipeline is a logical container that groups together a set of activities to perform a complete data integration workflow. It defines how data moves, transforms, and is orchestrated across different systems.

# Broad categories of activities in pipeline:

  •	 Data Transformation Activities – applying transformations, activities like aggregations.
   
  •	Control Flow Activities – loops, conditional branching, on demand activities.
   
  •	 Data Movement Activities - copy data, ingesting the data in to destination.

# Simple Differences (ADF Pipeline vs Fabric Pipeline) 

| Feature            | Azure Data Factory (ADF) Pipeline        | Microsoft Fabric Pipeline                 |
|-------------------|-------------------------------------------|-------------------------------------------|
| Trigger Types     | Schedule,Tumbling Window,storage,Event-based    | Only Schedule trigger                     |
| Integration       | Azure services + On‑prem via IR           | Fabric items (Lakehouse, Warehouse, PBI)  |
| Compute           | Uses Integration Runtime (IR)             | Uses Fabric Capacity (no IR needed)       |
| Main Use Case     | Enterprise data integration               | End‑to‑end analytics inside Fabric        |

# You can view how I worked on pipelines in MSFabric in the video link below.

https://youtu.be/S8yrTQ30Upk  





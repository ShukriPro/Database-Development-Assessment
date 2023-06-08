# Database-Development-Assessment
Database Development Assessment - Creating Tables, Inserting Spatial Data, and Implementing Triggers

https://github.com/ShukriPro/Database-Development-Spatial/assets/125324204/d05715ce-4fca-448b-8f8c-6153ca2edcca

Tasks:

1. Create a stored procedure called "UDP_CREATE_TABLES" that drops and creates three unrelated tables with an auto-incrementing ID column.
2. Research and create a stored procedure called "UDP_INSERT_WKT" that inserts Well Known Text (WKT) data into one of the tables based on provided parameters.
3. Create a view called "VW_ALL_SHAPES" to display shapes from all three tables.
4. Implement buffering to enhance the visibility of points in the "VW_ALL_SHAPES" view.
5. Develop a stored procedure called "UDP_ROUTE_DIFFERENCES_IN_METERS" to calculate the length and differences in meters between two linestrings.
6. Build a stored procedure called "UDP_DISJOINT" to filter points inside or outside a buffer zone based on a parameter.
7. Create a database trigger called "TRG_PREVENT_VIEW_DROP" to prevent dropping views and log the action in the "event_logs" table.
8. Prepare an in-class presentation to showcase the implemented stored procedures, view, and trigger.

# Coordination_Dashboard
Dashboard from Street Manager Data.  Displaying Graphs for Promotor stats.


There is a little bit of inital setup required.  You will need:


EXPORT DATA:
One Year of data (recommended minimum), from DfT Street Manager, from the "Permits and Works", "Inspections", and "FPNs" tiles.
To do this, navigate to Street Manager, click the appropriate tile, click "More filter options" and use one of the available appropriate date fields, click "Apply filters", then click "Export" (at the bottom of the page). Save the generated file, open it, and paste it into the Coordination Dashboard under the appropriate tab, either "PermitExport", "InspectionsExport", or "FPNExport", all coloured orange.  
Paste from cell A1, misaligned columns will cause the formula to stop functioning.


SETUP/CONFIG:
Next navigate in the Coordination Dashboard to the blue tab, labled "SETUP".

From Cell B3 to Cell B30 enter the names of the Promotors you wish to review data on, the top 4 cells (B3 to B6) are the "Focus Four", these promotors have additional graphs and should be promotors you want to see moredata on, or compare.  NOTE: It is important the names are exactly as they are listed in Street Manager, see your exports for examples of these names, some will be obvious, other perhaps may not be.

From cell D3, to cell D326, you can enter the names of the cities, towns, and villages in your coordination area.  These will allow you to amend graphs based on the towns listed.  Should you not wish to use this feature then populating this list is not required, as by default all data areas will assume you want to see data from all of your coordination area.
NOTE: Again, make sure any names entered are as they would appear in Street Manager, this may not always be what you think it may be, for example, "Durham" is listed as "Durham City".

Once the above is complete, you will be able to view details of yoru chosen promotors for the last 12 months (if data is available in the export provided).  You can use the "Interactive" tab to cycle through promotors and towns should you wish.

Hopefully this will be of assistance for you.

-Kevin Ferguson.

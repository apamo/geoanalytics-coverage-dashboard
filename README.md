# geoanalytics-coverage-dashboard
Imagine you have some sort of dynamic dashboard that allows the user to select one country, press a button, and "magically" load all geometries for all administrative levels in that country and, even better, have it visualized with pre-configured map visualizations. Furthermore, as a user I want to see the current coverage (April 2020) of the QGA location database included in the same dashboard. So, wouldn't it be great to have all that in one place? Your prayers haven been heard. I've created a dashboard "solution" for Qlik Sense SaaS that will speed up development every time and help you demonstrate our powerful Qlik GeoAnalytics mapping capabilities and country coverage. This solution is called 'GeoAnalytics Coverage Dashboard'.

How-to use it:
1. Download the .qvf application from GitHub
2. Import the app into your SaaS tenant
3. Once inside of the app you'll see four different sheets: Home, Areas for X, Points for X, and Location DB Coverage.
4. Go to the Home sheet to select Continent and only one Country. If you select more than one the Reload button will be greyed out. 
5. Click on the Reload button. A pop-up "error" message will show up indicating 'Reload in progress'. Just wait until the text (3 in the UI) and map object (4 in the UI) updates with the selected country to close it.
6. Now you can navigate to the Areas and Points sheet to explore and navigate through the geographical hierarchy by making selections (i.e. drill down/up) or zooming in/out.
7. Alternatively, you can navigate to the Location DB Coverage sheet to check the current coverage status for the desired countries.
8. Optionally, you can modify the load script to include Cities and Postal Codes. This will only work with small countries that won't hit the data size limitations imposed in the location database. See Home sheet to know more about his.
9. Last but not least, feel free to modify this app by blending in your own external data (demographics, socioeconomic, etc.) or business data, and displaying it as measures in the map objects (color, size, custom tooltip, etc.)

TL;DR

Dashboard for Qlik Sense SaaS that allows to automatically load the geometries for the selected country in the UI. It also includes a coverage table by country based on the available points and areas in Qlik's GeoAnalytics Location Database.

Created by Alvaro Palacios
Qlik Solutions Architect for OEM EMEA


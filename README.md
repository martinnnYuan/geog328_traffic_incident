# Seattle High-Risk Corridors: Crashes & Volume (2022)

**Group AD1:**
-   **Martin Yuan**
-   **Jenny Liu**
-   **Jiaxuan Su**
-   **Xinrui Yang**

## Project Description

Our project is an interactive web GIS that blends SDOT’s 2022 collision records with 2022 traffic flow counts to surface high risk corridors across Seattle. Users can toggle collision points, traffic volume lines scaled by AWDT/ADT, and a computed risk index that snaps crashes to the nearest flow segments to highlight crashes per volume hot spots. Feature popups and a ranked risk list provide detail, while reprojection from EPSG:2926 to WGS84 and client side turf.js keep everything running in the browser. Data comes from SDOT Traffic Flow Counts 2022 (AWDT/ADT) and SDOT Collisions (all years, filtered to 2022), cached in assets folder for fast loading, and the map is built with MapLibre GL, turf.js.


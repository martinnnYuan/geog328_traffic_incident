# Seattle High-Risk Corridors: Crashes & Volume (2022)

**Group AD1:**
-   **Martin Yuan**
-   **Jenny Liu**
-   **Jiaxuan Su**
-   **Xinrui Yang**

## Project Description

Our project is an interactive web GIS that blends SDOT’s 2022 collision records with 2022 traffic flow counts to surface high risk corridors across Seattle. Users can toggle collision points, traffic volume lines scaled by AWDT/ADT, and a computed risk index that snaps crashes to the nearest flow segments to highlight crashes per volume hot spots. Feature popups and a ranked risk list provide detail, while reprojection from EPSG:2926 to WGS84 and client side turf.js keep everything running in the browser. Data comes from SDOT Traffic Flow Counts 2022 (AWDT/ADT) and SDOT Collisions (all years, filtered to 2022), cached in assets folder for fast loading, and the map is built with MapLibre GL, turf.js.

## Favicon
![favicon](assests/favicon.png)

The favicon shows a cute white car driving across a blue and green circular background, which represents the city and its road network in a friendly, playful way. The soft gradient colours make it feel light and modern, rather than serious or stressful. Next to the car, there is a small pink location pin with a tiny exclamation mark inside, symbolising traffic incidents or points of interest that the map is highlighting. Together, the car and the pin communicate that this is a web GIS about traffic and safety, but the rounded shapes and bright colours keep the mood positive and approachable, inviting users to explore the map rather than feel worried about accidents.
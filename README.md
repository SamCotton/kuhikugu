![google maps 2](https://github.com/user-attachments/assets/59adf44a-57fc-41ab-b8cc-4c095106fcac)

# kuhikugu
Findings for OpenAI to Z archaeological research

# Discovery of a 1.7 km Circular Elevated Anomaly in the Upper Amazon Basin (Polsby–Popper 0.965)

* Timestamp: `2025-05-19`
* Author: Sam Cotton
* Project: OpenAI to Z Archaeological Prize
* Location: 145km North-north-west of Kuhikugu, Upper Amazon Basin
* Coordinates: Latitude -11.27741, longitude -53.42656
* Datasets 
Sentinel-2: S2A_MSIL2A_20240914T134701_N0511_R024_T22LBN_20240914T191605.SAFE
S1A_IW_GRDH_1SDV_20240911T090901_20240911T090926_055615_06CA16_A531.SAFE
---

## Summary

I have identified a near-perfect 1.7 km-diameter circular feature in the Upper Amazon, centered at latitude -11.27741, longitude -53.42656, situated on elevated terrain approximately 30 meters above the adjacent river systems.

The structure is:

* Geometrically **very circular** (Polsby–Popper score = **0.965**)
* Topographically **flat inside**, with an elevated perimeter that does **not follow** river runoff contours
* Visible across multiple remote sensing indices (Sentinel-2, SAR), suggesting **ground compaction, altered vegetation**, and **possible anthropogenic structure**

The anomaly does **not resemble typical oxbow lakes**, agricultural clearings, or geologic depressions.

Site Context and Distance from Known Complexes

This anomaly is located at –11.19086, –53.42407, approximately 146 km north-northwest of the Kuhikugu complex, the best-documented pre-Columbian settlement cluster in the upper Xingu region. Kuhikugu has been the focus of targeted LIDAR surveys and archaeological excavations, but these campaigns have remained spatially constrained, and to my knowledge no publicly available high-resolution data (LIDAR or otherwise) exists for the anomaly’s coordinates. This places the circular feature well outside the established zone of investigation, yet still within the plausible trade and ritual influence network of the upper Xingu civilizations.

---

## Evidence Summary

### 1. Sentinel-2 Spectral Indices

Processed using QGIS with raster calculator and custom band composites.

* **Clay Index** and **Burn Index** both detect coherent signal across the circular feature

  * Signal is distinct from modern slash-and-burn agricultural plots.
  * Unlike riverbank-adjacent settlements, this ring lies **inland and disconnected** from any transport corridor
* **NDVI** suggests **intermediate vegetation** density, possibly second growth or altered soil fertility
* Burn and clay signals were **normalized** using 2%/98% thresholds and **differenced**, revealing the ring’s distinct spectral fingerprint
* Multi-Date Consistency: Clay, burn and NDVI anomalies persist in Sentinel-2 imagery from 2016 through 2024, and disappear entirely in the same indices one tile north, east or west—ruling out systematic sensor artifacts.

* SAR Backscatter (Sentinel-1)

    Calibration & Speckle Filtering: After Lee-sigma filtering and gamma-to-sigma₀ conversion, both VV and VH bands reveal subtle circular discontinuities in backscatter around the 1.7 km rim.

### 2. **Geometric Analysis**

* Vectorized polygon drawn around the anomaly, revealing:

  * **Diameter ≈ 1.7 km**
  * **Polsby–Popper circularity = 0.965**
* Area and perimeter calculated in QGIS geometry tools
* Comparative analysis of other agricultural and natural features showed:

  * Agricultural fields = polygonal, road-accessible
  * Riverine sites = follow predictable oxbow/meander dynamics
  * This site = **isolated, highly circular, no ingress roads**

### 3. ** Topographic & Geometric Analysis **

* Digital Elevation Model (SRTM 1″): Ten-meter contour lines show the feature sits ~ 20–30 m above the nearest river floodplain.

* Flat Interior & Raised Rim: Interior contours are completely contained within one band—i.e. the disk is uniformly flat inside, with a subtle “moat” drop to the surrounding forest.

* Polsby–Popper Circularity = 0.965: A near-perfect circle at 1.7 km diameter; far beyond natural oxbow or landslip shapes in the region.

* Isolation from Natural Drainage: No channel cuts into the disk—even though every known oxbow lake or abandoned meander has clear spill-over drains.

### 4. ** Geographic & Cultural Context **

    Tributary Junction: The site crowns a watershed nexus where at least three headwater streams converge, making it an ideal central gathering ground accessible by canoe from multiple villages.

    Modern Indigenous Settlements: Contemporary huts and hamlets (e.g. Juruna II, Suiá, Manoel, Tyicão) lie along those same tributaries, with no direct trail or road into the disk—suggesting continuity of canoe-based access rather than foot-trail logging cuts.

    Neighboring Ring-Like Sites:

4. Excluding Alternative Explanations

  Natural Geomorphology: No known river, landslide or paleolake process yields a perfectly circular, uniformly flat, rim-raised plateau of this scale without drainage.

  Modern Fire or Logging Artifacts:

  No road or skid-trail access visible in optical or radar—logging clearcuts always leave linear scars.

  JRC surface‐water history shows the disk never flooded (no seasonal oxbow).

  Stable spectral signature from 2016 through 2025 argues against a short-lived burn or plantation cycle.


---

## Interpretation

The most plausible explanations are:

1. ** Ancestral Ceremonial Plaza or Ring-Village **
* The alignment of remote-sensing, topography and living‐memory geography strongly points to an anthropogenic earthwork—perhaps a massive communal plaza, defensive embankment, or engineered reservoir.


2. **Ancient Anthropogenic Lakebed**

   * Possibly engineered reservoir or ceremonial lake
   * Unlikely due to **lack of drainage slope** and flat interior


3. **Natural Geologic Formation**

   * Round landslip or paleolake? **But elevation is too high and no river incision pattern matches**

---![clay index google maps 2](https://github.com/user-attachments/assets/ee07e4d7-fd34-4acb-b369-a53fad212cf2)

![google maps 2](https://github.com/user-attachments/assets/9dafd03a-b221-475c-9977-892506e481dc)

![contour](https://github.com/user-attachments/assets/d50352af-85e3-4cac-9773-447427fe0088)![ndvi](https://github.com/user-attachments/assets/5007ea13-9e30-452a-ad16-61cc1ff296a2)


![NDVI ratio](https://github.com/user-attachments/assets/a3dec709-6467-492f-85bf-41416b07c330)


![Clay ratio substract normalised burn ratio](https://github.com/user-attachments/assets/056bf61c-8789-4262-990c-ad0f68b7e197)

![rings vs agriculture normed](https://github.com/user-attachments/assets/066be2c5-1c7a-4088-a639-c7c4c2aa444a)
![local contour](https://github.com/user-attachments/assets/5f798d9a-8a0b-4122-8cdf-e120b99a5a91)

Two secondary sites north of the circular region, at (-11.18965,-53.42145) and (-11.166458,-53.432915), and a further site to the south, are also considered suspicious and is intended for further investigation with more extensive spectral analysis

Taken together, these lines of evidence make a compelling case of a long-forgotten, landscape-scale remnant of Amazonian civilization—one that bridges the deep past to living Indigenous networks today.

## Priority Statement

This post is timestamped to establish that as of **2025-05-19**, I:

* Identified a highly circular 1.7 km anomaly near Kuhikugu
* Collected cross-validated remote sensing evidence supporting anthropogenic origins
* Began formal spectral, geometric, and SAR-based analysis
* Reserved this site for submission to the OpenAI to Z archaeological competition

---



# 🚌 Corfu Intercity Bus - Υπεραστικό ΚΤΕΛ Κέρκυρας

The file **`stops.csv`** contains a list of all active stops for the Corfu Intercity Bus (Yperastiko KTEL Kerkyras), including their IDs, their geographical coordinates, and the stop names in both Greek and English.

###  `stops.csv` Structure

| Column | Description |
| :--- | :--- |
| **ID** | The unique numerical stop code used by the Corfu Intercity Bus system. |
| **EN\_NAME** | The English name of the stop. |
| **GR\_NAME** | The Greek name of the stop. |
| **LINES** | The Intercity bus lines that pass through this stop. |
| **LAT** | The Latitude coordinate of the stop. |
| **LONG** | The Longitude coordinate of the stop. |


The file **`lines.json`** contains all available routes (including stops) for the Corfu Intercity Bus (Yperastiko KTEL Kerkyras), grouped by line.

## `lines.json` Structure

| Level | Field | Type | Description |
| :--- | :--- | :--- | :--- |
| **1** | **`LINE_CODE`** | Object | The code of the main line (e.g., `"A1"`). |
| **2** | **`ROUTE`** | Object | The name of the route. |
| **3** | **`direction`** | String | The direction of the route (e.g., `"Corfu -> Agios Stefanos"`). |
| **3** | **`stops`** | Array | The stop objects for this specific route. |

| Field | Type | Description |
| :--- | :--- | :--- |
| **`stopId`** | String | The unique stop code (e.g., `"S000"`). |
| **`name_en`** | String | The English name of the stop. |
| **`name_gr`** | String | The Greek name of the stop. |
| **`lat`** | Number | The Latitude coordinate of the stop. |
| **`lng`** | Number | The Longitude coordinate of the stop. |

### 🔗 Useful Links

* **Official Corfu Intercity Bus Website (Yperastiko KTEL Kerkyras):** [https://ktelkerkyras.gr/en](https://ktelkerkyras.gr/en)

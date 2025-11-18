# 🚌 Corfu Intercity Bus - Υπεραστικό ΚΤΕΛ Κέρκυρας

## 🇪🇳 English

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

## 🇬🇷 Ελληνικά

Το αρχείο **`stops.csv`** περιέχει μια λίστα με όλες τις ενεργές στάσεις του Υπεραστικού ΚΤΕΛ Κέρκυρας, συμπεριλαμβανομένων των ID τους, των γεωγραφικών συντεταγμένων και των ονομάτων των στάσεων στα Ελληνικά και τα Αγγλικά.

###  Δομή `stops.csv`

| Στήλη | Περιγραφή |
| :--- | :--- |
| **ID** | Ο μοναδικός αριθμητικός κωδικός στάσης που χρησιμοποιείται από το σύστημα του Υπεραστικού ΚΤΕΛ Κέρκυρας. |
| **EN\_NAME** | Το Αγγλικό όνομα της στάσης. |
| **GR\_NAME** | Το Ελληνικό όνομα της στάσης. |
| **LINES** | Οι γραμμές του Υπεραστικού ΚΤΕΛ που περνούν από αυτή τη στάση. |
| **LAT** | Το γεωγραφικό πλάτος (Latitude) της στάσης. |
| **LONG** | Το γεωγραφικό μήκος (Longitude) της στάσης. |

Το αρχείο **`lines.json`** περιέχει όλες τις διαθέσιμες διαδρομές (με τις στάσεις) του Υπεραστικού ΚΤΕΛ Κέρκυρας, ομαδοποιημένες ανά γραμμή.

###  Δομή `lines.json`

| Επίπεδο | Πεδίο | Τύπος | Περιγραφή |
| :--- | :--- | :--- | :--- |
| **1** | **`ΚΩΔΙΚΟΣ_ΓΡΑΜΜΗΣ`** | Object | O κωδικός της κύριας γραμμής (π.χ. `"A1"`). |
| **2** | **`ΔΙΑΔΡΟΜΗ`** | Object | Το όνομα της διαδρομής. |
| **3** | **`direction`** | String | Η κατεύθυνση της διαδρομής (π.χ., `"Corfu -> Agios Stefanos"`). |
| **3** | **`stops`** | Array | Τα αντικείμενα των στάσεων αυτής της διαδρομής. |

| Πεδίο | Τύπος | Περιγραφή |
| :--- | :--- | :--- |
| **`stopId`** | String | Ο μοναδικός κωδικός στάσης (π.χ., `"S000"`). |
| **`name_en`** | String | Το Αγγλικό όνομα της στάσης. |
| **`name_gr`** | String | Το Ελληνικό όνομα της στάσης. |
| **`lat`** | Αριθμός | Το γεωγραφικό πλάτος (Latitude) της στάσης. |
| **`lng`** | Αριθμός | Το γεωγραφικό μήκος (Longitude) της στάσης. |

### 🔗 Χρήσιμοι Σύνδεσμοι

* **Επίσημη Ιστοσελίδα Υπεραστικού ΚΤΕΛ Κέρκυρας:** [https://ktelkerkyras.gr](https://ktelkerkyras.gr)

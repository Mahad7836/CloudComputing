# Google Cloud Storage Options

## Data Types
Understanding the data type determines the storage solution.

* **Structured Data:** Highly organized (Tables, rows, columns). Easy to capture and analyze.
    * *Examples:* Transactional workloads, Analytical workloads.
* **Unstructured Data:** No predefined model (80% of world's data).
    * *Examples:* Documents, Images, Audio/Video.

## Cloud Storage (Object Storage)
A fully managed, scalable service for **unstructured data** (BLOBs - Binary Large Objects).

### Key Concepts
* **Buckets:** Containers for data. Must have a globally unique name and a specific geographic location.
* **Objects:** The actual data files.
    * **Immutable:** Objects cannot be edited in place. If you change a file, it creates a new version (overwrites unless versioning is on).
    * **Versioning:** Keeps history of changes/deletions.
* **Geo-Redundancy:** High durability and accessibility worldwide.

### Storage Classes
1.  **Standard:** Frequently accessed data ("Hot" data).
2.  **Nearline:** Accessed once per month.
3.  **Coldline:** Accessed once every 90 days.
4.  **Archive:** Accessed once a year (Long-term backup).

### Common Use Cases
* Content storage and delivery (CDN).
* Data analytics and general compute.
* Backup and archival storage.
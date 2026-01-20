# Database Services in Google Cloud

## 1. Relational Databases (RDBMS)
Best for structured data requiring strong consistency, transactions, and complex joins.

### **Cloud SQL**
* **Type:** Fully managed RDBMS.
* **Engines:** MySQL, PostgreSQL, SQL Server.
* **Benefits:**
    * No software installation required.
    * Automated replication and managed backups.
    * Handles patches and updates automatically.
* **Use Case:** Migrating existing web frameworks (WordPress, etc.) or general purpose RDBMS apps.

### **Cloud Spanner**
* **Type:** Fully managed, mission-critical relational database.
* **Key Feature:** Scales **horizontally** (across nodes) while remaining strongly consistent.
* **Architecture:** Synchronous replication; data is copied across locations.
* **Use Case:** Global applications requiring high availability and unlimited scale (e.g., global supply chain, banking).

---

## 2. NoSQL Databases
Best for semi-structured or unstructured data needing high throughput or flexibility.

### **Cloud Firestore**
* **Type:** Document-based NoSQL.
* **Structure:** Data -> Documents -> Collections -> Sub-collections.
* **Key Features:**
    * Indexed by default.
    * **Offline Sync:** Great for mobile/web apps that need to work without internet.
* **Use Case:** Mobile apps, web development, user profiles.

### **Cloud Bigtable**
* **Type:** Wide-column NoSQL.
* **Key Features:** High throughput, fast read/write via APIs.
* **Use Case:** Large-scale analytical data, IoT sensor data, ad-tech.
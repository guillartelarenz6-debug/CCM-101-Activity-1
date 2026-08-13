# Cloud Infrastructure Components Analysis

## 1. Compute Resources
* **Observed Environment:** Central Processing Unit (CPU) cores and Virtual RAM allocated in KillerCoda.
* **Purpose:** Executes application code, processes calculations, and manages memory operations.
* **Importance in Cloud:** Serves as the core engine that runs virtual machines, containers, and serverless workloads.

---

## 2. Storage Resources
* **Observed Environment:** Root filesystem (`/`) backed by virtualized block storage (`/dev/vda1` or similar).
* **Purpose:** Retains operating system binaries, applications, and persistent data across sessions.
* **Importance in Cloud:** Ensures data durability, scalability, and disaster recovery capability.

---

## 3. Networking Resources
* **Observed Environment:** Virtual Network Interface Card (vNIC) with an assigned IPv4 address.
* **Purpose:** Enables data communication between the host, local networks, and public Internet.
* **Importance in Cloud:** Facilitates routing, security group filtering, and service interconnectivity.

---

## 4. Operating System
* **Observed Environment:** Linux (Ubuntu / Debian cloud distribution).
* **Purpose:** Acts as the resource abstraction layer managing system hardware and user processes.
* **Importance in Cloud:** Provides a lightweight, stable, secure foundation for modern cloud services.

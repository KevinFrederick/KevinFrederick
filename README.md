## 👋 Hi there, I'm Kevin Frederick Yapiter

### **Android Developer | Kotlin • Jetpack Compose • Clean Architecture**

Detail-oriented Computer Science graduate and **Bangkit Academy Distinction Graduate** specializing in modern Native Android development. Passionate about building scalable, maintainable mobile applications using **Clean Architecture**, **Multi-Module design**, and **offline-first** data patterns.

---

### 🛠️ **Tech Stack & Tools**

| **Category** | **Technologies & Tools** |
| :--- | :--- |
| **Languages** | Kotlin, Python, SQL |
| **Android UI & Framework** | Jetpack Compose, Material 3, ViewModel, Navigation, Vico Charts |
| **Architecture & Patterns** | Clean Architecture, Multi-Module (Feature/Layer-based), MVVM, Offline-First |
| **Async & Dependency Injection** | Kotlin Coroutines, Flow, Dagger Hilt |
| **Data & Storage** | Room Database, Firebase DataStore, Retrofit, REST APIs |
| **Backend & Infrastructure** | Ktor Framework, PostgreSQL, MinIO Object Storage, Docker, Docker Compose, Cloudflare Tunnels |
| **DevOps, Testing & Tools** | GitHub Actions, Git, Android Studio, JUnit |

---

### 📌 **Featured Projects**

#### 📦 [Full-Stack Inventory System](https://github.com/KevinFrederick) *(In Active Development)*
*( [Android Client](https://github.com/KevinFrederick/Inventory) | [Ktor Backend](https://github.com/KevinFrederick/Inventory-Backend) )*
> *An end-to-end, multi-module inventory ecosystem featuring a native Android client and a custom Ktor backend.*

* **Android Client (`Inventory`):**
  * Built using **Jetpack Compose** and **Clean Architecture** split across core modules (`:core:database`, `:core:network`, `:core:ui`).
  * Integrated **CameraX** for hardware barcode scanning, **Room Database** for local caching, and **WorkManager** (`SyncWorker`) for background synchronization.
  * Continuous integration via **GitHub Actions** (`android-ci.yml`).

* **Ktor Backend Service (`Inventory-Backend`):**
  * Modular backend powered by **Ktor Framework** and **PostgreSQL**.
  * Integrated **MinIO Object Storage** for secure image upload pipelines (`MinioImageStorageService`).
  * Real-time bidirectional data synchronization using **WebSockets** (`SyncSocketManager`) and containerized with **Docker & Docker Compose**.
  * Automated testing and build pipelines via **GitHub Actions** (`backend-ci.yml`).

#### 📱 [Multi-Currency Expense Tracker](https://github.com/KevinFrederick/Spending)
> *A serverless personal finance Android application with multi-currency tracking.*
* **Tech Stack:** Kotlin, Jetpack Compose, Clean Architecture (`:app`, `:domain`, `:data`), Firebase Auth, Room, Retrofit, Dagger Hilt, Coroutines, Flow.
* **Key Features:** Layer-based modularization, date-specific exchange rate caching to reduce API overhead, reactive UI state management, and financial visualization with Vico charts.

--- 

### 📫 **Connect With Me**
* 💼 **LinkedIn:** [linkedin.com/in/kevin-frederick-yapiter](https://www.linkedin.com/in/kevin-frederick-yapiter/)
* 📧 **Email:** [Kevin55622@gmail.com](mailto:kevin55622@gmail.com)

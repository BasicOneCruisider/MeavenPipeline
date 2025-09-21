---
## 🚀 Project Overview
Welcome to our project'MaevenPipelineProject! 👋 This document serves as a guide to understanding, configuring, and managing our Java Maven application. It covers the development environment, the CI/CD pipeline, and other essential information.
<img width="1920" height="877" alt="2025-09-21 22_44_48-azcentquatre – 01-first-azure-pipelines yml" src="https://github.com/user-attachments/assets/428678de-ef39-4cd0-814c-aff885c7b704" />


---
## 📋 Prerequisites
To work on this project, you need to have the following installed and configured on your local machine:

* **JDK (Java Development Kit)**: Version 11 or higher.
* **Maven**: Version 3.6 or higher.
* **Git**: For version control.
* **IDE**: An Integrated Development Environment like IntelliJ IDEA, Eclipse, or VS Code.

---
## ⚙️ Local Setup
Follow these steps to clone and run the project locally:

1.  **Clone the repository**:
    ```bash
    git clone https://dev.azure.com/francispera0052/MaevenPipelineProject
    cd MaevenPipelineProject
    ```

<img width="602" height="624" alt="2025-09-21 22_53_29-2025-09-21 15_32_09- png" src="https://github.com/user-attachments/assets/cf60f645-d9da-4e14-a697-8ee10fd43f50" />

---

## 📦 Dependency Management
Project dependencies are managed by **Maven** and are listed in the `pom.xml` file.

* **Add a dependency**: To add a new library, simply declare it in the `<dependencies>` section of the `pom.xml`. Maven will automatically handle downloading and managing it.
* **Update dependencies**: You can use Maven commands to manage updates if needed, but it's recommended to follow best practices by manually checking versions to avoid conflicts.

---

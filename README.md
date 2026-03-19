# JavaFX Git Exercise

![Java](https://img.shields.io/badge/Java-23-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-GUI_Framework-217346?style=for-the-badge&logo=java)
![Maven](https://img.shields.io/badge/Maven-Build_Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git&logoColor=white)

This repository contains an introductory exercise developed for the Software Engineering course. The primary goal was to establish a solid development workflow using modern tools and build a foundational JavaFX application.

## Core concepts explored

* **Version Control:** Setting up Git, configuring `.gitignore` for Java/IntelliJ environments, and establishing a basic commit workflow.
* **Environment Setup:** Configuring IntelliJ IDEA with JDK 23 and Maven integration.
* **Build Automation:** Using Maven (`pom.xml`) and the Maven Wrapper (`mvnw`) to ensure consistent builds across different environments without requiring a local Maven installation.
* **GUI Development:** Building a basic Model-View-Controller (MVC) architecture using JavaFX.

## Architecture and Configuration

Although a simple application, the project is structured following standard Java modular practices:

1. **View (`hello-view.fxml`):** FXML layout definition defining the UI structure (VBox, Labels, Buttons).
2. **Controller (`HelloController.java`):** Handles UI events and binds the FXML elements to Java logic using `@FXML` annotations.
3. **Entry Point (`HelloApplication.java`):** Initializes the JavaFX runtime, loads the FXML view, and sets up the primary stage.
4. **Module System (`module-info.java`):** Configures Java Module System dependencies for JavaFX components and allows reflection access for FXML loading.

## What I learned

This exercise was crucial for understanding the foundational plumbing of a Java GUI project. It helped me get comfortable with configuring the Java Module System (which can often cause setup issues), structuring a project using the Maven directory layout, and establishing clean version control habits for IDE-based development.

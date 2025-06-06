# ☕ Hello Java Maven Project

A simple Java "Hello World" application built using **Apache Maven** and integrated with **Jenkins** as part of **Task 8** of my DevOps Internship at **Elevate Labs**.

---

## 📌 Project Objective

To run a Java application using **Jenkins** by:

- Configuring Maven in Jenkins
- Creating a Freestyle project
- Using the “Invoke top-level Maven targets” build step
- Verifying successful compilation and build

---

## 📂 Project Structure

hello-java-maven/
├── pom.xml
└── src/
└── main/
└── java/
└── HelloWorld.java

---

## 🛠 Technologies Used

- Java 8+
- Apache Maven
- Jenkins (local installation)
- Windows 10 OS

---

## 🚀 How to Run

### Prerequisites:
- Java and Maven installed locally
- Jenkins installed and running on localhost:8080

### Steps:

1. **Clone the repo:**
   ```bash
   git clone https://github.com/PHANTOM0905/hello-java-maven.git
   cd hello-java-maven

2. **Compile manually using Maven:**
    ```bash
    mvn compile

3. **To run using Jenkins:**

    Create a Freestyle project in Jenkins
    Configure build step: Invoke top-level Maven targets
    Set Goal: compile
    Trigger build and check logs for BUILD SUCCESS

4. **📸 Output**
    ```bash
    Hello, Jenkins + Maven!

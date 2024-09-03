# Java Spring & Spring Boot Development Setup Guide

Welcome! This guide will help you set up your environment for Java Spring and Spring Boot development using IntelliJ IDEA, Git, Maven, Postman, and a GitHub account.

## Prerequisites

Before starting, make sure you have:

- A stable internet connection
- Administrative rights to install software on your computer

## Step 1: Install Java Development Kit (JDK)

1. **Download the JDK:**
   - Go to the [Oracle JDK download page](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or [Adoptium](https://adoptium.net/) for an open-source option.
   - Download the installer for your operating system (Windows or macOS).

2. **Install the JDK:**
   - Follow the installer instructions to complete the installation.
   - Set the `JAVA_HOME` environment variable:
     - **Windows:** Control Panel > System and Security > System > Advanced system settings > Environment Variables > New system variable.
     - **Mac:** Add `export JAVA_HOME=$(/usr/libexec/java_home)` to your `~/.bash_profile` or `~/.zshrc` file.

3. **Verify the Installation:**
   - Open a terminal or command prompt.
   - Run the command `java -version` to ensure Java is installed correctly.

## Step 2: Install IntelliJ IDEA

1. **Download IntelliJ IDEA:**
   - Visit the [IntelliJ IDEA download page](https://www.jetbrains.com/idea/download/).
   - Download the Community Edition for your operating system.

2. **Install IntelliJ IDEA:**
   - Follow the installation instructions for your operating system.

3. **Verify the Installation:**
   - Open IntelliJ IDEA and create a new project:
     - Select "New Project."
     - Choose "Java" and ensure the JDK is configured correctly.
     - Create a simple Java application to test the setup.

## Step 3: Install Git

1. **Download Git:**
   - Visit the [Git download page](https://git-scm.com/downloads).
   - Download the installer for your operating system (Windows or macOS).

2. **Install Git:**
   - Follow the installation instructions for your operating system.
   - During installation, it is recommended to use the default settings unless you have specific requirements.

3. **Verify the Installation:**
   - Open a terminal or command prompt.
   - Run the command `git --version` to ensure Git is installed correctly.

## Step 4: Install Apache Maven

1. **Download Maven:**
   - Visit the [Maven download page](https://maven.apache.org/download.cgi).
   - Download the binary zip archive for your operating system.

2. **Install Maven:**
   - Extract the downloaded archive to a directory of your choice.
   - Set the `MAVEN_HOME` environment variable:
     - **Windows:** Control Panel > System and Security > System > Advanced system settings > Environment Variables > New system variable, set `MAVEN_HOME` to the directory where Maven is installed.
     - **Mac:** Add `export MAVEN_HOME=/path/to/maven` to your `~/.bash_profile` or `~/.zshrc` file.
   - Add Maven’s `bin` directory to the `PATH` environment variable.

3. **Verify the Installation:**
   - Open a terminal or command prompt.
   - Run the command `mvn -version` to ensure Maven is installed correctly.

## Step 5: Install Postman

1. **Download Postman:**
   - Visit the [Postman download page](https://www.postman.com/downloads/).
   - Download the installer for your operating system (Windows or macOS).

2. **Install Postman:**
   - Follow the installation instructions for your operating system.

3. **Verify the Installation:**
   - Open Postman and familiarize yourself with its interface. This tool will be used for API testing during the course.

## Step 6: Create a GitHub Account

1. **Sign Up for GitHub:**
   - Visit the [GitHub signup page](https://github.com/join).
   - Follow the instructions to create a new GitHub account.

2. **Set Up Your GitHub Account:**
   - Complete the account setup by following GitHub's on-screen instructions.
   - Verify your email address and set up your profile.

## Step 7: Test Your Setup

1. **Java Test:**
   - Create a new Java class named `HelloWorld`.
   - Copy and paste the following code:

    ```java
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, World!");
        }
    }
    ```

   - Run the program. If it prints `Hello, World!` to the console, your Java setup is complete!

2. **Git Test:**
   - Open a terminal or command prompt.
   - Run the command `git --version`. If it returns the installed version of Git, your Git setup is complete.

3. **Maven Test:**
   - Open a terminal or command prompt.
   - Run the command `mvn -version`. If it returns the installed version of Maven, your Maven setup is complete.

4. **Postman Test:**
   - Open Postman and create a simple GET request to `https://postman-echo.com/get`.
   - Send the request and check if you receive a valid response. This ensures Postman is working correctly.

---

You are now ready to start your journey with Java Spring and Spring Boot development!

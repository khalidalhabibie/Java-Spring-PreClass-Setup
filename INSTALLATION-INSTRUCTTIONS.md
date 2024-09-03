# Java Spring & Spring Boot Development Setup Guide

Welcome! This guide will help you set up your environment for Java Spring and Spring Boot development using IntelliJ IDEA and Git.

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

## Step 4: Test Your Setup

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

---

You are now ready to start your journey with Java Spring and Spring Boot development!

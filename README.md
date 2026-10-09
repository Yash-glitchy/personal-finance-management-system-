# personal-finance-management-system-

# Finora

Finora is a Java Swing desktop app for managing personal finances. Users can track income and expenses, set budgets, monitor savings goals, and review financial summaries. An administrator role provides account management and security activity views.

> **Demo project:** Finora uses an in-memory database. All accounts and financial records reset when the app closes. Do not enter real financial information.

## Features

- Register and sign in as a regular user or administrator
- Add, edit, search, filter, and sort income and expense transactions
- Create and manage budgets and savings goals
- View dashboard totals, category spending, and financial reports
- Manage users and review security activity as an administrator
- Store passwords as salted PBKDF2 hashes
- Keep each user’s financial records isolated by account

## Technology

- Java 17+
- Java Swing
- JDBC
- H2 in-memory database
- Maven
- JUnit 5

## Requirements

- JDK 17 or later
- Maven 3.9 or later


cd <repository-name>
mvn clean package

if not able to run via jar file directly 
Download and extract the [Finora project ZIP]

Open the extracted Finora folder—the one containing pom.xml—in File Explorer.

In that folder, open PowerShell (click the address bar, type powershell, and press Enter). Run:


java -jar target/finora-1.0.0.jar

if still not able to open 
open finora -> target -> finora 1.0.0.jar

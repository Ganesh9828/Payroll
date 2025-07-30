# Payroll – Android Application

**Payroll** is an Android application developed using Java that allows administrators to manage employee information and view payroll data efficiently. This project is built with Android Studio and uses SQLite for local data storage.

##  Features

- Admin login and secure passcode access
- Dashboard for employee and payroll management
- View, update, and delete employee details
- Integrated local database using SQLite
- Clean and intuitive UI for administrative users

##  Project Structure

Payroll/
├── app/
│ └── src/
│ └── main/
│ ├── java/com/example/payroll/
│ │ ├── AdminDashboardActivity.java
│ │ ├── AdminDatabaseViewActivity.java
│ │ ├── AdminPasscodeDialog.java
│ │ ├── DatabaseHelper.java
│ │ └── ...
│ └── res/
├── AndroidManifest.xml
├── build.gradle
├── settings.gradle
└── ...


##  Getting Started

### Prerequisites

- Android Studio (Arctic Fox or later recommended)
- JDK 8 or higher
- Android SDK

### Running the App

1. Clone or download this repository.
2. Open the project in Android Studio (`File > Open > Navigate to Payroll directory`).
3. Let Gradle sync and build the project.
4. Connect an emulator or Android device and click **Run**.

### Build via Terminal

`bash
./gradlew assembleDebug      # for Linux/macOS
gradlew.bat assembleDebug    # for Windows


 Technologies Used
Java – Programming Language

SQLite – Local Database Management

Android SDK – UI and system integration

Gradle – Build automation






















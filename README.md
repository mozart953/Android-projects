# Android Projects Repository

This repository contains multiple Android exercises organized as independent Android Studio projects (App2 through App30, AppFrutas, Conexion-Api, MyApplication, PruebaApi, PruebaRetrofit, RestConexion, SegundaPruebaRetrofit).

## Characteristics

- Language: Java (majority of projects use Java; some projects may use Kotlin depending on configuration)
- Build system: Gradle (each project includes gradlew, build.gradle, settings.gradle)
- Minimum/target SDK and dependencies are defined per project in build.gradle files
- Each app follows standard Android structure: app/src/main/java, app/src/main/res, app/src/main/AndroidManifest.xml
- Many exercises demonstrate UI controls, event handling, basic logic, and data handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
```
2. Open each project individually in Android Studio (File > Open) or import as needed.
3. Sync Gradle when prompted.
4. Build and run on an emulator or physical device with appropriate API level.

## Usage

Each directory is a standalone Android project. Open the specific project directory in Android Studio to run/edit it. Main entry points are typically MainActivity in the package defined in AndroidManifest.xml.

## Exercises

### App2 - Average Grade Calculator
- Package: com.example.app2
- MainActivity: App2/app/src/main/java/com/example/app2/MainActivity.java
- Description: Calculates average of three grades (Matematicas, Fisica, Quimica). Displays approval if average >= 6, else failure.
- UI elements: three EditText inputs, one TextView for result, button triggering estatus() method.

### App3 - Basic Calculator (Sum/Subtract)
- Package: com.example.app3
- MainActivity: App3/app/src/main/java/com/example/app3/MainActivity.java
- Description: Performs addition or subtraction based on RadioButton selection.
- UI elements: two EditText inputs, two RadioButtons (sumar/restar), TextView result, button calling Calcular(View).

### App4 - Calculator with Four Operations
- Package: com.example.app4
- MainActivity: App4/app/src/main/java/com/example/app4/MainActivity.java
- Description: Performs addition, subtraction, multiplication, or division based on RadioButton selection. Division by zero shows a Toast.
- UI elements: two EditText inputs, four RadioButtons, TextView result, button calling Calcular(View).

### App5 - Calculator with CheckBoxes
- Package: com.example.app5
- MainActivity: App5/app/src/main/java/com/example/app5/MainActivity.java
- Description: Performs sum and/or subtraction depending on CheckBox selection; concatenates results.
- UI elements: two EditText inputs, two CheckBoxes, TextView result, button calling Calcular(View).

### App6 - Calculator with Spinner
- Package: com.example.app6
- MainActivity: App6/app/src/main/java/com/example/app6/MainActivity.java
- Description: Performs operation selected from Spinner (Sumar, Restar, Multiplicar, Dividir). Division by zero shows Toast. Uses custom spinner layout.
- UI elements: two EditText inputs, Spinner, TextView result, button calling Calcular(View).

### Other Projects
The repository contains additional projects (App8 through App30, AppFrutas, Conexion-Api, MyApplication, PruebaApi, PruebaRetrofit, RestConexion, SegundaPruebaRetrofit). Each follows the same Android project structure. To understand each exercise's functionality, inspect the corresponding MainActivity and layout files (res/layout) within that project.

## Notes
- No top-level README existed prior to this addition.
- Project numbering goes up to App30 with additional named projects present.
- Each project is self-contained with its own Gradle configuration.

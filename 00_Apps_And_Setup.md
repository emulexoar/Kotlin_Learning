# Lesson 00 - Apps and Setup

Goal:
Set up everything needed to write, run, and debug Kotlin code.

## Required Apps

1. JDK 17
- Needed to compile and run Kotlin on JVM.
- Download: https://adoptium.net/

2. IntelliJ IDEA Community (recommended for Kotlin learning)
- Best beginner IDE for Kotlin.
- Download: https://www.jetbrains.com/idea/download/

3. Git
- Needed for version control and project sharing.
- Download: https://git-scm.com/downloads

4. Visual Studio Code (optional)
- Good lightweight editor.
- Download: https://code.visualstudio.com/

## Optional But Useful Apps

1. Android Studio
- Needed if you want to build Android apps with Kotlin.
- Download: https://developer.android.com/studio

2. Postman
- Useful for testing APIs when Kotlin apps call backend services.
- Download: https://www.postman.com/downloads/

3. DBeaver
- Useful for learning SQL while building Kotlin backend or app data features.
- Download: https://dbeaver.io/download/

4. Docker Desktop
- Useful for local services (databases, API mocks).
- Download: https://www.docker.com/products/docker-desktop/

## IntelliJ Setup Steps

1. Install IntelliJ IDEA Community.
2. Open IntelliJ and choose New Project.
3. Select Kotlin then Kotlin/JVM.
4. Set JDK to 17.
5. Create project.
6. Run the sample Main.kt.

## VS Code Setup Steps (If Using VS Code)

1. Install VS Code.
2. Install Extension Pack for Java.
3. Install Kotlin Language extension.
4. Ensure JDK 17 is installed and configured in PATH.

## Verify Installation

Run in terminal:

kotlin -version
java -version
git --version

If kotlin command is missing:
- Install Kotlin compiler from https://kotlinlang.org/docs/command-line.html
- Or use IntelliJ run button (compiler bundled by Gradle project).

## Beginner Troubleshooting

Problem: java not found
- Fix: reinstall JDK 17 and set JAVA_HOME.

Problem: Kotlin SDK not detected in IDE
- Fix: close project and reopen; set project SDK to JDK 17.

Problem: Gradle sync fails
- Fix: check internet/firewall and Gradle JVM settings.

Checklist:
- JDK installed
- IDE installed
- Git installed
- Kotlin project runs successfully

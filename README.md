# Task Manager (Kotlin + Jetpack Compose)

A task manager Android app built with Kotlin, Jetpack Compose, and Material 3. Tasks can be created, prioritized, searched, filtered, and tracked, and they are saved on the device so they persist after the app is closed.

## Features

- Add and edit tasks with a title, optional description, and priority (High, Medium, Low)
- Mark tasks as completed, with strikethrough styling
- Delete individual tasks or clear all completed tasks at once
- Progress card with a completion bar
- Search by title or description
- Filters: All, Active, Completed
- Automatic sorting: unfinished tasks first, then by priority
- Color-coded priority indicators
- Local persistence with SharedPreferences (JSON)

## Tech Stack

- Kotlin
- Jetpack Compose and Material 3
- Android Studio
- SharedPreferences with org.json for storage

## Screenshots

![Main screen](screenshots/main.png)

## Getting Started

1. Clone the repository:
   `git clone https://github.com/Nafis-dsu/Task-Manager.git
2. Open the project in Android Studio.
3. Let Gradle sync, then run the app on an emulator or an Android device (API 24+).

## Project Structure

All app code is in `app/src/main/java/com/example/taskmanager/MainActivity.kt`, organized into:

- **Model:** `Task`, `Priority`, `TaskFilter`
- **Data:** `TaskRepository` (loads and saves tasks)
- **UI:** `TaskManagerApp`, `TaskCard`, `ProgressCard`, `TaskDialog`

## Author

MD NAFIS SADIK ([@Nafis-dsu](https://github.com/Nafis-dsu))

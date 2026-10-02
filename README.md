# XPlore

XPlore is an adventure exploration Android app that turns real-world
movement into exploration progress.

The core idea is simple:

> Explore the real world → reveal the map → discover places → track progress.

## Current Status

🚧 Development

Currently completing Step 1: Development environment and project setup.

## Planned Technology

- Kotlin
- Jetpack Compose
- MapLibre
- Room / SQLite
- Supabase
- PostgreSQL + PostGIS
- FastAPI (later, when needed)

## Architecture

The application will follow a local-first architecture.

The phone will process and save exploration locally first. Data will
synchronize with the server when an internet connection is available.

## Planned MVP

- User sign-up and sign-in
- Fog-of-war exploration map
- Foreground location tracking
- GPS filtering
- Grid-based exploration
- Local exploration persistence
- Exploration statistics
- Place discovery
- Offline exploration
- Server synchronization
- Account deletion

## Future Features

- Background tracking
- XP and levels
- Achievements
- Streaks
- Friends
- Leaderboards
- Challenges
- Travel journal
- City and country completion

## Development

This project is being developed incrementally while learning the
technologies involved.

Each major architectural decision will be documented in the project
Decision Log.
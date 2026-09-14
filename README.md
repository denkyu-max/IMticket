# IMticket
# Project Rules for OpenCode

## Architecture Overview
- Stack: Tauri (Rust backend), React + Tailwind (Frontend), Python FastAPI (Central Backend).
- Purpose: Internal desktop app replacing Spark IM + handling Snipe-IT maintenance logs.

## Constraints
- NO financial or cost tracking logic (no parts cost, billing, or pricing).
- UI must separate regular End-Users (minimal chat layout) from Admins (full ticket dashboard).
- Sync all resolved maintenance events directly to Snipe-IT REST API endpoints.

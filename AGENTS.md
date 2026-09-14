# AGENTS.md - Global Project Instructions

## Project Overview
A unified desktop application replacing legacy Spark IM. Handles 1-on-1 chat, broadcast messaging, support ticket queues, scheduled system maintenance, and direct integration with Snipe-IT for inventory tracking.

## Core Rules & Constraints
1. NO FINANCIAL OR COST LOGIC: Strictly omit all fields, UI elements, and API logic related to pricing, parts cost, or vendor billing. Focus solely on device health, service actions, downtime, and technical logs.
2. DUAL ROLE LAYOUT:
   - End-User View: Minimalist Spark-style chat, broadcast receiver, ticket status tab, and "My Assigned Assets" drawer.
   - Admin/Technician View: Multi-pane dashboard with active chat queues, ticket conversion tools, scheduled maintenance calendar, and Snipe-IT logging card.
3. TECH STACK: Python FastAPI (Backend), PostgreSQL/SQLite (DB), WebSockets (Real-time Chat), Tauri 2.0 + React + Tailwind CSS (Desktop UI).

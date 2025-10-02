# Copilot Instructions for AI Coding Agents

## Project Overview
This project is a **heat loss calculation web app**.  
Users upload images of a room, which are analyzed by an AI model to estimate room size and materials. The app calculates heat loss based on these insights and provides recommendations for energy efficiency improvements.

## Workspace Structure
- `docs/`
  - `app-overview.md`: Contains a detailed overview of the app's features, architecture, and UX patterns.
- No source code, configuration, or workflow files are present yet.

## Technology Stack
- **Frontend:** React (TypeScript), managed with Nx
- **Backend:** Node.js (TypeScript)
- **Testing:** Playwright (end-to-end)
- **AI Model Integration:** MCP (Model Control Platform)
- **Monorepo Management:** Nx

## Planned Architecture
- **Frontend App:** React/Nx for UI, image upload, and results display
- **Backend API:** Node.js service for image upload, AI invocation, and results
- **AI Service:** MCP integration for image analysis (room features extraction)
- **Testing:** Playwright for browser-based automation

## Key Features & UX Patterns
- Image upload (drag-and-drop, multi-select, camera integration)
- Progressive upload and feedback
- AI-driven analysis (dimensions, materials)
- Heat loss calculation and visualization (3D model, heat map, drill-down)
- Interactive recommendations and export/share options
- Responsive, accessible, and guided workflow

## Immediate Guidance for AI Agents
- **No Established Conventions:** No project-specific coding patterns, build/test workflows, or integration points to document at this time.
- **Next Steps:**
  - Scaffold Nx workspace with React and Node apps.
  - Define API endpoints for image upload and analysis.
  - Integrate MCP for AI-driven image analysis.
  - Implement heat loss calculation logic.
  - Add Playwright tests for critical user flows.
  - Update this file as new components, workflows, or conventions are added.

## Example Update Section (for future reference)
> When source code or workflows are added, document:
> - Major components and their responsibilities
> - Build/test/debug commands and scripts
> - Integration points and external dependencies
> - Project-specific conventions and patterns

---
_Last updated: 2 October 2025_

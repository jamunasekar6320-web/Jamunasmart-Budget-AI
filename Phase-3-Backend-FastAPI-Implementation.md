# Phase 3: Backend - FastAPI Integration (main.py)

This is bridge between frontend and Gemini AI.

### Activity 3.1: Define FastAPI Routes (from your PDF Page 5)
- Home Planner (/generate-home)
- Party Planner (/generate-party)
- Jewelry Planner (/generate-jewelry)
- User Auth (/register, /login, /logout, /token)
- Session Info (/session-info, /session-data)
- /recommendations-details, /history, /startup

### Activity 3.2: Modular Architecture
- app/main.py - Entry point with uvicorn
- app/routers/ - pages, auth, api
- app/config.py, database.py

### Activity 3.3: CORS & Static Routing
- app.mount("/static", StaticFiles)
- CORS setup for frontend communication

### Activity 3.4: Startup Function
- lifespan() -> init_db()
- get_settings(), health check: {"status": "ok"}

Run: uvicorn app.main:app --reload

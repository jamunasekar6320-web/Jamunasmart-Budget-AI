# Phase 2: Core Functionality Development

### Activity 2.1: Flask / FastAPI Structure Design
- Design backend for routing, session control, planner modules
- Folder: routes/, services/, models/

### Activity 2.2: Create Endpoints
- `/generate-home` - Home interior recommendations
- `/generate-party` - Catering, venue, decoration
- `/generate-jewelry` - Text + Image input -> jewelry

### Activity 2.3: Integrate Gemini Prompts
- Linking websites: Amazon, Flipkart, IKEA, Swiggy, Zomato, OYO
- Using if condition to categorize situation-based products

Core File: gemini_utils.py for AI calls

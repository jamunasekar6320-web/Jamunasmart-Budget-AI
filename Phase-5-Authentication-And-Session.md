# Phase 5: Authentication & Session Management

### Activity 5.1: Login & Register Routing (from PDF Page 4)
- /login: Authenticates credentials & starts session
- /register: Securely stores user credentials (hashed)
- /logout: Terminates session & redirects to login
- /token: Issues secure JWT token

### Activity 5.2: Session Handling
- /session-info: User ID, login status
- /session-data: Personalization & recommendation tracking
- Depends(get_current_active_user)

### Security:
- Password hashing with bcrypt
- JWT token validation
- Protected routes for planners

# Luqman Courier Service Management System

## Setup Instructions

1. **Database Setup:**
   - Open SQL Server Management Studio
   - Run `database/CA2_database.sql`

2. **Install Dependencies:**
```bash
   pip install -r requirements.txt
```

3. **Run Backend Server:**
```bash
   python server_and_backend/app_backend.py
```
   Server will run on: http://localhost:5003

4. **Access Web Interfaces:**
   - Admin Dashboard: Open `client_and_frontend/admin_dashboard.html` in browser
   - Driver Dashboard: Open `client_and_frontend/driver_dashboard.html` in browser

## Testing

Run unit tests:
```bash
python tests/test_suite.py
```

## Project Structure
- `backend/` - Server-side code
- `client_and_frontend/` - Desktop/console clients & Web interfaces 
- `database/` - Database setup
- `models/` - Data models
- `services/` - Business logic
- `tests/` - Unit tests
# Running AYUSHEASE Platform

## Quick Start - Run Both Servers Simultaneously

From the root directory (`/Users/sunilsuri/ayushease`), run:

```bash
npm run dev
```

This will start both:
- **Backend** server on `http://localhost:5001`
- **Frontend** server on `http://localhost:5173` (or next available port)

## Alternative: Run Servers Separately

If you prefer to run them in separate terminals:

### Terminal 1 - Backend:
```bash
cd Backend
npm run dev
```

### Terminal 2 - Frontend:
```bash
cd Frontend
npm run dev
```

## Individual Commands

- `npm run dev` - Run both frontend and backend together
- `npm run dev:backend` - Run only backend server
- `npm run dev:frontend` - Run only frontend server
- `npm run install:all` - Install all dependencies (root, backend, frontend)

## Access the Application

Once both servers are running:
- **Frontend**: http://localhost:5173
- **Backend API**: http://localhost:5001

## Notes

- Make sure MongoDB is running if your backend requires it
- The backend uses nodemon for auto-restart on file changes
- The frontend uses Vite for fast hot module replacement



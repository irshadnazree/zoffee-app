# Zoffee App

This repository contains a full-stack application with a modern React frontend and Go backend, managed in a monorepo structure.

## Structure

The monorepo is organized as follows:

```
zoffee-app/
├── frontend/           # React + TypeScript frontend application
│   ├── src/           # Source code
│   ├── public/        # Static assets
│   └── ...           # Configuration files (vite, typescript, etc.)
│
└── backend/          # Go backend application
    ├── main.go       # Main application entry point
    └── go.mod        # Go module definition
```

## Frontend

The frontend is built with:
- React 19
- TypeScript
- Vite as the build tool
- ESLint for code linting
- TanStack Router for routing

### Development
```bash
cd frontend
npm install
npm run dev     # Start development server
npm run build   # Build for production
npm run lint    # Run linting
```

## Backend

The backend is built with:
- Go
- Standard library

### Development
```bash
cd backend
go run main.go
```

## Getting Started

1. Clone the repository
2. Set up the frontend:
   ```bash
   cd frontend
   npm install
   ```
3. Set up the backend:
   ```bash
   cd backend
   go mod tidy
   ```
4. Start both services in development mode

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request

## License

[Add your license here]

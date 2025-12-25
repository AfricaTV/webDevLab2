# React + TypeScript + Vite

### To run front BE and FE part one command. Project should be launched in a different terminals
## BE launches on http://localhost:3001/
## FE launches on http://localhost:3002/
```bash
npm run dev
```bash


## Cypress Installation

```bash
# Install Cypress as dev dependency
npm install -D cypress

# Install Cypress binary (if needed)
npx cypress install
```

## Cypress E2E Tests (in third terminal)

```bash
# Open Cypress GUI (interactive mode)
npm run cy:open

# Run tests in headless mode
npm run cy:run

# Run E2E tests
npm run test:e2e
```

**Note:** Make sure both frontend (`npm run dev`) and backend are running before running tests.
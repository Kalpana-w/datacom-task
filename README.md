
║         🚀 KALPANA PORTFOLIO CI/CD        ║


                 GitHub Actions
                       │
              ┌────────┴────────┐
              │                 │
          🔵 CI Pipeline     🟣 CD Pipeline
              │                 │
        Pull Request         Push → main
              │                 │
              ▼                 ▼
        ┌───────────┐      ┌────────────┐
        │ Checkout  │      │  Checkout  │
        └─────┬─────┘      └─────┬──────┘
              │                   │
              ▼                   ▼
        ┌───────────┐      ┌────────────┐
        │   Test    │      │   Build    │
        └─────┬─────┘      └─────┬──────┘
              │                   │
              ▼                   ▼
        ✅ CI Passed        🚀 Deploy
                                  │
                                  ▼
                         ┌────────────────┐
                         │ GitHub Pages   │
                         └───────┬────────┘
                                 │
                                 ▼
                         🌐 MY PORTFOLIO

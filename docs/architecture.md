# BuildCalc Architecture

## Current repository architecture

```mermaid
flowchart LR
    U[User] --> W[construction-estimator.html]
    W --> C[Client-side calculation logic]
    W --> S[WhatsApp share flow]
    W --> N[Netlify deployment]
```

BuildCalc is currently a single static HTML application. The public repository does not contain a separate backend or database layer.

## Evidence boundary
The architecture above reflects the files currently committed to the repository. Do not claim a backend/API/database architecture unless those components are actually added and documented.

## 12.2 Logical Architecture

```mermaid
flowchart LR
    U[User] --> W[Next.js Web App]
    W --> A[Better Auth]
    W --> S[Application Services]
    S --> G[GitHub API]
    G --> R[GitHub Repository]
    S --> D[Diagram Rendering Layer]
    S --> N[Note Management Layer]
    S --> X[Future AI Services]
```
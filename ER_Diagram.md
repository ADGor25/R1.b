flowchart TD
    A[ToDo List] --> B(Main View)

    B --> C{Parent Views}

    C --> D[Top]
    D --> G[Title]
    D --> H[Button]
    H --> I[Instruction Modal/Video]

    C -->E[Middle]
    E --> J[Plus Button]
    E --> K[Child View]
    K --> L[Toggle Activity]
    K --> M[List of ToDos]
    K --> N[Course/Project Group]
    K --> O[Priority]
    K --> P[Notification Checkbox]

    C -->F[Bottom Bar]
    F --> Q[Home]
    Q --> R[Welcome Text]
    Q --> S[Calendar View]
    F --> T[Settings]
    T --> U[Change Notif. Timing]
    T --> V[Create Groups, Prioities]

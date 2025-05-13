```mermaid
flowchart TB
    A[Ease of Booking] -->|"increases"| B[Customer Flexibility]
    B -->|"leads to"| C[Frequent Cancellations]
    C -->|"reduces"| D[Revenue Stability]
    D -->|"reduces"| E[Hotel Confidence]

    C -->|"increases"| F[Need for Cancellation Prediction Model]
    F -->|"leads to"| G[Model Performance]
    G -->|"increases"| H[Evaluation & Monitoring]
    H -->|"increases"| I[Policy Adjustments]
    I -->|"reduces"| C

    J[Seasonal & External Factors] -->|"leads to"| C
    J -->|"leads to"| G

    %% Styling: class definition
    classDef pos fill:#e6ffe6,stroke:#000,color:#000;
    classDef neg fill:#ffe6e6,stroke:#000,color:#000;
    classDef process fill:#f0f8ff,stroke:#000,color:#000;

    %% Assign class to each node
    class A,B pos;
    class C,D,E,J neg;
    class F,G,H,I process;


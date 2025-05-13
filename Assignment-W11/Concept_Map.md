```mermaid
graph TB
  A[Hotel Booking Cancellation]

  A --> B1[Background]
  B1 --> C1[Tech makes booking/cancel easy]
  B1 --> C2[Causes uncertainty & losses]

  C1 --> B2[Customer Behavior]
  B2 --> C3[Looking for better price]
  B2 --> C4[Frequent cancellations]

  C4 --> C6[Cancellation factors]
  C6 --> C5[Model performance]

  C5 --> B6[Evaluation Metric]
  B6 --> C11[Focus on Recall]
  B6 --> C12[Reduce undetected cancellations]

  C2 --> B5[Production Scenario]
  B5 --> C10[Monthly analysis & review]
  B5--> C8[Support better policies]


  %% Assign classes
  class B1,C1,C2 background;
  class B2,C3,C4 background2;
  class C5,C6,B6,C11,C12 background3;
  class B5,C8,C9,C10 background4;
  class A title;

  %% Define background styles
  classDef background fill:#ffe6cc,color:#000,stroke:#333,stroke-width:1px;
  classDef background2 fill:#ccf2ff,color:#000,stroke:#333,stroke-width:1px;
  classDef background3 fill:#e6ccff,color:#000,stroke:#333,stroke-width:1px;
  classDef background4 fill:#d5f5e3,color:#000,stroke:#333,stroke-width:1px;
  classDef title fill:#fff3cd,color:#000,stroke:#333,stroke-width:2px;


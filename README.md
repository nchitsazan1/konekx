```mermaid
graph LR
    subgraph "Big Vision: Universal Autonomous Driving Ecosystem"
        %% Phase 1: The ADAIS Proposal (POC)
        subgraph "Phase 1: POC"
            style POC fill:#e6f3ff,stroke:#0055cc,stroke-width:2px
            A["Deploy Roadside Units"]
            B["Data Collection & Fusion"]
            C["3D Maps & Hazard Alerts"]
            D["V2I Communication"]
        end

        %% Phase 2: Software Development
        subgraph "Phase 2: Development"
            E["Aggregate Network Data"]
            F["Train Universal Models"]
            G["Develop Core Software"]
        end

        %% Phase 3: Market Adoption
        subgraph "Phase 3: Adoption"
            H["License Software to OEMs"]
            I["Widespread AV Adoption"]
            J["Continuous Improvement"]
        end
    end

    %% Define connections between stages
    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J

    %% Apply styling to the POC subgraph
    classDef poc fill:#e6f3ff,stroke:#0055cc,stroke-width:3px,stroke-dasharray: 5 5;
    class POC,A,B,C,D poc;

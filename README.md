```mermaid
graph TD
    subgraph "Big Vision: Universal Autonomous Driving Ecosystem"
        %% Phase 1: The ADAIS Proposal (POC)
        subgraph "Phase 1: Infrastructure & Data Foundation (ADAIS POC)"
            style POC fill:#e6f3ff,stroke:#0055cc,stroke-width:2px
            A["Deploy Roadside Units (LiDAR, Thermal/HD Cameras)"]
            B["Real-Time Data Collection & AI Sensor Fusion"]
            C["Generate 3D Maps & Predictive Hazard Alerts"]
            D["V2I Communication via Private 5G"]
        end

        %% Phase 2: Software Development
        subgraph "Phase 2: Centralized Software Development"
            E["Aggregate Data from Nationwide ADAIS Network"]
            F["Train Universal Autonomous Driving Models (ML/RL)"]
            G["Develop Core Autonomous Driving Software Stack"]
        end

        %% Phase 3: Market Adoption
        subgraph "Phase 3: Market Adoption & Continuous Improvement"
            H["License Software Stack to Automotive OEMs"]
            I["Enable Widespread AV Adoption in OEM Vehicles"]
            J["Continuous Software Improvement via Fleet Learning"]
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

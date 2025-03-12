# Annual OT Closure Process Flowchart

```mermaid
graph TD
    A[Start] --> B["Procurement of HEPA filter (CC)"]
    B --> C["Repair/Replacement Areas Identification (User + CC)"]
    C --> D["Repair Request Issuance (User)"]
    D --> E["Readiness Check (CC: Man, Method, Material, Machine)"]
    E --> F["Material List Submission (CC)"]
    F --> G["Material List Check (Engineering Unit)"]
    G --> H{"Material List OK?"}
    H -->|Yes| I["Material List Approval (Hospital Director)"]
    H -->|No| J["Revise Material List (Concession Company)"]
    J --> F
    I --> K["Submission of Hourly Schedule (Concession Company)"]
    K --> L["Hourly Schedule Check (Engineering Unit)"]
    L --> M{"Hourly Schedule OK?"}
    M -->|Yes| N["Hourly Schedule Approval (Hospital Director)"]
    M -->|No| O["Revise Hourly Schedule (Concession Company)"]
    O --> K
    N --> P["Preparation of Presentation Slides (Concession Company)"]
    P --> Q["Presentation Slides Check (Engineering Unit)"]
    Q --> R{"Slides OK?"}
    R -->|Yes| S["Call for Meeting"]
    R -->|No| T["Revise Slides (Concession Company)"]
    T --> P
    S --> U["Inter-department Meeting"]
    U --> V["OT Closure"]
    V --> W[End]

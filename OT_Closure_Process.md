# Annual OT Closure Process Flowchart

```mermaid
graph TD
    A[Start] --> B["Procurement of HEPA filter\n(Concession Company)"]
    B --> C["Repair/Replacement Areas Identification\n(User + Concession Company)"]
    C --> D["Repair Request Issuance\n(User)"]
    D --> E["Readiness Check\n(Concession Company: Man, Method, Material, Machine)"]
    E --> F["Material List Submission\n(Concession Company)"]
    F --> G["Material List Check\n(Engineering Unit)"]
    G --> H{"Material List OK?"}
    H -->|Yes| I["Material List Approval\n(Hospital Director)"]
    H -->|No| J["Revise Material List\n(Concession Company)"]
    J --> F
    I --> K["Submission of Hourly Schedule\n(Concession Company)"]
    K --> L["Hourly Schedule Check\n(Engineering Unit)"]
    L --> M{"Hourly Schedule OK?"}
    M -->|Yes| N["Hourly Schedule Approval\n(Hospital Director)"]
    M -->|No| O["Revise Hourly Schedule\n(Concession Company)"]
    O --> K
    N --> P["Preparation of Presentation Slides\n(Concession Company)"]
    P --> Q["Presentation Slides Check\n(Engineering Unit)"]
    Q --> R{"Slides OK?"}
    R -->|Yes| S["Call for Meeting"]
    R -->|No| T["Revise Slides\n(Concession Company)"]
    T --> P
    S --> U["Inter-department Meeting"]
    U --> V["OT Closure"]
    V --> W[End]

graph TB
    %% Main Project
    P[<b>CyberShield</b>] --- P1(1: Governance)
    P --- P2(2: Backend)
    P --- P3(3: Frontend)
    P --- P4(4: Integration)
    P --- P5(5: Closure)

    %% Phase 1 - Governance
    P1 --> P1_1[Roles - Rifat]
    P1 --> P1_2[Risk Reg - Rifat]
    P1 --> P1_3[Logs - Rifat]

    %% Phase 2 - Backend
    P2 --> P2_1[Flask - Samiur]
    P2 --> P2_2[DB - Samiur]
    P2 --> P2_3[Spike - Samiur]

    %% Phase 3 - Frontend
    P3 --> P3_1[UI/Wire - Abd.]
    P3 --> P3_2[Emails - Abd.]
    P3 --> P3_3[Dash - Abd.]

    %% Phase 4 - Integration
    P4 --> P4_1[Merge - Team]
    P4 --> P4_2[API Test - Team]
    P4 --> P4_3[Ethics - Rifat]

    %% Phase 5 - Final
    P5 --> P5_1[Peer Rev - Team]
    P5 --> P5_2[Video - Team]
    P5 --> P5_3[<b>Due: May 15</b>]

    %% Compact Styling
    style P fill:#2c3e50,color:#fff
    style P1 fill:#e67e22,color:#fff
    style P2 fill:#f1c40f
    style P3 fill:#9b59b6,color:#fff
    style P4 fill:#2ecc71
    style P5 fill:#e74c3c,color:#fff

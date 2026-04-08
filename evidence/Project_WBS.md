graph LR
    %% Main Project
    Project[<b>CyberShield Project</b>] --- P1(Phase 1: Governance)
    Project --- P2(Phase 2: Backend)
    Project --- P3(Phase 3: Frontend)
    Project --- P4(Phase 4: Integration)
    Project --- P5(Phase 5: Closure)

    %% Phase 1 - Rifat's Domain
    P1 --> P1_1[Appoint Roles <br/><i>Owner: Rifat</i>]
    P1 --> P1_2[Risk Register <br/><i>Owner: Rifat</i>]
    P1 --> P1_3[3 Meeting Logs <br/><i>Owner: Rifat</i>]

    %% Phase 2 - Samiur's Domain
    P2 --> P2_1[Flask Env Setup <br/><i>Owner: Samiur</i>]
    P2 --> P2_2[SQLite DB Design <br/><i>Owner: Samiur</i>]
    P2 --> P2_3[Technical Spike <br/><i>Owner: Samiur</i>]

    %% Phase 3 - Abdullah's Domain
    P3 --> P3_1[UI Wireframes <br/><i>Owner: Abdullah</i>]
    P3 --> P3_2[Email Templates <br/><i>Owner: Abdullah</i>]
    P3 --> P3_3[Admin Dashboard <br/><i>Owner: Abdullah</i>]

    %% Phase 4 - Team Domain
    P4 --> P4_1[System Merging <br/><i>Owner: Team</i>]
    P4 --> P4_2[API Testing <br/><i>Owner: Team</i>]
    P4 --> P4_3[Ethical Check <br/><i>Owner: Rifat</i>]

    %% Phase 5 - Final Domain
    P5 --> P5_1[Peer Review <br/><i>Owner: Team</i>]
    P5 --> P5_2[Final Demo Video <br/><i>Owner: Team</i>]
    P5 --> P5_3[<b>Submission May 15th</b>]

    %% Styling for better look
    style P1 fill:#e67e22,stroke:#333,color:#fff
    style P2 fill:#f1c40f,stroke:#333
    style P3 fill:#9b59b6,stroke:#333,color:#fff
    style P4 fill:#2ecc71,stroke:#333
    style P5 fill:#e74c3c,stroke:#333,color:#fff
    style Project fill:#2c3e50,color:#fff,stroke-width:4px

graph TD
    %% Main Project Header
    Project[<b>Project: CyberShield Simulator</b>] --- Bridge(( ))
    
    %% Horizontal Branching Line (The Shoulder)
    Bridge --- P1(<b>Initiation</b><br/>Phase 1)
    Bridge --- P2(<b>Planning</b><br/>Phase 2)
    Bridge --- P3(<b>Execution</b><br/>Phase 3)
    Bridge --- P4(<b>Control</b><br/>Phase 4)
    Bridge --- P5(<b>Closure</b><br/>Phase 5)

    %% Column 1 - Rifat (Initiation)
    P1 --- P1_1[Appoint Roles - Rifat]
    P1 --- P1_2[Define Goals - Rifat]
    P1 --- P1_3[3 Meeting Logs - Rifat]
    P1 --- P1_4[Risk Analysis - Rifat]

    %% Column 2 - Samiur (Planning)
    P2 --- P2_1[Setup Flask - Samiur]
    P2 --- P2_2[Task Plan - Samiur]
    P2 --- P2_3[SQLite Design - Samiur]
    P2 --- P2_4[Tech Spike - Samiur]

    %% Column 3 - Abdullah (Execution)
    P3 --- P3_1[UI Wireframes - Abdullah]
    P3 --- P3_2[Email Templates - Abdullah]
    P3 --- P3_3[Admin Portal - Abdullah]
    P3 --- P3_4[Documentation - Team]

    %% Column 4 - Rifat/Team (Control)
    P4 --- P4_1[Scope Control - Rifat]
    P4 --- P4_2[System Merge - Team]
    P4 --- P4_3[Perform Tracking - Rifat]
    P4 --- P4_4[Quality Mgmt - Team]

    %% Column 5 - Team (Closure)
    P5 --- P5_1[Internal Review - Team]
    P5 --- P5_2[Project Report - Team]
    P5 --- P5_3[Product Delivery - Team]
    P5 --- P5_4[<b>Submission May 15</b>]

    %% Style colors to match your picture exactly
    style P1 fill:#e67e22,stroke:#333,color:#fff
    style P2 fill:#f1c40f,stroke:#333
    style P3 fill:#FF69B4,stroke:#333,color:#fff
    style P4 fill:#9ACD32,stroke:#333
    style P5 fill:#e74c3c,stroke:#333,color:#fff
    style Project fill:#2c3e50,color:#fff,stroke-width:2px
    style Bridge width:0px,height:0px,opacity:0

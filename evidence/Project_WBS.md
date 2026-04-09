graph TD
    %% This 'Bridge' creates the horizontal 'shoulder' line you want
    Project[<b>Project: CyberShield Simulator</b>] --- Bridge(( ))
    
    %% Horizontal Branching
    Bridge --- P1(<b>Initiation</b><br/>Phase 1)
    Bridge --- P2(<b>Planning</b><br/>Phase 2)
    Bridge --- P3(<b>Execution</b><br/>Phase 3)
    Bridge --- P4(<b>Control</b><br/>Phase 4)
    Bridge --- P5(<b>Closure</b><br/>Phase 5)

    %% Column 1 - Rifat
    P1 --- P1_1[Appoint Roles<br/><i>Rifat</i>]
    P1 --- P1_2[Define Goals<br/><i>Rifat</i>]
    P1 --- P1_3[3 Meeting Logs<br/><i>Rifat</i>]
    P1 --- P1_4[Risk Analysis<br/><i>Rifat</i>]

    %% Column 2 - Samiur
    P2 --- P2_1[Setup Flask<br/><i>Samiur</i>]
    P2 --- P2_2[Task Plan<br/><i>Samiur</i>]
    P2 --- P2_3[SQLite Design<br/><i>Samiur</i>]
    P2 --- P2_4[Tech Spike<br/><i>Samiur</i>]

    %% Column 3 - Abdullah
    P3 --- P3_1[UI Wireframes<br/><i>Abdullah</i>]
    P3 --- P3_2[Email Templates<br/><i>Abdullah</i>]
    P3 --- P3_3[Admin Portal<br/><i>Abdullah</i>]
    P3 --- P3_4[Documentation<br/><i>Team</i>]

    %% Column 4 - Rifat
    P4 --- P4_1[Scope Control<br/><i>Rifat</i>]
    P4 --- P4_2[System Merge<br/><i>Team</i>]
    P4 --- P4_3[Task Tracking<br/><i>Rifat</i>]
    P4 --- P4_4[Quality Mgmt<br/><i>Team</i>]

    %% Column 5 - Team
    P5 --- P5_1[Internal Review<br/><i>Team</i>]
    P5 --- P5_2[Project Report<br/><i>Team</i>]
    P5 --- P5_3[Product Delivery<br/><i>Team</i>]
    P5 --- P5_4[<b>Submission May 15</b>]

    %% Colors matching your picture
    style P1 fill:#e67e22,stroke:#333,color:#fff
    style P2 fill:#f1c40f,stroke:#333
    style P3 fill:#FF69B4,stroke:#333,color:#fff
    style P4 fill:#9ACD32,stroke:#333
    style P5 fill:#e74c3c,stroke:#333,color:#fff
    style Project fill:#2c3e50,color:#fff,stroke-width:2px
    style Bridge width:0px,height:0px,opacity:0

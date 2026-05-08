# recruitment-pipeline-tracker
End-to-end recruitment tracker for 10 roles, 135 candidates — sourcing channel performance, TAT analysis, and stage funnel dashboard in Excel.
What This Is
A fully functional recruitment pipeline tracker covering 10 open requisitions, 135 candidates, and end-to-end stage tracking from JD sharing to joining. Built to replicate what an actual HR team would maintain in a shared Excel — but structured properly, with a dashboard, TAT analysis, and source channel performance.

Key Numbers
MetricValueOpen Requisitions10Total Candidates Tracked135Hires Closed9Offer Conversion Rate~11.9%Average TAT (JD to Joining)26 daysBest sourcing channelLinkedIn / Naukri

Files
project2-recruitment-tracker/
├── data/
│   └── recruitment_pipeline_data.csv   # Full candidate dataset
├── outputs/
│   └── Recruitment_Tracker_Swarnadwip.xlsx  # Dashboard + pipeline
├── build_tracker.py                    # Build script
└── README.md

How to Run
bashpip install pandas openpyxl
python3 build_tracker.py

What the Excel Contains

Recruitment Dashboard — KPI tiles (requisitions, candidates, hires, offer rate, avg TAT), sourcing channel performance table with hit rate per portal, full pipeline stage funnel with visual bar indicators
Full Pipeline sheet — All 135 candidates with current stage, dates, salary expectations, notes, and status
TAT Analysis sheet — Role-by-role TAT vs target comparison with over/under flag per requisition


Roles Tracked
Network Engineer, HR Executive, Sales Manager, DevOps Engineer, Finance Analyst, Content Strategist, QA Engineer, Payroll Specialist, Operations Lead, Brand Manager

Skills Demonstrated

Python (pandas, openpyxl)
Recruitment operations and pipeline management
TAT tracking and target-setting logic
Multi-sheet Excel dashboard design
Sourcing channel performance analysis

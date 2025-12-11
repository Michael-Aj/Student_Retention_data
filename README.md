README


This synthetic dataset is generated to mimic at-risk tracking for student retention analytics.
Rules:
- Marks only appear when an assessment is present; otherwise blank.
- Reason for AR is derived from thresholds:
   * Attendance < 0.70 -> Class Attendance_007
   * Canvas Activity < 0.60 -> Canvas Activity_007
   * If assessment exists and Mark < 50 -> Assessment Failure_007
- Risk Level is computed: High if assessment failure or both attendance & canvas very low; Medium for a single low factor; early weeks escalate Medium to High.
- Interventions map to risk: High -> Counselling/Escalation/Tutoring; Medium -> Email/Mentorship/Tutoring; Low -> None.
- Resolution likelihood increases over weeks and is lower for High risk.
Use ethically: no real student data. For research/teaching only.
South Africa (SA) Context:
- 'NQF Level' has been added to align qualifications with the South African National Qualifications Framework (NQF).
- Example mapping used in this synthetic dataset: Programme1=NQF5 (Higher Certificate), Programme2=NQF6 (Diploma), Programme3=NQF7 (Bachelor's), Programme4=NQF8 (Honours/PGDip), Programme5=NQF9 (Master's).
- No real student data is used; all values are randomly generated within rule-driven thresholds for ethical use.

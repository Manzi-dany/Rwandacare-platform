# RwandaCare Intelligence Platform

A health intelligence platform designed to improve health outcomes 
for Rwandans in underserved communities by giving patients, community 
health workers, and clinicians better information at every stage of 
the care journey.

Built by a Rwandan founder who experienced the failures this platform 
addresses — personally and in his family.



 The Problem

Rwanda's health system has made real progress. But three persistent 
gaps affect millions of patients, particularly in rural communities:

1. Information loss at the point of care
Patients arrive at consultations without structured records of their 
symptom history. Doctors make decisions with incomplete information. 
Conditions that should be caught early are missed.

2. No personalized nutrition guidance
Patients with chronic conditions receive generic advice with no 
connection to locally available foods or their specific situation. 
Diet-related complications are preventable with the right information 
delivered the right way.

3. No medication verification
Patients cannot verify whether medications are genuine, properly 
stored, or within expiry date. Counterfeit and degraded medications 
are an underreported problem affecting treatment outcomes across 
Rwanda.



 The Solution

Three integrated modules delivered through one mobile-first platform:

 Module 1 — HealthIQ
A patient health history collection and structured summary tool.

Patients input their symptoms, previous illnesses, medications, and 
family health history. The system generates a structured summary in 
Kinyarwanda and English that the patient brings to their consultation. 
The doctor receives better information. The patient gets continuity 
of care across every visit.

Status: In development



 Module 2 — NutriIQ
Personalized nutrition guidance for chronic disease patients.

Using data already collected in HealthIQ, NutriIQ analyzes the 
patient's specific health conditions and generates a personalized 
weekly meal plan using foods available in their district. Built on 
a Rwandan food database — not Western food databases that recommend 
ingredients unavailable in rural Rwanda.

Status: Planning phase — dependent on HealthIQ completion



 Module 3 — MedScan
Medication verification through barcode scanning.

Patients, community health workers, and pharmacists scan medication 
barcodes to verify registration with Rwanda FDA, check expiry dates, 
and access medication information in Kinyarwanda. Suspicious 
medications can be reported directly to Rwanda FDA through the app.

**Status:** Planning phase — requires Rwanda FDA partnership



 Who This Is For

- Patients in rural and peri-urban Rwanda managing chronic conditions
- Rwanda's 45,000+ community health workers
- Clinicians at health centers and district hospitals
- Rwanda Ministry of Health and health program implementers



Technology Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js — mobile-first, low-bandwidth optimized |
| Backend | Python with Django REST framework |
| Database | PostgreSQL with encrypted patient data |
| AI Layer | Python scikit-learn for symptom pattern analysis |
| Cloud | AWS S3 and Lambda |
| Languages | Kinyarwanda and English throughout |
| Offline | Core functions work without internet, sync on connection |

---

 Why This Will Work

Most health technology built for Africa is designed by people who 
have never needed it personally.

This platform is built by someone who:

- Grew up in a rural community in Rubavu District, Rwanda, where 
  his mother went undiagnosed for months with a blood infection 
  that basic diagnostic tools would have caught
- Found out about his own chronic condition during a medical 
  screening rather than through the health system
- Spent eight months conducting nutrition research on affordable 
  supplements for underserved communities at UVU Bio Laboratories
- Worked as a Digital Health Ambassador training rural community 
  health workers on digital health tools at Society for Family 
  Health Rwanda
- Has direct relationships with the community health worker network 
  in western Rwanda



 Development Roadmap

  Phase 1 — Foundation (Current — Months 1 to 3)
- [ ] Build SQL and Python data analysis skills for health data
- [ ] Design HealthIQ patient data schema
- [ ] Build Rwandan symptom and disease dataset
- [ ] Create HealthIQ wireframes and user flow

 Phase 2 — HealthIQ Prototype (Months 4 to 6)
- [ ] Build patient data input interface in Next.js
- [ ] Build Python backend for symptom pattern analysis
- [ ] Build structured summary generator in Kinyarwanda and English
- [ ] Test with 20 community members in Rubavu District
- [ ] Document user feedback and iterate

 Phase 3 — Partnership and Validation (Months 7 to 9)
- [ ] Pilot with SFH Rwanda community health program
- [ ] Academic partnership with UGHE or University of Rwanda
- [ ] Apply for Rwanda ICT innovation funding through RDB
- [ ] Begin building Rwandan food database for NutriIQ

 Phase 4 — NutriIQ Integration (Months 10 to 12)
- [ ] Build NutriIQ on top of HealthIQ patient database
- [ ] Complete Rwandan food nutrient database
- [ ] Connect health conditions to nutritional recommendations
- [ ] Integrate with Bio-Nutri supplement recommendations

 Phase 5 — MedScan and Scale (Year 2)
- [ ] Initiate Rwanda FDA partnership for medication database
- [ ] Build MedScan verification module
- [ ] Seek development organization partnership for national scale



 Current Progress

April 2026**
- Project concept documented
- Technical architecture defined
- GitHub repository created
- Building SQL and Python foundations for data layer


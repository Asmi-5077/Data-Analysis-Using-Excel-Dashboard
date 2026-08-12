# Hospital-Emergency-Room-Data-Analysis (Interactive Dashboard creation using Ms Excel)
## Project Objectives 
The hospital management wants to create an Emergency Room Operational Report for 2023–2024 to understand patient volume, wait times, and attendance delays. By analyzing this data, administrators can reduce patient wait times, fix triage bottlenecks (59% delay), optimize doctor staffing, and improve emergency care quality

## Dataset Used 
- <a href="https://github.com/Asmi-5077/Data-Analysis-Using-Excel-Dashboard/blob/main/Hospital%20Emergency%20Room%20Data%20xlsx.xlsx">Dataset</a>

## Questions (KPIs) 
-  How many total patients were processed in the Emergency Room during the selected period?
-  What is the average patient wait time before receiving medical care?
-  How satisfied are patients with the emergency service provided?
-  What proportion of emergency patients require hospital admission vs. discharge?
-  What percentage of patients were attended on time versus experiencing operational delays?
-  Which medical specialties receive the highest volume of ER referrals?
-  How are ER visits distributed across age groups and gender?

- Dashboard Interaction <a href="https://github.com/Asmi-5077/Data-Analysis-Using-Excel-Dashboard/blob/main/hospital%20emergency%20dashboard%20pic.png">View Dashboard</a>

- ## Process
- Imported raw emergency room patient data with times, ages, gender, and admission records.
- Cleaned date formats, removed duplicate or missing data, and fixed data types.
- Grouped patient ages into age ranges and split attendance into delay or on time.
- Calculated key metrics like total patients, average wait time, and satisfaction score.
- Created pivot tables according to the questions asked.
- Merge all pivot tables into one dashboard and apply slicer to make it dynamic
- Tested all filters and charts to make sure the data updates correctly.

## Dashboard 
![Uploading hospital emergency dashboard pic.png…](https://github.com/Asmi-5077/Data-Analysis-Using-Excel-Dashboard/blob/main/hospital%20emergency%20dashboard%20pic.png)

## Project Insight

### 1. Patient Admission Analysis
- **Admitted:** ~4,612 patients (~50.04%) required hospital admission for further treatment.
- **Not Admitted:** ~4,604 patients (~49.96%) were discharged after emergency care.

### 2. Patient Attend Status
- **Delay:** **59%** of patient attendances experienced operational delay.
- **On Time:** **41%** of patients were attended on time.

### 3. Demographic & Gender Analysis
- **Female:** **51%**
- **Male:** **49%**
- A balanced gender ratio across all emergency room visits.

### 4. Age Group Distribution
- **20–29 Years:** Peak emergency room visits (**1,207 patients**).
- **30–39 Years:** **1,191 patients**.
- **0–9 Years:** **1,176 patients**.
- **60–69 Years:** **1,150 patients**.
- **50–59 Years:** **1,147 patients**.
- **10–19 Years:** **1,160 patients**.
- **40–49 Years:** **1,137 patients**.
- **70–79 Years:** **1,048 patients**.

### 5. Departmental Referrals
- **None (Direct Care/Discharge):** Highest share of cases.
- **General Practice:** Primary secondary referral line (~1,800+ patients).
- **Orthopedics:** Second most common specialty referral (~1,000+ patients).
- **Other Departments:** Physiotherapy, Cardiology, Neurology, Gastroenterology, Renal.












# Movie Box Office Analysis & Insights
## Project Overview
This project analyzes movie industry data from multiple sources to identify the types of films that perform best at the box office.  
It aims to guide a new movie studio in making data-driven decisions on what to produce, when to release it, and how to budget effectively.
## Business Understanding
**Stakeholder:** Head of the company’s new movie studio.  
**Key Business Questions:**
1. Which genres generate the highest revenue and ROI?
2. What is the optimal budget range for maximizing profit?
3. Does release timing (month/season) impact movie success?
4. Do movie ratings correlate with box office performance?
5. Which studios consistently produce high-grossing films?
## Data Understanding and Analysis
**Data Sources**
- **Box Office Mojo** – Domestic and worldwide gross earnings.
- **The Numbers** – Production budgets and financials.
- **Rotten Tomatoes** – Movie ratings and reviews.
- **TMDb** – Additional movie metadata.

**Description of Data**
- **Key Columns:** `release_date`, `title`, `production_budget`, `domestic_gross`, `worldwide_gross`, `genres`, `ratings`, etc.  
- **Cleaning Steps:** Removed duplicates, handled missing values, standardized column formats, and merged datasets by title.
- 
**Tools and Technologies**
**Python** (pandas, matplotlib, seaborn)
**Tableau** – Interactive dashboards
**Jupyter Notebook** – Data cleaning, exploration, and visualization

**Visualizations:**
1. **ROI by Budget Range**
<img width="954" height="846" alt="Budget Range vs ROI" src="https://github.com/user-attachments/assets/746fe72e-d709-428b-962f-8b12e0078849" />
2. **Profitability by Genre** 
<img width="1569" height="847" alt="Genre Vs Revenue" src="https://github.com/user-attachments/assets/e783bd22-f86d-497d-9d9a-437b3eee3aff" />
3. **Release Month Performance**
<img width="1524" height="846" alt="Release Month vs Box Office Success" src="https://github.com/user-attachments/assets/1432c141-500e-4d4d-84f6-b324cd92552c" />

## Conclusion
**Key Findings**
**Genres**: Family + Fantasy + Musical and Adventure-based films lead in revenue; low-cost Horror/Thriller blends yield high ROI.
**Budgets**: $0M–$3M films have the highest ROI; big-budget films have smaller margins.
**Timing**: Summer (May–July) is most profitable; avoid January and February for ROI-driven releases.
**Ratings**: High ratings don’t guarantee high revenue — audience appeal matters more.
**Studios**: Paramount/DreamWorks and Disney dominate global earnings.

**Recommendation**
- Prioritize Action/Adventure films.
- Target for less than $10M budgets.
- Aim for June/ July / December releases.
- Prioritize crowd-pleasing stories and clever marketing.
- Collaborate with top studios like P/WD and BV.

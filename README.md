# portugese-bank-marketing-campaign  
## Marketing Campaign Analysis Report  
**Dataset Size:** 4,521 rows × 17 columns  
## Objective  
To understand customer behavior and improve the effectiveness of marketing campaigns based on call interactions and subscription outcomes.  

## 🧼 Data Preparation  
**Delimiter Adjustment:** Used Excel's Text to Columns feature to convert semicolon-separated values into structured format.  

**Outlier Detection:** Employed IQR method to detect outliers in numerical columns (Age, Balance, Duration, Campaign, Pdays, Previous).  

**Categorization:** Grouped numerical outliers for easier interpretation (e.g., balance levels: overdrawn, low, medium, high, very high).  

**Missing Values:** No nulls; values marked as unknown were retained and grouped for visualization.  

**Data Cleaning Outcome:** A clean and structured dataset ready for visualization and insight extraction.  

## 📌 Dashboard 1:  
### customer Profile Overview  
This dashboard visualizes demographic characteristics of customers and how these attributes relate to call frequency and term deposit subscriptions.  

### 🔍 Key Observations & Causes  
**Age (25–44):** This age group made the highest call volume and subscription rate. This could be due to some factors like Prime working-age; financially active and decision-capable  
**Marital (Married):**62% of calls and over 50% of subscriptions were made by the married people which is quite significant. Married individuals may prioritize long-term financial security  
**Education (Secondary):**Largest share of both calls and subscriptions	Possibly the dominant educational group in the customer base is the secondary group.  
**Job (Manager, Technician, Blue Collar):** These jobs hadh igh subscription rates.	These job types often correlate with stable incomes and savings potential.  
**Default Status:**	Only 2% of defaulters subscribed. Indicates risk aversion or automatic disqualification.  
**Balance Level:**	Low balance group had most calls and subscriptions,	May indicate large population segment or recent salary deposits.  
**Housing Loan:** 42% of subscribers had a housing loan. Homeowners may be more financially engaged.  
**Personal Loan:**	Only 8% of personal loan holders subscribed, Personal debt might discourage further financial commitment.  

### ✅ Recommendations for Customer Profile Targeting  
**Segment-Focused Campaigns:**  

Prioritize age groups 25–44, especially 35–44, for future outreach.  

Target married individuals with tailored messages on long-term savings benefits.  

**Refine Customer Personas:**  

Create job-based personas (e.g., “Manager Investor”) to drive personalized messaging.  

**Deprioritize High-Risk Segments:**  

Avoid targeting defaulting and personal loan customers for term deposit offers.  

**Leverage Low & Medium Balance Groups:**  

These segments are most active and responsive—tailor offers around growth potential.  

<img src="/assets/WhatsApp Image 2025-06-04 at 8.30.21 AM.jpeg" alt="Dashboard 1" width="350"/>

## 📌 Dashboard 2: Marketing Campaign Performance  
This dashboard highlights the effectiveness of marketing strategies including contact methods, timing, call duration, and customer history.

### 🔍 Key Observations & Causes  
**Contact History (Pdays):** 82% of customers were never contacted before. Cold contacts likely reached through bulk campaign blast.  
**Campaign Frequency:**	Follow-up (2–3 calls) and first-time contacts made the most calls.	First contact has higher freshness, follow-ups show persistence—but too many deter.  
**Call Duration:**	Very long calls (outliers) converted better	Indicates that persuasive calls require time and explanation.  
**Contact Type:** Cellular generated most subscriptions	Personal and direct channel, ideal for engaging conversations.  
**Previous Campaign Outcome (Poutcome):**	New contacts converted most	Cold outreach performs surprisingly well, might be due to improved pitch or timing.  
**Seasonality (Month):**	May had the highest subscriptions. May could coincide with bonuses, tax returns, or seasonal financial planning.  

### ✅ Recommendations for Campaign Strategy  
**Optimize Contact Frequency:**  

Maintain follow-up range at 1–2 attempts; avoid aggressive re-contacting (>4 calls).  

Emphasize first contact conversion with strong messaging.  

**Improve Agent Training:**  

Train agents for longer and high-quality calls to maximize persuasive opportunities.  

Implement soft scripts and active listening techniques.  

**Prioritize Contact Channels:**  

Focus on cellular contacts; deprioritize low-performance channels (e.g., telephone/unknown).  

**Leverage Historical Insights:**  

Customers never contacted before are still highly convertible—don’t ignore cold lists.  

Use A/B testing to compare message effectiveness by campaign stage.  

**Time Campaigns Strategically:**  

Run major pushes during May and August—optimize around financial seasons or bonuses.  

<img src="/assets/WhatsApp Image 2025-06-04 at 8.30.26 AM.jpeg" alt="Dashboard 2" width="350"/>

## 📉 Performance Overview  
Total Calls: 4,521  

Subscribers: 521  

Conversion Rate: 11.5%  

Despite low conversion, detailed segmentation and campaign behavior analysis reveal several levers for optimization.  

## 🧠 Final Thoughts  
This analysis suggests that effective marketing outcomes are not solely driven by volume but by targeting the right segments with thoughtful communication and timing. Focusing on customer relevance, engagement quality, and strategic timing can significantly improve campaign efficiency and ROI.

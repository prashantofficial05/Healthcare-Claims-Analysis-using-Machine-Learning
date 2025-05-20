### Healthcare-Claims-Analysis-using-Machine-Learning
    
  **Introduction:** 
  
  This project involves the exploratory data analysis and predictive modeling of a synthetic healthcare claims dataset. The goal is to uncover patterns in patient-level data (PLD), understand treatment compliance, and identify risk factors contributing to treatment dropouts. These insights can support healthcare providers and payers improve patient care pathways, reducing costs, and optimizing claim processing strategies. 
  
**Goal:**

  To analyze synthetic healthcare claims data to predict treatment dropout risk, understand patient journey and claim status behavior, and support healthcare compliance and operational decision-making using machine learning models.

**Description:**
 
  The project leverages synthetic claims data simulating real-world claim submissions, denials, and outcomes. It answers key business and clinical questions, including:

  - **Dropout Prediction:** Identify patients at high risk of discontinuing treatment prematurely.
  - **Claim Status Patterns:** Understand approval/denial trends and root causes.
  - **Compliance Behavior:** Model the patient journey and analyze follow-up and AR (Accounts 
    Receivable) behavior.
  - **Payer Trends:** Compare claim approval rates and payment behavior across insurance types 
     (Self-Pay, Medicare, Commercial).
  - **Revenue Leakage:** Identify partially paid or denied claims that could be recovered with improved billing practices..
   
**Skills:**
  - **Python:**
  - Data cleaning with Pandas and NumPy
  - EDA using Seaborn, Matplotlib
  - Predictive modeling using Random Forest and Logistic Regression
  - **Analytics:** Classification modeling, patient segmentation, outcome analysis
  Tools:
  - Python: pandas, scikit-learn, seaborn, matplotlib
  - SQL: PostgreSQL (for querying large relational claims datasets)
  - Jupyter Notebook: For full workflow development and visualization
    

**Metrics:**
  - **Dropout Prediction Accuracy:** 88%.
  - **F1 Score:** 0.85
  - **Claim Denial Rate:** % of denied vs total claims
  - **Partial Payment Rate:** % of claims paid < billed amount.
  - **Follow-up Requirement Rate:** % of claims flagged for additional action
  - **AR Status by Outcome:** Recovery likelihood based on claim status
    
**Key Findings:**

   - **Self-pay claims** had the highest denial and partial payment rates, often due to missing 
     or incorrect billing codes.
   - **Commercial insurance** showed the fastest approval cycle but had a high rate of "Under 
      Review" claims.
   - **Claims requiring follow-up** were 3.5x more likely to be partially paid or denied.
   - **Dropout risk was higher among patients with **pending AR status, multiple denials, and 
       frequent diagnosis of chronic conditions**.
   - **Procedure code 99213** was most commonly associated with denied claims when billed with 
    specific diagnosis codes like A00.1 and A16.5.


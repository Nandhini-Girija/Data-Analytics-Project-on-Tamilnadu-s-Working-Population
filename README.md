# Workforce Distribution Analysis in Tamil Nadu  

## **Project Overview**  
This project analyzes the **workforce distribution in Tamil Nadu, India**, based on **demographic and industrial factors**. The dataset provides insights into **employment trends, gender disparities, and age distribution** across rural and urban regions. The study leverages **data analytics techniques** to support policymakers in improving labor policies.  

## **Key Features**  
✔ **Gender & Age Distribution Analysis**: Workforce composition by gender and age groups.  
✔ **Industry-Wise Workforce Analysis**: Employment trends across 18+ industry sectors.  
✔ **Employment Trends**: Identifies industries with the highest workforce concentration.  
✔ **Data Preprocessing & Normalization**: Cleans and structures the dataset for analysis.  
✔ **Visualization & Insights**: Uses charts and graphs to depict employment patterns.  

## **Dataset Attributes**  
The dataset includes:  
- **District Code & Area Name**: Identifies rural and urban regions.  
- **Age Groups**: Categorized workforce from **5-9 years** to **80+ years**.  
- **Industry Categories (A-U)**: Workforce distribution across sectors like **Agriculture, Manufacturing, IT, Construction, Healthcare, Education, and Public Administration**.  
- **Gender-Based Employment**: Workforce count segmented by male and female employees.  

## **Workflow**  
### **1. Data Preprocessing**  
- Removed redundant attributes (e.g., **State Code, Table Code**).  
- Normalized dataset structure for **efficient processing**.  
- Handled missing values and formatted age groups.  
- Mapped industry categories to **short codes for easier visualization**.  

### **2. Gender & Age Distribution Analysis**  
- Compared **male vs. female workforce participation** in different industries.  
- Used **pie charts, bar graphs, and heatmaps** to visualize gender disparities.  
- Modeled **age distribution trends** to predict future workforce shifts.  

### **3. Industry-Wise Employment Trends**  
- Analyzed **top 5 industries with the highest workforce concentration**.  
- Explored **employment trends across 33 districts** of Tamil Nadu.  
- Evaluated **young workforce participation** in emerging industries.  


## **Installation & Setup**  
### **1. Prerequisites**  
Ensure you have **Python** installed along with required libraries:  

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

### **2. Run the Analysis Script**  
To process and visualize the workforce data:  

```sh
python workforce_analysis.py
```

## **Results & Insights**  
✔ **Gender Disparities in Employment**:  
   - **Higher male participation** in Agriculture, Mining, and Manufacturing.  
   - **Higher female participation** in Education, Healthcare, and NGOs.  

✔ **Age-Based Workforce Trends**:  
   - **40-49 age group** has the highest employment share across industries.  
   - **Youth workforce (20-24 years)** is concentrated in **IT & Manufacturing**.  

✔ **Industry-Wise Workforce Trends**:  
   - **Agriculture & Manufacturing dominate** employment in 21 out of 33 districts.  
   - **Public Administration & Trade** have steady workforce growth.  

✔ **Policy Recommendations**:  
   - Need for **youth skill development programs** in key industries.  
   - Strategies to **bridge the gender gap** in male-dominated sectors.  
   - **Better workforce planning** to ensure industry sustainability.  

## **Future Enhancements**  
🔹 **Predictive Analysis**: Forecast employment trends using machine learning.  
🔹 **Geospatial Mapping**: Visualize workforce data across districts on an interactive map.  
🔹 **Web Dashboard**: Develop a real-time dashboard for policymakers.  

## **Authors**  
- **Nandhini K (M230788EC)**  
- **National Institute of Technology Calicut, India**  

# Public Company ESG Performance Analysis

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)



## Project Overview

### Business Case

Environmental, Social and Governance (ESG) performance has become an important consideration for organisations and stakeholders seeking to understand how companies perform beyond traditional financial measures.

This project analyses ESG ratings for publicly traded companies to identify patterns in Environmental, Social and Governance performance, explore differences across industries, and examine relationships between ESG dimensions.

The analysis combines data preparation, exploratory data analysis and interactive Power BI visualisations to communicate key findings in a clear and accessible way. The final dashboard is designed to support data-driven understanding of company ESG performance and industry-level variation.

### Target Audience

The primary target audience is business decision-makers and sustainability-focused stakeholders who need a clear overview of ESG performance and industry-level differences without requiring detailed technical knowledge of the underlying analysis.
## Dataset Content

The dataset used in this project is the **Public Company ESG Ratings Dataset**, obtained from Kaggle. It contains data for **722 publicly traded companies** across **21 columns**, including company information, industry, exchange, and Environmental, Social, Governance and Total ESG scores, grades and levels.

The dataset is used to analyse overall ESG performance, compare ESG dimensions, explore industry-level differences and investigate relationships between ESG indicators.

**Dataset Source:** [Public Company ESG Ratings Dataset - Kaggle](https://www.kaggle.com/datasets/alistairking/public-company-esg-ratings-dataset)

## Business Requirements

The project addresses the following business requirements:

### BR1 - Overall ESG Performance

**Requirement:** What is the overall ESG performance of the companies in the dataset?

**How it was addressed:** Overall ESG performance was analysed during EDA and presented on the **ESG Overview** dashboard page using KPI cards and the Overall ESG Level Distribution.

**Outcome:** The analysis showed that **62.47%** of companies were classified as High ESG level and **37.53%** as Medium.

### BR2 - ESG Dimensions

**Requirement:** How do Environmental, Social and Governance performance compare across the companies?

**How it was addressed:** Environmental, Social and Governance scores were analysed during EDA and compared on the **ESG Overview** dashboard page.

**Outcome:** The analysis provided a clear comparison of performance across the three ESG dimensions.

### BR3 - ESG Performance Across Industries

**Requirement:** How does overall ESG performance vary across industries?

**How it was addressed:** Average Total ESG scores were compared across industries during EDA and visualised on the **Industry Analysis** dashboard page.

**Outcome:** Clear differences in average Total ESG performance were identified across industries, supporting **Hypothesis 2**.

### BR4 - Environmental Performance Across Industries

**Requirement:** How does Environmental performance vary across industries?

**How it was addressed:** Average Environmental scores were compared across industries during EDA and presented on the **Industry Analysis** dashboard page.

**Outcome:** Clear differences in Environmental performance were identified across industries, supporting **Hypothesis 3**.


## Hypotheses and Validation

Three hypotheses were investigated during the exploratory data analysis:

### Hypothesis 1: Environmental and Social Performance

**Hypothesis:** Companies with higher Environmental scores tend to have higher Social scores.

**Validation:** The relationship was assessed using correlation analysis and visualisation.

**Result:** Supported. A positive correlation of approximately **0.67** was identified between Environmental and Social scores.

### Hypothesis 2: ESG Performance Across Industries

**Hypothesis:** Overall ESG performance varies across industries.

**Validation:** Average Total ESG scores were compared across industries.

**Result:** Supported. Differences in average Total ESG scores were observed across industries.

### Hypothesis 3: Environmental Performance Across Industries

**Hypothesis:** Environmental performance varies across industries.

**Validation:** Average Environmental scores were compared across industries.

**Result:** Supported. Environmental performance showed clear variation across industries.
## Project Plan

The project followed a structured data analysis workflow:

1. **Planning** - Defined the business case, requirements and hypotheses.
2. **ETL** - Inspected, cleaned and prepared the ESG dataset for analysis.
3. **EDA** - Explored ESG performance, analysed industry patterns and validated the hypotheses.
4. **Power BI Dashboard** - Created interactive visualisations to communicate the main findings.
5. **Evaluation** - Tested the notebooks and dashboard and evaluated the project against the business requirements.

The project uses Git and GitHub for version control, with changes committed throughout the development process.
## Rationale for Mapping Business Requirements to Data Visualisations

The Power BI dashboard was designed around the business requirements:

- **ESG Overview:** KPI cards and charts provide an overview of company ESG performance and compare Environmental, Social and Governance dimensions.
- **Industry Analysis:** Bar charts compare Total ESG and Environmental performance across industries and show the number of companies represented in each industry.
- **ESG Relationships:** A scatter plot with a trend line shows the relationship between Environmental and Social scores and supports the validation of Hypothesis 1.
- **Interactive Filters:** Industry slicers allow users to explore and compare ESG results for selected industries.
## Analysis Techniques Used

The following techniques were used throughout the project:

- **Data Cleaning** - Checked and prepared the dataset for analysis.
- **Descriptive Analysis** - Examined ESG scores and their distributions.
- **Grouping and Aggregation** - Calculated average ESG scores across industries.
- **Comparative Analysis** - Compared Environmental, Social, Governance and Total ESG performance.
- **Correlation Analysis** - Examined the relationship between Environmental and Social scores.
- **Data Visualisation** - Used Python during EDA and Power BI to communicate the main findings.

Generative AI was used to support project planning, code troubleshooting, interpretation and documentation. The final analysis and outputs were reviewed and validated against the project data.
## Key Findings and Recommendations

### Key Findings

- Environmental and Social scores show a positive relationship, with a correlation of approximately **0.67**.
- Overall ESG performance varies across industries.
- Environmental performance also shows clear differences across industries.
- **62.47%** of companies are classified as High overall ESG level, while **37.53%** are classified as Medium.
- Industry representation is uneven, meaning some industries contain considerably more companies than others.

### Recommendations

- ESG performance should be considered across multiple dimensions rather than relying on a single ESG indicator.
- Industry context should be considered when comparing company ESG performance.
- Environmental and Social performance can be assessed together as related indicators, while avoiding causal interpretations of their correlation.
- Industry-level results should be interpreted alongside the number of companies represented in each industry.
## Ethical Considerations

### Data Privacy, Bias and Fairness

The dataset contains public company-level information and does not contain personal or sensitive individual data. Therefore, no significant personal data privacy concerns were identified.

However, potential bias and fairness limitations exist. The dataset contains 722 publicly traded companies and does not represent all companies or industries equally. Some industries contain more companies than others, which may influence industry-level comparisons. ESG ratings are also dependent on the methodology used by the data provider and should not be treated as an absolute measure of whether a company is ethical or unethical.

To reduce misleading interpretations, industry representation was considered when interpreting results, and conclusions were limited to patterns supported by the available dataset.

### Legal and Societal Considerations

The dataset is licensed under **CC BY-NC-SA 4.0**. The original dataset and data providers are acknowledged to comply with attribution requirements, and the data is used for a non-commercial educational project.

From a societal perspective, ESG ratings can influence perceptions of companies. To reduce the risk of misleading conclusions, findings are presented with appropriate context and limitations. Correlations are not interpreted as causation, and ESG scores are presented as provider-based performance indicators rather than definitive judgements about companies.
## Dashboard Design

The interactive Power BI dashboard consists of three pages designed to communicate ESG insights clearly to both technical and non-technical users.

### Page 1 - ESG Overview

Provides a high-level overview of ESG performance using KPI cards, ESG dimension comparisons, overall ESG level distribution and an Industry filter.

![ESG Overview](dashboard/page%201.png)

### Page 2 - Industry Analysis

Compares Total ESG and Environmental performance across industries and shows the number of companies represented in each industry.

![Industry Analysis](dashboard/page%202.png)

### Page 3 - ESG Relationships

Explores the relationship between Environmental and Social scores using a company-level scatter plot and trend line.

![ESG Relationships](dashboard/page%203.png)

### Communication and Accessibility

The dashboard uses clear titles, KPI cards, data labels, short insight statements and interactive Industry filters to make the findings accessible to both technical and non-technical audiences. A consistent layout across the pages supports simple navigation and interpretation.
## Project Evaluation

The project successfully addressed the defined business requirements through ETL, exploratory data analysis and an interactive Power BI dashboard.

The analysis identified differences in ESG performance across industries and a positive relationship between Environmental and Social performance. All three project hypotheses were supported by the analysis.

The Power BI dashboard provides an accessible way for users to explore the results through ESG indicators, industry comparisons and interactive filters.

The findings should be interpreted within the limitations of the dataset, particularly the uneven representation of industries and the methodology used to calculate ESG ratings.

## Testing

Final testing was carried out across the project:

- Both `01_ETL.ipynb` and `02_EDA.ipynb` were run from start to finish without errors.
- The cleaned dataset loaded correctly into Power BI.
- All three dashboard pages were checked for correct visualisation and data display.
- Industry slicers were tested and correctly updated the relevant KPIs and visualisations.
- The ESG relationship scatter plot and trend line displayed correctly.
- The published Power BI dashboard was tested online and worked as expected.
## Unfixed Bugs

No known unfixed bugs were identified during final testing.
## Development Roadmap

### Challenges and Reflection

One of the main challenges was ensuring that the analysis remained focused on the business requirements while avoiding unnecessary complexity.

The dataset also contains some inconsistencies in industry classification and uneven representation across industries. These limitations were considered when interpreting industry-level results.

Power BI was used to transform the analytical findings into an interactive dashboard that could communicate the results clearly to both technical and non-technical users.

### Maintenance and Updates

The project can be updated when new ESG data becomes available by:

1. Updating the raw dataset.
2. Re-running the ETL notebook.
3. Re-running the EDA notebook.
4. Refreshing the cleaned dataset in Power BI.
5. Re-publishing the updated dashboard.
## Deployment

The interactive dashboard was developed in **Microsoft Power BI Desktop** and published to **Power BI Service**.

The published dashboard allows users to explore ESG performance, industry-level differences and the relationship between Environmental and Social performance through interactive visualisations and filters.

### Live Dashboard

https://app.powerbi.com/view?r=eyJrIjoiMzVjODYzOTEtNjNlNC00MTg4LWE0ZGMtODI4NzczNDc4ZDIyIiwidCI6ImMyMzNjMDcyLTEzNWItNDMxZC1hZjU5LTM1ZTA1YmFiZjk0MSIsImMiOjh9 
## Main Data Analysis Libraries

The main Python libraries used in this project include:

- **Pandas** - Data loading, cleaning, transformation and analysis.
- **NumPy** - Numerical operations and data analysis.
- **Matplotlib** - Data visualisation during exploratory data analysis.
- **Seaborn** - Statistical data visualisation and exploration of relationships between ESG variables.

**Power BI** was used to create the interactive dashboard and communicate the final analytical findings.
## Credits and References

- **Dataset:** [Public Company ESG Ratings Dataset - Kaggle](https://www.kaggle.com/datasets/alistairking/public-company-esg-ratings-dataset)
- **ESG Data Source:** [ESG Enterprise](https://www.esgenterprise.com/)
- **Company and Financial Data:** [Finnhub](https://finnhub.io/)
- **Project Template and Learning Materials:** Code Institute - Data Analytics with AI programme.
- **Dashboard:** Microsoft Power BI.
- **Generative AI:** ChatGPT used for troubleshooting during project development.

The dataset is available under the **CC BY-NC-SA 4.0** licence. All external data sources and resources used in the project have been acknowledged.

## Acknowledgements

I would like to thank **Vasi**, my instructor, for his guidance, support and feedback throughout the development of this project.

I would also like to acknowledge **Code Institute** for the course materials, project guidance and resources provided throughout the Data Analytics with AI programme.
# Portfolio Asset: Computational Health Informatics

## Predictive Risk Stratification for Hospital Readmissions: A Comparative Machine Learning Approach Using a Multi-Center Clinical Dataset

* **Author:** Adrian Faña
* **Institutional Alignment:** Department of Health and Nutrition Sciences, Brooklyn College (CUNY)
* **Core Technical Infrastructure:** Python (Pandas, NumPy, Scikit-Learn), SQL, Git
* **Open Source Repository Domain:** [adrianfana.github.io](https://github.io)
* **Contact Architecture:** adrianfana.nyc@gmail.com

---

### 1. Strategic Background & Public Health Objective
Unplanned hospital readmissions within a 30-day post-discharge window represent an expensive, high-friction bottleneck in the United States healthcare matrix, driving significant clinical complications and compounding federal hospital readmission financial penalties. Traditional clinical scoring indexes often fall short because they fail to capture complex, non-linear interactions across diverse, multi-center patient variables. This study engineers an automated computational pipeline to predict 30-day readmission risk, providing clinicians with a high-scarcity, data-driven tool to optimize discharge protocols, lower patient morbidity, and protect institutional hospital bandwidth.

### 2. Clinical Data Source & Advanced Preprocessing
The predictive engine utilizes a comprehensive clinical data archive encompassing **130-US Hospitals and multi-center clinical registries**, spanning thousands of unique inpatient rows. The backend data pipeline was hardcoded natively to parse highly complex demographic, diagnostic, and therapeutic matrices. Crucial preprocessing phases executed in the Python environment included:
* **Missing Value Imputation:** Implementing robust algorithmic controls to handle incomplete clinical records without introducing demographic or diagnostic bias.
* **Categorical Feature Encoding:** Transforming multi-categorical variables—including ICD-9 diagnostic codes, primary admissions anchors, and multi-tiered medication regimens—into clean, high-dimensional numerical vectors.
* **Feature Scaling:** Standardizing continuous physiological indicators (such as blood glucose metrics, lab parameters, and age distributions) to prevent model weight distortion.

### 3. Computational Methodology & Algorithm Architecture
To establish absolute analytical authority, this study implements a rigorous comparative layout contrasting a traditional parametric baseline with an advanced ensemble architecture:
* **Logistic Regression (Parametric Baseline):** Deployed to isolate clear log-odds ratios and map direct linear relationships between primary clinical predictors and discharge outcomes.
* **Random Forest Classifier (Ensemble Machine Learning):** Engineered to map the dense, non-linear feature interactions inherent in multi-center clinical data. The ensemble model was optimized utilizing cross-validation loops, fine-tuning tree depth parameters, and evaluating split metrics to maximize out-of-bag classification velocity while completely preventing training set overfitting.

### 4. Evaluation Dynamics & Analytical Metrics
Model performance was evaluated across strict statistical boundaries to ensure complete data verification. The Random Forest architecture out-classed the traditional baseline models, capturing high-velocity predictive capacity across the full patient pool:
* **ROC-AUC Score:** Demonstrating superior classification sensitivity and mapping a clear probability boundary to separate high-risk and low-risk patient tiers cleanly.
* **Precision-Recall Curve Optimization:** Tailored specifically to maximize recall parameters, ensuring high-risk patient flags are captured accurately without generating unnecessary clinical alarm noise.

### 5. Institutional Moat & Graduate School Alignment
By merging pure biostatistical control with applied predictive machine learning, this framework provides an elite, scalable solution for modern health informatics. Displaying high-scarcity algorithmic capabilities, this portfolio asset proves graduate-level computing maturity—offering direct alignment with advanced research frameworks at **Carnegie Mellon University (CMU), New York University (NYU), and Columbia University**.

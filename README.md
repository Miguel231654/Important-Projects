# Important-Projects
Most significant projects in university years.

**Juice Shop - Web Application Security.**
## Overview
Comprehensive security assessment and penetration testing project conducted on the intentionally vulnerable **OWASP Juice Shop** web application. Following the **CA3 Project** guidelines.

- Tools Used
## Tech Stack & Tools
* **Vulnerable Application:** OWASP Juice Shop.
* **Testing Tools:** Burp Suite.
* **Environment:** Windows / Chrome DevTools.

- Personal contribution
## Key Contributions & Solved Challenges
* **Empty User Registration:** Bypassed frontend and backend validation checks by injecting empty strings (`""`) into the email and password fields during registration, exposing improper input handling.
* **Admin Registration:** Intercepted the registration POST request using Burp Suite and manually added the `"role": "admin"` parameter to successfully register a new user with administrator privileges.
* **Payback Time:** Manipulated the shopping cart's order quantity to a negative value (`-5000`) in the API request, resulting in a negative checkout total and effectively making money from the transaction.
* **Access Log:** Discovered exposed server directories (`/ftp` and robots.txt rules) to navigate through file paths and gain unauthorized access to server access logs (`/support/logs/access.log`).
* **Upload Size:** Bypassed client-side file upload limits in the complaint section by intercepting the POST request via Burp Suite and replacing a small file payload with a file larger than 100 kB.
 
## My Role
Responsible for manually exploiting improper input validation vulnerabilities, manipulating HTTP requests via proxy tools, and analyzing logging and observability failures.

**Fundamentals of AI and Data Science**
Development of a predictive model of CRISP-DM to identify malicious patterns and network traffic in a financial network. This project addresses complex challenges such as class imbalance, data imputation and advanced feature engineering to enhance network security.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Google Colab

## Key Contributions & Pipeline
* **EDA & Imbalance Handling:** Identified class distribution prioritizing **Recall** to avoid missing cyber-attacks.
* **Cleaning & Imputation:** Imputed missing values (mode for categorical, median for numerical).
* **Feature Engineering:** Built custom metrics
* **Classification Model:** Trained a `DecisionTreeClassifier` with `StandardScaler` to classify benign vs. attack traffic.
* **Regression Model:** Developed a Linear Regression model to predict session duration
## My Role
Sole developer responsible for data preprocessing, feature engineering, model training, evaluation, and visualizations.

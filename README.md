# Employees Performance Clustering and Resignation Prediction / Employee Attrition Analysis

![image](https://github.com/roniantoniius/Employees-Performance-Clustering-and-Resignation-Prediction/assets/121453378/cdc2262b-1339-4bfb-a4b1-75a4d5e72fd2)
Image Sources: Pexels.com

## Business Understanding
In the domain of human resource management, understanding and optimizing employee performance is paramount for organizations striving for success and competitiveness in today's dynamic business landscape. The ability to effectively assess and cluster employees based on their performance can provide valuable insights for talent management, resource allocation, and organizational development 📈.

One of the core challenges lies in deciphering the multifaceted nature of employee performance within diverse work environments. Factors such as individual skills, job satisfaction, team dynamics, and organizational culture all contribute to the overall performance landscape. By recognizing these complexities, organizations can harness the power of machine learning techniques to analyze vast arrays of employee data and uncover patterns that illuminate different performance clusters.

The proposed solution involves implementing a clustering model to categorize employees based on performance metrics derived from various sources such as performance evaluations and productivity records. By leveraging machine learning algorithms, organizations can gain deeper insights into the distinct clusters of employees, enabling targeted strategies for talent development, performance improvement, and succession planning. This solution not only enhances HR decision-making processes but also fosters a culture of continuous improvement and employee engagement within the organization ✨.

## Data Understanding 📊
The dataset for the 'Employee's Performance Clustering' project encompasses various attributes pertaining to employee performance within an organization. These attributes serve as key indicators to evaluate and understand the dynamics of workforce productivity and engagement. The dataset includes:

- tingkat_kepuasan: Reflects the level of satisfaction reported by employees, indicating their overall contentment with their roles and the work environment.
- evaluasi_terakhir: Represents the most recent performance evaluation score assigned to each employee, offering insights into their recent job performance.
- jumlah_proyek: Indicates the number of projects an employee has been involved in, providing a measure of their workload and contribution to project activities.
- rata-rata_jam_bulan: Specifies the average number of hours worked by employees per month, offering insights into their productivity levels and work habits.
- waktu_spent_for_perusahaan (year): Represents the duration of time an employee has been with the company, reflecting their tenure and potential impact on performance.
- Kecelakaan_kerja: Indicates whether an employee has experienced a work-related accident, offering insights into workplace safety and its potential effects on performance.
- resign: Binary indicator denoting whether an employee has left the company, providing valuable information on attrition rates and potential turnover factors.
- promosi_5tahun_terakhir: Indicates whether an employee has received a promotion within the last five years, offering insights into career progression and organizational recognition.
- Departemen: Specifies the department or functional area within the organization where the employee is employed, providing context for performance evaluation and analysis.
- gaji: Represents the salary level or compensation package of employees, serving as a proxy for their perceived value and potential motivations within the organization.

## Data Preparation
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Feature Selection
- Encoding
- Balancing Data

## Modelling
- Clustering
- K-Nearest Neighbors Classifier
- Light Gradient Boosting Machine
- Categorical Boosting
- Neural Network

### Clustering
- Cluster 4 (**Underperform**) = Employees in this cluster tend to be dissatisfied and underperforming.
- Cluster 3 (**Overachievers**) = Despite low satisfaction levels, employees in this cluster remain high performers and may feel compelled.
- Cluster 2 (**Balanced Performers**) = Employees in this cluster show a balance between satisfaction and good performance.
- Cluster 1 (**Satisfactory Performers**) = Employees in this cluster have adequate levels of satisfaction and performance.
- Cluster 0 (**High Performers**) = Employees in this cluster are very satisfied and perform very well. It is possible that he/she just got the job
![image](https://github.com/roniantoniius/Employees-Performance-Clustering-and-Resignation-Prediction/assets/121453378/54cc61ce-a0fc-4977-bcb7-468976e6cf33)


## Evaluation
- accuracy
- recall
- f1-score
- precision
- loss

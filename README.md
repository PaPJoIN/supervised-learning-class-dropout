# Applying Supervised Learning to predict student dropout
Evaluating student demographics, engagement and performance metrics for predicting dropout likelihood using supervised learning techniques - Neural Networks &amp; Decision Trees.


## 🔸 Data
The data used in this project was divided into 3 stages, each representing the students' progression through their academic journey, starting with enrollment details, followed by incorporating engagement metrics and finally introducing subject gradings.

## 🔸 Methodology
* Performed data exploration and the necessary preprocessing steps, including encoding and scaling.
* Identified the key correlations between variables.
* Defined, compiled and trained the Neural Network models.
* Performed hyperparamater optimisation using Keras Tuner to further refine accuracy.
* Instantiated and trained the Extreme Gradient Boosting models.
* Applied Grid & Ramdom-Search to further tune the XGBoost models.
* Calculated and compared the models' perfomances across a range of metrics [Accuracy, AUC, Recall & Precision].

## 🔸 Tools
* Python, NumPy, Pandas
* Matplotlib, Seaborn, Scikit-learn
* Keras-Tensorflow & Keras Tuner
* XGboost & Sklearn's GridSearch Cross Validation 

## 🔸 Results & Findings
* The conducted data exploration and analysis provided valuable insights into the factors influencing student dropout. The predictive performance of both XGBoost and Neural Network models progressively improved across the three stages of data inclusion, demonstrating the benefit of incorporating more detailed and performance-based student information (Figures below).
* The findings further revealed areas for improvement. For this, a number of solutions were proposed for imporving in the recruitment & monitoring of student to ensure maximised rates of course completion, including:
  * **Refined Candidate Vetting and tracking Risk profiles per intake:** Conduct further refinement and incorporate predictive indicators identified in application data into the admissions process to better evaluate dropout risk and provide guided 
support.

  * **Enhanced Student Engagement Monitoring:** Integrate systems for continuous monitoring of student absences and engagement metrics and develop automated alerts to flag students exhibiting decreasing attendance.

  * **Strengthened Academic Support triggers:** Design and implement targeted programmes for addressing academic learning challenges, such as academic leads being alerted when students reach dropout-risk thresholds (e.g., >30 unauthorised absences, 1+ failed modules).

<img width="1791" height="590" alt="image" src="https://github.com/user-attachments/assets/0a83bd72-a88f-409d-a933-307f0bccbc43" />
<img width="592" height="166" alt="image" src="https://github.com/user-attachments/assets/294aad0b-ee66-410a-affb-5ca7c2d6aaea" />

## Decision Tree Implementation

This project demonstrates the implementation and visualization of a **Decision Tree** model using **scikit-learn**, one of the most widely used machine learning libraries in Python. The goal is to build a Decision Tree classifier that can predict or classify outcomes based on input data. Decision Trees are intuitive and interpretable models that split data into branches to arrive at a decision, making them an ideal starting point for beginners in machine learning.

---

## Internship Information

- **Company**: CODTECH IT SOLUTIONS PVT. LTD  
- **Name**: Peethani Satya Durga Rao  
- **Intern ID**: CT06DF395  
- **Domain**: Machine Learning  
- **Duration**: 6 Weeks  
- **Mentor**: Neela Santhosh Kumar  

---

## Task Description

The objective of this task is to explore and implement a Decision Tree algorithm from scratch using the `scikit-learn` library. The project follows the entire pipeline of a typical machine learning project—from importing and preparing the data to training, evaluating, and visualizing the model. The decision tree is a supervised learning algorithm used for both classification and regression tasks, and in this project, it is specifically applied for classification.

The main goals of this task include:

- Understanding the fundamental theory behind Decision Tree models.
- Learning how the Gini Index or Entropy is used to decide optimal splits.
- Implementing a Decision Tree classifier on a real-world or sample dataset.
- Evaluating the model's accuracy and understanding potential overfitting.
- Visualizing the decision-making process to interpret how decisions are made.

This task is valuable for building a solid foundation in machine learning, especially for beginners looking to develop their skills in data handling, model training, and result interpretation.

---

## Features

This project includes the following components:

- **Data Preprocessing**: Cleaning and preparing the dataset by handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
- **Model Building**: Using `DecisionTreeClassifier` from scikit-learn to build the model and train it on the dataset.
- **Model Evaluation**: Assessing the performance of the model using metrics such as accuracy, confusion matrix, and classification report.
- **Visualization**: Graphical representation of the decision tree using `matplotlib` and `graphviz` for better interpretability.
- **Code Documentation**: Well-commented and structured code to make it easy to understand and modify.

---

## Technologies Used

- **Python** – Programming language used for implementation.
- **scikit-learn** – Machine learning library for model training and evaluation.
- **pandas** – Used for data manipulation and analysis.
- **matplotlib** – For plotting the decision tree and other visualizations.
- **seaborn** – Optional, for advanced visualization styles.

---

## Requirements

To run this project locally, ensure you have the following installed:

- Python 3.x  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn *(optional for enhanced visuals)*

Install the dependencies using:

```bash
pip install pandas scikit-learn matplotlib seaborn
```
## Expected Output

- Training and testing accuracy
<table style="width: 100%; table-layout: fixed; border-collapse: collaps; text-align: center; max-width: 500px;">
    <tr>
       <th width="20px"> </th><th>sepal length (cm) </th><th>	sepal width (cm) </th><th>	petal length (cm)	</th> <th>petal width (cm)</th><th>	target</th>
    </tr>
    <tr>
<td>0</td><td>	5.1</td><td>	3.5</td><td>	1.4	</td><td>0.2	</td><td>0</td>
    </tr>
    <tr>
<td>1</td><td>	4.9	</td><td>3.0	</td><td>1.4</td><td>	0.2</td><td>	0</td>
</tr><tr>
<td>2	</td><td>4.7	</td><td>3.2</td><td>	1.3</td><td>	0.2	</td><td>0</td>
</tr><tr>
<td>3	</td><td>4.6</td><td>	3.1</td><td>	1.5</td><td>	0.2</td><td>	0</td>
</tr><tr>
<td>4</td><td>	5.0</td><td>	3.6	</td><td>1.4	</td><td>0.2	</td><td>0</td>
    </tr>
</table>

  
- Confusion matrix and classification report
<p>
Accuracy: 1.0
</p>
<p>
Classification Report:
</p>
<table>
    <tr>
     <th> </th> <th>precision </th><th>  recall </th> <th>f1-score  </th> <th>support</th>
    </tr>
    <tr>
     <th> setosa    </td><td>   1.00   </td><td>   1.00  </td><td>    1.00    </td><td>    19 </td>
     </tr><tr>
 <th> versicolor    </td><td>   1.00   </td><td>   1.00   </td><td>   1.00   </td><td>     13 </td>
  </tr><tr>
 <th>  virginica    </td><td>   1.00  </td><td>    1.00   </td><td>   1.00   </td><td>     13 </td>
</tr><tr></tr>
<tr>
  <th>  accuracy   </td><td>          </td>     <td></td>    <td> 1.00 </td><td>       45 </td>
    </tr><tr>
 <th>  macro avg    </td><td>   1.00   </td><td>   1.00    </td><td>  1.00     </td><td>   45 </td>
   </tr><tr>
 <th> weighted avg   </td><td>    1.00   </td><td>   1.00    </td><td>  1.00   </td><td>     45 </td>
</tr>
</table>

- Visual representation of the decision tree

<p align="center">
  <img src="https://github.com/user-attachments/assets/5d5b5981-6c97-40b8-959d-ceb79ad97485" alt="Decision Tree Output" width="500"/>
  <br>
  <em>Figure: Visual Representation of the Trained Decision Tree</em>
</p>


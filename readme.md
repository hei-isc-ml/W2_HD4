# Week 2 - Halfday 4

## Missions & Activities:

### Activity 1 – ~30 minutes
- **Peer Review and Validation of Data Analysis (Halfday 3)**: Work in pairs to review and compare your code and results. Exchange the outcome of the previous activity and discuss your approach. Write together 1-2 slides with a list of the key-differences concerning:
    - The result you had
    - The method you used to get to that results
- **Consolidation by the Professor**: After peer review, the professor will provide further clarification and consolidation of the concepts.

### Activity 2
- **Problem**: Discover and implement Random Forest, and improve your understanding about proper evaluate a classification model.
- **Tools**: scikit-learn
- **New/Consolidation of ML Glossary**: Random Forest, Feature Importance

## Expected Outcomes:
- **Notebook**: Continue and complete your Jupyter notebook by integrating the tasks and explanations outlined below. Provide direct answers to **all** the questions listed below (Section [Questions](#questions)).

## Tasks – Classification (Random Forest)
0. As usual, Copy & Paste your notebook (the .ipynb file) from the previous part in this folder.
    In the terminal, `cd` to the project folder and run the following instructions:

     ```bash
        pip install poetry
        poetry install
    ```
1. **Learn the Basics of Random Forest (RF)**:
   - Understand the transition from Decision Tree to Random Forest: List the steps to theoretically implement a Random Forest by hand.
2. **Implement RF Classification Using scikit-learn on the Titanic Dataset**:
   - Find the best hyperparameters for RF using grid search and k-fold cross-validation.
3. **Evaluate the Performance**:
   - Print the confusion matrix, accuracy, precision, and F1-score.
   - Print the [learning curve](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.learning_curve.html).
   - Identify and print the most [important features](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier.feature_importances_) according to RF and compare them with your earlier correlation analysis.

## Questions:
- Present a step-by-step approach to implementing a Random Forest (RF) from Decision Trees.
- What are the hyperparameters of a Random Forest? What do they represent?
- How can the learning curve help you understand if your model is overfitting or underfitting the data?
- What are the values in the x axis of a learning curve?
- What are possible solutions to overfit/underfit using Random Forest ?
- Talking about model evaluation, why is considering only "accuracy" not enough? Can you provide an example?
- **Random Forest (RF) vs. Decision Tree (DT)**:
   - Which approach is better for explainability and why?
   - Do these approaches require feature rescaling? Why or why not?
   - How should feature encoding be handled in each approach, and why?

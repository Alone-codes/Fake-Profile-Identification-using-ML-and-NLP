# Fake Profile Identification using ML and NLP

This project aims to identify fake profiles on social media (specifically Twitter) using Machine Learning (ML) and Natural Language Processing (NLP) techniques. Three algorithms (Naive Bayes, Linear SVM, and K-Nearest Neighbors) are implemented to classify profiles as genuine or fake based on their textual content.

## Project Overview

The project involves the following components:

1. **Data Collection**: Twitter datasets are used as the source of profile data for training and testing the models.

2. **Preprocessing**: Text preprocessing techniques such as tokenization, stop-word removal, and TF-IDF vectorization are applied to prepare the textual data for model training.

3. Model Training:
   - Naive Bayes: Uses the Naive Bayes algorithm for classification based on probabilistic principles.
   - Linear SVM: Utilizes Support Vector Machine (SVM) with a linear kernel for classification.
   - K-Nearest Neighbors (KNN): Implements the KNN algorithm to classify profiles based on similarity to neighboring data points.

4. Evaluation: The trained models are evaluated using metrics like accuracy, precision, recall, and F1-score to assess their performance in identifying fake profiles.

5. GUI Implementation: The project includes a graphical user interface (GUI) developed using Tkinter to allow users to input profile data and visualize classification results.

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/Alone-codes/fake-profile-identification-using-ML-and-NLP.git
   ```

2. Install the required Python libraries using pip:

   ```
   pip install pandas numpy scikit-learn matplotlib tkinter
   ```

3. Navigate to the project directory:

   ```
   cd fake-profile-identification-using-ML-and-NLP
   ```

## Usage

1. Run the GUI application:

   ```
   python gui.py
   ```

2. Use the GUI interface to input profile data or load Twitter datasets.

3. Select an algorithm (Naive Bayes, Linear SVM, or KNN) to perform profile classification.

4. View the classification results and metrics displayed on the GUI.

## Contributors

- C Vishwanathan
- (https://github.com/Alone-codes)

## References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Python Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README according to your project's specific details and implementation. Include additional sections, such as detailed instructions for dataset preparation, model training, or GUI design, as needed.

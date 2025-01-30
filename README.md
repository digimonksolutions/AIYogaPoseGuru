# YogAi - Yoga Pose Suggestion

## Overview
YogAi is a Jupyter Notebook-based application that recommends personalized yoga poses based on the user's fitness level, flexibility, and desired outcomes. The project utilizes machine learning algorithms to suggest the best yoga poses suited for individual needs, making it perfect for yoga practitioners, fitness enthusiasts, and those looking for personalized exercise guidance.

### Potential Applications:
- Fitness apps
- Yoga studios
- Personalized exercise recommendations

### Intended Audience:
- Yoga practitioners
- Fitness enthusiasts
- Individuals seeking personalized exercise guidance

---

## Libraries and Frameworks

This project uses the following libraries for data manipulation and machine learning:
- **pandas**: For data analysis and manipulation of user profile data and the yoga pose dataset.
- **CountVectorizer**: Converts text data into numerical representations to be used with machine learning algorithms.
- **NearestNeighbors**: A machine learning algorithm to find similar data points, used to recommend poses based on user profiles.
- **LabelEncoder**: Used to encode categorical features into numerical labels for machine learning models.

---

## Dataset

- **Name**: Yoga Pose Dataset
- **Source**: [Google Sheets - Yoga Pose Dataset](https://docs.google.com/spreadsheets/d/1tt-_VuK8Sf1o-Wy-e8EH6MNTah86hiwMeiHHFLHG6Q4/edit?usp=sharing)
- **Format**: CSV
- **Size**: 100 poses
- **Features**: Pose

---

## Usage

The repository contains Jupyter Notebooks that demonstrate how the AI model recommends yoga poses based on user input. To use the notebooks:

1. Open a notebook (e.g., `YogaModelTraining.ipynb`).
2. Follow the steps to input user data such as fitness level, flexibility, and desired outcomes.
3. Run the cells to see personalized yoga pose recommendations.

---

## Contributing

We welcome contributions to improve the functionality of YogAi. If you'd like to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

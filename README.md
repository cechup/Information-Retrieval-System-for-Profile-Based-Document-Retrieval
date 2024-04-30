# Information Retrieval System for Profile-Based Document Retrieval

This repository contains scripts, data, and a detailed report for an Information Retrieval System tailored for Profile-Based Document Retrieval. Leveraging advanced text processing and machine learning techniques, the system offers personalized document recommendations by adapting to individual user preferences.

## Project Overview

The project utilizes several methodologies to analyze and categorize text data, enabling the system to match documents with user profiles effectively. The system's core lies in its ability to adapt to the unique preferences of each user, enhancing user engagement and information consumption efficiency.

## Folder Contents

### Scripts
- `script.ipynb`: Jupyter notebook containing text preprocessing, modeling, and analysis scripts.

### Data
- `bbc-text.csv`: Dataset used for training and evaluating the retrieval system, containing categorized news articles.
- `words.txt`: Contains key vocabulary terms used in text processing and model training to enhance retrieval accuracy.

### Report
- `report.pdf`: Comprehensive report detailing the project's methodologies, implementation, and key findings.

## Installation and Setup

Before running the script, ensure that Jupyter Notebook is installed along with the necessary libraries:

```bash
pip install -r requirements.txt
```

## Running the Scripts
To execute the system, you can run the Python script directly or use the Jupyter notebook:
```
jupyter notebook script.ipynb
```
## Key Components

### Text Processing
- Cleaning and preprocessing text data to improve model performance.
- Utilizing techniques such as tokenization, lemmatization, and TF-IDF to prepare the data for analysis.

### Methodologies
- **Latent Dirichlet Allocation (LDA)** for topic modeling to categorize documents.
- **TF-IDF Similarity Calculation** to match documents with user profiles based on content relevance.

### User Profile Simulation
- Simulating user interaction to demonstrate how the system recommends documents based on individual profiles.

## Results
Results are discussed in the included report, highlighting the effectiveness of different methodologies in matching documents to user profiles and vice versa.

## Authors
Federico Paschetta \
Cecilia Peccolo \
Nicola Maria D’Angelo 

## License
This project is open-source and available under the terms of the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this software for any purpose with proper attribution to the original authors.

See the [LICENSE](LICENSE) file for the full text of the MIT License.

## Contact
If you have any questions, suggestions, or feedback, feel free to reach out to us at peccolo.cecilia00@gmail.com.


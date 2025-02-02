README

🏥स्वास्थ्य सहायक (Swasthya Sahayak)

OVERVIEW
The objective was to build a comprehensive healthcare recommendation platform, functioning as a doctor-finder system. It analyzes user-provided symptoms to identify possible health conditions, then matches these with doctors specializing in the relevant fields who have available appointments. The system also incorporates user ratings to suggest top-rated healthcare providers. Utilizing datasets that detail disease-symptom relationships and extensive healthcare provider profiles—including specialties, ratings, and availability—ensures precise, personalized recommendations.

FEATURES
🩺 Symptom Analysis: Utilizes machine learning algorithms to evaluate symptoms entered by users, identifying potential health conditions. The system draws from a dataset that maps disease-symptom relationships to ensure accurate predictions.

📋 Doctor Recommendation: Suggests doctors whose specialties align with the identified symptoms and who have available appointments. The recommendation engine emphasizes doctors with higher ratings and compatible schedules, ensuring quality and convenience.

PREREQUISITES

Latest version of Python installed on your system

Jupyter Notebook installed (optional) or access to Google Colab for running the code

INSTALLATION

Download the project files from the repository.

Confirm that Python is updated to the latest version on your system.

Install Jupyter Notebook (optional) or open the code in Google Colab.

Upload the dataset named updated_dataset.csv along with the code files in your working directory.

USAGE

Open the main_updated.ipynb file in Jupyter Notebook or Google Colab.

Execute the code cells.

Input your symptoms when prompted, ensuring they match those listed in the dataset.

The system will display the most likely health conditions and recommend doctors specializing in those areas, considering their availability and user ratings.

FUTURE SCOPE

User Ratings Update: Add functionality allowing users to update doctor ratings over time to maintain accurate and relevant recommendations.

Dynamic Doctor Schedules: Enable real-time updates to doctor schedules to reflect current availability.

Emergency Button: Incorporate an emergency feature providing instant access to nearby healthcare facilities based on the user's location.

Multilingual Chatbot Assistant: Implement a multilingual chatbot using NLP to allow users to input symptoms in their preferred language, enhancing accessibility.

Interactive UI: Develop an intuitive and accessible user interface with features like text-to-speech and alternative text for images, ensuring usability for individuals with disabilities.

REFERENCES

Symptom-Disease Dataset: Kaggle Dataset

Healthcare Provider Dataset: Web-scraped from DrData

Review Paper on Healthcare Recommendation Systems: ScienceDirect

CONTRIBUTING
👩‍💻 Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit an issue on GitHub or create a pull request with your updates.

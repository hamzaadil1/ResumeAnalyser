# 📄 Resume Analyser Model

A Django-based web application that uses machine learning to analyze resumes and match them with job requirements. The system can categorize resumes, calculate match scores, and provide improvement suggestions.

## 🚀 Features

- **Resume Upload & Analysis**: Upload multiple resume files (PDF, DOC, DOCX) or paste resume text
- **ML-Powered Categorization**: Automatically categorizes resumes using machine learning
- **Job Matching**: Calculates match scores between resumes and job requirements
- **Intelligent Suggestions**: Provides recommendations for resume improvement
- **Multi-format Support**: Supports various file formats for resume upload
- **Batch Processing**: Analyze multiple resumes simultaneously

## 🛠️ Technologies Used

- **Backend**: Django (Python)
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Text Processing**: Natural Language Processing (NLP)
- **File Processing**: PyPDF2, python-docx
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default, can be configured for PostgreSQL/MySQL)

## 📋 Requirements

- Python 3.8+
- Django 4.0+
- Required Python packages (see requirements.txt)

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/hamzaadil1/ResumeAnalyser.git
cd ResumeAnalyser
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py migrate
```

### 5. Start Development Server
```bash
python manage.py runserver
```

### 6. Access Application
Open your browser and go to: `http://localhost:8000`

## 📁 Project Structure

```
RESUME-ANALYSER-MODEL/
├── ml_model/                 # Machine learning components
│   ├── predict.py           # Resume categorization
│   ├── file_utilis.py       # File processing utilities
│   └── recommender.py       # Matching and suggestions
├── templates/               # HTML templates
├── static/                  # CSS, JS, images
├── manage.py               # Django management script
├── settings.py             # Django settings
├── urls.py                 # URL routing
├── views.py                # View functions
├── models.py               # Database models
├── forms.py                # Django forms
├── UpdatedResumeDataSet.csv # Training dataset
└── requirements.txt        # Python dependencies
```

## 🔧 How It Works

1. **Upload/Input**: Users can upload resume files or paste resume text
2. **Text Extraction**: The system extracts text from various file formats
3. **ML Analysis**: Machine learning model categorizes the resume
4. **Data Extraction**: Key information is extracted (skills, experience, education)
5. **Job Matching**: Calculates compatibility score with job requirements
6. **Suggestions**: Provides recommendations for improvement
7. **Results**: Displays analysis results with scores and suggestions

## 📊 ML Model Features

- **Resume Categorization**: Classifies resumes into different job categories
- **Skill Extraction**: Identifies technical and soft skills
- **Experience Analysis**: Extracts years of experience
- **Education Parsing**: Identifies educational qualifications
- **Match Scoring**: Calculates percentage match with job requirements

## 🎯 Usage Examples

### Single Resume Analysis
1. Upload a resume file or paste resume text
2. Enter job requirements (title, skills, experience, education)
3. Click "Analyze" to get results
4. View category, match score, and improvement suggestions

### Batch Resume Processing
1. Upload multiple resume files
2. Enter job requirements
3. System processes all resumes and ranks them by match score
4. Compare candidates side by side

## 🔮 Future Enhancements

- [ ] Advanced NLP for better text extraction
- [ ] Integration with job boards APIs
- [ ] Real-time resume scoring
- [ ] Email notifications for recruiters
- [ ] Resume template suggestions
- [ ] Integration with ATS systems
- [ ] Multi-language support

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

- **Hamza Adil** - [hamzaadil1](https://github.com/hamzaadil1)

## 🙏 Acknowledgments

- Django community for the excellent web framework
- Scikit-learn for machine learning capabilities
- Contributors and testers

---

⭐ **Star this repository if you find it helpful!**

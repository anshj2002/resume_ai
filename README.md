# 📑 Resume Analyzer

An intelligent resume analysis tool that evaluates resumes, provides scoring, and recommends best-fit job roles using NLP! 🎯

![Resume Analyzer Demo](demo-screenshot.png)

## ⭐ Features

- 📊 Smart resume scoring based on multiple factors:
  - Skills matching
  - Academic performance (CGPA)
  - Work experience
  - Projects and achievements
- 🎯 Job role matching with percentage fit
- 🔍 Automatic skill extraction using NLP and RegEx
- 📋 Missing skills identification
- 📚 Personalized course recommendations
- 🚀 Real-time analysis
- 📱 Responsive web interface

## 🛠️ Technology Stack

- **Backend**: 
  - FastAPI (Python)
  - spaCy for NLP
  - PyPDF2 for PDF processing
  - Custom keyword matching algorithms
  - Regex for pattern matching

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript
  - Modern responsive design

## 🔥 Demo

Check out our demo video to see the Resume Analyzer in action:
[Watch Demo Video](18.12.2024_12.37.53_REC.mp4)

## 📊 How It Works

1. **Resume Upload**: Users upload their resume in PDF format
2. **Text Extraction**: System extracts text using PyPDF2
3. **NLP Processing**: 
   - Keyword extraction using spaCy
   - Pattern matching using RegEx
   - Entity recognition for skills and experiences
4. **Score Calculation**: 
   - Skills weight: 40%
   - Experience: 30%
   - Education: 20%
   - Projects: 10%
5. **Job Matching**: Compares extracted information with job requirements
6. **Recommendations**: Generates personalized skill and course recommendations

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip
- Virtual environment (recommended)

### Installation

1. Clone the repository
```bash
git clone https://github.com/anshj2002/resume-analyzer.git
cd resume-analyzer
```

2. Create and activate virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Install spaCy model
```bash
python -m spacy download en_core_web_sm
```

### 🏃‍♂️ Running the Application

1. Start the FastAPI server
```bash
python main.py
```

2. Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
resume-analyzer/
├── frontend/                # Frontend files
│   ├── index.html
│   ├── style.css
│   └── script.js
├── algo.py                 # Algorithm implementations
├── main.py                 # FastAPI application
├── skill.py               # Skill extraction logic
├── temp.py                # Utility functions
├── requirements.txt       # Python dependencies
└── README.md
```

## 🎯 Key Components

- `main.py`: FastAPI application and API endpoints
- `algo.py`: Core algorithms for resume analysis
- `skill.py`: Skill extraction and matching logic
- `frontend/`: Web interface files
- `requirements.txt`: Project dependencies

## 📊 Score Calculation

The resume score (0-100) is calculated based on:
- Technical skills match
- Educational background
- Work experience
- Projects and achievements
- Certifications
- Overall resume quality

## 🛠️ Development

To contribute to this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Ansh J - [@anshj2002](https://github.com/anshj2002)

## 🙏 Acknowledgments

- spaCy community for the excellent NLP tools
- FastAPI team for the amazing framework
- All contributors and testers

---
⭐ Star us on GitHub — it helps!

### 📸 Screenshots

![Resume Analysis](screenshot1.png)
*Resume Analysis Dashboard*

![Job Matching](screenshot2.png)
*Job Role Matching Results*

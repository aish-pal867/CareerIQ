# CareerIQ – Intelligent Job Matching & Skill Gap Analysis System

**CareerIQ** is a C++-based, console-driven recruitment and career-readiness application designed to simulate essential functionalities of a real-world hiring ecosystem. It enables candidates to explore relevant job opportunities, evaluate their technical and cognitive skills, identify competency gaps, and receive structured recommendations for career development.

The system also provides recruiter-side functionality for managing job listings, defining skill requirements, and maintaining job records through persistent file storage.

## 🚀 Key Features

### 1. Student Mode
- Enter personal skills and experience.
- Explore job opportunities based on skill compatibility.
- Identify suitable career opportunities.
- Receive personalized learning recommendations.

### 2. Job Seeker Mode
- Apply for specific job roles.
- Participate in skill assessment tests.
- Evaluate performance through score-based analysis.
- Identify areas requiring improvement.

### 3. Recruiter Mode
- Create and manage job postings.
- Define required skills and salary information.
- Store job records using file handling.
- Retrieve previously saved job listings.

### 4. Multi-Dimensional Skill Assessment
Evaluates candidates across three major competency areas:
- Language Skills
- Logical Thinking
- Critical Thinking

Generates performance scores to help candidates understand their current skill levels.

### 5. Personalized Recommendation Engine
Provides recommendations according to assessment performance:

- **Beginner:** Foundational learning recommendations.
- **Intermediate:** Improvement areas and skill-development guidance.
- **Advanced:** Further development and career progression suggestions.

### 6. Market Trends & Skill Gap Analysis
- Highlights relevant in-demand skills such as AI, Cloud Computing, and DevOps.
- Compares existing skills against job requirements.
- Helps candidates identify missing competencies.
- Provides direction for targeted skill development.

## 🛠️ Technical Implementation

| Technology / Concept | Application |
|---|---|
| C++ (C++17) | Core application development |
| Object-Oriented Programming | Classes, objects, encapsulation and abstraction |
| Arrays & Vectors | Dynamic data storage and traversal |
| Searching Algorithms | Job discovery and skill matching |
| Sorting Logic | Job prioritization, where implemented |
| String Manipulation | Skill comparison and data processing |
| File Handling | Persistent storage and retrieval |
| Conditional Logic | Assessment and recommendation generation |

## 🧠 Core Problem-Solving Components

- **Job Matching:** Identifies relevant job opportunities by comparing candidate skills with job requirements.
- **Skill Gap Analysis:** Determines the difference between existing candidate skills and required job competencies.
- **Assessment Engine:** Evaluates performance across multiple skill categories.
- **Recommendation Logic:** Generates improvement suggestions based on assessment results.
- **Persistent Data Management:** Uses file streams to maintain job records between application sessions.

## 📂 Project Structure

```text
CareerIQ/
│
├── code.cpp        # Main application implementation
├── jobs.txt        # Persistent job records (generated/used by application)
├── README.md       # Project documentation
└── .gitignore      # Git ignored files
```

## ⚙️ Installation & Execution

### Prerequisites
- C++ compiler supporting C++17 or later.
- GCC / MinGW or an equivalent compiler.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Navigate to the Project Directory

```bash
cd CareerIQ
```

### 3. Compile the Application

```bash
g++ code.cpp -std=c++17 -o job_app
```

### 4. Execute

**Windows:**
```bash
job_app.exe
```

**Linux / macOS:**
```bash
./job_app
```

## ⚠️ Current Limitations

- Console-based user interface.
- Limited predefined job roles and skill categories.
- File-based storage instead of database integration.
- Recommendations rely on predefined logical rules rather than machine learning.
- Limited scalability for large recruitment datasets.

## 🔮 Future Enhancements

- Graphical interface using Qt.
- Database integration using MySQL or MongoDB.
- Resume parsing and automated skill extraction.
- Advanced job recommendation algorithms.
- Expanded skill assessment modules.
- Web-based deployment and multi-user support.

## 👨‍💻 Author

**Aishwary Bahadur Pal**

B.Tech – Computer Science & Engineering  
Madan Mohan Malaviya University of Technology (MMMUT), Gorakhpur

**Areas of Interest:** Data Structures & Algorithms | C++ | Problem Solving | Software Development

---

*CareerIQ – Bridging the gap between candidate capabilities and industry requirements.*

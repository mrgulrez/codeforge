# **CodeForge - Hackathon**  

## **Overview**  
CodeForge is a Django-based application designed for efficient complaint management and user authorization. It integrates AI-powered text processing, knowledge graphs, and automated summary generation to streamline workflows.  

## **Project Structure**  
```
/codeforge        # Core application logic
/admin           # Admin panel configurations
/authorization   # User authentication and permissions
/user           # User-related operations
.gitignore      # Files to exclude from Git tracking
README.md       # Project documentation
manage.py       # Django project management script
```  


## **Tech Stack** and **Features**  

- **Frontend:**  
  - HTMX (HTML + JS) – Lightweight, high-performance interactivity  
  - Tailwind CSS – Utility-first styling for responsive UI  

- **Backend:**  
  - Django – Scalable web framework for backend logic  
  - Django REST Framework (DRF) – API development  
  - Neo4j – Graph database for knowledge representation  

- **Database:**  
  - PostgreSQL – Relational database for structured data  
  - MySQL – Alternative relational DB for flexibility  
  - Any other relational DB (as per requirements)  

- **Authentication:**  
  - Clerk – Secure authentication & user management  
  - Role-Based Access Control (RBAC) – Admin, User, Authority roles  

- **AI & NLP Integration:**  
  - Gemini, Mistral, CoHere – AI-driven text and document processing  
  - PDFPyDF2 – Document parsing and extraction  
  - Knowledge Graph – AI-powered relational data visualization  

- **Deployment & DevOps:**  
  - Docker – Containerization for consistent environments  
  - GitHub Actions – CI/CD pipeline for automated testing & deployment  
  - Cloud Platforms (AWS/GCP) – Future cloud deployment support  


## **Contributors**  

- **Gulrez Alam**  
- **Yasir Khan** 
- **Mohd Irshad**  

### **Key Skills & Expertise**  
✅ **Backend Development** (Django, APIs, Database Management)  
✅ **Frontend Development** (HTMX, Tailwind CSS)  
✅ **Authentication & Authorization** (Clerk, Role-based Access)  
✅ **AI & NLP Integration** (Gemini, Mistral, CoHere, Neo4j)  
✅ **Data Processing & Document Handling** (PDFPyDF2)  
✅ **Software Engineering Best Practices** (Code Structuring, Modularization)  

## **Installation & Setup**  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/mrgulrez/codeforge.git
   cd codeforge
   ```
2. **Set up a virtual environment:**  
   ```sh
   python -m venv env
   source env/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies:**  
   ```sh
   pip install -r requirements.txt
   ```
4. **Run migrations & start the server:**  
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```

## **Usage**  
- Navigate to `http://127.0.0.1:8000/`  
- Log in or sign up using Clerk authentication  
- Manage complaints, users, and authorization settings  
- Utilize AI-powered tools for summarization and complaint tracking  

## **Contributing**  
We welcome contributions! If you want to enhance features, fix bugs, or improve documentation, feel free to fork the repository and submit a pull request.  

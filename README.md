
🚀 Enterprise-Dev-Portal
A comprehensive full-stack application designed to streamline developer networking and enterprise project collaboration. This platform integrates a Django REST Framework (DRF) backend with a dynamic React/Redux frontend to provide a seamless, data-driven user experience.

🛠️ Tech Stack
Frontend: React.js, CSS3.

Backend: Django, Django REST Framework (DRF).

Database: PostgreSQL (Optimized for relational data and enterprise scalability).

Authentication: JWT (JSON Web Tokens) for secure, stateless session management.

Data Tools: Pandas & NumPy (Integrated for backend data processing and analytics).

🌟 Key Features
Modular Architecture: A decoupled monorepo structure allowing for independent scaling of the frontend and backend services.

Dynamic Profile Management: Real-time profile creation and updates with GitHub API integration to showcase live repository data.

Secure API Design: Robust RESTful endpoints protected by custom middleware and JWT authentication.

Data Insights Module: Leverages backend Python logic to aggregate user engagement metrics—aligning with data science best practices.

📈 Data Science Integration
As a final-year student specializing in Data Science, I implemented specific optimizations within this project:

Query Optimization: Used select_related and prefetch_related in Django to minimize database hits during complex data retrieval.

Statistical Summaries: Developed backend scripts to process user interaction data, providing structured JSON outputs for frontend visualization.

🚀 Installation & Setup
Backend (Django)
Navigate to the directory: cd backend

Create virtual environment: python -m venv venv

Install dependencies: pip install -r requirements.txt

Run migrations: python manage.py migrate

Start server: python manage.py runserver

Frontend (React)
Navigate to the directory: cd frontend

Install packages: npm install

Start application: npm start

# Angel Investment Tracker

A full-stack web application for tracking and analyzing angel investments in startup companies.

## 🚀 Features

- Track multiple angel investments with detailed information
- Portfolio dashboard with key metrics
- Financial calculations (IRR, MOIC, multiples)
- Investment timeline and updates
- Data export capabilities (CSV, Excel)
- Secure authentication

## 🛠️ Tech Stack

**Backend:**
- Python 3.11+
- FastAPI
- SQLAlchemy
- SQLite (development) / PostgreSQL (production)
- Alembic (migrations)

**Frontend:**
- HTML5, CSS3, JavaScript (ES6+)
- Chart.js for data visualization
- Vanilla JS (no framework initially)

**DevOps:**
- Docker & Docker Compose
- Git version control

## 📋 Prerequisites

- Python 3.11 or higher
- Git
- Node.js 18+ (for frontend tooling)

## 🔧 Setup

### 1. Clone the repository
\`\`\`bash
git clone <your-repo-url>
cd angel-investment-tracker
\`\`\`

### 2. Backend Setup
\`\`\`bash
cd backend
python -m venv venv

# Activate virtual environment
# Windows: venv\Scripts\activate
# macOS/Linux: source venv/bin/activate

pip install -r requirements-dev.txt
\`\`\`

### 3. Environment Variables
\`\`\`bash
cp .env.example .env
# Edit .env with your configuration
\`\`\`

### 4. Run Development Server
\`\`\`bash
cd backend
uvicorn app.main:app --reload
\`\`\`

Visit http://localhost:8000/docs for API documentation.

## 📚 Project Structure

See [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md) for detailed explanation.

## 🧪 Testing

\`\`\`bash
cd backend
pytest
pytest --cov=app tests/
\`\`\`

## 🐳 Docker

\`\`\`bash
docker-compose up --build
\`\`\`

## 📝 License

MIT License - feel free to use this project for learning or production.

## 👨‍💻 Author

[Your Name]
Learning project following a structured curriculum.

---

**Status:** 🚧 In Development
**Current Module:** Module 1 - Project Setup
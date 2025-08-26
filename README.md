# BazaarBrain-Pro

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-brightgreen.svg)
![Next.js](https://img.shields.io/badge/Next.js-13+-black.svg)

**BazaarBrain-Pro** is an advanced AI-powered research assistant designed to provide intelligent insights and automation for research workflows. This full-stack application combines cutting-edge AI models with a modern web interface to deliver a comprehensive research solution.

## 🚀 Features

- **AI-Powered Research**: Leverages advanced language models for intelligent research assistance
- **OCR Integration**: Extract and analyze text from documents and images
- **Vector Search**: Semantic search capabilities using Weaviate for knowledge retrieval
- **Modern UI**: Clean, responsive Next.js frontend for optimal user experience
- **RESTful API**: FastAPI-powered backend with comprehensive API endpoints
- **Database Integration**: Robust data management and persistence

## 🏗️ Architecture

### Backend (Python)
- **FastAPI**: Modern, fast web framework for building APIs
- **AI Models**: Integration with LlamaIndex, OCR processing, and Weaviate search
- **Database**: SQLite/PostgreSQL support with SQLAlchemy ORM
- **Schemas**: Pydantic models for data validation

### Frontend (Next.js)
- **React**: Component-based UI development
- **Next.js 13+**: Modern React framework with app router
- **Responsive Design**: Mobile-first approach for all devices

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- Node.js 16 or higher
- npm or yarn package manager

### Backend Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/BazaarBrain-Pro.git
cd BazaarBrain-Pro
```

2. Create a virtual environment:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the backend server:
```bash
python main.py
```

The API will be available at `http://localhost:8000`

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

The frontend will be available at `http://localhost:3000`

## 🔧 Configuration

Environment variables can be configured in `.env` files:

### Backend (.env)
```env
DATABASE_URL=sqlite:///./app.db
OPENAI_API_KEY=your_openai_key
WEAVIATE_URL=your_weaviate_instance
```

### Frontend (.env.local)
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

## 🧪 Usage

1. Start both backend and frontend servers
2. Navigate to `http://localhost:3000` in your browser
3. Begin using the AI research assistant features
4. Explore the API documentation at `http://localhost:8000/docs`

## 📚 API Documentation

The API is documented with OpenAPI/Swagger. When the backend is running, visit:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Documentation](docs/)
- [API Reference](http://localhost:8000/docs)
- [Issues](https://github.com/your-username/BazaarBrain-Pro/issues)
- [Discussions](https://github.com/your-username/BazaarBrain-Pro/discussions)

## 🙏 Acknowledgments

- Built for hackathon participants and researchers
- Inspired by the need for intelligent research automation
- Community-driven development approach

---

**Made with ❤️ for the research community**

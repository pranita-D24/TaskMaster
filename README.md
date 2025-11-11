# 🚀 TaskMaster - Collaborative Task Management Platform

A modern, full-stack task management application inspired by Trello, featuring real-time collaboration, drag-and-drop Kanban boards, and comprehensive workspace management.

![TaskMaster Dashboard](./screenshots/dashboard.png)

## ✨ Features

- 🔐 **User Authentication** - Secure JWT-based login/registration
- 🏢 **Workspaces** - Create and manage multiple workspaces
- 📊 **Kanban Boards** - Visual boards with customizable colors
- 🎯 **Drag & Drop** - Intuitive card movement between lists
- ✅ **Task Management** - Create, edit, and organize tasks
- 🔍 **Advanced Filtering** - Filter by status, due date, and completion
- 📈 **Analytics Dashboard** - Track productivity and progress
- 👥 **Team Collaboration** - Invite members and manage roles
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile

## 🛠️ Tech Stack

### Frontend
- React 18 + Vite
- React Router v6
- Context API for state management
- React Beautiful DnD for drag-and-drop
- Axios for API calls

### Backend
- Django 5.0 + Django REST Framework
- PostgreSQL database
- JWT Authentication
- CORS enabled

## 📦 Installation

### Prerequisites
- Python 3.10+
- Node.js 18+
- PostgreSQL 15+

### Backend Setup
```bash
# Clone repository
git clone https://github.com/yourusername/taskmaster.git
cd taskmaster/backend

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure database in config/settings.py
# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver
```

### Frontend Setup
```bash
cd ../frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### Environment Variables

Create `.env` in backend:
```
DEBUG=True
SECRET_KEY=your-secret-key
DATABASE_URL=postgresql://user:password@localhost:5432/taskmaster_db
```

## 🚀 Usage

1. Open `http://localhost:5173` in your browser
2. Register a new account or login
3. Create your first workspace
4. Add boards and start organizing tasks!

## 📸 Screenshots

### Dashboard
![Dashboard](./screenshots/dashboard.png)

### Kanban Board
![Board View](./screenshots/board.png)

### Task Management
![Tasks](./screenshots/tasks.png)

## 🗺️ Roadmap

- [ ] Real-time WebSocket notifications
- [ ] Email invitations for team members
- [ ] Calendar view for tasks
- [ ] File attachments
- [ ] Comments and activity logs
- [ ] Mobile app (React Native)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Inspired by Trello
- UI design inspired by modern web applications
- Built as a portfolio project

---

⭐ Star this repo if you find it helpful!

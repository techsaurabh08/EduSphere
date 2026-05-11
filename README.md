#  EduSphere — Smart ERP Management System Portal

EduSphere is a modern Django-based Smart ERP Management System Platform designed to streamline attendance management, grievance handling, student analytics, and academic monitoring in educational institutions.

Built with a production-oriented architecture, EduSphere combines real-time attendance sessions, analytics-driven student insights, and a modern SaaS-style dashboard UI.

---

##  Features

###  Student Features
- Smart attendance dashboard
- Attendance prediction engine
- Subject-wise attendance analytics
- Attendance streak tracking
- Weekly attendance heatmap
- Attendance session check-in system
- Grievance submission & tracking
- Real-time dashboard updates

###  Teacher Features
- Live attendance session generation
- 4-digit attendance code system
- Attendance auto-finalization
- Student performance monitoring
- Attendance export to CSV
- Subject analytics dashboard
- Grievance management system

###  Admin Features
- Full Django admin panel
- User management
- Attendance oversight
- Analytics overview

###  UI/UX
- Modern SaaS-inspired design
- Dark / Light theme support
- Mobile responsive layout
- Animated dashboard components
- Professional landing page

---

##  Tech Stack

| Technology | Usage |
|------------|-------|
| Django 6 | Backend Framework |
| SQLite / PostgreSQL | Database |
| Bootstrap 5 | Frontend UI |
| JavaScript | Dynamic UI |
| Channels | Real-time updates |
| Gunicorn | Production server |
| WhiteNoise | Static file serving |
| Jazzmin | Admin panel enhancement |

---

##  Project Structure

```bash
EduSphere/
│
├── portal/
│   ├── templates/
│   ├── static/
│   ├── views.py
│   ├── models.py
│   ├── urls.py
│   └── consumers.py
│
├── media/
├── staticfiles/
├── manage.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md

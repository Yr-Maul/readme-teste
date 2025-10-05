<div align="center">
  <img src="https://via.placeholder.com/150x150/4C51BF/ffffff?text=UC" alt="UniCrossed Logo" width="120" height="120" style="border-radius: 20px;">

UniCrossed

  🎓 Academic Networking Platform for University Students

  Connect with fellow students • Form study groups • Exchange knowledge

  [!Django](https://www.djangoproject.com/)
  [!Python](https://www.python.org/)
  [!SQLite](https://www.sqlite.org/)
  [!HTML5](https://html.spec.whatwg.org/)
  [!CSS3](https://www.w3.org/Style/CSS/)
  [!JavaScript](https://www.javascript.com/)

  [!GitHub issues](https://github.com/leonardomarcolin/UniCrossed/issues)
  [!GitHub forks](https://github.com/leonardomarcolin/UniCrossed/network)
  [!GitHub stars](https://github.com/leonardomarcolin/UniCrossed/stargazers)
  [!License](LICENSE)

  🚀 Live Demo • 📖 Documentation • 🐛 Report Bug • 💡 Request Feature

</div>
***📋 Table of Contents
About the Project
Features
Technologies Used
Prerequisites
Installation
Usage
Project Structure
Data Models
APIs & Endpoints
Security Features
Contributing
Development Team
License
Contact
***🎯 About the Project
<div align="center">
  <img src="https://via.placeholder.com/800x400/4C51BF/ffffff?text=UniCrossed+Platform" alt="UniCrossed Platform" style="border-radius: 10px; margin: 20px 0;">
</div>
UniCrossed is a modern web platform built with Django that solves two main challenges faced by university students:
🤝 Difficulty Meeting People - Through a Tinder-like matching system focused on academic compatibility
📚 Struggling with University Content - Facilitating study group formation and knowledge exchange between students
The platform combines intelligent recommendation algorithms with a modern, intuitive interface, providing students with a unique academic networking experience.
🎯 Mission Statement
> "Connecting knowledge through networking - making academic collaboration as simple as swiping right."
📊 Platform Stats
🎓 Target Audience: University Students
🏫 University Integration: Multi-institution support
👥 Matching Algorithm: Academic compatibility-based
📱 Interface: Mobile-responsive design
***✨ Features
<div align="center">
  <table>
    <tr>
      <td align="center">🎓<br><b>Academic Matching</b></td>
      <td align="center">👥<br><b>Profile Management</b></td>
      <td align="center">📚<br><b>Study Groups</b></td>
      <td align="center">💬<br><b>Communication</b></td>
    </tr>
  </table>
</div>
🎓 Academic Matching System
🔥 Swipe Interface: Tinder-like UI to discover fellow students
🧠 Compatibility Algorithm: Based on course, university, interests, and schedules
💕 Interaction System: Complete like, superlike, and dislike functionality
🔗 Auto-Matching: Automatic "links" creation when mutual interest exists
👥 Profile Management
📋 Complete Profiles: Academic info, biography, skills, profile pictures
📸 Photo System: Upload up to 6 photos with order management
⏰ Study Preferences: Available times, methods, and study days
🏷️ Academic Skills: Tags and student specialties
📚 Study Groups
🏗️ Group Creation: Organization by subject, schedule, and location
👨‍👩‍👧‍👦 Member Management: Participant limits and activity status
📅 Meeting Calendar: Organization of meeting days and times
📝 Detailed Information: Description, location, and group objectives
💬 Communication System
💭 Direct Chat: Messaging interface for "linked" users
⭐ Enhanced Superlikes: Special messages up to 500 characters
🟢 Presence Status: Online/offline indicators
💾 Chat History: Secure message storage
🔐 Security & Authentication
🔒 Two-Factor Authentication: SMS verification system
🛡️ Django Allauth: Robust authentication framework
🎫 Session Management: Secure login/logout controls
✅ Data Validation: Protection against malicious data
⚙️ Customizable Settings
🔔 Notification Preferences: Granular alert controls
🔒 Privacy Settings: Profile visibility controls
🎨 Interface Customization: Dark mode, font size, language
💾 Data Management: Export and automatic backup
📊 Reporting System
🐛 Bug Reports: Complete problem reporting interface
📋 Data Export: GDPR/LGPD compliance
📈 Internal Analytics: Usage and engagement metrics
***🛠 Technologies Used
<div align="center">
  <table>
    <tr>
      <td align="center"><b>Backend</b></td>
      <td align="center"><b>Frontend</b></td>
      <td align="center"><b>Security</b></td>
      <td align="center"><b>Database</b></td>
    </tr>
    <tr>
      <td>🐍 Python<br>🌟 Django<br>📡 Django REST</td>
      <td>🌐 HTML5<br>🎨 CSS3<br>⚡ JavaScript</td>
      <td>🔐 2FA<br>🛡️ Allauth<br>🔒 CSRF Protection</td>
      <td>🗃️ SQLite<br>📊 Django ORM<br>💾 Media Files</td>
    </tr>
  </table>
</div>
🎯 Core Framework
!Python Python 3.8+ - Primary programming language
!Django Django 4.x - Web framework for backend and frontend
!SQLite SQLite - Development database
Django ORM - Object-relational mapping
🔐 Authentication & Security
Django Allauth - Social authentication system
Django OTP - Two-factor authentication
Multiselectfield - Multiple selection fields
CSRF Protection - Cross-site request forgery protection
🎨 Frontend & Interface
!HTML5 HTML5 - Modern semantic structure
!CSS3 CSS3 - Advanced styling with animations
!JavaScript JavaScript (ES6+) - DOM manipulation and interactivity
Font Awesome 6.4+ - Professional icon library
Responsive Design - Multi-device compatible interface
📱 Media Management
Django Static Files - Static file management
Django Media - Image upload and management
Image Processing - Automatic image optimization
***📋 Prerequisites
<div align="center">
  <table>
    <tr>
      <td align="center">🐍<br><b>Python 3.8+</b></td>
      <td align="center">📦<br><b>pip</b></td>
      <td align="center">🌐<br><b>Git</b></td>
      <td align="center">🔧<br><b>Virtual Environment</b></td>
    </tr>
  </table>
</div>
System Requirements:
!Python Python 3.8 or higher
pip (Python package manager)
Git (version control)
Virtual Environment (recommended)
🔧 Main Python Dependencies
Django>=4.0,<5.0
django-allauth>=0.50.0
django-otp>=1.1.0
multiselectfield>=0.1.12
Pillow>=9.0.0  # For image processing
***🚀 Installation
<div align="center">
  <img src="https://via.placeholder.com/600x300/4C51BF/ffffff?text=Quick+Setup+Guide" alt="Installation Guide" style="border-radius: 10px; margin: 20px 0;">
</div>
1. 📥 Clone the Repository
git clone https://github.com/leonardomarcolin/UniCrossed.git
cd UniCrossed
2. 🔧 Set Up Virtual Environment
# Windows
python -m venv venv
venv\Scripts\activate
# macOS/Linux
python3 -m venv venv
source venv/bin/activate
3. 📦 Install Dependencies
pip install django
pip install django-allauth
pip install django-otp
pip install multiselectfield
pip install Pillow
# Or if requirements.txt exists:
pip install -r requirements.txt
4. 🗃️ Configure Database
python manage.py makemigrations
python manage.py migrate
5. 👤 Create Superuser (Optional)
python manage.py createsuperuser
6. 🏃‍♂️ Run the Server
python manage.py runserver
<div align="center">
  <h3>🎉 Ready! Access <a href="http://127.0.0.1:8000">http://127.0.0.1:8000</a> to use the application.</h3>
</div>
***📱 Usage
<div align="center">
  <table>
    <tr>
      <td align="center">👤<br><b>Create Account</b></td>
      <td align="center">📋<br><b>Complete Profile</b></td>
      <td align="center">🎯<br><b>Set Preferences</b></td>
      <td align="center">🔗<br><b>Start Matching</b></td>
    </tr>
  </table>
</div>
🚀 First Steps
📝 Sign Up: Access /accounts/signup/ to create your account
✏️ Complete Profile: Fill in your academic and personal information
⚙️ Set Preferences: Define your study schedules and preferred methods
📸 Add Photos: Upload up to 6 photos to your profile
🧭 Main Navigation
🏠 Home (/): Main matching interface with swipe system
🔗 Links (/linkeds/): View your matches and connections
⚙️ Settings (/configuracoes/): Manage your profile and preferences
📚 Study Groups: Access via APIs to manage participation
💫 Interaction System
👍 Like: Like a profile for potential match
⭐ Superlike: Like with personalized message (10-500 characters)
👎 Pass: Skip to the next profile
💬 Match: When there's mutual interest, you can chat!
***📁 Project Structure
<div align="center">
  <img src="https://via.placeholder.com/700x350/4C51BF/ffffff?text=Django+Project+Architecture" alt="Project Structure" style="border-radius: 10px; margin: 20px 0;">
</div>
UniCrossed/
├── 📂 UniCrossed/              # Main project settings
│   ├── settings.py             # Django configuration
│   ├── urls.py                 # Main URLs
│   ├── wsgi.py                 # WSGI configuration
│   └── asgi.py                 # ASGI configuration
│
├── 📂 accounts/                # Main user application
│   ├── migrations/             # Database migrations
│   ├── models.py               # Data models
│   ├── views.py                # Business logic
│   ├── forms.py                # Django forms
│   ├── urls.py                 # App URLs
│   └── admin.py                # Admin interface
│
├── 📂 templates/               # HTML templates
│   ├── account/                # Authentication templates
│   ├── configuracoes/          # Configuration templates
│   ├── informacoes/            # Information pages
│   ├── home.html               # Main page
│   ├── linkeds.html            # Connections page
│   └── landingPage.html        # Landing page
│
├── 📂 static/                  # Static files
│   └── css/                    # CSS styles
│       └── global-vars.css     # Global CSS variables
│
├── 📁 media/                   # Media files (auto-generated)
├── 📄 db.sqlite3               # SQLite database
├── 📄 manage.py                # Django management script
└── 📄 README.md                # Project documentation
***🗃 Data Models
<div align="center">
  <img src="https://via.placeholder.com/800x300/4C51BF/ffffff?text=Database+Schema" alt="Database Models" style="border-radius: 10px; margin: 20px 0;">
</div>
<div align="center">
  <table>
    <tr>
      <td align="center">👤<br><b>User Models</b></td>
      <td align="center">🔗<br><b>Interaction Models</b></td>
      <td align="center">📚<br><b>Study Models</b></td>
      <td align="center">⚙️<br><b>Configuration</b></td>
    </tr>
  </table>
</div>
👤 CustomUser - Enhanced User Model
# Inherited fields
- username, email, password
# Academic information
- data_nascimento, genero, cidade, estado
- universidade, universidade_nome, curso, semestre
- bio, habilidades, celular
- foto_perfil (relationship)
🏷️ Habilidades - Academic Skills
- nome: CharField(unique=True)
- descricao: TextField
💕 Like/Superlike/Dislike - Interaction System
- de_usuario, para_usuario: ForeignKey(CustomUser)
- data_realizacao: DateTimeField
- mensagem: CharField (Superlike only)
🔗 Linkeds - Matches/Connections
- usuario1, usuario2: ForeignKey(CustomUser)
- data_realizacao: DateTimeField
- unique_together: ['usuario1', 'usuario2']
📚 GrupoDeEstudos - Study Groups
- nome, materia, descricao
- usuario_criador: ForeignKey(CustomUser)
- dias_encontros, horario_encontros, localizacao
- ativo, maximo_membros
⏰ PreferenciasEstudo - User Preferences
- user: OneToOneField(CustomUser)
- dia_semana, horario, metodo_preferido: MultiSelectField
⚙️ ConfiguracoesUsuario - Customizable Settings
- notificacoes: BooleanFields (links, messages, events, etc.)
- privacidade: BooleanFields (online_status, visibility, etc.)
- interface: dark_mode, font_size, language
***🔌 APIs & Endpoints
<div align="center">
  <table>
    <tr>
      <td align="center">🔑<br><b>Authentication</b></td>
      <td align="center">💕<br><b>Matching System</b></td>
      <td align="center">🔗<br><b>Connections</b></td>
      <td align="center">⚙️<br><b>Settings</b></td>
    </tr>
  </table>
</div>
🔑 Authentication & User
GET    /                              # Home with matching interface
POST   /accounts/signup/              # User registration
GET    /accounts/login/               # User login
POST   /accounts/logout/              # User logout
GET    /api/perfil-usuario/           # Profile data
💕 Matching System
GET    /pegar-proximo-perfil/         # Get next available profile
POST   /like/<user_id>/               # Like user
POST   /superlike/<user_id>/          # Superlike with message
POST   /dislike/<user_id>/            # Pass/dislike user
🔗 Connections & Groups
GET    /linkeds/                      # Connections page
GET    /api/linkeds/                  # List of linked users
GET    /api/grupos-estudo/            # User's study groups
GET    /api/grupos-estudo/<id>/       # Group details
⚙️ Settings & Utilities
GET|POST  /api/configuracoes/         # Manage settings
POST      /api/relatorio-problema/    # Report bug/issue
GET       /api/exportar-dados/        # Export data (GDPR/LGPD)
🔒 Two-Factor Authentication
POST   /2fa/setup/                    # Set up 2FA
POST   /2fa/verificar/                # Verify 2FA code
POST   /2fa/desabilitar/              # Disable 2FA
GET    /2fa/status/                   # 2FA status
***🔒 Security Features
<div align="center">
  <img src="https://via.placeholder.com/700x250/4C51BF/ffffff?text=Security+%26+Privacy+First" alt="Security Features" style="border-radius: 10px; margin: 20px 0;">
</div>
🔐 Multi-Factor Authentication
📱 SMS 2FA: SMS verification using django-otp
🔑 Secure Tokens: 6-digit code generation
📱 Device Management: Authorized device control
✅ Input Validation
🧩 Data Sanitization: XSS and SQL Injection prevention
🛡️ Form Validation: Robust server-side validations
⏱️ Rate Limiting: Protection against interaction spam
🔒 Privacy & Compliance
📄 Data Export: GDPR/LGPD compliance
👁️ Visibility Control: Granular privacy settings
🕵️ Anonymization: Secure personal data removal
***🤝 Contributing
<div align="center">
  <img src="https://via.placeholder.com/600x200/4C51BF/ffffff?text=Join+Our+Community" alt="Contributing" style="border-radius: 10px; margin: 20px 0;">
</div>
Contributions are very welcome! We believe in building great software together. 🚀
🛣️ How to Contribute
🍴 Fork the project
💾 Clone your fork: git clone https://github.com/your-username/UniCrossed.git
🌱 Create a branch: git checkout -b feature/amazing-new-feature
🔧 Implement your changes following project conventions
🧨 Test your changes locally
📝 Commit: git commit -m 'feat: add amazing new feature'
🚀 Push: git push origin feature/amazing-new-feature
🔄 Pull Request: Open a PR explaining your changes
📏 Code Standards
🐍 PEP 8: Follow Python style conventions
🎆 Django Best Practices: Use Django recommended patterns
📚 Documentation: Document complex functions and classes
🧨 Tests: Add tests for new features
🐛 Report Bugs
Use our internal reporting system (/api/relatorio-problema/) or open a GitHub issue with:
📝 Detailed description of the problem
🔄 Steps to reproduce the error
📷 Screenshots when applicable
💻 Environment info (OS, browser, Python/Django version)
***👨‍💻 Development Team
<div align="center">
  <img src="https://via.placeholder.com/800x200/4C51BF/ffffff?text=Meet+Our+Amazing+Team" alt="Our Team" style="border-radius: 10px; margin: 20px 0;">
</div>
<div align="center">
  <table>
    <tr>
      <td align="center">🎨<br><b>Frontend</b></td>
      <td align="center">📋<br><b>Product</b></td>
      <td align="center">⚙️<br><b>Backend</b></td>
      <td align="center">🔍<br><b>QA</b></td>
      <td align="center">🎨<br><b>UX</b></td>
    </tr>
  </table>
</div>
🎆 Our Creators
🎨 Kauã Filipe Spezia - Frontend Developer  
  👨‍💻 Expert in modern interfaces and user experience
📋 Yan Maul - Product Manager  
  🎯 Project coordination and strategic product vision
⚙️ Leonardo Marcolin - Backend Developer  
  🏧 System architecture and Django backend development
🔍 Erik Santana - QA Tester  
  🔬 Quality assurance and system testing
🎨 Matheus Rudiguer - UX Designer  
  🎨 Interface design and user experience research
***🚀 Roadmap & Next Steps
<div align="center">
  <img src="https://via.placeholder.com/800x300/4C51BF/ffffff?text=Future+Vision+2025" alt="Roadmap 2025" style="border-radius: 10px; margin: 20px 0;">
</div>
🎆 Roadmap 2025
📱 Mobile App: React Native/Flutter development
📡 Complete REST API: Swagger/OpenAPI documentation
🔔 Push Notifications: Firebase/OneSignal integration
💬 Real-time Chat: WebSockets with Django Channels
🤖 ML Algorithm: Machine Learning to improve matches
🎮 Gamification: Points and achievements system
🏫 University Integration: Partnerships with educational institutions
⚡ Planned Improvements
🏃‍♂️ Performance: Query optimization and Redis cache
📚 Scalability: PostgreSQL and Docker migration
📈 Monitoring: Sentry integration for error tracking
🛠️ CI/CD: Automated pipeline with GitHub Actions
***📄 License
<div align="center">
  <img src="https://img.shields.io/badge/License-Private%20Development-red?style=for-the-badge" alt="Private License">
</div>
This project is currently under development by the creators listed above. Usage and distribution rights are reserved to the development team.
For licensing questions or commercial permissions, please contact the team through official channels.
***📞 Contact
<div align="center">
  <img src="https://via.placeholder.com/600x200/4C51BF/ffffff?text=Get+In+Touch" alt="Contact Us" style="border-radius: 10px; margin: 20px 0;">
</div>
📊 Project Information
📛 Name: UniCrossed
🏷️ Version: 1.0.0
🔧 Technology: Django 4.x + Python 3.8+
💾 Repository: https://github.com/leonardomarcolin/UniCrossed
🌐 Communication Channels
📧 Email: unicrossed.team@gmail.com
📱 Instagram: @UniCrossed
💼 LinkedIn: UniCrossed
💻 GitHub: leonardomarcolin/UniCrossed
🔧 Technical Support
🐛 Bugs: Use internal reporting system or open a GitHub issue
💡 Suggestions: Contact us through social channels
🤝 Partnerships: Direct contact via email
***<div align="center">
<img src="https://via.placeholder.com/100x100/4C51BF/ffffff?text=UC" alt="UniCrossed" width="50" height="50" style="border-radius: 25px;">
✨ Crafted with ❤️ by the UniCrossed Team ✨
Connecting knowledge through academic networking
🎓 For students, by students 🎓
[!Made with Love](https://github.com/leonardomarcolin/UniCrossed)
[!Django](https://www.djangoproject.com/)
[!Python](https://www.python.org/)
***🌟 Show your support
Give a ⭐️ if this project helped you!
[!GitHub stars](https://github.com/leonardomarcolin/UniCrossed/stargazers)
[!GitHub forks](https://github.com/leonardomarcolin/UniCrossed/network/members)
</div>

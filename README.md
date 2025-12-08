# Resume Builder

A modern, feature-rich resume builder application built with React.js that allows users to create, customize, and manage professional resumes with multiple templates and real-time preview.

## 🚀 Features

- **Multiple Professional Templates**: Choose from 5 distinct templates (Modern, Elegant, Creative, Professional, Minimal)
- **Real-Time Preview**: See your resume update instantly as you type
- **Comprehensive Resume Sections**: 
  - Personal Information & Contact Details
  - Professional Summary
  - Skills (Programming, Frameworks, Databases, Tools, Soft Skills)
  - Work Experience (multiple entries)
  - Projects (with links and descriptions)
  - Education (with CGPA support)
  - Certifications, Achievements, Languages
- **Save & Manage Resumes**: Save multiple resumes, edit them anytime, and manage through a dashboard
- **User Authentication**: Secure login and signup system
- **Dark Mode Support**: Toggle between light and dark themes
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **PDF Export**: Download your resume as a PDF with A4 formatting

## 🛠️ Tech Stack

- **Frontend**: React.js, React Router DOM
- **Styling**: Tailwind CSS
- **State Management**: React Hooks (useState, useEffect)
- **API**: Axios for HTTP requests
- **Backend**: JSON Server (REST API)
- **PDF Export**: React-to-Print
- **Animations**: Framer Motion
- **Notifications**: React Toastify

## 📦 Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/resume-builder.git
   cd resume-builder
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start JSON Server** (in one terminal)
   ```bash
   npm run server
   ```
   This will start the backend server at http://localhost:5000

4. **Start the development server** (in another terminal)
   ```bash
   npm run dev
   ```
   This will start the React app at http://localhost:5173

5. **Open your browser**
   Navigate to http://localhost:5173

## 📁 Project Structure

```
resume-builder/
├── public/                 # Static assets
├── src/
│   ├── api/               # API configuration
│   ├── assets/            # Images and illustrations
│   ├── components/        # Reusable components
│   │   ├── templates/     # Resume template components
│   │   ├── Navbar.jsx
│   │   └── ResumePreview.jsx
│   ├── pages/             # Page components
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── ResumeEditor.jsx
│   │   └── SavedResumes.jsx
│   ├── App.jsx            # Main app component
│   └── main.jsx          # Entry point
├── db.json                # JSON Server database
├── server.js              # JSON Server configuration
└── package.json           # Dependencies
```

## 🎯 Usage

1. **Sign Up / Login**: Create an account or login with existing credentials
2. **Create Resume**: Click "Start building" to create a new resume
3. **Fill Information**: Enter your personal details, experience, projects, etc.
4. **Choose Template**: Select from 5 professional templates
5. **Preview**: See real-time preview on the right side
6. **Save**: Save your resume to access it later
7. **Download**: Export as PDF for job applications
8. **Manage**: View and edit all saved resumes from the dashboard

## 📚 Project Documentation

- **[Project Report](./PROJECT_REPORT.md)**: Comprehensive project documentation
- **[Video Guide](./VIDEO_GUIDE.md)**: Instructions for creating demonstration and code explanation videos
- **[Next Steps](./NEXT_STEPS.md)**: Checklist for project submission

## 🎥 Project Videos

- **Project Demonstration Video (3-4 minutes)**: [Add link here]
- **Project Code Explanation Video (4-5 minutes)**: [Add link here]

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run server` - Start JSON Server backend
- `npm run lint` - Run ESLint

## 🔧 Configuration

### JSON Server

The backend uses JSON Server for REST API. The server configuration is in `server.js` and the database is stored in `db.json`.

### API Endpoints

- `GET /resumes` - Get all resumes
- `GET /resumes/:id` - Get a specific resume
- `POST /resumes` - Create a new resume
- `PUT /resumes/:id` - Update a resume
- `DELETE /resumes/:id` - Delete a resume
- `GET /users` - Get all users
- `POST /users` - Create a new user

## 🌟 Key Features Explained

### Real-Time Preview
The preview updates instantly as you type, thanks to React's state management and component re-rendering.

### Template System
Five distinct templates are implemented as separate React components, allowing easy switching without data loss.

### Data Persistence
Resumes are saved to JSON Server, allowing users to access and edit their resumes anytime.

### PDF Export
Uses react-to-print library to generate print-ready PDFs with proper A4 formatting.

## 🤝 Contributing

This is a project submission. For contributions, please follow standard Git workflow:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request



---

**Note**: Make sure to start both the JSON Server and React development server for the application to work properly.

---

*** Happy Coding!! ***

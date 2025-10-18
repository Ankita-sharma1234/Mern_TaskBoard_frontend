# Task Management Frontend

A React-based frontend application for the Task Management system.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/Ankita-sharma1234/Mern_TaskBoard_frontend.git
cd Mern_TaskBoard_frontend
```

2. **Install dependencies:**
```bash
npm install
```

3. **Start development server:**
```bash
npm run dev
```

4. **Access the application:**
   - Open [http://localhost:5173](http://localhost:5173) in your browser

## 🔧 Development

### Available Scripts

```bash
npm run dev        # Start development server
npm run build      # Build for production
npm run preview    # Preview production build
npm run lint       # Run ESLint
```

### Environment Configuration

The application automatically detects the environment:
- **Development**: Uses `http://localhost:5000/api` for backend
- **Production**: Uses `https://mern-taskboard-backend.onrender.com/api` for backend

## 🚀 Deployment

### Vercel Deployment

1. **Connect GitHub repository to Vercel**
2. **Import project from GitHub**
3. **Configure build settings:**
   - **Framework Preset**: Vite
   - **Root Directory**: `./` (current directory)
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
4. **Deploy**

### Netlify Deployment

1. **Connect GitHub repository to Netlify**
2. **Configure build settings:**
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist`
3. **Deploy**

## 📁 Project Structure

```
Frontend/
├── src/
│   ├── api/           # API configuration
│   ├── components/    # Reusable components
│   ├── context/       # React context
│   ├── pages/         # Page components
│   └── assets/        # Static assets
├── public/            # Public assets
├── index.html         # Main HTML file
├── vite.config.js     # Vite configuration
└── package.json       # Dependencies
```

## 🛠️ Tech Stack

- **React 19** - UI library
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **Axios** - HTTP client
- **React Router** - Navigation

## 🌐 Features

- ✅ User Authentication (Login/Register)
- ✅ Project Management
- ✅ Task Management
- ✅ Responsive Design
- ✅ Real-time Updates
- ✅ JWT Authentication

## 🔧 Configuration

### API Configuration

The frontend automatically connects to the backend API:

- **Development**: `http://localhost:5000/api`
- **Production**: `https://mern-taskboard-backend.onrender.com/api`

### Environment Variables

No environment variables needed for frontend. The API URL is automatically configured based on the build environment.

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 🎨 UI Features

- Modern, clean interface
- Dark/Light theme support
- Intuitive navigation
- Real-time feedback
- Error handling

## 🚀 Build for Production

```bash
# Build the application
npm run build

# Preview the build
npm run preview
```

## 📞 Support

For issues or questions:
1. Check the troubleshooting section
2. Verify backend API is running
3. Check browser console for errors
4. Ensure all dependencies are installed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
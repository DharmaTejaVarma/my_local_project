# Study Planner & Productivity Dashboard

A modern, responsive React application designed to help students and professionals manage their study sessions, track productivity, and stay motivated with a comprehensive task management system.

![Study Planner Dashboard](https://via.placeholder.com/800x400/3b82f6/ffffff?text=Study+Planner+Dashboard)

## ✨ Features

### 🎯 Task Management
- **Add, edit, and delete tasks** with detailed information
- **Priority levels** (High, Medium, Low) with color coding
- **Due dates and estimated time** tracking
- **Category organization** for better task grouping
- **Mark tasks as complete** with visual feedback
- **Search and filter** functionality

### 📅 Calendar View
- **Interactive calendar** showing tasks by due date
- **Visual task indicators** with priority colors
- **Click on dates** to view scheduled tasks
- **Upcoming tasks** sidebar for quick access
- **Overdue task** highlighting

### ⏰ Pomodoro Timer
- **Customizable timer** (work, short break, long break)
- **Visual progress circle** with smooth animations
- **Auto-start options** for breaks and work sessions
- **Completed pomodoro** tracking
- **Settings panel** for timer customization

### 📊 Productivity Analytics
- **Weekly progress charts** showing completed vs pending tasks
- **Category performance** analysis
- **Priority distribution** pie charts
- **Time tracking** with completion percentages
- **Productivity score** calculation
- **Multiple time ranges** (week, month, year)

### 💡 Daily Motivation
- **Random inspirational quotes** from ZenQuotes API
- **Daily quote updates** with local caching
- **Beautiful gradient design** for motivation
- **Manual refresh** option for new quotes

### 🎨 Modern UI/UX
- **Responsive design** for desktop and mobile
- **Dark/Light mode** toggle with system preference detection
- **Clean, modern interface** with TailwindCSS
- **Smooth animations** and transitions
- **Accessible design** with proper contrast and focus states

### 💾 Data Persistence
- **LocalStorage** for data persistence
- **Export/Import** functionality for data backup
- **Settings persistence** across sessions
- **Demo data** preloaded for immediate testing

## 🚀 Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd study_planner_dashboard
   ```

2. **Install dependencies**
   
   **Option A: Using npm (if PowerShell execution policy allows)**
   ```bash
   npm install
   ```
   
   **Option B: Using batch file (Windows)**
   ```bash
   install.bat
   ```

3. **Start the development server**
   
   **Option A: Using npm**
   ```bash
   npm run dev
   ```
   
   **Option B: Using batch file (Windows)**
   ```bash
   start-dev.bat
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the application.

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

## 🛠️ Tech Stack

- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and development server
- **TailwindCSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Recharts** - Beautiful, responsive charts
- **Lucide React** - Beautiful & consistent icon toolkit
- **ZenQuotes API** - Motivational quotes integration

## 📁 Project Structure

```
study_planner_dashboard/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Navbar.jsx          # Top navigation bar
│   │   ├── Sidebar.jsx         # Side navigation
│   │   ├── TaskCard.jsx        # Individual task component
│   │   ├── PomodoroTimer.jsx   # Timer component
│   │   └── QuoteBox.jsx        # Motivational quotes
│   ├── pages/
│   │   ├── Dashboard.jsx       # Main dashboard page
│   │   ├── Calendar.jsx        # Calendar view
│   │   ├── Analytics.jsx       # Analytics and charts
│   │   └── Settings.jsx        # Settings page
│   ├── hooks/
│   │   └── useTheme.jsx        # Theme management hook
│   ├── assets/                 # Static assets
│   ├── App.jsx                 # Main app component
│   ├── main.jsx               # App entry point
│   └── index.css              # Global styles
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🎯 Usage Guide

### Adding Tasks
1. Click the **"Add Task"** button on the dashboard
2. Fill in the task details:
   - Title (required)
   - Description (optional)
   - Priority level
   - Due date
   - Estimated time
   - Category
3. Click **"Add Task"** to save

### Using the Pomodoro Timer
1. Navigate to the timer section on the dashboard
2. Choose your focus mode (Work, Short Break, Long Break)
3. Click **"Start"** to begin the timer
4. Use **"Pause"** to pause or **"Reset"** to restart
5. Configure settings using the gear icon

### Viewing Analytics
1. Go to the **Analytics** page from the sidebar
2. Select your preferred time range
3. View various charts and statistics:
   - Weekly progress
   - Task distribution by priority
   - Category performance
   - Time tracking

### Calendar Navigation
1. Click on the **Calendar** page
2. Use arrow buttons to navigate months
3. Click on any date to view scheduled tasks
4. View upcoming tasks in the sidebar

## ⚙️ Configuration

### Timer Settings
- **Work Time**: 25 minutes (default)
- **Short Break**: 5 minutes (default)
- **Long Break**: 15 minutes (default)
- **Auto-start**: Enable/disable automatic timer progression

### Theme Settings
- **Light Mode**: Clean, bright interface
- **Dark Mode**: Easy on the eyes for night studying
- **Auto-detection**: Follows system preference

### Data Management
- **Export**: Download all your data as JSON
- **Import**: Restore data from a backup file
- **Reset**: Clear all data and start fresh

## 🔧 Customization

### Adding New Task Categories
Edit the category input in the task creation form to add custom categories.

### Modifying Timer Durations
Adjust timer settings in the Settings page or modify default values in the PomodoroTimer component.

### Styling Changes
The app uses TailwindCSS for styling. Modify `tailwind.config.js` for theme customization.

## 🚀 Deployment

### Netlify
1. Build the project: `npm run build`
2. Drag the `dist` folder to Netlify
3. Configure environment variables if needed

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect Vite and deploy
3. Configure build settings if needed

### GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add deploy script to package.json
3. Run: `npm run deploy`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **ZenQuotes API** for providing inspirational quotes
- **Lucide React** for beautiful icons
- **Recharts** for responsive charts
- **TailwindCSS** for utility-first styling
- **React** and **Vite** for the amazing development experience

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/your-repo/issues) page
2. Create a new issue with detailed information
3. Contact the development team

---

**Happy Studying! 📚✨**

Built with ❤️ for students and productivity enthusiasts.

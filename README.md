# Secure E-Voting System 🗳️

A modern, secure, and transparent digital voting platform built with React and Vite. Features biometric verification, real-time results tracking, and progressive web app (PWA) capabilities.

## 🌟 Features

### For Voters
- **Secure Registration**: Complete voter registration with identity verification
- **Biometric Authentication**: Webcam-based face detection for secure verification
- **Easy Voting**: Intuitive candidate selection interface
- **Vote Confirmation**: Multi-step verification process
- **Real-time Results**: Live election results with interactive charts
- **Mobile PWA**: Install as native app on iOS, Android, or Desktop

### For Administrators
- **Election Management**: Configure elections with dates and requirements
- **User Management**: Manage voters and voting eligibility
- **Results Dashboard**: Visual analytics and vote tracking
- **Voter History**: Complete audit trail of voting activities
- **System Controls**: Full administrative capabilities

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Open your browser to http://localhost:5174
```

### Build for Production

```bash
# Create optimized build
npm run build

# Preview production build
npm run preview
```

## 📱 Progressive Web App (PWA)

The app is fully PWA-enabled and can be installed on any device:

### Installation

**Android:**
1. Open in Chrome/Firefox
2. Tap menu → "Install app"
3. Confirm installation

**iPhone/iPad:**
1. Open in Safari
2. Tap Share → "Add to Home Screen"
3. Name and confirm

**Desktop:**
1. Open in Chrome/Edge
2. Click install prompt in address bar
3. Complete installation

### Offline Support
- Service Worker enables offline functionality
- Cached assets work without internet
- Smart caching strategy for API calls
- Auto-updates when connection restored

## 📦 Tech Stack

- **Frontend**: React 19 with Vite
- **UI Framework**: Material-UI (MUI) v6
- **Styling**: Emotion CSS-in-JS
- **Charts**: Chart.js with react-chartjs-2
- **Animations**: GSAP & react-confetti
- **PWA**: Service Workers, Web App Manifest
- **State Management**: React Hooks
- **Build Tool**: Vite 6

## 🔒 Security Features

- Biometric verification (webcam-based)
- Secure session management
- Vote anonymity with verification
- Admin authentication
- Input validation and sanitization
- HTTPS enforced in production

## 📊 Data

- **6 Candidates** with profiles and bios
- **70 Pre-registered Voters** with timestamps
- **Real-time Vote Tracking** with analytics
- **User Management** system

## 📂 Project Structure

```
voting website/
├── public/
│   ├── manifest.json          # PWA manifest
│   ├── sw.js                  # Service Worker
│   └── vite.svg
├── src/
│   ├── components/            # React components
│   ├── App.jsx               # Main app component
│   ├── App.css               # Global styles
│   ├── index.css             # Base styles
│   ├── main.jsx              # React entry point
│   ├── serviceWorkerRegister.js  # PWA setup
│   └── assets/               # Static assets
├── index.html                # HTML entry point
├── vite.config.js           # Vite configuration
├── vercel.json              # Vercel deployment config
├── package.json             # Dependencies
└── .gitignore               # Git ignore rules
```

## 🌐 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: E-Voting PWA"
   git remote add origin https://github.com/kumardevansh787-cmyk/E-Voting.git
   git push -u origin main
   ```

2. **Deploy to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import the GitHub repository
   - Vercel auto-detects Vite settings
   - Click "Deploy"
   - Your app is live!

### Environment Variables

For production deployment, set these in Vercel dashboard:
```
VITE_API_URL=https://your-api.com
```

## 📋 Available Scripts

```bash
# Development
npm run dev          # Start dev server with HMR

# Production
npm run build        # Build optimized production bundle
npm run preview      # Preview production build locally

# Code Quality
npm run lint         # Run ESLint on code
```

## 🔄 Service Worker Management

### Testing Offline Mode

1. Open DevTools (F12)
2. Go to **Application** → **Service Workers**
3. Check "Offline" to test offline functionality
4. Refresh page - app should work without internet

### Checking Cache

1. DevTools → **Application** → **Cache Storage**
2. View cached assets and API responses
3. Clear cache to force update

## ♿ Accessibility

- WCAG 2.1 compliance
- Keyboard navigation support
- Touch-friendly (44px+ tap targets)
- Screen reader compatible
- High contrast support
- Respects `prefers-reduced-motion`

## 📱 Responsive Design

- Mobile (320px+)
- Tablet (768px+)
- Desktop (1024px+)
- Landscape orientation support
- Safe area support (notched devices)

## 🐛 Troubleshooting

### Service Worker Not Working
```bash
# Hard refresh to clear cache
Ctrl+Shift+R (Windows/Linux)
Cmd+Shift+R (Mac)
```

### App Won't Install
- Clear browser cache and cookies
- Use Chromium-based browser (Chrome, Edge)
- Check manifest.json is accessible

### Build Fails
```bash
# Clean install
rm -rf node_modules package-lock.json
npm install
npm run build
```

## 📖 Documentation

- [PWA Setup Guide](./PWA_SETUP_GUIDE.md) - Detailed PWA documentation
- [Vite Docs](https://vitejs.dev/) - Build tool documentation
- [React Docs](https://react.dev/) - React framework documentation
- [MUI Docs](https://mui.com/) - Component library documentation

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👥 Author

**Devansh Kumar**
- GitHub: [@kumardevansh787-cmyk](https://github.com/kumardevansh787-cmyk)
- Repository: [E-Voting](https://github.com/kumardevansh787-cmyk/E-Voting)

## 🙏 Acknowledgments

- Material-UI team for the component library
- React team for the framework
- Vite team for the build tool
- All contributors and users

## 💬 Support

For issues, questions, or suggestions:
1. Open an [Issue on GitHub](https://github.com/kumardevansh787-cmyk/E-Voting/issues)
2. Check existing documentation
3. Review the [PWA Setup Guide](./PWA_SETUP_GUIDE.md)

---

**Status**: 🟢 Active Development  
**Last Updated**: May 2026  
**Version**: 1.0.0

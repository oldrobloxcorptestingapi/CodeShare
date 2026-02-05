# CodeShare 📦

> A modern, GitHub-inspired code repository platform for sharing and discovering code projects

![CodeShare](https://img.shields.io/badge/CodeShare-v1.0-red?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-v10.8.0-orange?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-r128-blue?style=for-the-badge)

## 🌟 Overview

CodeShare is a sleek, dark-themed repository platform that allows developers to upload, share, and discover code projects. Built with modern web technologies and Firebase backend, it features real-time updates, user authentication, and an interactive 3D particle background.

## ✨ Features

### 🔐 Authentication & User Management
- **Email/Password Authentication** - Secure sign-up and sign-in
- **User Profiles** - Personalized profiles with avatars and bios
- **Points System** - Earn points for creating repositories and receiving stars
- **Account Settings** - Manage your profile, bio, and account status
- **Account Deactivation** - Temporarily disable your account
- **Account Deletion** - Permanently remove your account and all data

### 👥 User Roles & Badges
- **Admin Badge** ⚡ - Special privileges for platform administrators
- **Verified Badge** ✓ - Awarded to trusted creators (100+ points or admin-granted)
- **Account Status** - Active or Deactivated indicators
- **Custom Avatars** - Color-coded initials for each user

### 📂 Repository Management
- **Create Repositories** - Upload multiple code files with descriptions
- **README Support** - Markdown-formatted project documentation
- **Language Tags** - Specify primary programming language
- **Topics & Tags** - Categorize projects with custom topics
- **Public Visibility** - All repositories are publicly accessible
- **File Preview** - View repository files in an organized tree structure

### ⭐ Social Features
- **Star Repositories** - Show appreciation for projects you love
- **View Counter** - Track repository popularity
- **Owner Profiles** - Click on any username to view their profile
- **Points Rewards**:
  - Create repository: **+25 points**
  - Receive a star: **+2 points**
  - Auto-verified at: **100+ points**

### 🔍 Search & Discovery
- **Real-time Search** - Find repositories by name or description
- **Language Filters** - Filter by programming language
- **Sort Options**:
  - Recently updated
  - Least recently updated
  - Most stars
  - Most viewed
- **View Filters**:
  - All repositories
  - Your repositories
  - Starred repositories

### 🎨 User Interface
- **Dark Theme** - GitHub-inspired aesthetic with red accents
- **Responsive Design** - Works on desktop, tablet, and mobile
- **3D Particle Background** - Interactive Three.js animation
- **Smooth Animations** - Professional transitions and effects
- **Toast Notifications** - Real-time feedback for user actions
- **Modal Code Viewer** - Full-screen repository exploration

### 👑 Admin Features
- **Admin Panel** - Exclusive control panel for administrators
- **Grant Verified Badges** - Manually verify trusted users
- **Full Access** - Manage platform-wide settings

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- Email address for registration

### Installation

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. **Sign up** for a new account or **sign in** if you already have one

### Creating Your First Repository

1. **Sign in** to your account
2. Navigate to the **"Create new repository"** panel
3. Fill in the required fields:
   - Repository name (required)
   - Description (optional)
   - Primary language (required)
   - Topics (optional, comma-separated)
   - README content (optional, Markdown supported)
4. **Upload files** by dragging and dropping or clicking the upload area
5. Click **"Create repository"**
6. **Earn +25 points** instantly!

## 📖 User Guide

### Profile Management

#### Viewing Your Profile
- Click on your **email/avatar** in the header
- View your stats: repositories, points, and stars received
- Switch between **Repositories** and **Settings** tabs

#### Editing Your Bio
1. Go to your profile
2. Click the **Settings** tab
3. Click **"Edit"** next to Bio
4. Enter your bio and confirm

#### Account Deactivation
1. Navigate to **Settings** → **Danger Zone**
2. Click **"Deactivate"**
3. Confirm the action
4. Reactivate anytime by signing in

#### Account Deletion
1. Navigate to **Settings** → **Danger Zone**
2. Click **"Delete Forever"**
3. Type **"DELETE"** to confirm
4. ⚠️ This action is permanent and cannot be undone

### Repository Features

#### Starring Repositories
- Click the **⭐ Star** button on any repository
- Repository owner receives **+2 points**
- Track starred repos in the **"Starred"** filter

#### Viewing Repositories
- Click **"View code"** or the repository title
- Browse files in the file tree
- Switch between **Code** and **README** tabs
- Copy file contents with the **"Copy"** button

#### Deleting Repositories
- Only repository owners can delete
- Click the **"Delete"** button on your repository
- Confirm the action

## 🛠️ Technical Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (ES6+)** - Modular code structure
- **Three.js (r128)** - 3D particle animation

### Backend
- **Firebase Authentication** - User management
- **Cloud Firestore** - NoSQL database
- **Firebase SDK v10.8.0** - Latest features

### Design
- **Custom CSS Framework** - GitHub-inspired design system
- **Google Fonts** - Inter & JetBrains Mono
- **Responsive Grid** - Mobile-first approach
- **SVG Icons** - Scalable vector graphics

## 🎨 Design System

### Color Palette
```css
--gh-bg: #0a0a0a          /* Background */
--gh-canvas: #000000       /* Main canvas */
--gh-card: #161616         /* Card backgrounds */
--gh-border: #2d2d2d       /* Borders */
--gh-accent: #ff3333       /* Primary accent (red) */
--gh-success: #00ff00      /* Success (green) */
--gh-danger: #ff0000       /* Danger (red) */
```

### Typography
- **Body**: System fonts (-apple-system, Segoe UI, etc.)
- **Code**: JetBrains Mono (monospace)
- **Headings**: Inter (sans-serif)

## 🔒 Security Features

- **Firebase Authentication** - Industry-standard security
- **Secure Password Storage** - Encrypted credentials
- **Input Sanitization** - XSS protection
- **Admin-Only Features** - Role-based access control
- **Account Recovery** - Email-based password reset

## 📊 Points System

| Action | Points Earned |
|--------|--------------|
| Create repository | +25 points |
| Receive a star | +2 points |
| Auto-verified threshold | 100 points |

## 🏆 Badge System

### Verified Badge ✓
- **Green badge** with checkmark icon
- Awarded at **100+ points** automatically
- Can be granted by **admins** manually
- Indicates trusted, quality creators

### Admin Badge ⚡
- **Red badge** with lightning bolt icon
- Reserved for platform administrators
- Full access to admin controls
- Configured in `ADMIN_EMAILS` array

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 📱 Mobile Responsive

CodeShare is fully responsive and optimized for:
- 📱 Mobile phones (320px+)
- 📲 Tablets (768px+)
- 💻 Desktops (1024px+)
- 🖥️ Large screens (1280px+)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Report Bugs** - Submit detailed bug reports
2. **Suggest Features** - Share your ideas
3. **Improve Documentation** - Help others understand the platform
4. **Code Contributions** - Submit pull requests

## 📝 Admin Configuration

To add admin users, update the `ADMIN_EMAILS` array:

```javascript
const ADMIN_EMAILS = [
    'admin@example.com',
    'another.admin@example.com'
];
```

## 🎯 Roadmap

- [ ] Private repositories
- [ ] Repository collaborators
- [ ] Fork functionality
- [ ] Pull requests
- [ ] Issues and discussions
- [ ] Notifications system
- [ ] OAuth integration (GitHub, Google)
- [ ] Code syntax highlighting
- [ ] Download repository as ZIP
- [ ] Repository templates
- [ ] Editable repositories
- [ ] Username Changer (change once every 1 week)

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- **Firebase** - Backend infrastructure
- **Three.js** - 3D graphics library
- **Google Fonts** - Typography
- **GitHub** - Design inspiration

## 📞 Support

Need help? Have questions?
- Check the user guide above
- Use the platform's built-in feedback system
- Contact platform administrators

---

<div align="center">

**Built with ❤️ for the developer community**

⭐ **Star this platform** to show your support!

** Try out CodeShare V1.0 Today Stable Release **

</div>
